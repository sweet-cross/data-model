---
title: tech_generation
parent: Dimensions
layout: default
nav_order: 2
---

# Electricity generation technologies

```
tech_generation
├── thermal							# Thermal power plants
│	├── methane_pp					# Methane (includes natural gas, biogas, biomethane) power plant
│	│	├── methane_chp				# Methane (includes natural gas, biogas, biomethane) CHP
│	│	│	├── methane_chp_woccs	# Methane (includes natural gas, biogas, biomethane) CHP without CCS
│	│	│	└── methane_chp_ccs		# Methane (includes natural gas, biogas, biomethane) CHP with CCS
│	│	├── methane_oc				# Methane (includes natural gas, biogas, biomethane) open cycle
│	│	│	├── methane_oc_woccs	# Methane (includes natural gas, biogas, biomethane) open cycle without CCS
│	│	│	└── methane_oc_ccs		# Methane (includes natural gas, biogas, biomethane) open cycle with CCS
│	│	└── methane_cc				# Methane (includes natural gas, biogas, biomethane) combined cycle
│	│		├── methane_cc_woccs	# Methane (includes natural gas, biogas, biomethane) combined cycle without CCS
│	│		└── methane_cc_ccs		# Methane (includes natural gas, biogas, biomethane) combined cycle with CCS
│	├── coal_pp						# Coal power plant
│	│	├── coal_chp				# Coal CHP
│	│	│	├── coal_chp_woccs		# Coal CHP without CCS
│	│	│	└── coal_chp_ccs		# Coal CHP with CCS
│	│	├── coal_oc					# Coal open cycle
│	│	│	├── coal_oc_woccs		# Coal open cycle without CCS
│	│	│	└── coal_oc_ccs			# Coal open cycle with CCS
│	│	└── coal_cc					# Coal combined cycle
│	│		├── coal_cc_woccs		# Coal combined cycle without CCS
│	│		└── coal_cc_ccs			# Coal combined cycle with CCS
│	├── liquids_pp					# Liquid fuel power plant
│	│	├── liquids_chp				# Liquid fuel CHP
│	│	│	├── liquids_chp_woccs	# Liquid fuel CHP without CCS
│	│	│	└── liquids_chp_ccs		# Liquid fuel CHP with CCS
│	│	├── liquids_oc				# Liquid fuel open cycle
│	│	│	├── liquids_oc_woccs	# Liquid fuel open cycle without CCS
│	│	│	└── liquids_oc_ccs		# Liquid fuel open cycle with CCS
│	│	└── liquids_cc				# Liquid fuel combined cycle
│	│		├── liquids_cc_woccs	# Liquid fuel combined cycle without CCS
│	│		└── liquids_cc_ccs		# Liquid fuel combined cycle with CCS
│	├── hydrogen_pp					# Hydrogen thermal power plant
│	│	├── hydrogen_chp			# Hydrogen CHP without CCS
│	│	└── hydrogen_cc				# Hydrogen combined cycle without CCS
│	├── wood_pp						# Wood power plant
│	│	├── wood_chp				# Wood CHP
│	│	│	├── wood_chp_woccs		# Wood CHP without CCS
│	│	│	└── wood_chp_ccs		# Wood CHP with CCS
│	│	└── wood_cc					# Wood combined cycle
│	│		├── wood_cc_woccs		# Wood combined cycle without CCS
│	│		└── wood_cc_ccs			# Wood combined cycle with CCS
│	├── waste_pp					# Waste incinerators
│	│	├── waste_chp				# Waste CHP
│	│	│	├── waste_chp_woccs		# Waste CHP without CCS
│	│	│	└── waste_chp_ccs		# Waste CHP with CCS
│	│	└── waste_cc				# Waste combined cycle
│	│		├── waste_cc_woccs		# Waste combined cycle without CCS
│	│		└── waste_cc_ccs			# Waste combined cycle with CCS
│	└── nuclear						# Nuclear
├── electrochemical					# Electrochemical
│	├── fuel_cell_h2				# Fuel cell using hydrogen
│	└── fuel_cell_methane			# Fuel cell using methane
├── renewable						# Renewables
│	├── hydro						# Hydopower
│	│	├── hydro_dam				# Hydro Dams
│	│	└── hydro_ror				# Run-off-river
│	├── spv							# Solar PV
│	│	├── spv_rooftop				# Rooftop solar PV
│	│	├── spv_facade				# Facade solar PV
│	│	└── spv_mountain			# Mountain solar PV
│	├── wind						# Wind
│	│	├── wind_on					# Wind onshore
│	│	└── wind_off				# Wind offshore
│	└── geothermal_pp				# Geothermal
├── renewable_other					# Other renewables
├── imports							# Imports of electricity
└── storage_elec					# Electricity storage
    ├── battery_out					# Discharge of batteries
    └── phs_out						# Discharge of pumped hydro storage
```
[Download csv file with labels](files/tech_generation.csv)
 

- Used in variables: `electricity_supply`, `electricity_supply_typical_day`
