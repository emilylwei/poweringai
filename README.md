## *Phase 1 - Establish the baseline grid*

- Using existing EIA data pull to calculate for each market (ERCOT, PJM, CAISO, MISO, and SPP):
  - 2025 average load
  - Peak load
  - Minimum load
  - Load factor


## *Phase 2 - Bring in the PNNL Data Center Atlas*

- Important values in this data set:
  - Growth scenario
  - Market-gravity assumption
  - State/region
  - Facility IT power in MW
  - Campus size
  - Cooling-energy demand
  - Cooling-water demand
  - Locational-cost score
  - Siting score
  - Geographic location

- Projects locations through 2035 using 4 annual electricity-demand growth scenarios of:
  - 3.71%
  - 5%
  - 10%
  - 15%

- PNNL excludes candidate locations that are:
  - More than 2 km from an electrical substation
  - More than 5 km from municipal water service
  - More than 2 km from high-speed fiber service
  - In high flood-risk areas
  - On steep slopes
  - Wetlands/protected lands/etc.

- Projected data-center MW + an actual siting methodology to study and critique


## *Phase 3 - Connect projected data centers to power markets*

- PNNL gives geographic data-center locations, so we'll need to map each projected facility to its power-market geography
- This is a geospatial join:
  - Introduces GeoPandas + geographic data + spatial joins


## *Phase 4 - Turn projected IT MW into actual grid load*


## *Phase 5 - Modify the real load curves*


## *Phase 6 - Estimate the physical power required*

- How much solar do we need?
  - Depending on capacity factor, annual energy matching, and 24/7 physical supply + batteries
- Later we can add:
  - Natural gas
  - Nuclear
  - Grid purchases
  - Solar + BESS
  - Mixed portfolios


## *Phase 7 - Economics*

- Electricity price
- Solar Capex
- BESS Capex
- PPA price
- NPV
