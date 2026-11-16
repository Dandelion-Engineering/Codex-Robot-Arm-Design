# R300B bill of materials and cost estimate

One prototype; USD, accessed15 November2026. Prices are planning evidence, not binding quotations. See each line for listed versus estimated basis. Quantity is net installed; order packs/spares may increase cost.

| Cost group | USD |
|---|---:|
| purchased mechanism | 2,875.61 |
| hardware | 152.90 |
| electrical allowance | 404.68 |
| raw material allowance | 618.00 |
| fabrication labor | 3,645.00 |
| parts material and electrical | 4,051.19 |
| assembly and basic wiring labor | 900.00 |
| nominal build | 8,596.19 |
| budget with 25pct contingency | 10,745.24 |

Engineering allowance:8h mechanical assembly +4h basic wiring at USD75/h; does not include controller development or qualification.

Tax/VAT, freight, tariffs, vendor minimum order packs, PC, bench, 1kg cube, test instrumentation, controller software, safety/stop-system design, additional brakes or guards, electrical qualification, machining rework and physical validation. No purchasing performed.

## Purchased components and hardware

| Item / full specification | Qty | Each USD | Extended USD | Source and basis |
|---|---:|---:|---:|---|
| CubeMars AK60-39 V3.0 KV80; 24 Nm | 2 | 448.90 | 897.80 | [Supplier](https://www.digikey.com/en/products/detail/cubemars/AK60-39-V3-0/28141870); Listed USD price; CubeMars Marketplace. Shoulder and elbow; confirm driver included and current mechanical drawing. |
| CubeMars AK60-6 V3.0 KV80; 3 Nm | 2 | 298.90 | 597.80 | [Supplier](https://www.digikey.com/en/products/detail/cubemars/AK60-6-V3-0-KV80/27612229); Listed USD price; CubeMars Marketplace. Yaw and wrist; selected integrated driver variant. |
| DH PGEA-100-26-W-F1-M1-L1-J0 | 1 | 816.00 | 816.00 | [Supplier](https://dh-robotics.eu/product/dh-robotics-pgea-100-26-w-electric-parallel-gripper/); EUR680 ex VAT; budget conversion EUR1=USD1.20. Brake, 24V, RS485, 1m cable, no fingertips. Supplier quote must confirm suffix configuration; conversion is an assumption, not a spot FX quote. |
| SKF 61818-2RS1, 90x115x13 | 2 | 200.00 | 400.00 | [Supplier](https://www.motion.com/products/sku/00143234); Engineering allowance; price quote required. Two sealed yaw bearings. |
| SKF 6002-2RSH, 15x32x9 | 3 | 54.67 | 164.01 | [Supplier](https://www.motion.com/es/products/sku/04670602); Listed USD price. Passive shoulder, elbow and wrist bearings. |
| DIN 7984 M3 x 8; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| DIN 965 M2 x 5; A2-70 | 8 | 0.60 | 4.80 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| DIN 965 M3 x 10; A2-70 | 4 | 0.60 | 2.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| DIN 965 M4 x 14; A2-70 | 4 | 0.60 | 2.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M3 x 10; 12.9 | 29 | 0.60 | 17.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M3 x 12; 12.9 | 8 | 0.60 | 4.80 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M3 x 14; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M3 x 20; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M3 x 6; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M4 x 10; 12.9 | 2 | 0.60 | 1.20 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M4 x 12; 12.9 | 3 | 0.60 | 1.80 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M4 x 14; 12.9 | 15 | 0.60 | 9.00 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M4 x 16; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M5 x 14; 12.9 | 4 | 0.60 | 2.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M5 x 20; 12.9 | 6 | 0.60 | 3.60 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M5 x 70; 12.9 | 6 | 1.25 | 7.50 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M6 x 25; 12.9 | 4 | 0.60 | 2.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 4762 M8 x 12; 12.9 | 3 | 0.60 | 1.80 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 7089 M6 washer 200 HV | 4 | 0.60 | 2.40 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 8734 3 m6 x 6 | 6 | 1.50 | 9.00 | [Supplier](https://chapmanbradshaw.co.uk/images/Product%20Datasheets/Dowels%20and%20Pins/Solid_and_Extractable_Dowels_Datasheet.pdf); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| ISO 8734 4 m6 x 12 | 6 | 1.50 | 9.00 | [Supplier](https://chapmanbradshaw.co.uk/images/Product%20Datasheets/Dowels%20and%20Pins/Solid_and_Extractable_Dowels_Datasheet.pdf); Engineering allowance; order by full standard and size. Counts from actual CAD bolt groups; individual head/shank solids are not separate purchases. Confirm small-quantity availability; cut/deburr a longer screw where a nonpreferred length is unavailable. |
| Bench attachment set: ISO4017 M8x60 class8.8 bolts x4; ISO7089 M8 washers x8; ISO10511 M8 class8 locknuts x4 | 1 | 18.00 | 18.00 | [Supplier](https://www.mcmaster.com/products/socket-head-screws/); Engineering allowance. For a 25mm through-bolted bench with four 50x50x3 steel backing plates. Adapt length only after measuring actual bench. |
| Selective shim stock 0.02/0.05/0.10 mm + medium-strength threadlocker | 1 | 35.00 | 35.00 | [Supplier](https://www.mcmaster.com/products/shim-stock/); Engineering allowance. Includes bearing endplay setting; keep threadlocker away from bearings and seals. |
| MEAN WELL GST360A48-C6P, 48V 7.5A 360W | 1 | 150.00 | 150.00 | [Supplier](https://www.cdiweb.com/products/detail/gst360a48c6p-mean-well-usa/740108/); Engineering allowance. External supply, not modeled. Regenerative voltage handling must be qualified before operation. |
| MEAN WELL RSD-60L-24, 18-72V input /24V 2.5A | 1 | 43.70 | 43.70 | [Supplier](https://www.bravoelectro.com/rsd-60l-24.html); Listed USD price. L input range required for48V; do not substitute G variant. |
| Waveshare USB-CAN-A SKU23635 | 1 | 18.99 | 18.99 | [Supplier](https://www.waveshare.com/USB-CAN-A.htm); Listed USD price. PC to motor CAN; controller application not supplied. |
| Waveshare USB TO RS485 (C) SKU34620 | 1 | 11.99 | 11.99 | [Supplier](https://www.waveshare.com/product/iot-communication/usb-to-rs485-c.htm); Listed USD price. Gripper communication. |
| Wiring, fuses, connectors, strain relief, enclosed DC distribution and regenerative clamp provision | 1 | 180.00 | 180.00 | [Supplier](https://www.mcmaster.com/products/electrical-enclosures/); Unspecified engineering allowance. Not an electrical release or a selected regenerative clamp design; final schematic, harness routing and stop behavior remain open. |

## Fabricated items

Blank prices include offcut/small-order allowance. Labor is an engineering estimate at USD100/hour, not a machine-shop quote. Part-specific STEP files and native sketches carry the profiles; `fabrication.md` controls fits and assembly.

| Custom part | Qty | Material | Finished envelope mm | Blank each USD | Hours each | Labor total USD |
|---|---:|---|---|---:|---:|---:|
| R3B-BASE | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 240.0 x 230.0 x 12.0 | 18.00 | 0.65 | 65.00 |
| R3B-ElbowAdapter | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 44.0 x 44.0 x 5.5 | 8.00 | 0.65 | 65.00 |
| R3B-ElbowIdler-CAP | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 44.0 x 44.0 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-ElbowPassiveShaft | 1 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 44.0 x 44.0 x 29.0 | 12.00 | 1.20 | 120.00 |
| R3B-ElbowStackSpacer | 3 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 9.0 x 9.0 x 1.0 | 4.00 | 0.20 | 60.00 |
| R3B-FINGER-Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 65.0 x 27.4 x 32.0 | 18.00 | 1.20 | 120.00 |
| R3B-FINGER-Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 65.0 x 27.4 x 32.0 | 18.00 | 1.20 | 120.00 |
| R3B-FOOT-Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 90.0 x 20.0 x 16.0 | 8.00 | 0.65 | 65.00 |
| R3B-FOOT-Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 90.0 x 20.0 x 16.0 | 8.00 | 0.65 | 65.00 |
| R3B-ForearmCheek_Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 237.0 x 82.0 x 6.0 | 22.00 | 1.00 | 100.00 |
| R3B-ForearmCheek_Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 237.0 x 82.0 x 6.0 | 22.00 | 1.00 | 100.00 |
| R3B-PAD | 2 | [Polyurethane 70 Shore A](https://psiurethanes.com/standard-urethane-sheeting/) | 36.0 x 20.0 x 3.0 | 20.00 | 0.75 | 150.00 |
| R3B-PAD-CLAMP | 4 | [304 stainless annealed](https://www.mcmaster.com/products/stainless-steel-sheets/) | 36.0 x 6.0 x 0.8 | 2.00 | 0.10 | 40.00 |
| R3B-PAD-FLANGE | 4 | [Polyurethane 70 Shore A](https://psiurethanes.com/standard-urethane-sheeting/) | 36.0 x 6.0 x 0.8 | 0.00 | 0.00 | 0.00 |
| R3B-SADDLE | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 78.0 x 54.0 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-SHAFT-WASHER 8.4 x 24 x 2 | 3 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 24.0 x 24.0 x 2.0 | 4.00 | 0.20 | 60.00 |
| R3B-ShoulderAdapter | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 44.0 x 44.0 x 2.5 | 8.00 | 0.65 | 65.00 |
| R3B-ShoulderIdler-CAP | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 44.0 x 44.0 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-ShoulderPassiveShaft | 1 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 44.0 x 44.0 x 26.0 | 12.00 | 1.20 | 120.00 |
| R3B-ShoulderStackSpacer | 3 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 9.0 x 9.0 x 2.0 | 4.00 | 0.20 | 60.00 |
| R3B-TIE-46 | 2 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 10.0 x 10.0 x 46.0 | 4.00 | 0.20 | 40.00 |
| R3B-TIE-90 | 4 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 10.0 x 10.0 x 90.0 | 4.00 | 0.20 | 80.00 |
| R3B-Tower_Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 92.0 x 121.0 x 6.0 | 14.00 | 0.80 | 80.00 |
| R3B-Tower_Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 92.0 x 121.0 x 6.0 | 14.00 | 0.80 | 80.00 |
| R3B-Turntable | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 160.0 x 160.0 x 8.0 | 18.00 | 0.65 | 65.00 |
| R3B-UpperCheek_Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 302.0 x 82.0 x 8.0 | 22.00 | 1.00 | 100.00 |
| R3B-UpperCheek_Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 302.0 x 82.0 x 8.0 | 22.00 | 1.00 | 100.00 |
| R3B-WRIST-DROP-Left | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 59.0 x 71.5 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-WRIST-DROP-Right | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 59.0 x 71.5 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-WristAdapter | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 34.0 x 34.0 x 3.0 | 8.00 | 0.65 | 65.00 |
| R3B-WristIdler-CAP | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 44.0 x 44.0 x 6.0 | 8.00 | 0.65 | 65.00 |
| R3B-WristPassiveShaft | 1 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 44.0 x 44.0 x 16.0 | 12.00 | 1.20 | 120.00 |
| R3B-YAW-HOUSING | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 140.0 x 140.0 x 48.0 | 55.00 | 2.00 | 200.00 |
| R3B-YAW-INNER-CAP | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 98.0 x 98.0 x 4.0 | 8.00 | 0.65 | 65.00 |
| R3B-YAW-SPINDLE | 1 | [C45E +N; certified Rp0.2 >= 300 MPa](https://www.westyorkssteel.com/files/c45.pdf) | 98.0 x 98.0 x 50.0 | 65.00 | 2.50 | 250.00 |
| R3B-YawMount | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 140.0 x 140.0 x 6.0 | 18.00 | 0.65 | 65.00 |
| R3B-YawOuterCap | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 140.0 x 140.0 x 3.0 | 18.00 | 0.65 | 65.00 |
| R3B-YawOuterSpacer | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 114.9 x 114.9 x 22.0 | 4.00 | 0.20 | 20.00 |
| R3B-YawSeat | 1 | [6061-T651; certified Rp0.2 >= 240 MPa](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) | 140.0 x 140.0 x 12.0 | 18.00 | 0.65 | 65.00 |
| Bench backing plate50x50x3, hole9 | 4 | [S235JR steel](https://www.thyssenkrupp-materials.rs/en/products/carbon-steel-flat-products) | 50 x 50 x 3 | 3.00 | 0.05 | 20.00 |
| Pin fit finishing and common machining setup/inspection | 1 | [Labor only]() |  | 0.00 | 4.00 | 400.00 |

Purchase certificates must establish specified material condition/minimum strength. Stock plate/bar must be thicker than the finished envelope to allow facing. Certified material/blank availability, final gripper suffix, small fastener lengths and vendor hole depths must be checked before committing a fabrication order.
