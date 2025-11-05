---
title: Fields
nav_order: 2
---

# Fields
{:toc}


| Field name | Description  | Valid entries | Example |
| ---- | ------------ | ------------------- |------ |
| `scenario_group`      | Scenario group | `nuclear2025`<br>`cross202506`<br>`cross202209`  | `cross202506`  |
| `scenario_name`       | Scenario name  | [Valid scenarios](/instructions-data/docs/scenarios) | `abroad-res-full` |
| `scenario_variant`    | Scenario variant | `reference`<br>`high`<br>`low` |
| `variable`            | Variable name  | [Valid variables](/instructions-data/docs/variables) |  `electricity_supply`|
| `use_technology_fuel` | Subcategory including end-uses, technology or fuel, depending on the variable  | [Valid subcategories](/instructions-data/docs/use_technology_fuel)| `spv_rooftop`|
| `country`             | Country        | `CH` ||
| `model`               | Model ID         |  [Valid model IDs](/instructions-data/docs/models) | `seseth` |
| `unit`                | Unit             | `TWh` (GWh/a) for annual data <br> `GW` (GWh/h) for hourly data | `TWh` |
| `time_resolution`     | Time resolution  | `annual` <br> `typical-day`   |
| `timestamp`           | Timestamp, depending on the time_resolution       | `annual`: `yyyy`<br>`typical-day`: `dd.MM.yyyy HH:mm`  | `2050` <br> `01.02.2050 07:00` |