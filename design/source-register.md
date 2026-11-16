# R300B source register

Accessed15 November2026. Manufacturer facts, prices and engineering assumptions are distinguished in the report.

1. [CubeMars AK60-39 V3.0 KV80](https://www.cubemars.com/product/ak60-39-v3-0-kv80-robotic-actuator.html) - 24Nm rating,0.75kg actuator; manufacturer-controlled specification.
2. [CubeMars AK60-39 mechanical drawing](https://www.cubemars.com/images/202507/AK60-39-draw.jpg) - 18.5mm nose and stator/output/dowel interfaces.
3. [CubeMars AK60-6 V3.0 KV80](https://www.cubemars.com/product/ak60-6-v3-0-kv80-robotic-actuator.html) - 3Nm,0.38kg; drawing also linked in design/source-register.md.
4. [DH Robotics PGEA/PGIA catalogue V255](https://en.dh-robotics.com/wp-content/uploads/2025/06/DH_PGEAPGIA-catalog_V255.pdf) - Printed pages13-16 (PDF pages8-9): selection, force, brake, mass, mounting drawing and finger-length reference plots.
5. [DigiKey /CubeMars AK60-39 listing](https://www.digikey.com/en/products/detail/cubemars/AK60-39-V3-0/28141870) - USD448.90 listed unit price.
6. [DigiKey /CubeMars AK60-6 driver listing](https://www.digikey.com/en/products/detail/cubemars/AK60-6-V3-0-KV80/27612229) - USD298.90 listed unit price.
7. [DH Robotics Europe PGEA-100-26-W](https://dh-robotics.eu/product/dh-robotics-pgea-100-26-w-electric-parallel-gripper/) - EUR680 ex VAT; exact suffix/cable quote confirmation remains.
8. [SKF61818-2RS1 product sheet](https://cdn.skfmediahub.skf.com/api/public/0901d196802809de/pdf_preview_medium/0901d196802809de_pdf_preview_medium.pdf) - 90x115x13,0.29kg,19.5kN dynamic/17kN static ratings.
9. [SKF-authored6002-2RSH product sheet](https://www.kalasanati.com/Portals/0/FaraShopFiles/Catalogue/Bearing/SKF/Deep%20Groove/6002-2RSH.pdf) - 15x32x9,0.03kg,5.85/2.85kN dynamic/static.
10. [Motion SKF61818-2RS1](https://www.motion.com/products/sku/00143234) - Purchasing route; price is a USD200 engineering allowance.
11. [Motion SKF6002-2RSH](https://www.motion.com/es/products/sku/04670602) - USD54.67 listed unit price.
12. [Alro aluminum plate catalogue](https://www.alro.com/Resources/WebResources/AlroCom/Literature/PDFs/7%20-%20Aluminum-Plate.pdf) - 6061-T651 stock route. Project minimum strength must be certified, not inferred from typical values.
13. [West Yorkshire Steel C45 supply sheet](https://www.westyorkssteel.com/files/c45.pdf) - Normalized stock route; order must explicitly confirm C45E+N and the project minimum strength.
14. [Gmsh reference manual](https://gmsh.info/doc/texinfo/gmsh.html) - STEP meshing, second-order elements and high-order optimization.
15. [CalculiX CrunchiX2.22 manual](https://www.dhondt.de/ccx_2.22.pdf) - C3D10, gravity, stress/displacement output and solver input conventions.
16. [MEAN WELL RSD-60 datasheet](https://www.meanwell.com/Upload/PDF/RSD-60/RSD-60-spec.pdf) - L input range18..72V,24V output; distinguishes incorrect G substitution.
17. [MEAN WELL GST360A datasheet](https://www.meanwellaustralia.com.au/sites/default/files/2025-04/MEAN%20WELL%20GST360A%20DATA%20SHEET.pdf) - 48V/7.5A external supply specification; electrical system not released.
18. [Waveshare USB-CAN-A](https://www.waveshare.com/USB-CAN-A.htm) - SKU23635,USD18.99 listing.
19. [Waveshare isolated USB TO RS485(C)](https://www.waveshare.com/product/iot-communication/usb-to-rs485-c.htm) - SKU34620,USD11.99 listing.
20. [PSI Urethanes standard sheeting](https://psiurethanes.com/standard-urethane-sheeting/) - 70A stock route. Does not establish pad-cube friction.
21. [McMaster-Carr socket-head screw range](https://www.mcmaster.com/products/socket-head-screws/) - Commercial procurement route; full standards/sizes and engineering allowances in BOM.
22. [FreeCAD expression documentation](https://github.com/FreeCAD/FreeCAD-documentation/blob/main/wiki/Expressions.md) - Native expressions, trigonometric functions, min/max and conditionals.
23. [Bravo Electro RSD-60L-24](https://www.bravoelectro.com/rsd-60l-24.html) - USD43.70 listing; primary MEAN WELL datasheet controls current/input specification.

Additional interface evidence: [AK60-6 drawing](https://store.tmotor.com/images/202410/221729588988317529.jpg); [SKF61818 abutment dimensions](https://docs.rs-online.com/7331/A700000007139745.pdf).
