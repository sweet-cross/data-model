---
title: tech_heat
parent: Sets
layout: default
nav_order: 8
---

# Heat technologies

{: .important }
Used in variables: `process_heat_useful_energy_production`, `space_heat_useful_energy_supply`, `district_heat_useful_energy_supply`

```
tech_heat
├── boiler                        # Boiler
│   ├── boiler_methane            # Methane boiler
│   ├── boiler_h2                 # Hydrogen boiler
│   ├── boiler_liquids            # Liquid fuel boiler
│   ├── boiler_wood               # Wood boiler
│   │   ├── boiler_wood_chips     # Wood chips boiler
│   │   └── boiler_wood_pellets   # Wood pellets boiler
│   ├── boiler_waste              # Waste boiler
│   ├── boiler_coal               # Coal boiler
│   └── boiler_electrode          # Electrode boiler
├── chp                           # Combined heat and power
│   ├── chp_methane               # Methane CHP
│   ├── chp_h2                    # Hydrogen CHP
│   ├── chp_liquids               # Liquid fuel CHP
│   ├── chp_wood                  # Wood CHP
│   ├── chp_waste                 # Waste CHP
│   └── chp_coal                  # Coal CHP
├── heat_pump                     # Heat pump
│   ├── air_source                # Air source heat pump
│   ├── ground_source             # Ground source heat pump
│   └── water_source              # Water source heat pump
├── heater_elec                   # Electric heater
├── solar_thermal                 # Solar thermal
├── geothermal_heat               # Geothermal
├── district_heat                 # District heat
├── storage_thermal_out           # Thermal storage
└── data_centers                  # Waste heat from data centers
```
[Download csv file with labels](/data-model/files/tech_heat.csv)

