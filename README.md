# Collection of K3 Modifications

**Beacon Compatible Nozzle Wiper and Purge Bucket**<br>
A modified nozzle wiper and purge bucket that works with the beacon probe instead of the default Quickdraw. It replaces the magnet activated swing arm used by Quickdraw with a fixed arm and ensures all parts are lower than the bottom of the beacon PCB.

https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-Beacon_Nozzle_Wiper<br>
<br>

**Glueless Tophat using M5 bolts**<br>
A redesign of the K3 tophat that replaces the printed dowel pins (which often needed to be glued together for rigidity) with M5 bolts and heat set inserts (or hex nuts). This allows the tophat to be more rigid and have less gaps for a better heated chamber.

https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-M5_Tophat<br>
<br>

**Wago Mount for the Heated Bed**<br>
A small Wago mount that holds six of the two conductor Wagos for connecting the bed wires, thermistor, a ground wire, and an inline thermal fuse. The Wago mount fits under the bed between the rear bed mount and the (small) corner brackets. An eight Wago mount is listed below if more connections are desired.

https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-Wago_Bed_Mount<br>
<br>

**Detachable Spool Holder**<br>
The default spool holder is very minimal and not very easy to remove. This spool holder allows the protruding part to be removed easily and uses a piece of PTFE tubing as the bearing surface (based on the Voron Switchwire spool holder).

https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-Spool_Holder<br>
<br>

**Modified Electronic Box Panels, Grommets, and Brackets**<br>
Alternate electronic box panels that are dual tone and slightly thinner for a sleeker look. Also including are some alternate grommets for better wiring and chamber heating, and alternate electronic brackets to make assembly easier. Dual tone panels by Karabox that are the same thickness as the default panels are listed below.

https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-Electronic_Box<br>
<br>

**Sherpa Micro with Fixed Idler and Integrated PTFE Collet**<br>
A modified (RIDGA compatible) Sherpa Micro extruder that is based on the fixed idler Micro from the official github but has an integrated PTFE collet. A non fixed idler version with an integrated PTFE collet by Ryan G. is listed below. Note that for most K3 builds you will want a mirrored Sherpa Micro, which can be done in the slicer.  

https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Extruders/Sherpa_Micro/Extruder_Mods/everycoloryouare-Fixed_Idler_Micro_and_Collet<br>
<br>

**XY Gantry Pulley/Idler Alignment Tool**<br>
The stock instructions for selecting the shim placement for the idler and pulley stacks on the XY gantry assumes very specific dimensions for the motion pieces. Fabreeko later added their own instructions for the pulleys and idlers they included. An alternate method is to use a small printed tool that allows you to determine your own shims stacks for any sized pulley or idler by manually adding shims until the indexed belt locations on the printed tool align with the pulleys and idlers.

[Github](https://github.com/everycoloryouare/Annex-Engineering_User_Mods/tree/main/Printers/K3/everycoloryouare-Alignment_Tools/XY_Pulley_Shim_Tool)<br>
<br>

# Userful Resources

**Annex Example Klipper Configurations**<br>
Due to license related disagreements with mainline Klipper devs, Annex decided to "officially" move to using Danger Klipper as the recommended control software. Normal Klipper still works fine for the most part (see below), but the Klipper configs for the various Annex Printers were moved to its own repository so the licenses could be better separated (my personal interpretation of the move).<br>

[Github](https://github.com/Annex-Engineering/ANNEX-Printer-Firmware/tree/main/Klipper_and_Klipper_Derivatives/K3)<br>
<br>

**Quickdraw and Dockable Probe Module**<br>
For a while Annex had maintained an independent dockable_probe.py module for use with the Quickdraw z probe option which is the default option on the K3. Unfortunately, Klipper has never fully embraced the module and has refused to include it in mainline and eventually introduced changes that broke the original module. If you wish to use Quickdraw you have a couple options, 1) Use a slightly older version of Klipper and the dockable_probe module, 2) Switch to Danger Klipper which has native dockable probe support among many other new features, or 3) use the macros based approach used by Klicky and similar probes.

[Dockable_Probe Github](https://github.com/Annex-Engineering/ANNEX-Printer-Firmware/tree/main/Klipper_and_Klipper_Derivatives/Quickdraw_Probe)<br>
[Danger Klipper Github](https://github.com/DangerKlippers/danger-klipper)<br>
[Klicky Github](https://github.com/jlas1/Klicky-Probe/tree/main/Klipper_macros)<br>
<br>

**K3rabiner and Carabiner Distribution Board Pinouts**<br>
The pinout information for the K3 specific toolhead board (K3rabiner) and the Carabiner Distribution board are a bit scattered. The current locations of the board info including pinouts and current ratings are located in the following locations.

[K3rabiner Github](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/main/Release_1_2/PCBs/K3rabiner), [Carabiner Distributor Github](https://github.com/Annex-Engineering/Annex_Engineering_PCBs/tree/master/carabiner-series-toolboard/carabiner-distributor)

# Userful Mods By Others:

**Przy's Modified Z Motor Mount Brace**<br>
Depending on material shrinkage and other printer tolerance factors, some users had trouble getting the bolt holes on the Z Motor Mount Brace (that connects the front two motors mounts to the middle extrusion) to line up properly. A modified brace has been created that has slotted bolt holes to allow for easier alignment. This modification will eventually make it into the final 1.2 release according to Przy.

[Discord](https://discord.com/channels/641407187004030997/1183429817429921883/1185665144328568902)<br>
<br>

**Ryan G's Sherpa Micro with iIntegrated PTFE Collet and Filament Sensor**<br>
A (RIDGA compatible) Sherpa Micro extruder with integrated PTFE collet and filament sensor, useful for MMUs such as Tradrack.

[Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Extruders/Sherpa_Micro/Extruder_Mods/Ryan_G-Idler_Filament_Sensor_and_Collet)<br>
<br>

**TurtleCrawler's Kraken Controller Bracket**<br>
Replaces the default universal controller bracket with a version that is large enough for the Kraken board.

[Discord](https://discord.com/channels/893696029512302602/1019365375865012266/1229767868472889344)<br>
<br>

**Ruiqimao's 8x 221-412 Wago Mount**<br>
An eight Wago mount for connecting various bed electronics to the bed umbilical.

Images: [Discord](https://discord.com/channels/893696029512302602/1019365375865012266/1221853746556960778), STL: [Discord](https://discord.com/channels/893696029512302602/1019365375865012266/1221894934961979462)<br>
<br>

**Karabox's eBox**<br>
An entire electronic box redesign with many unique electronic mounting brackets and cable management solutions. And more importantly dual tone panels based on the default panel design.

[Github](https://github.com/karabox/MISC/tree/main/Annex%20Mods/K3%20eBox%20mod)<br>
<br>

**Airox's Dual Pane Tophat**<br>
An alternate tophat that uses two top panels and an interlocking design to reduce heat loss through the top for better chamber temperatures.

[Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/K3/airox-double-pane-tophat)<br>
<br>

**Minsekt's Waveshare Electronic Box Screen**<br>
A modified electronic box panel that allows mounting of a 7.9 inch Waveshare Screen on the side of the electronic box (vertically). This is typically done in a "sidepack" configuration of the electronic box instead of a backpack. Requires modifications to one of the laser cut panels.

[Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/K3/Minsekt-K3_WaveshareScreen)<br>
<br>

**Ryan G's Backpack Camera**<br>
A mount for using the large grommet feedthrough hole for a camera facing the build plate. Not the best angle but keeps the camera out of the hot chamber. Requires the PTFE and umbilical for the toolhead to be routed through one of the small grommet feedthroughs.

[Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/K3/Ryan_G-K3_Outside_Camera)<br>
Airox's mod to use Raspberry Pi Cam instead of a webcam: [Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/K3/airox-rpi-mount-for-camera-mod-ryan)<br>
<br>

**MathematicaPotato's Metal Toolhead**<br>
Cut metal plates that replace the printed toolhead for a stiffer setup. Compatible with mosquito (or mosquito clones), dragon, or Chube hotends.

[NorthPrint3D](https://northprint3d.ca/product/k3-metal-toolhead-kit/), [Luke's Labritory](https://lukeslabonline.com/products/k3-metal-toolhead-kit), DXFs: [Github](https://github.com/MathematicalPotato/DooKi3-Toolhead)<br>
<br>

**Various Metal Motor Mounts for High Current Motors**<br>
If 2504 or 2804 motors are used at high currents, the motors can get quite hot, possibly melting the printed motor mounts. These motor mounts replace the printed parts to help with heat dissipation and increase stiffness.

CNCed Aluminum<br>
[Fabreeko](https://www.fabreeko.com/products/k3-motor-mounts-by-honeybadger), CAD: [Github](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Printers/K3/DennisB-K3_Metal_XY_Motor_Mount)<br>
<br>
Laser Cut Plates<br>
[Annex Store](https://store.annex.engineering/collections/metal-parts/products/k3-ldo-motor-metal-motor-mounts), DXFs: [Github](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/main/Release_1_2/DXFs/Motor_Mounts)<br>
<br>

**Ryan G's Carriage Adapter for Dragon UHF Hotend**<br>
Printed parts that allow use of the Dragon UHF Hotend with or without the nozzle extender instead of the stock Dragon HF hotend. Might require the lower Z idler (see "Cbon's 3628 Fan Ducts and Alternate Z Idler for Chube" below) instead of the low Z idler in the main repo.

[Discord](https://discord.com/channels/641407187004030997/1139276599645179946/1139276599645179946)<br>
<br>

**Ryan G's Carriage Adapter for Rapido UHF Hotend**<br>
Printed parts that allow use of the Rapido 1 or 2 UHF Hotend. Might require the lower Z idler (see "Cbon's 3628 Fan Ducts and Alternate Z Idler for Chube" below) instead of the low Z idler in the main repo. Might work with Rapido 2F?<br>

[Discord](https://discord.com/channels/641407187004030997/1146449573187952802/1205745937197043832)<br>
<br>

**Chube High Flow Hotend**<br>
A very high flow and ridgid hotend designed, pricey but very high flow. Currently only compatible on the K3 with the metal toolhead plate above.

[ChubeHotend.com](https://chubehotend.com/)<br>
<br>

**Cbon's 3628 Fan Ducts and Alternate Z Idler for Chube**<br>
Printed parts for using extremely high airflow 3628 fars with Chube, and a lowered rear Z idler to make sure the entire build area is still usable without the fans colliding with the idler.

STLs: [Discord](https://discord.com/channels/641407187004030997/910647734506258442/1234572830499143722), Fans: [Digikey](https://www.digikey.com/en/products/detail/delta-electronics/FFB03612EHNYCL/6580720)<br>
<br>

**Newtwo's Chonk K3 Frame**<br>
A completely new frame redesign that increases most extrusions to 2040 or 4040 which massively increases the printer stiffness and makes sealing and insulating the printer much easier. Also replaces the tophat with an extrusion based tophat which was not really feasible with the stock frame. Very expensive as it requires basically all new extrusions and panels.

Images: [Discord](https://discord.com/channels/893696029512302602/1019365375865012266/1239699476461916331), DXFs and BOM: [Discord](https://discord.com/channels/893696029512302602/1019365375865012266/1244371404867244033)
