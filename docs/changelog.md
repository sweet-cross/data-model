---
layout: default
title: Changelog
nav_order: 50
---

# Changelog
All notable changes to this project will be documented in this file.

## -2026-03-17
### Added
```
tech_generation
├── vehicle_to_grid       # Vehicle to grid
```

```
tech_heat
└── waste_heat            # Waste heat from industrial processes
```

```
use_elec
├── fuel_production       # Electricity used for fuel production
│   ├── methane_pyrolysis # Electricity used for methane pyrolysis
├── other_elec	          # Other uses of electricity
```

```
use_hydrogen
├── other_h2              # Other uses of hydrogen
```

```
use_liquids
└── aviation              # Liquid fuel aviation
├── other_liquids         # Other uses of liquid fuels
```

```
use_methane
├── other_methane         # Other uses of methane
```

## - 2025-11-25
### Added

| Variable name<br>`variable` | Description  | Dimension (defined over) <br>`use_technology_fuel` | Unit<br>`unit` |
| ---- | ------------ | ------------------------ |
| `total_system_costs`| Total annual system costs | | `BCHF` |
| `carbon_price`| Marginal price of carbon | | `CHF/tCO2` |
| `carbon_emissions`| Carbon emissions by end-use | [`use_emissions`](/data-model/docs/dimensions/use_emissions)| `MtCO2` |


```
tech_generation
├── renewable                       # Renewables
│   ├── renewable_other             # Other renewables
│   │   └── spv                     # Solar photovotaics (PV, post-curtailment)
│   │      └── spv_agriculture      # Agricultural or field PV (post-curtailment)
│   ├── wind                        # Wind
│   │   └── wind_off                # Wind offshore
└── curtailment                     # Curtailed electricity from any source
```
```
tech_heat
└── data_centers                  # Waste heat from data centers
```
```
use_elec
├── grid_losses                          # Grid losses across all grid levels
├── storage_losses                       # Storage losses
└── data_centers                         # Electricity used in data centers
```

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

### Improved definition


| Variable name<br>`variable` | Description  | Dimension (defined over) <br>`use_technology_fuel` | Unit<br>`unit` |
| ---- | ------------ | ------------------------ |
| `space_heat_useful_energy_supply` | Space heat <b>and hot water</b> useful energy production by technology | [`tech_heat`](/data-model/docs/dimensions/tech_heat) |`TWh` |



```
tech_generation
├── renewable                       # Renewables
│   ├── renewable_other             # Other renewables
│   │   └── spv                     # Solar photovotaics (PV, post-curtailment)
│   │      ├── spv_rooftop          # Rooftop solar PV (post-curtailment)
│   │      ├── spv_facade           # Facade solar PV (post-curtailment)
│   │      ├── spv_mountain         # Mountain solar PV (post-curtailment)
```


```
use_elec
├── dac                                  # Electricity used for carbon capture and storage (including DAC)
```





