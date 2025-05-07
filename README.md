# Lenovo-B50-70-Hackintosh-BigSur-i5-4210U

Opencore-EFI-for-Lenovo B50-70 --4210u-haswell Hackintosh

OpenCore--latest 1.0.4

BigSur_11.7.5

CPU 			    i5-4210U
IGPU			    Intel HD4400
GPU 			    Radeon HD 8550M
Ethernet                    Realtek RTL8168/8111/8112 Gigabit Ethernet Controller / Asus 
Wireless network adapter    Atheros AR9565
Operate System              macOS BigSur_11.7.5 + Windows 10 Pro + Ubuntu 18.04 LTSB
RAM: 			    2x8GB DDR3
SSD: 			    512 Gb 2.5" SATA

		BIOS SETUP

OS Optimized Defaults 		Other OS
	
	Enable:
VT-x
Hyper-Threading
OS type: UEFI Mode
SATA Mode: AHCI
	
	DISABLE
Secure Boot

	Advanced bios

I know a way to enter bios advanced
I have b50-45 but this one will work too.
(It only works when the laptop is connected to the network)
Turn off the laptop and
And hold down fn and do not release the combination until the end
Then f4, 4,r,f,v
Then F5,5,t,g,b
Then F6,6,y,h,n
Turn on the laptop and enter bios

Znayu sposob voyti v bios advanced
U menya b50-45 no etot tozhe poydet.
(Rabotayet tol'ko pri podklyuchenii noutbuka k seti)
Vyrubayem noutbuk i
I zazhimayem fn i ne otzhimayem do kontsa kombinatsii
Potom f4, 4,r,f,v
Potom F5,5,t,g,b
Potom F6,6,y,h,n
Vklyuchayem noutbuk i vkhodim v bios

		Advanced BIOS
	Video Configuration --Internal Graphic Device
IGD - DVMT Pre-Allocated			64 MB
IGD - DVMT Size					MAX
	
	Chipset Configuration
VT-d						Disabled

	Working

CPU: OK TURBO BOOSTER: OK GPU INTEL HD 4400: OK HDMI: OK Wi-Fi: AR9565 OK Audio: OK TrackPad: OK USB: OK
Audio 			alcid=28

