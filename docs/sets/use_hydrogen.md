---
title: use_hydrogen
parent: Sets
layout: default
nav_order: 17
---

# Hydrogen end-uses

{: .important }
Used in variables: `h2_fec`

```
use_hydrogen
├── elec_generation              # Hydrogen for electricity generation
│   ├── hydrogen_pp              # Hydrogen thermal power plant
│   └── fuel_cell_h2             # Fuel cell using hydrogen
├── storage                      # Hydrogen storage
│   ├── h2_short_storage         # Hydrogen short-term storage
│   └── h2_long_storage          # Hydrogen long-term storage
├── passenger                    # Passenger hydrogen vehicles
│   ├── passenger_road_public    # Private passenger hydrogen vehicles
│   └── passenger_road_private   # Public passenger hydrogen vehicles
├── freight_road                 # Hydrogen road freight
│   ├── truck                    # Hydrogen trucks
│   └── ldv                      # Hydrogen light duty vehicles
├── space_heating                # Hydrogen used for space heating
├── process_heat                 # Hydrogen used for process heat production
├── fuel_synthesis               # Hydrogen used for fuel synthesis
└── exports                      # Hydrogen exports
```
    
[Download csv file with labels](/data-model/files/use_hydrogen.csv)
