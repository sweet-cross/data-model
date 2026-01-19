---
title: Assumptions
parent: Variables
layout: default
nav_order: 2
---

# Model assumptions 

The following are the variables used as assumptions by energy system models. 

##  Macro-economic assumptions

| Variable name<br>`variable` | Description  | Sets (defined over) |
| ---- | ------------ | ------------------------ |
| `population` | Population |  |
| `households` | Number of households | |
| `working_population` | Working population |  |
| `gdp` | Gross domestic product| |
| `energy_reference_area` | Energy reference area | [`endusesector`](/data-model/docs/sets/endusesector), [`building`](/data-model/docs/sets/building), [`age`](/data-model/docs/sets/age) |


## Demands

| Variable name<br>`variable` | Description  | Sets (defined over) |
| ---- | ------------ | ------------------------ |
| `space_heating_useful_energy_demand` | Space heating useful energy demand | [`endusesector`](/data-model/docs/sets/endusesector) |
| `warm_water_useful_energy_demand` | Warm water useful energy demand | [`endusesector`](/data-model/docs/sets/endusesector) |
| `process_heat_useful_energy_demand` | Process heat useful energy demand | [`endusesector`](/data-model/docs/sets/endusesector) |
| `electric_appliances_useful_energy_demand` | Electricity appliances useful energy demand | [`endusesector`](/data-model/docs/sets/endusesector) |
| `passenger_transport_useful_energy_demand` | Passenger transport useful energy demand | [`trn_mode_private`](/data-model/docs/sets/trn_mode_private) |
| `freight_transport_useful_energy_demand` | Freight transport useful energy demand | [`trn_mode_freight`](/data-model/docs/sets/trn_mode_freight) |
| `aviation_fuel_demand` | Aviation fuel demand | [`fuel`](/data-model/docs/sets/fuel) |

## Resources

| Variable name<br>`variable` | Description  | Sets (defined over) |
| ---- | ------------ | ------------------------ |
| `import_prices` | Fuel import prices | [`fuel`](/data-model/docs/sets/fuel) |
| `biomass_potential` | Biomass potentials | [`resource`](/data-model/docs/sets/resource) |
 