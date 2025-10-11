---
title: Files
layout: default
nav_order: 2
---


# Files 
{: .no_toc }
1. TOC
{:toc}


## Fields

| Field name | Description  | Valid entries | Example |
| ---- | ------------ | ------------------- |------ |
| `scenario_group`      | Scenario group | `cross202506`<br>`cross202209`  | `cross202506`  |
| `scenario_name`       | Scenario name  | [Valid scenarios](/instructions-data/docs/scenarios) | `abroad-res-full` |
| `scenario_variant`    | Scenario variant | `reference`<br>`high`<br>`low` |
| `variable`            | Variable name  | [Valid variables](/instructions-data/docs/variables) |  `electricity_supply`|
| `use_technology_fuel` | Subcategory including end-uses, technology or fuel, depending on the variable  | [Valid subcategories](/instructions-data/docs/use_technology_fuel)| `spv_rooftop`|
| `country`             | Country        | `CH` ||
| `model`               | Model ID         |  [Valid model IDs](/instructions-data/docs/models) | `seseth` |
| `unit`                | Unit             | `TWh` (GWh/a) for annual data <br> `GW` (GWh/h) for hourly data | `TWh` |
| `time_resolution`     | Time resolution  | `annual` <br> `typical-day`   |
| `timestamp`           | Timestamp, depending on the time_resolution       | `annual`: `yyyy`<br>`typical-day`: `dd.MM.yyyy HH:mm`  | `2050` <br> `01.02.2050 07:00` |


## File formats
The platform accepts two file formats: comma-separated values (csv) and Excel (xlsx).

{: .important }
You should submit **one single file**. The submitted file must include all category and value columns.

File type | Sheet |Category columns | Value columns | Template and example file |
| ---- | ---- | ---- | ---- | --- | 
csv | | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | `value` |[csv template](/instructions-data/files/resultsCross_stacked.csv)<br>[csv example](/instructions-data/files/resultsCross_SES_stacked.csv)| 
excel |  `annual` | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | One column per year with header `yyyy` |[xslx template](/instructions-data/files/resultsCross_excel.xlsx) <br> [xslx example](/instructions-data/files/resultsCross_SES.xlsx)|  
| `hourly` | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | One column per typical day with header `dd.MM.yyyy HH:mm` | 


## Zero values
Zero values must be explicitly written as `0`.

{: .warning }
Empty cells will return an error during submission

## Variables not in your model
You can exclude all variables that are not part of your model results.

{: .warning }
Empty cells will return an error during submission


