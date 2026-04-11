# Cars Fuel Efficiency: Benchmark Edition

[датасет](https://www.kaggle.com/datasets/hassnainzaidi/cars-fuel-efficiency-benchmark-edition)

This dataset contains enriched trip-level car fuel efficiency data, cleaned and enhanced for Kaggle projects.

## Columns

- trip\_id: Unique trip identifier  
- car\_name: Car model name  
- vehicle\_type: Type of vehicle  
- fuel\_type: Fuel type used  
- trip\_category: Category of trip  
- distance\_km: Trip distance (km)  
- trip\_duration\_hr: Trip duration (hours)  
- avg\_speed\_kmph: Average speed (km/h)  
- base\_mileage\_kmpl: Manufacturer mileage (km/l)  
- actual\_mileage\_kmpl: Observed mileage (km/l)  
- mileage\_delta\_kmpl: Difference between base and actual mileage  
- fuel\_consumed\_L: Fuel consumed (liters)  
- fuel\_cost\_usd: Total fuel cost (USD)  
- cost\_per\_km\_usd: Fuel cost per km (USD/km)  
- co2\_emissions\_kg: Total CO₂ emissions (kg)  
- co2\_per\_km: CO₂ emissions per km (kg/km)  
- relative\_efficiency: Relative efficiency score  
- efficiency\_band: Efficiency band classification  
- fuel\_efficiency\_ratio: Actual vs base mileage ratio  
- speed\_efficiency\_ratio: Average speed divided by actual mileage  
- cost\_to\_emission\_ratio: Fuel cost per unit CO₂ emitted  
- trip\_efficiency\_profile: Trip type classification (Urban, Mixed, Highway)  
- trip\_intensity: Distance divided by duration (km/h proxy)  
- efficiency\_class: Categorical efficiency rating (Low, Medium, High, Ultra)  
- benchmark\_flag: True if trip meets ideal efficiency criteria  
- outlier\_flag: True if trip is an outlier in mileage or emissions  
- data\_quality\_score: Score based on data completeness and plausibility



## Перевод

- trip_id: Уникальный идентификатор поездки
- car_name: Название модели автомобиля
- vehicle_type: Тип транспортного средства
- fuel_type: Тип используемого топлива
- trip_category: Категория поездки
- distance_km: Расстояние поездки (км)
- trip_duration_hr: Длительность поездки (часы)
- avg_speed_kmph: Средняя скорость (км/ч)
- base_mileage_kmpl: Паспортный расход топлива от производителя (км/л)
- actual_mileage_kmpl: Фактический расход топлива (км/л)
- mileage_delta_kmpl: Разница между паспортным и фактическим расходом
- fuel_consumed_L: Израсходованное топливо (литры)
- fuel_cost_usd: Общая стоимость топлива (USD)
- cost_per_km_usd: Стоимость топлива на км (USD/км)
- co2_emissions_kg: Общие выбросы CO₂ (кг)
- co2_per_km: Выбросы CO₂ на км (кг/км)
- relative_efficiency: Относительный показатель эффективности
- efficiency_band: Классификация по диапазону эффективности
- fuel_efficiency_ratio: Отношение фактического расхода к паспортному
- speed_efficiency_ratio: Отношение средней скорости к фактическому расходу
- cost_to_emission_ratio: Стоимость топлива на единицу выбросов CO₂
- trip_efficiency_profile: Тип поездки (городская, смешанная, трасса)
- trip_intensity: Интенсивность поездки (расстояние / время, аналог км/ч)
- efficiency_class: Категориальная оценка эффективности (низкая, средняя, высокая, ультра)
- benchmark_flag: True, если поездка соответствует идеальным критериям эффективности
- outlier_flag: True, если поездка является выбросом по расходу или выбросам
- data_quality_score: Оценка качества данных (полнота и правдоподобие)