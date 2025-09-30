---
title: Electricity consumption by end-use
parent: Variables
layout: default
nav_order: 1
---

# Fuels

- variables: `electricity_consumption`, `electricity_consumption_typical_day`
- use_technology_fuel: 
    ```
    use_elec
    ├── elec_appliances                     # Electricity used for appliances and motors in all sectors
    ├── storage                             # Electricity storage
    │   └── battery_in                      # Charging of batteries
    ├── phs_in                              # Pumped hydro charging
    ├── passenger                           # Passenger electric vehicles
    │   ├── road_public                     # Private passenger electric vehicles
    │   └── road_private                    # Public passenger electric vehicles
    ├── freight_road                        # Electric road freight
    │   ├── truck                           # Electric trucks
    │   └── ldv                             # Electric light duty vehicles
    ├── rail                                # Rail
    │   ├── passenger_rail                  # Passenger rail
    │   └── freight_rail                    # Freight rail
    ├── space_heating                       # Electricity used for space heating
    │   ├── space_heating_boiler_electrode  # Electricity used for space heating using boiler electrode
    │   ├── space_heating_heater_elec       # Electricity used for space heating using electric heater
    │   └── space_heating_heat_pump         # Electricity used for space heating using heat pump
    ├── process_heat                        # Electricity used for process heat production
    │   ├── process_heat_boiler_electrode   # Electricity used for process heat production using boiler electrode
    │   ├── process_heat_heater_elec        # Electricity used for process heat production using electric heater
    │   └── process_heat_heat_pump          # Electricity used for process heat production using heat pump
    ├── fuel_production                     # Electricity used for fuel production
    │   ├── electrolysis                    # Electricity used for hydrogen production with electrolysis
    │   └── power_to_liquid                 # Electricity used for power to liquids
    ├── exports                             # Electricity exports
    ├── grid_losses                         # Grid losses
    └── dac                                 # Direct air capture
    ```
    [Download csv file with labels](../files/use_elec.csv)