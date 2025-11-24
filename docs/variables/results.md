---
title: Results
parent: Variables
layout: default
nav_order: 2
---

# Model results variables

The following are the variables produced as results by energy system models. 

| Variable name<br>`variable` | Description  | Set (defined over)<br>`use_technology_fuel` | Unit<br>`unit` |
| ---- | ------------ | ------------------------ |
| `electricity_consumption` | Electricity consumption by end-use | [`use_elec`](/instructions-data/docs/sets/use_elec) | `TWh` |
| `electricity_consumption_typical_day` | Electricity consumption by end-use - Hourly| [`use_elec`](/instructions-data/docs/sets/use_elec)| `GW` |
| `electricity_supply` | Electricity supply by technology | [`tech_generation`](/instructions-data/docs/sets/tech_generation) | `TWh` |
| `electricity_supply_typical_day` | Electricity supply by technology - Hourly| [`tech_generation`](/instructions-data/docs/sets/tech_generation)|`GW` |
| `installed_capacity` | Total installed capacity by electricity generation technology| [`tech_generation`](/instructions-data/docs/sets/tech_generation)|`GW` |
| `h2_fec` | Hydrogen final energy consumption by end-use | [`use_hydrogen`](/instructions-data/docs/sets/use_hydrogen) |`TWh` |
| `h2_supply` | Hydrogen supply by technology | [`tech_hydrogen`](/instructions-data/docs/sets/tech_hydrogen) |`TWh` |
| `liquids_fec`| Liquid fuels final energy consumption by end-use | [`use_liquids`](/instructions-data/docs/sets/use_liquids) |`TWh` |
| `liquids_supply` | Liquid fuels supply by technology | [`tech_liquids`](/instructions-data/docs/sets/tech_liquids) |`TWh` |
| `methane_fec` | Methane final energy consumption by end-use | [`use_methane`](/instructions-data/docs/sets/use_methane) |`TWh` |
| `methane_supply` | Methane supply by technology | [`tech_methane`](/instructions-data/docs/sets/tech_methane) |`TWh` |
| `process_heat_useful_energy_production` | Process heat useful energy production by technology | [`tech_heat`](/instructions-data/docs/sets/tech_heat) |`TWh` |
| `space_heat_useful_energy_supply` | Space heat useful energy production by technology | [`tech_heat`](/instructions-data/docs/sets/tech_heat) |`TWh` |
| `district_heat_useful_energy_production` | District heat useful energy production by technology | [`tech_heat`](/instructions-data/docs/sets/tech_heat) |`TWh` |
| `passenger_road_public_fec` | Passenger road public transport final energy consumption by fuel | [`fuel`](/instructions-data/docs/sets/fuel)|`TWh` |
| `passenger_road_private_fec`  | Passenger road transport final energy consumption by fuel | [`fuel`](/instructions-data/docs/sets/fuel)|`TWh` |
| `freight_road_fec` | Fright road transport final energy consumption by fuel | [`fuel`](/instructions-data/docs/sets/fuel)|`TWh` |
| `storage_installed_volume`| Installed storage volume by storage type | [`tech_storage`](/instructions-data/docs/sets/tech_storage)|`TWh` |
| `storage_output`| Storage output by storage type | [`tech_storage`](/instructions-data/docs/sets/tech_storage)|`TWh` |
| `total_system_costs`| Total annual system costs | | `BCHF` |
| `carbon_price`| Marginal price of carbon | | `CHF/tCO2` |
| `carbon_emissions`| Carbon emissions by end-use | [`use_emissions`](/instructions-data/docs/sets/use_emissions)| `MtCO2` |


