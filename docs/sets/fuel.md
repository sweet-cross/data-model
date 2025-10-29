---
title: fuel
parent: Sets
layout: default
nav_order: 1
---

{: .important }
Used in variables: `passenger_road_public_fec`, `passenger_private_public_fec`, `freight_road_fec`


# Fuels

```
fuel
├── fossil                        # Fossil Fuel
│   ├── coal                      # Coal
│   ├── gas                       # Natural Gas
│   ├── oil                       # Oil Products
│   └── kerosene                  # Kerosene
├── nuclear                       # Nuclear fuel
├── renewable                     # Renewables
│   ├── hydro                     # Hydopower
│   │   ├── dam                   # Hydro Dams
│   │   └── ror                   # Run-off-river
│   └── renewable_other           # Other renewables
│      ├── spv                    # Solar PV
│      │   ├── spv_rooftop        # Rooftop solar PV
│      │   ├── spv_facade         # Facade solar PV
│      │   └── spv_mountain       # Mountain solar PV
│      ├── wind                   # Wind
│      │   ├── wind_on            # Wind onshore
│      │   └── wind_off           # Wind offshore
│      └── geothermal             # Geothermal
├── biomass                       # Biomass
│   ├── wood                      # Wood
│   │   ├── wood_forest           # Forest wood
│   │   ├── wood_landscape        # Wood from landscape
│   │   └── wood_waste            # Waste wood
│   ├── manure                    # Animal manure
│   ├── sewage                    # Fresh sewage sludge
│   └── green_waste               # Green waste
│      ├── organic_waste          # Collected organic waste
│      └── agri_byproducts        # Agricultural by-products
├── waste                         # Waste
│   └── mixed                     # Mixed waste
├── electricity                   # Electricity
├── h2                            # Hydrogen
├── methane                       # Methane
├── ethanol                       # Ethanol
├── biodiesel                     # Biodiesel
├── biogas                        # Biogas
├── saf                           # Sustainable aviation fuel
└── liquids                       # Liquid fuels
```
[Download csv file with labels](/instructions-data/files/fuel.csv)

