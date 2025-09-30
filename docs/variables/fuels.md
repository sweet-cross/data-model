---
title: Fuels
parent: Variables
layout: default
nav_order: 2
---

# Fuels

- variables: `passenger_road_public_fec`, `passenger_private_public_fec`, `freight_road_fec`
- use_technology_fuel: 
    ```
    dim_fuel
    ├── fossil          # Fossil Fuel
    │	├── coal        # Coal
    │	├── gas         # Natural Gas
    │	├── oil         # Oil Products
    │	└── kerosene    # Kerosene
    ├── electricity     # Electricity
    ├── h2              # Hydrogen
    ├── methane         # Methane
    ├── ethanol         # Ethanol
    ├── biodiesel       # Biodiesel
    ├── biogas          # Biogas
    ├── saf             # Sustainable aviation fuel
    └── liquids         # Liquid fuels
    ```
    [Download csv file with labels](../files/fuel.csv)