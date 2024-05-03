# uMSX Pro Rev.3.79
 The latest uMSX hardware improvement design file includes the motherboard and card slot PCB design, which I think is perfect. The latest version is motherboard v3.79+Cart v0.28
#### What is it?
The latest version of uMSX Pro Rev.3.79 is newly launched with sufficient stock. I hope that everyone can easily own 1ChipMSX and get the best MSX2+ experience!  
It originated from the va-de-retro retro computer forum.   
The uMSX is a MSX2+ FPGA implementation that basically mimics the Zemmix (one of the first FPGA based MSX2+ one chip MSX computers commercially available). 

uMSX Rev3.7 PCB original design by BCH.  
Gerber to PCB conversion (reverse engineering) by Null.  
The acrylic shell is manufactured by Xiaohao Studio.  
Motherboard PCB modification + optimization by Denjhang, Null.  
Card slot version modified + optimized by Denjhang, BH2VGM.  

The VHDL used is the well known KDL PLD implementation for the MSX2+ used by the vast majority of the FPGA based MSX computers known. The uMSX uses the first generation of the KDL VHDL source, also known by esemsx.  

Based on the already obsolete (but relatively easy to find) Altera EP1C12 FPGA (specifically the EP1C12Q240C8N), the uMSX uses SMD based components (and a few PTH) in a nice compact form factor. It uses the 4 megabit EPCS4 active serial configuration flash memory to host the firmware and configure the FPGA chip at each time the circuit turns on.  

A MT48LC16M16A2 SRAM chip offers memory for the computer, which also uses a few other components to implement the clock logic (NC7WV04P6X inverter and 21.47727 basic PTH crystal oscillator) and a 953B voltage detector and reset IC.  

Heavily based on 0603 SMT resistance arrays, and other 0805 SMT components, the uMSX is a compact little OCM MSX that can be used to evolve your SMD soldering skills, challenge your knowledge of modern electronics applied to retro computing, and give you a lot of fun through the journey.  


#### Why did you make it?
Soldering chips like EP1C12Q240C8N is very difficult, but you can easily find a soldering foundry in China, which ensures the yield rate of my various products.  

The uMSX Pro Rev.3.7 I made is based on the uMSX Rev.3.5 of the vdr forum, which features a translucent acrylic case, and restores the deleted JoyPort 2, USB Wi-Fi, USB keyboard port, and I also designed a Conversion board, which can convert the VGA port of uMSX to S-Video and RGB. Buying uMSX Pro Rev.3.7 now will give you a 5V DC power supply, 1GB MicroSD (built-in system files), two MD controllers, two JoyMega, and a USB Wi-Fi dongle, making it truly ready to use out of the box. I also sell PS/2 or USB keyboards for uMSX if needed.  
#### What makes it special?  
After I modified and optimized it, I added many functions:  
1.Fix the power switch on the motherboard and use a reliable self-locking switch to get rid of the instability caused by the two pin headers of version 3.5.  
2.USB WI-FI dongle (support 2.4G wireless Internet access),  
3.USB keyboard interface (PS2 protocol),  
4.The second handle interface (JoyStick Port 2),  
5.MSX analog RGB video interface,  S-Video Output   
6.Two upright MSX expansion card slots with dust covers.    
7. Add a pre-audio amplifier to support volume adjustment    
8. Add the power filter IB0505S to make the sound quality better.   
9. Restore S-Video port and experience retro videos.  
10. Self-ejecting SD card slot for better experience.  
11. The interface layout has been improved. Compared with the original uMSX Rev.3.7, the VGA interface position is more reasonable (at the rear).  
12. Improved VGA display quality and avoided color deviation and interference.  
And I designed the acrylic case to integrate the motherboard and the card slot.Getting rid of the exposed PCB and handle connection ribbons makes this project a little more serious.  
By default, this product comes with an assembled acrylic case,And also comes with the following accessories:    
1.a MegaDrive controller with a Joymega,    
2.a DC 5V power supply  
3.a 1GB Micro SD. Among them, Micro SD will have built-in OCM BIOS and various system files, 
so that it can be used out of the box.    
If you buy uMSX Pro 3.7, You will get an extra MD controller and JoyMega, USB WI-FI dongle needs to be purchased additionally.  
uMSX supports the use of 4GB MicroSD as a hard drive. I will pre-install the sofarun game browser. You can easily select games without coding. And it has built-in scc flashrom and floppy drive emulator, you can play various 2M ROM large-capacity games and multi-disk games without any problem. Multi-disk games switch disks via keyboard hotkeys. So just one umsx is needed and you don't need any additional msx cartridges to play all MSX, MSX2, MSX2+ games.
