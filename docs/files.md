---
title: Files
layout: default
nav_order: 2
---


# Files
{: .no_toc }

The platform accepts two file formats.

## CSV file

 | Column | Description  | Valid entries CROSS 2025 |
| ---- | ------------ | ------------------------ |
| scenario_name       | Scenario name           | `abroad-res-full` <br> `abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
| variable            | Variable name           | [Valid variables](/variables) |
| use_technology_fuel | Use, technology or fuel | Depending on variable  |
| country             | Country                 | CH  |
| scenario_group      | Scenario group          | cross202506  |
| scenario_variant    | Scenario variant        | reference, high or low |
| model               | Model ID                | Model ID (identical to the username for loggin to the platform)  |
| unit                | Unit                    | TWh for annual data and GW (GWh/h) for hourly data |
| time_resolution     | Time resolution         | annual or typical-day   |
| timestamp           | Time stamp              | annual: YYYY<br>typical-day: YYYY MM DD HH:mm  |
| value               | Value                   |   |


## Excel file

| Sheet | Column | Description  | Valid entries CROSS 2025 |
| ---- | ---- | ------------ | ------------------------ |
annual | scenario_name       | Scenario name           | `abroad-res-full`<br>`abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
|| variable            | Variable name           | [Valid variables](/variables) |
|| use_technology_fuel | Use, technology or fuel | Depending on variable  |
|| country             | Country                 | CH  |
|| scenario_group      | Scenario group          | cross202506  |
|| scenario_variant    | Scenario variant        | reference, high or low |
|| model               | Model ID                | Model ID (identical to the username for loggin to the platform)  |
|| unit                | Unit                    | TWh for annual data and GW (GWh/h) for hourly data |
|| time_resolution     | Time resolution         | annual or typical-day   |
|| YYYY or YYYY MM DD HH:mm          | Value of the variable for year YYYY or hour YYYY MM DD HH:mm |   |
  

