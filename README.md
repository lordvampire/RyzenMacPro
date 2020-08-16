# Ryzen Mac Pro - OpenCore EFI for ASRock Fatal1ty AB350 ITX


## Ryzen Mac Pro build

**Prozessor:** AMD Ryzen 7 1700X  
**Cooler:** boxed
**Motherboard:** AsRock AB350 Fatal1ty Gaming ITX (BIOS 5.6)  
**Memory:** Kingston HyperX 16GB @2400Mhz
**Storage:** Samsung SSD over SATA 256GB
**Video Card:** Radeon RX 480 8GB 
**Power Supply:** HKC 550W ITX  
**Case:** Jonsbo ITX U1 
**Wifi:**  BCM94360CS2 card with adapter from alibaba Replaced the original Intel card. 

I used https://github.com/aluveitie/RyzenMacPro files and changed some Data in ACPI for USB porting and also to get sleep working. 
Some SSDT´s are deactivated other new ones are added. Not used or needed kexts are deactivated but still in the directory, if you want to test them.


What is working: 
So far everything....

Only thing is, that if too much USB ports are used, sleep does not work and ends in kernel-panic. Seems to be a USB power topic. No time so far to dive deeper, since it workes with no issues here, since i have only 3-4 USB ports in use at a time...


