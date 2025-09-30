---
title: Files
layout: default
nav_order: 2
---


# Files
{: .no_toc }

## File types

The platform accepts two file formats:
- Excel file

    | Column | Description  | Valid entries CROSS 2025 |
    | ---- | ------------ | ------------------------ |
    | scenario_name       | Scenario name           | `abroad-res-full`<br>`abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
    | variable            | Variable name           | [`electricity_consumption`](#electricity_consumption)<br>[`electricity_supply`](#electricity_supply)<br>[`h2_fec`](#h2_fec)<br>[`h2_supply`](#h2_supply)<br>[`methane_fec`](#methane_fec)<br>[`methane_supply`](#methane_supply)<br>[`liquids_fec`](#liquids_fec)<br>[`liquids_supply`](#liquids_supply)<br>[`process_heat_useful_energy_production`](#tech_heat)<br>[`space_heat_useful_energy_supply`](#tech_heat)<br>[`district_heat_useful_energy_production`](#tech_heat)<br>[`passenger_road_public_fec`](#fuel)<br>[`passenger_road_private_fec`](#fuel)<br>[`freight_road_fec`](#fuel)<br>[`storage_installed_volume`](#storage_installed_volume)<br>[`storage_output`](#storage_output)<br>[`electricity_consumption_typical_day`](#electricity_consumption)<br>[`electricity_supply_typical_day`](#electricity_supply) |
    | use_technology_fuel | Use, technology or fuel | Depending on variable  |
    | country             | Country                 | CH  |
    | scenario_group      | Scenario group          | cross202506  |
    | scenario_variant    | Scenario variant        | reference, high or low |
    | model               | Model ID                | Model ID (identical to the username for loggin to the platform)  |
    | unit                | Unit                    | TWh for annual data and GW (GWh/h) for hourly data |
    | time_resolution     | Time resolution         | annual or typical-day   |
    | YYYY or YYYY MM DD HH:mm          | Value of the variable for year YYYY or hour YYYY MM DD HH:mm |   |
  

- CSV file

   	| Column | Description  | Valid entries CROSS 2025 |
    | ---- | ------------ | ------------------------ |
    | scenario_name       | Scenario name           | `abroad-res-full`<br>`abroad-res-lim`<br>`abroad-nores-full`<br>`abroad-nores-lim`<br>`domestic-res-full`<br>`domestic-res-lim`<br>`domestic-nores-full`<br>`domestic-nores-lim` |
    | variable            | Variable name           | [`electricity_consumption`](#electricity_consumption)<br>[`electricity_supply`](#electricity_supply)<br>[`h2_fec`](#h2_fec)<br>[`h2_supply`](#h2_supply)<br>[`methane_fec`](#methane_fec)<br>[`methane_supply`](#methane_supply)<br>[`liquids_fec`](#liquids_fec)<br>[`liquids_supply`](#liquids_supply)<br>[`process_heat_useful_energy_production`](#tech_heat)<br>[`space_heat_useful_energy_supply`](#tech_heat)<br>[`district_heat_useful_energy_production`](#tech_heat)<br>[`passenger_road_public_fec`](#fuel)<br>[`passenger_road_private_fec`](#fuel)<br>[`freight_road_fec`](#fuel)<br>[`storage_installed_volume`](#storage_installed_volume)<br>[`storage_output`](#storage_output)<br>[`electricity_consumption_typical_day`](#electricity_consumption)<br>[`electricity_supply_typical_day`](#electricity_supply) |
    | use_technology_fuel | Use, technology or fuel | Depending on variable  |
    | country             | Country                 | CH  |
    | scenario_group      | Scenario group          | cross202506  |
    | scenario_variant    | Scenario variant        | reference, high or low |
    | model               | Model ID                | Model ID (identical to the username for loggin to the platform)  |
    | unit                | Unit                    | TWh for annual data and GW (GWh/h) for hourly data |
    | time_resolution     | Time resolution         | annual or typical-day   |
    | timestamp           | Time stamp              | annual: YYYY<br>typical-day: YYYY MM DD HH:mm  |
    | value               | Value                   |   |