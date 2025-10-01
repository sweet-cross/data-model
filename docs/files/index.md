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
| scenario_name       | Scenario name  | [Valid scenarios](/instructions-data/docs/scenarios) | `abroad-res-full` |
| variable            | Variable name  | [Valid variables](/instructions-data/docs/variables) |  `electricity_supply`|
| use_technology_fuel | Subcategory including end-uses, technology or fuel, depending on the variable  | `spv_rooftop`|
| country             | Country        | `CH` ||
| scenario_group      | Scenario group | `cross202209` or `cross202506`  |
| scenario_variant    | Scenario variant        | `reference`, `high` or `low` |
| model               | Model ID                |  [Valid model IDs](/instructions-data/docs/models) |
| unit                | Unit                    | `TWh` for annual data and `GW` (GWh/h) for hourly data |
| time_resolution     | Time resolution         | `annual` or `typical-day`   |
| timestamp           | Time stamp              | annual: YYYY<br>typical-day: YYYY MM DD HH:mm  |
| value               | Value                   |   |




# File formats
The platform accepts two file formats: [CSV](#csv) and [Excel](#excel) files with specific columns. 


<a id="csv"></a>
### CSV file

 | Column | Description  | Valid entries CROSS 2025 |
| ---- | ------------ | ------------------------ |
| scenario_name       | Scenario name           | `abroad-res-full` <br> `abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
| variable            | Variable name           | [Valid variables](/instructions-data/docs/variables) |
| use_technology_fuel | Subcategory including end-uses, technology or fuel | Depending on [variables](/instructions-data/docs/variables)  |
| country             | Country                 | `CH` |
| scenario_group      | Scenario group          | `cross202506`  |
| scenario_variant    | Scenario variant        | `reference`, `high` or `low` |
| model               | Model ID                |  [Valid model IDs](/instructions-data/docs/models) |
| unit                | Unit                    | `TWh` for annual data and `GW` (GWh/h) for hourly data |
| time_resolution     | Time resolution         | `annual` or `typical-day`   |
| timestamp           | Time stamp              | annual: YYYY<br>typical-day: YYYY MM DD HH:mm  |
| value               | Value                   |   |


[Download empty csv file](/instructions-data/files/resultsCross_stacked.csv)

<a id="excel"></a>
### Excel file

The excel file is the unstack version of the CSV file, it has two sheets:

1.  `annual`

	| Column | Description  | Valid entries CROSS 2025 |
	| ---- | ------------ | ------------------------ |
	| scenario_name       | Scenario name           | `abroad-res-full`<br>`abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
	| variable            | Variable name           | [Valid variables](/instructions-data/docs/variables) |
	| use_technology_fuel | Use, technology or fuel | Depending on [variables](/instructions-data/docs/variables)   |
	| country             | Country                 | `CH`  |
	| scenario_group      | Scenario group          | `cross202506`  |
	| scenario_variant    | Scenario variant        | `reference`, `high` or `low` |
	| model               | Model ID                |  [Valid model IDs](/instructions-data/docs/models) |
	| unit                | Unit                    | `TWh` for annual data and `GW` (GWh/h) for hourly data |
	| time_resolution     | Time resolution         | `annual`  |
	| YYYY 				  | Value of the variable for year YYYY |   |
  
2.  `hourly`

	| Column | Description  | Valid entries CROSS 2025 |
	| ---- | ------------ | ------------------------ |
	| scenario_name       | Scenario name           | `abroad-res-full`<br>`abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
	| variable            | Variable name           | [Valid variables](/instructions-data/docs/variables) |
	| use_technology_fuel | Use, technology or fuel | Depending on [variables](/instructions-data/docs/variables)   |
	| country             | Country                 | `CH`  |
	| scenario_group      | Scenario group          | `cross202506`  |
	| scenario_variant    | Scenario variant        | `reference`, `high` or `low` |
	| model               | Model ID                |  [Valid model IDs](/instructions-data/docs/models) |
	| unit                | Unit                    | `TWh` for annual data and `GW` (GWh/h) for hourly data |
	| time_resolution     | Time resolution         | `typical-day`   |
	| YYYY MM DD HH:mm    | Value of the variable for hour YYYY MM DD HH:mm |   |

[Download empty excel file](/instructions-data/files/resultsCross_excel.csv)

# Zero values
Zero values should be explicitly written as `0`.

{: .warning }
Empty cells will throw and error in the submission

# Variables not in your model
You can exclude all variables that are not included in your model.

{: .warning }
Empty cells will throw and error in the submission


