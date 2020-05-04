# "PTFE" FDM printable BMG Bondtech extruder for Prusa

 This design is based on [MarcoZ76's Bondtech BMG Upgrade MK3S FDM printable new sensor integrated](https://www.thingiverse.com/thing:3469271) and [Bondtech BMG Prusa MK3S/MK2.5S v2 FDM printable + RHD ver.C fan Shroud](https://www.thingiverse.com/thing:3754163/files) with some modify to maker the part easier to be printed with FDM printer, added PTFE tube as filament path to fix the jamming problem of non-smooth printed filament path.

### You will need [bear X axis](https://www.thingiverse.com/thing:3716110) for this extruder(v1).

## Feature

- Use PTFE tube instead of printed filament path that might cause jam if the printed path is not smooth enought.(v1 and v2)
- Lighter body(v1 mod)
- Custom support built in on STL(v1 and v2)
- Accessable to the gear for manual control.(v1 and v2)

## Require printed parts(v1)

| Part name | Link | Other option |
|---|---|---|
| Nozzle  duct | [MK3 RHD Fan Duct Rev. C](https://www.thingiverse.com/thing:3249344) | [Micro-tweaks to Nozzle RHD Rev C for Slic3r](https://www.thingiverse.com/thing:4054462) |
| Nozzle duct mounter | [MK3 Nozzle RHD Rev. C Support for FDM Printable Bondtech BMG](https://www.thingiverse.com/thing:3429508) | - |
| X carrier | [Bondtech_BMG_Upgrade_MK3S_sensor_Bear_carriage.stl](https://www.thingiverse.com/thing:3469271/files) | - |
| Body front | PTFE-BMG-body-front.stl |  |
| Body back | PTFE-BMG-body-back.stl |   |
| Filament sensor level | 3469271__fs-level.stl |   |
| Hingle | 3469271_Hinge_with_2mm_recession.stl |   |
| Filament sensor cover | 3469271__Sensor_cover_PC4-M10_new.stl or 3469271__Sensor_cover_PC4-M6_new.stl |   |
| PTFE cutter guide(base & cap) | PTFE-cutter-guide-base.stl & PTFE-cutter-guide-cap.stl |   |

## Require printed parts(v2)

| Part name | Link | Other option |
|---|---|---|
| Nozzle  duct | [MK3 RHD Fan Duct Rev. C](https://www.thingiverse.com/thing:3249344) | [Micro-tweaks to Nozzle RHD Rev C for Slic3r](https://www.thingiverse.com/thing:4054462) |
| Nozzle duct mounter | [MK3 Nozzle RHD Rev. C Support for FDM Printable Bondtech BMG](https://www.thingiverse.com/thing:3429508) | - |
| X carrier | Bear Bondtech mounter | Standard bondtech carrier also work on stock mk3?(not tested) |
| Body front | v2-ptfe-body-front..stl |  |
| Body back | v2-ptfe-body-back.stl |   |
| Filament sensor level | v2-fs-lever.stl | Use the fix version instead. This version has extend the level by 0.5mm to address the unstable trigger problem in the original design  |
| Sensor ballbearing adapter | v2-adapter-printer.stl |   |
 Hingle | v2-hingle.stl |  |
| Filament sensor cover | v2-Sensor_Cover_MK3s.stl | v2-Sensor_Cover_MK3s-M5x08.STL, v2-Sensor_Cover_MK3s-M6x1.stl |
| PTFE cutter guide(base & cap) | PTFE-cutter-guide-base.stl & PTFE-cutter-guide-cap.stl |   |

## Require part

| Part name | Link |  |
|---|---|---|
| 1x Shaft Assembly  | https://www.bondtech.se/en/product/shaft-assembly |  |
| 2x Ball Bearing 5x8x2.5  | https://www.bondtech.se/en/product/ballbearing-5x8x2-5/ |  |
| 1x Motor Gear | https://www.bondtech.se/en/product/motor-gear/ |  |
| 1x 1.75 / 5.0 Bontech Drivergear kit. | b | No need if you own a MK3 |
| 1x Thumbscrew Assembly | https://www.bondtech.se/en/product-category/spare-parts/thumbscrew-assembly/ | Can use a long M3 bolt instead |

## Assemply guide

- You will need to use the ptfe cutting guide to cut and file down the ptfe tube. USe a small file or a rotaty tool to file down about 0.5mm the side of the tube.
- Other step is the same as on the Bondtech guide.

## Print setting(Prusa slicer)
- 0.2mm layer height
- No support