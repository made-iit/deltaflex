# BOM

## Before you begin

This BOM is generated automatically from CAD. The BOM file contains two sections: 1) the assembly breakdown section and 2) the summary section.
The breakdown section is useful to understand the structure of the system, and also reflects the assembly sequence.
The summary section contains the full list of materials to be sourced.
- Components marked as `CUST` are custom components that need to be manufactured.
- Components marked as `COMM` are COTS components
- Components marked as `FAST` are fasteners
  
Note: please beware that the codes for fasteners (`FAST`) derive for our fasteners libray and might be difficult to interpret. For fasteners refer to the components' descriptions. 

## Manufacturing custom components

All plastic custom components were manufactured in Selective Laser Sintering (SLS) on a 3D Systems ProX SLS 6100 additive manufacturing unit in DuraformPA.


## BREAKDOWN

### Assembly: `MWS_021_A_001`
Description: DeltaFlex

| Code                              | Qt.y  | Description                                                                     | Type |
|-------|-------|-------|--------------|
|`MWS_021_G_003`| 1   | base assembly, DeltaFlex                                                        | Sub-Assem|
|`MWS_021_P_005`| 1   | lower support tower, DeltaFlex                                                  | Part     |
|`V4-12--_-_U5933_C`| 9   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M4X12                               | Part     |
|`MWS_021_G_001`| 3   | actuator module, DeltaFlex                                                      | Sub-Assem|
|`MWS_021_G_004`| 1   | main body w. switches                                                           | Sub-Assem|
|`ARDUINO_UNO`| 1   | Arduino UNO, Compass DHM cod. 19140023                                          | Part     |
|`ARDUINO_CNC_SHIELD`| 1   | Arduino CNC Shield, Compass-DHM cod. 08020210                                   | Part     |
|`POWER_SUPPLY`| 1   | Power supply                                                                    | Part     |
|`USB_B_CONN`| 1   | USB B connector                                                                 | Part     |
|`CONNECTOR_ARDUINO_MALE`| 1   | Adruino power supply connector                                                  | Part     |
|`MWS_021_P_009`| 1   | side panel, cover, DeltaFlex                                                    | Part     |
|`V3-12--_-_U5933_C`| 12  | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M3X12                               | Part     |
|`MWS_021_P_011`| 1   | side panel, cover, DeltaFlex                                                    | Part     |
|`MWS_021_P_010`| 1   | side panel, cover, DeltaFlex                                                    | Part     |
|`MWS_021_P_012`| 1   | side panel, cover, DeltaFlex                                                    | Part     |
|`MWS_021_P_014`| 1   | top panel, cover, DeltaFlex                                                     | Part     |
|`V4-20--_-_U5933_C`| 3   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M4X20                               | Part     |

### Sub-Assembly: `MWS_021_G_003`
Description: base assembly, DeltaFlex

| Code                              | Qt.y  | Description                                                                     | Type |
|-------|-------|-------|--------------|
|`MWS_021_P_004`| 1   | base plate, base assembly, DeltaFlex                                            | Part     |
|`MWS_021_P_007`| 4   | corner tower, base assembly, DeltaFlex                                          | Part     |
|`V6-20--_-_U5931_GC`| 4   | HEX. SOCKET HEAD CAP SCREW ISO4762 - UNI5931 M6X20                              | Part     |
|`MWS_021_P_008`| 4   | corner tower, base assembly, DeltaFlex                                          | Part     |
|`V6-16--_-_U5933_C`| 4   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M6X16                               | Part     |

### Sub-Assembly: `MWS_021_G_001`
Description: actuator module, DeltaFlex

| Code                              | Qt.y  | Description                                                                     | Type |
|-------|-------|-------|--------------|
|`MWS_021_P_003`| 1   | Main frame, motor support, DeltaFlex                                            | Part     |
|`NEMA_17_STEPPER`| 1   | Nema17 stepper motor                                                            | Part     |
|`MISUMI_HTPT14S2M060-K-P4`| 1   | Misumi HTPT14S2M060-K-P4  flanged timing pulley, S2M type, p=2, w=6, z=14       | Part     |
|`V3-12--_-_U5931_GC`| 3   | HEX. SOCKET HEAD CAP SCREW ISO4762 - UNI5931 M3X12                              | Part     |
|`MWS_021_G_002`| 2   | Timing belt roller, belt tensioner, DeltaFlex                                   | Sub-Assem|
|`S4-24--_-_I2338_B`| 2   | Dowel pin Ø4.0 x 24 stainless steel A2, DIN7, ISO2338B, VSM12771, UNI1707       | Part     |
|`D4--_-_I4032`| 2   | HEXAGON NUT ISO 4032 M4                                                         | Part     |
|`G4-30--_-_U5923_G`| 2   | Set screw, hex socket, M4,0 x 30,0, stainless steel A2, DIN913, ISO4026, UNI5923| Part     |
|`MISUMI_HTUN1274S2M-60`| 1   | Misumi HTUN1274S2M-60 polyurethane timing belt, S2M type, p=2, w=6, z=637       | Part     |

### Sub-Assembly: `MWS_021_G_002`
Description: Timing belt roller, belt tensioner, DeltaFlex

| Code                              | Qt.y  | Description                                                                     | Type |
|-------|-------|-------|--------------|
|`MWS_021_P_006`| 1   | Outer roller, DeltaFlex                                                         | Part     |
|`624-ZZ`| 2   | 624-ZZ radial ball bearing                                                      | Part     |

### Sub-Assembly: `MWS_021_G_004`
Description: main body w. switches

| Code                              | Qt.y  | Description                                                                     | Type |
|-------|-------|-------|--------------|
|`MWS_021_P_001`| 1   | main body, DeltaFlex                                                            | Part     |
|`OMRON_LIMIT_SWITCH`| 3   | Omron D2MQ miniature basic switch                                               | Part     |
|`V1_6-6--_-_ISO7045_CZ`| 6   | CROSS RECESSED SCREW ISO7045 M1.6X6 Z                                           | Part     |

## SUMMARY
| Code                               | Qt.y | Description                                                                    | Type |
|-------|-------|-------|-------------|
|`MWS_021_P_004`| 1   | base plate, base assembly, DeltaFlex                                             | `CUST`|
|`MWS_021_P_007`| 4   | corner tower, base assembly, DeltaFlex                                           | `CUST`|
|`V6-20--_-_U5931_GC`| 4   | HEX. SOCKET HEAD CAP SCREW ISO4762 - UNI5931 M6X20                               | `FAST`|
|`MWS_021_P_008`| 4   | corner tower, base assembly, DeltaFlex                                           | `CUST`|
|`V6-16--_-_U5933_C`| 4   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M6X16                                | `FAST`|
|`MWS_021_P_005`| 1   | lower support tower, DeltaFlex                                                   | `CUST`|
|`V4-12--_-_U5933_C`| 9   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M4X12                                | `FAST`|
|`MWS_021_P_003`| 3   | Main frame, motor support, DeltaFlex                                             | `CUST`|
|`NEMA_17_STEPPER`| 3   | Nema17 stepper motor                                                             | `COMM`|
|`MISUMI_HTPT14S2M060-K-P4`| 3   | Misumi HTPT14S2M060-K-P4  flanged timing pulley, S2M type, p=2, w=6, z=14        | `COMM`|
|`V3-12--_-_U5931_GC`| 9   | HEX. SOCKET HEAD CAP SCREW ISO4762 - UNI5931 M3X12                               | `FAST`|
|`MWS_021_P_006`| 6   | Outer roller, DeltaFlex                                                          | `CUST`|
|`624-ZZ`| 12  | 624-ZZ radial ball bearing                                                       | `COMM`|
|`S4-24--_-_I2338_B`| 6   | Dowel pin Ø4.0 x 24 stainless steel A2, DIN7, ISO2338B, VSM12771, UNI1707        | `FAST`|
|`D4--_-_I4032`| 6   | HEXAGON NUT ISO 4032 M4                                                          | `FAST`|
|`G4-30--_-_U5923_G`| 6   | Set screw, hex socket, M4,0 x 30,0, stainless steel A2, DIN913, ISO4026, UNI5923 | `FAST`|
|`MISUMI_HTUN1274S2M-60`| 3   | Misumi HTUN1274S2M-60 polyurethane timing belt, S2M type, p=2, w=6, z=637        | `COMM`|
|`MWS_021_P_001`| 1   | main body, DeltaFlex                                                             | `CUST`|
|`OMRON_LIMIT_SWITCH`| 3   | Omron D2MQ miniature basic switch                                                | `COMM`|
|`V1_6-6--_-_ISO7045_CZ`| 6   | CROSS RECESSED SCREW ISO7045 M1.6X6 Z                                            | `FAST`|
|`ARDUINO_UNO`| 1   | Arduino UNO, Compass DHM cod. 19140023                                           | `ELTR`|
|`ARDUINO_CNC_SHIELD`| 1   | Arduino CNC Shield, Compass-DHM cod. 08020210                                    | `ELTR`|
|`POWER_SUPPLY`| 1   | Power supply                                                                     | `COMM`|
|`USB_B_CONN`| 1   | USB B connector                                                                  | `COSM`|
|`CONNECTOR_ARDUINO_MALE`| 1   | Adruino power supply connector                                                   | `COSM`|
|`MWS_021_P_009`| 1   | side panel, cover, DeltaFlex                                                     | `CUST`|
|`V3-12--_-_U5933_C`| 12  | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M3X12                                | `FAST`|
|`MWS_021_P_011`| 1   | side panel, cover, DeltaFlex                                                     | `CUST`|
|`MWS_021_P_010`| 1   | side panel, cover, DeltaFlex                                                     | `CUST`|
|`MWS_021_P_012`| 1   | side panel, cover, DeltaFlex                                                     | `CUST`|
|`MWS_021_P_014`| 1   | top panel, cover, DeltaFlex                                                      | `CUST`|
|`V4-20--_-_U5933_C`| 3   | SOCKET FLAT HEAD SCREW  DIN 7991 - UNI 5933 M4X20                                | `FAST`|




