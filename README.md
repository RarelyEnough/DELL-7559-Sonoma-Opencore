	First Stable release of Opencore EFI folder for booting and using MacOs Sonoma 14.4 for 
DELL INSPIRION 7559 

![macOs_e2bde33a-15c8-4c3c-adb0-3d73e21b81bb](https://github.com/user-attachments/assets/9ca641f6-4372-4efd-a505-76c70898df9e)
![Zrzut ekranu 2024-10-1 o 20 49 13](https://github.com/user-attachments/assets/fd12f158-2cea-4dba-85ef-b32f3b6f00c4)

	Laptop spec:
	-Intel Core I7-6700HQ
	-Intel HD Graphics 530
	-16 GB DDR3 RAM
	-Nvdia Geforce 960m
	-1 TB ADATA M.2 Sata SSD

	Working:
	-Intel HD 530 (Accelerated)
	-Intel WiFi
	-Intel Bluetooth
	-HDMI Output (Accelerated)
	-CPU Power Menagment
	-Battery
	-Keyboard Backlight
	-Build-in speakers
	-LCD Panel Brightness Controll

	Not Working:
	-Handoff, Airdrop and Continuity Features (OEM Intel Cards) can work with BCM94360 WiFi+BT card
	-Nvdia Geforce 960m (Still not figured out how to enable it)
	-Can't remember more :) 

	!NOTE!
	REMEBER TO GENERATE
	YOUR OWN SMBIOS INFO FOR MACBOOKPRO 16,4 (via OCAT software for example)
![PI generate](https://github.com/user-attachments/assets/04660b2f-5493-4884-bba1-24474e8e3ee4)
	!AND! GENERATE ApECID using Dortania Opencore Guide
![OC ECID](https://github.com/user-attachments/assets/349a6a5b-b464-4b5e-ac0f-912fb4169934)
	https://dortania.github.io/OpenCore-Post-Install/universal/security/applesecureboot.html#apecid and Adding under Security tab in Misc Settings (via OCAT software for example)
