---
title: trn_mode_private
parent: Sets
layout: default
nav_order: 14
---

{: .important }
Used in variables: `passenger_transport_useful_energy_demand`

# Modes passenger transport

```
trn_mode_private
├── passenger_rail          # Rail transport, it includes trains, rack railways, funiculars and aerial cableways
├── passenger_road          # Road transport
│   ├── road_public         # Public road transport
│   │   ├── tram            # Tram
│   │   ├── trolley         # Trolley buses
│   │   └── bus             # Buses
│   ├── road_private        # Private road transport
│   │   ├── passenger_car   # Private cars
│   │   ├── motorcycle      # Motorcycles
│   │   └── moped_ebike     # Mopeds and e-bikes
│   └── slow_private        # Slow private transport
│      ├── bike             # Bicycles
│      └── foot             # By foot
└── other_private           # Other private transport mode
```
[Download csv file with labels](/data-model/files/trn_mode_private.csv)

