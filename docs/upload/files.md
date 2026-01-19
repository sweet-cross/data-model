---
title: Files
parent: Upload
layout: default
nav_order: 1
---


# Files 
{: .no_toc }
1. TOC
{:toc}

## File formats
The platform accepts two file formats: comma-separated values (csv) and Excel (xlsx).

{: .important }
You should submit **one single file**. The submitted file must include all category and value columns.

File type | Sheet |Category columns | Value columns | Templates |
| ---- | ---- | ---- | ---- | --- | 
csv | | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | `value` |[`cross2025`](/data-model/files/resultsCross_stacked.csv)<br>[`nuclear2025`](/data-model/files/results_cross_nuclear2025_stacked.csv)| 
excel |  `annual` | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | One column per year with header `yyyy` |[`cross2025`](/data-model/files/resultsCross_excel.xlsx) <br> [`nuclear2025`](/data-model/files/results_cross_nuclear2025.xlsx)|  
| `hourly` | `scenario_group`, `scenario_name`, `scenario_variant`, `variable`, `use_technology_fuel`, `country`, `model`, `unit`, `time_resolution`, `timestamp` | One column per typical day with header `dd.MM.yyyy HH:mm` | 


## Zero values
Zero values must be explicitly written as `0`.

{: .warning }
Empty cells will return an error during submission

## Variables not in your model
You can exclude all variables that are not part of your model results.

{: .warning }
Empty cells will return an error during submission


## Problems uploading data

If you encounter issues when uploading data, please send an email to [sweet-cross](mailto:sweet.cross.ch[at]gmail.com?subject=technicalproblem) including:
- The file you tried to upload
- A description of the error