# 3D Printer Project

### Tech

* [Marlin](http://marlinfw.org/) - Optimized firmware for RepRap 3D printers based on the Arduino platform.
* [Arduino](https://www.arduino.cc/) - Open-source electronic prototyping platform enabling users to create interactive electronic objects.
* [Octoprint](https://octoprint.org/) - OctoPrint is an open source 3D print controller application.
* [Telegram](https://telegram.org/) - Telegram is a cloud-based instant messaging and voice over IP service.
* [Fusion 360](https://www.autodesk.com/products/fusion-360/overview#banner) - Cloud-based CAD/CAM tool.
* [Raspberry Pi 3b+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/) - Small single-board computer.
* [Cura](https://ultimaker.com/software/ultimaker-cura) - Open source 3D printer slicing application.

### Photos
<p align="center">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/flashbootloader3.jpg" width="256">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/flashbootloader2.jpg" width="256">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/flash%20bootloader.jpg" width="256">
</p>

Pictures above are of the RBP hooked up to the printer's motherboard with jumpers. The printer did not come with a bootloader on it so one had to be flashed so that the firmware could be changed. The firmware has some cool features like manual mesh bed leveling, but that wasn't the main reason I wanted to update the firmware. The main thing I wanted from the firmware was thermal runaway protection. This makes the printer able to turn itself off incase it gets too hot.

<br>

<p align="center">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/telegramexample.jpg" width="512">
</p>

Used an early variant of the SJCAM (a chinese go pro knockoff) as the camera to intermittently take photos of the print. The photos could then be viewed when you send the command /status to the printer's telegram chat. Was tough to get the SJCAM and the debian distro to play nicely because of a lack of driver support for the camera.

I was able to almost fully control the printer through telegram. I could get the extruder and build plate heated up, upload new prints to the printer, and start/stop prints. Someone just needed to be around to clean the build plate off. 

<br>

<p align="center">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/rbpaddition.jpg" width="512">
</p>

Picture of printer with the RBP attachment. It's also easy to see the glass build plate that I added. Had to get the glass cut at a local Lowes. The glass build plate has better adhesion properties than the original plastic coated build plate that came with the printer. 

<br>

<p align="center">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/UTA_vs_Personal.jpg" width="256">
  <img src="https://github.com/LewkyB/3D_Printer/blob/master/3d%20printer%20pictures/post%20calibration.jpg" width="256">
</p>

The picture on the left compares my prints against my university's prints. Both game pieces were printed using PLA. The top game piece was printed with my printer while the bottom piece was printed with the university's printer. The main difference between the printers is the slicing software that is used. I used Cura while the university uses KISSlicer. Cura allows for a lot smaller layer heights than KISSlicer and that translate to a lot higher quality prints. 

The picture on the right is of another game piece that I printed after completing a lot of calibration adjustments. I was pretty proud to get such a perfect looking print. 


### Tasks
- [x] Glass build plate
- [x] Improved Bed Tensioning Springs
- [x] Dampers
- [x] RBP3b+ with Octoprint
- [x] Bootloader
- [x] Marlin Firmware
- [ ] BLTouch Auto Bed Leveling Sensor
