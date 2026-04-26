# Простые запросы к базе bicycle_renalt

## 1) Арендатор с максимальным чеком за год

```javascript
db.orders.aggregate([
  { $match: { start: { $regex: "^2026" } } },
  { $group: { _id: "$client id", totalCheck: { $sum: "$cost" } } },
  { $sort: { totalCheck: -1 } },
  { $limit: 1 },
  { $project: { _id: 0, "client id": "$_id", totalCheck: 1 } }
]);
```

## 2) Месяц с максимальной прибылью

```javascript
db.orders.aggregate([
  { $match: { start: { $regex: "^2026" } } },
  { $group: { _id: { $substr: ["$start", 5, 2] }, monthlyProfit: { $sum: "$cost" } } },
  { $sort: { monthlyProfit: -1 } },
  { $limit: 1 },
  { $project: { _id: 0, month: "$_id", monthlyProfit: 1 } }
]);
```
