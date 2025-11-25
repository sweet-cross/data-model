---
title: use_emissions
parent: Sets
layout: default
nav_order: 16
---

# End-uses used to report carbon emissions

{: .important }
Used in variables: `carbon_emissions`

```
use_emissions
├── elec_appliances                      # Emissions from electricity used for appliances and motors in all sectors
├── passenger                            # Emissions from passenger electric vehicles
│   ├── road_public                      # Emissions from private passenger electric vehicles
│   └── road_private                     # Emissions from public passenger electric vehicles
├── freight_road                         # Emissions from electricity used for road freight
│   ├── truck                            # Emissions from electricity used for electric trucks
│   └── ldv                              # Emissions from electricity used for electric light duty vehicles
├── rail                                 # Emissions from rail transport
│   ├── passenger_rail                   # Emissions from passenger rail transport
│   └── freight_rail                     # Emissions from freight rail
├── space_heating                        # Emissions from energy used for space heating
├── process_heat                         # Emissions from energy used for process heat production
├── fuel_production                      # Emissions from energy used for fuel production
├── dac                                  # Emissions captured by DAC
```


