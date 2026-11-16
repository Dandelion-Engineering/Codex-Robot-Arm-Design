# R300B fabrication and assembly schedule

This is a prototype design package for shop review. Dimensions are millimeters. The editable assembly and individual STEP solids define nominal profiles. This schedule controls materials, threads, fits and assembly details that a solid envelope cannot describe. Release to machining still requires a machinist to check cutter access, certificates and the actual purchased interfaces. There is no completed tolerance-stack or GD&T drawing release.

## Material and process rules

* Structural aluminum: **6061-T651 plate, certified Rp0.2 >=240 MPa**. Mill from oversize plate; do not substitute cast tooling plate or as-printed material. Small turned ties/adapters may also be machined from plate. An equivalent T6511 bar substitution requires the same minimum strength certificate. No welding, bending or post-machining heat treatment is assumed. Bare machined prototype finish; corrosion finish is optional only if bearing seats/dowels/threads are masked and dimensions reinspected.
* Shafts, yaw spindle, stack spacers and thick retaining washers: **C45E +N, certified Rp0.2 >=300 MPa**, machined from normalized stock. Source-specific chemistry/condition must be confirmed; a generic C45 listing is not certification of C45E. Use a100mm blank for the98mm spindle flange so the procurement strength requirement remains explicit. Bearing journal finish Ra<=0.8 micrometer, seat runout<=0.02mm.
* Pad clamps: annealed304 stainless sheet0.8mm. Pads: cast polyurethane70 Shore A, target36x32 overall, central36x20 contact region3mm thick and two36x6x0.8 integral edge flanges. The CAD displays the flanges as separate touching bodies; fabricate each pad as **one piece**, not three bonded pieces. Machine/trim or mold the profile; actual friction and creep must be measured.
* Unless specified: non-fit linear dimensions +/-0.10, finished plate thickness +/-0.05, mating-face flatness0.05. Paired pivot-center spacing220/155 +/-0.03, axis parallelism0.05 over100, interface hole position within0.05 relative to pivot datum. Bearing shoulders square0.02. Internal tool corners may have R1 where nonmating, but do not remove the finger's specified R3. Break exposed edges0.3; no knife edges. These are proposed shop tolerances, not an accumulated clearance proof.
* Modeled pilot bores represent **tapped holes**, not smooth clearance holes. Tap after drilling. Diameters: M2x0.4 pilot1.6; M3x0.5 pilot2.5; M4x0.7 pilot3.3; M5x0.8 pilot4.2; M6x1 pilot5.0; M8x1.25 pilot6.8. Provide full thread to scheduled engagement, using bottoming/thread milling where necessary; blind drill depth must allow tool point and avoid breakthrough into adjacent features. Native CAD has flat-bottom idealized drill ends.
* Commercial bolt heads and motor bodies are envelope geometry. Screw drive recesses, helical threads, motor internals and cable connectors are not modeled. Use the specified head standard; ISO10642 and DIN965 heads are not interchangeable without checking countersink diameter. Small unusual lengths can be cut from the next longer commercial screw, deburred and gauged; fabrication allowance includes this. Maintain full vendor thread engagement and never bottom a screw.

## Main fabricated parts

The full per-part quantities, envelopes, material allowances and STEP links are in [BOM.md](BOM.md) and [fabricated-parts.json](fabricated-parts.json).

| Part family | Nominal construction | Controlled details |
|---|---|---|
| Bench plate |240x230x12, one|Four9 clearance holes at x+/-100,y+/-95; six M5x0.8 taps on PCD126,10 full-thread depth from top. Through-bolt to bench, never rely on loose standing weight.|
| Yaw motor mount / seat |OD140,6 /12 thick|Mount has six M3 rear holes PCD68 and underside counterbores5.8x3.2; seat ID102; six M5 clearance on PCD126.|
| Yaw outer housing |OD140,48 high, bore115H7|Lower bearing z30..43, upper z65..78. Outer-ring spacer22 long, OD114.9 ID102. Six M5 head counterbores9x5.5; six M3 retainer taps PCD124 phase30. Bore/shoulders in one setup.|
| Yaw outer cap |OD140 ID102,3 thick|M3 low-head seats5.8x2; M5 head clearances. Cap top81, turntable underside82: nominal1mm running clearance. Cap must not scrape after tolerance/endplay adjustment.|
| Yaw spindle |OD90 journals, ID81 lower bore, integral OD98x2 lower flange|One-piece C45E; upper17mm web has six M3 through holes PCD20 and six M5 taps10 deep PCD64. Removable OD98x4 inner cap permits assembly from above. Journal90g6, shaft/cap axial stack selectively shimmed.|
| Turntable |160 envelope,8 thick|Six M5 clamp holes PCD64; four M6 taps at x+/-15,y+/-58,7.4mm nominal engagement.|
| Tower cheeks and feet |Two6mm cheeks; two90x20x16 feet|Shoulder axis165 above bench. Right bore58.2 and eight M3 stator holes PCD68 phase22.5. Left bearing pocket. Horizontal M5 feet taps10 deep; vertical M6 clearance. No loose angle feet.|
| Upper cheeks |Two8mm plates,220 centers,82 wide end lobes|Inside faces y+/-45; outside+/-53. Three M4 output clearances PCD30 phase90; right plate adds three4mm dowels PCD28.5 phase30. Right elbow bore58.2; eight M3 stator holes PCD68. Left elbow bearing pocket32H7x4. Four OD10x90 cross ties with M4 taps10 both ends.|
| Forearm cheeks |Two6mm plates,155 centers|Inside faces y+/-23; outside+/-29. Same root M4/dowel circles. Right wrist stator bore50, six M3 PCD68. Left wrist bearing pocket. Two OD10x46 cross ties.|
| Output adapters |Shoulder44ODx2.5; elbow44ODx5.5; wrist34ODx3|All ID15; manufacturer bolt patterns. AK60-39 nose is **18.5mm** long,57 diameter, not the baseline6mm envelope. Eight stator screws and three output screws must be checked against the current drawing.|
| Passive bearing caps |Three44ODx6|ID26 through; recess32.2x5; three M3 holes PCD38. Bearing seat32H7x4 in adjoining plate;6002 bearing9 wide. Use shims to leave0.05..0.15 outer-ring axial clearance, with cap still bolted firmly to plate.|
| Passive shafts |15g6 journal;20 shoulder;44 flange|Shoulder total26, elbow29, wrist16 long. Bearing journal9 long. Flange6 thick, wrist4.5. Axial M8 tap12 full-thread depth; custom8.4x24x2 retaining washer. M4 flange taps through6, wrist M3 through4.5. Radius at15 journal shoulder<=0.3 to clear SKF6002 corner.|
| Wrist drops / saddle |Two6mm drop plates;78x54x6 saddle|Wrist center70 above gripper center. Six M3 output holes PCD20. Two M4 vertical taps9 deep per drop at x=-15,24. Saddle mounts on PGEA broad face: four M3 holes20x20 centered78 behind front jaw face; two3mm locators at mid-x, y+/-10.|
| Fingers |Two32mm high,10mm root and5mm cantilever|Root x55..65, cantilever to120, R3 inside root. M4 clearance4.5 and7.5x4 counterbore; two3mm blind locators3.2 deep, z+/-5.25. Four M2 pad-clamp taps4 deep. Pads straddle the cube center longitudinally.|

**Bearing fits are low-speed prototype selections.** H7/g6 enables removal and axial shimming. Alternating/rotating bearing loads can cause creep with loose fits; inspect fit and fretting in the trial. A bearing specialist may specify transition/interference fits after measuring actual loads and temperature. That change requires an assembly/endplay review; the current report does not claim bearing life or preload validation.

**Dowel fits:** buy ISO8734 m6 pins, then grind the3mm vendor-engaging tip to h6. Selectively ream the custom seat to a light transition fit and retain the pin there. Do not press an m6 pin blindly into the manufacturer's0/+0.02 locating bore. Three4x12 pins per AK60-39 joint bridge the driven cheek and adapter; final3mm enters the vendor's3.5mm hole. Use one round and one relieved locator where a two-pin mount could overconstrain assembly. Vendor mounting drawings control the permissible relief/slot direction.

## Fastener stack and engagement schedule

| Interface | Installed screw | Stack before female thread | Nominal engagement / available |
|---|---|---|---|
| AK60-39 shoulder output |3 M4x16|2 spacer +8 cheek +2.5 adapter|3.5 /4 manufacturer depth|
| AK60-39 elbow output |3 M4x16|1 spacer +6 cheek +5.5 adapter|3.5 /4|
| AK60-6 wrist output |6 M3x14|6 drop +3 adapter|5 /6|
| AK60-6 yaw output |6 M3x20|17 spindle web|3 /6|
| Shoulder/elbow stator |8 M3x10 /8 M3x12|6 tower /8 upper|4 /6|
| Wrist stator |6 M3x10|6 forearm|4 /6|
| Yaw rear mount |6 M3x6|2.8 remaining plate|3.2 /3.5|
| Upper /fore cross ties |M4x14|8 /6 plate|6 /8 into10-deep taps|
| Idler flange |Shoulder M4x14; elbow M4x12; wrist M3x10|8 /6 /6 plate|6 /6 /4 in6 /6 /4.5 flange|
| Idler axial |M8x12|2 washer|10 into12 full thread;2mm nominal bottom clearance|
| PGEA body |4 DIN965 M3x10 overall|6 saddle (includes countersink)|4 /5|
| Saddle to wrist |4 DIN965 M4x14 overall|6 saddle|8 /9|
| PGEA fingertip |1 M4x10 per jaw|6 root after counterbore|4 /5|
| Pad clamps |4 DIN965 M2x5 per finger|0.8 strip +0.8 pad flange|3.4 /4|
| Tower feet horizontal |4 M5x14|6 tower|8 /10|
| Tower feet vertical |4 M6x25|1.6 washer +16 foot|7.4 /8 turntable|
| Turntable /inner cap |6 M5x20|8 table +4 cap|8 /10 spindle|
| Yaw housing |6 M5x70|60.5 stack below recessed head|9.5 /10 base|
| Outer cap |6 DIN7984 M3x8|1 remaining cap thickness|7 /8 housing tap|

Nominal lengths above include no generic lock washer. Inspect the actual screw's maximum length, head height and thread runout. At the M5 housing joint, add a selective0.3..0.5mm shim under the head or shorten the screw after stack measurement if needed to guarantee bottom clearance. Retaining washers remain in contact with the bearing inner ring. Such selective shims are in the BOM allowance; they are not a modeled operating clearance claim. Use manufacturer tightening limits in bought-in aluminum threads. Establish low custom-joint torque from strip capacity and a measured preload trial; a grade12.9 screw does not make its aluminum female thread grade12.9.

## Assembly sequence and access

1. Inspect vendor mount faces/hole circles and material certificates first. Finish/ream mating parts in a common jig; dry-fit all paired axes. Keep the external bench hardware and wiring outside the arm's moving envelope.
2. Fit yaw motor to the mount from below, then mount/seat to base. Seat lower bearing in the housing; introduce the spindle without the removable upper cap. Fit outer spacer, upper bearing and outer cap; shim axial stack. Access yaw motor-output screws through the spindle web before fitting inner cap/turntable. Tighten housing screws before the turntable covers their heads. Check free rotation and1mm cap clearance.
3. Attach feet/towers to turntable. Fit shoulder actuator, driven adapter/dowels/upper plate, then passive shaft and bearing cap. Tighten the idler flange from inside while the opposite plate/cross ties are accessible. Fit axial retaining washer from outside. Repeat elbow and wrist. Do not fully assemble both cheeks before inserting inaccessible stator/output screws; final cross ties close each stage.
4. Bolt saddle to wrist drops **before** bolting gripper onto saddle; its underside countersunk screws become covered by the gripper. Locate and bolt the PGEA from above using its four broad-face mounts. Fit each finger to its jaw using the front counterbore and two locators; fit integral pads and recessed strips last.
5. Through-bolt the base to a bench using four M8 bolts, large backing plates and locknuts. The assumed25mm bench is an interface description, not a strength result for an unknown bench. Verify substrate, backing access, bolt length and resistance to25Nm overturning. A freestanding arm can tip and is outside the operating definition.
6. Route flexible motor/CAN/gripper cables with independent strain relief and service loops. Cable envelopes, connector protrusions and wrench access have not undergone a full3D swept-volume study. Hand-cycle without power throughout the allowed range before wiring qualification; check bend radii and every moving pinch gap. No continuous yaw rotation is allowed.

## Commissioning criteria still open

Before a live1kg lift: inspect all fits/engagements, measure joint play, verify cable clearance and bench attachment, verify motor torque/current calibration and holding temperature, validate software limits/trajectory/stop behavior and regenerated bus voltage, measure each jaw force at the actual fingertip and dry pad-cube friction, and perform incremental payload trials with a catch/support. Confirm gripper guide load acceptance with DH Robotics for this orientation: the published Fz and moment limits are not a complete transverse-load interaction rule. The gripper brake retains only its jaws; it does not brake the arm's pitch joints on power loss. Whole-arm power-loss retention and an emergency-stop strategy remain unresolved design requirements for unattended or exposed operation.
