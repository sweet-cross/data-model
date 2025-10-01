---
title: tech_storage
parent: Dimensions
layout: default
nav_order: 7
---

# Storage technologies

{: .important }
Used in variables: `storage_installed_volume`, `storage_output`

```
tech_storage
├── thermal             # Thermal energy storage
│   ├── thermal_short   # Short term thermal energy storage
│   └── thermal_long    # Long term thermal energy storage
├── h2                  # Hydrogen
│   ├── h2_short        # Hydrogen-short-term
│   └── h2_long         # Hydrogen-long-term
├── electricity         # Electricity storage
│   ├── batteries       # Battery storage
│   └── phs             # Pumped hydro storage
├── methane             # Methane storage
├── liquid_fuels        # Liquid fuels storage
└── waste               # Waste storage
```

[Download csv file with labels](/instructions-data/files/tech_storage.csv)