# IMPORTANT! READ BEFORE DOWNLOAD!
DO NOT TRY TO CONVERT THIS EFI TO OPENCORE!! THIS WILL BREAK YOUR HACKINTOSH AND CAUSE KERNEL PANIC!! EVEN IF YOU
MANAGES TO BOOT UP YOU WILL NEVER GET QE/CI ON HACKINTOSH MAKING IT IS COMPLETELY USELESS!!! I WONT TAKE ANY RESPONSIBILITY
IF YOU CONVERT THE EFI YOURSELF AND BREAK UP YOUR HACKINTOSH!! THIS IS REALLY IMPORTANT, THIS IS REALLY IMPORTANT, THIS IS
REALLY IMPORTANT!!!

# HackintoshPentium3556U-HSWGT1
this is a clover EFI for U series Haswell cpu with Intel HD Graphics Haswell gt1 GPU, I know there is so many people saying that
pentium is not gonna work, but here is a clover efi which successfully boots up EI captian 10.11 with patches for QE/CI and audio driver
-->> tested on VAIO 15E <<--

# THIS IS FOR CLOVER ONLY NOT FOR OPENCORE
My tested laptop specs:
CPU: INTEL PENTIUM 3556U
RAM: 4GB DDR3
STORAGE: 1TB HDD
IGPU: INTEL HD GRAPHICS HASWELL (GT1-ULT)
WIFICARD: INTEL WIRELESS N-7260
CARD READER

# ISSUES
the os itself runs pretty smoooth on this potato, but here are the current working/not working things for this potato:
- [x] Graphics acceleration (need AGPM patch + HD5000VADRIVER -> included)
- [x] Audio Support
- [x] Card reader
- [x] Intel WIFI (using itlwm -> change the SSID and pw urself!)
- [x] HDMI AUDIO/VIDEO
- [x] Sleep
- [x] iServices (sort of)
- [x] built in microphone
- [ ] Bluetooth
- [ ] Brightness control
- [ ] Webcam

# HOW TO USE :
DOWNLOAD THE EFI FOLDER VIA THIS REPO AND REPLACE YOUR OLD EFI FOLDER WITH THIS ONE WITH CLOVER

# INTEL WIFI:
Please self grab a itlwm.kext file, as it isn't included in the EFI, if you want wifi then grab one youself :3
