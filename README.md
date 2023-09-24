# bios
## VERSION
- Flash v1.23 dated 17th Aug 2018 (or 18th July 2018 on some machines) from [this link](https://ftp.hp.com/pub/softpaq/sp91001-91500/sp91342.exe). Recent bios versions refuse to boot and get stuck at [HID: Legacy shim 2](hid_legacy_shim.jpg). If you want to get the most recent version of bios, you could test bios versions between 1.25 up to 1.37 as i haven't tested these versions (and franky I WON'T 😛)
- Run the installer to extract your .bin bios file
- Place your bios .bin file inside EFI/HP/BIOS/Previous at the root of your usb stick
- Flash the bios in computer setup (f10 while laptop is booting) by updating in local media

## ENABLE
- VT-d & VT-x
- iGPU Mem. >=64MB

## DISABLE (basically everything in Dortiana guide)
- Fast boot
- Secure boot

# wifi
Needs [HeliPort](https://openintelwireless.github.io/HeliPort/Installation.html)

# working
- Wi-FI w/ HeliPort
- Sound (3.5mm and Internal Speakers)
- Fn keys
- Touchpad
- USB mapping (2.0)
- Webcam
- Sleep

# not working
- Bluetooth
- SD Reader
- USB mapping (3.0. feel free to map all ports with usbtoolbox)
