---
title: Assumptions
parent: Variables
layout: default
nav_order: 2
---

# Model assumptions 

The following are the variables used as assumptions by energy system models. 

##  Macro-economic assumptions

| Variable name<br>`variable` | Description  | Dimensions (defined over) |
| ---- | ------------ | ------------------------ |
| `population` | Population |  |
| `households` | Number of households | |
| `working_population` | Working population |  |
| `gdp` | Gross domestic product| |
| `energy_reference_area` | Energy reference area | [`endusesector`](/data-model/docs/dimensions/endusesector), [`building`](/data-model/docs/dimensions/building), [`age`](/data-model/docs/dimensions/age) |


## Demands

| Variable name<br>`variable` | Description  | Dimensions (defined over) |
| ---- | ------------ | ------------------------ |
| `space_heating_useful_energy_demand` | Space heating useful energy demand | [`endusesector`](/data-model/docs/dimensions/endusesector) |
| `warm_water_useful_energy_demand` | Warm water useful energy demand | [`endusesector`](/data-model/docs/dimensions/endusesector) |
| `process_heat_useful_energy_demand` | Process heat useful energy demand | [`endusesector`](/data-model/docs/dimensions/endusesector) |
| `electric_appliances_useful_energy_demand` | Electricity appliances useful energy demand | [`endusesector`](/data-model/docs/dimensions/endusesector) |
| `passenger_transport_useful_energy_demand` | Passenger transport useful energy demand | [`trn_mode_private`](/data-model/docs/dimensions/trn_mode_private) |
| `freight_transport_useful_energy_demand` | Freight transport useful energy demand | [`trn_mode_freight`](/data-model/docs/dimensions/trn_mode_freight) |
| `aviation_fuel_demand` | Aviation fuel demand | [`fuel`](/data-model/docs/dimensions/fuel) |

## Resources

| Variable name<br>`variable` | Description  | Dimensions (defined over) |
| ---- | ------------ | ------------------------ |
| `import_prices` | Fuel import prices | [`fuel`](/data-model/docs/dimensions/fuel) |
| `biomass_potential` | Biomass potentials | [`resource`](/data-model/docs/dimensions/resource) |
 