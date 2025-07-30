# 1.4.1
- Prevented part upgrade icon dummy parts from appearing in VAB part list in sandbox mode
- Fixed N2F4 part upgrade tech tree placement when not using Community Tech Tree
# 1.4.0
- Added Aniline
- Shifted some part upgrades down the tech tree:
  - HTP: General Rocketry → Basic Rocketry
  - TEATEB: Advanced Rocketry → General Rocketry
  - NTO: Propulsion Systems → Advanced Rocketry
# 1.3.0
- Added part upgrade activation system which keeps part upgrades and associated switch subtypes hidden if unused
# 1.2.0
- Added IWFNA (Nitric acid)
- Balanced HTPB and PBAN cost
- Changed resource colour definitions to use hex codes for modules that can't parse colour names
# 1.1.0
- Added Ethanol
- Changed Kerosene and NTO colours
# 1.0.0
- Release
- Added HTPB and PBAN
- Changed TEATEB display name to "TEA-TEB"
# 0.5.0
- Added part upgrades for chemical resources (many of which were split from Chemical Propulsion 0.5.1)
- Added TEATEB (for Chemical Propulsion kerolox ignition)
- Rebalanced HTP cost to 0.5 per unit
- Minor localization tweaks
# 0.4.1
- Added N2F4
- Added "Liquid" to cryogenic resource names
- Added resource icon assets
# 0.4.0
- Renamed from "Immersive Chemical Core" to "Chemical Core"
# 0.3.1
- Readded tank definitions for stock liquids (LiquidFuel, Oxidizer and MonoPropellant) for better control of tank switching
- Fixed units-per-volume in B9 tank types
# 0.3.0
- Added HTP tank definition
- Balanced HTP cost to a more reasonable 0.2 per unit (vs. original CRP 2.1465!?)
- Added common resource colours to be used in part switches
- Added auto-computing of tank masses using a formula back-derived from CryoTanks definitions, keeps everything consistent and makes adding new resources simpler
# 0.2.0
- Add CryoTanks flagging system to add generic boiloff configs to flagged parts
- Add fuel tank switcher title
# 0.1.0
- Pre-release
- Added B9 tank types for stock propellants and a variety of Community Resource Pack resources intended to be used throughout the Chemical Technologies mod suite:
  - Stock resources:
    - LiquidFuel
    - Oxidizer
    - MonoPropellant
    - XenonGas
  - Storable chemicals:
    - LqdAmmonia
    - LqdCO2
    - NTO
    - Hydrazine
    - Kerosene
    - Pentaborane
    - Water
  - Cryogenic chemicals:
    - LqdCO
    - Diborane
    - LqdFluorine
    - LqdHydrogen
    - LqdMethane
    - LqdNitrogen
    - LqdOxygen
- Added CryoTanks boiloff configs for applicable B9 tank types: