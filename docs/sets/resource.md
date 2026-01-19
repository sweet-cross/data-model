---
title: resource
parent: Sets
layout: default
nav_order: 5
---

{: .important }
Used in variables: `biomass_potential`


# Resources

```
resource
├── fossil                        # Fossil Fuel
│   ├── coal                      # Coal
│   ├── gas                       # Natural Gas
│   └── oil                       # Oil
├── nuclear                       # Uranium
├── renewable                     # Renewables
│   ├── hydro                     # Hydopower
│   │   ├── dam                   # Hydro Dams
│   │   └── ror                   # Run-off-river
│   └── renewable_other           # Other renewables
│      ├── spv                    # Solar PV
│      │   ├── spv_rooftop        # Rooftop Solar
│      │   ├── spv_facade         # Facade Solar
│      │   └── spv_mountain       # Mountain Solar
│      ├── wind                   # Wind
│      │   ├── wind_on            # Wind onshore
│      │   └── wind_off           # Wind offshore
│      └── geothermal             # Geothermal
├── biomass                       # Biomass
│   ├── wood                      # Wood
│   │   ├── wood_forest           # Forest wood
│   │   ├── wood_landscape        # Wood from landscape
│   │   ├── wood_waste            # Waste wood
│   │   └── wood_residues         # Wood residues
│   ├── manure                    # Animal manure
│   ├── sewage                    # Fresh sewage sludge
│   └── green_waste               # Green waste
│      ├── organic_waste          # Collected organic waste
│      └── agri_byproducts        # Agricultural by-products
└── waste                         # Waste
   ├── mixed                      # Mixed waste
   └── other_waste                # Other waste fraction
```
[Download csv file with labels](/data-model/files/resource.csv)

