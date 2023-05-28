## Opencore EFI
The opencore EFI I use to run macOS Ventura on my personal machine. You can use this as an example or try to replicate it, but *always* build your efi from scratch. The [dortania](https://dortania.github.io/OpenCore-Install-Guide/) guide has great instructions, and it covers almost every system out there. If something isn't covered in the guide use google, DON'T INSTALL THE FILES IN THIS REPO.
## Specs
- CPU: intel i3-12100f
- GPU: AMD rx 5600 xt (Asus)
- Motherboard: Asus Prime H610I-PLUS D4
- Chipset: intel H610
- RAM: 2x 8GB PNY (3200mt/s)
- SSD: 1TB M.2 SP
- Audio: Realtek ALC897
- Networking: 1GB Realtek ethernet
## Caveats
- no bluetooth or wifi (I connect to a wifi extender with ethernet and use a wireless keyboard dongle)
- apple ID sign in works, but it's buggy
- iMessage fails to sign in
## Additional Info
- **boot-args** -v keepsyms=1 debug=0x100 agdpmod=pikera unfairgva=1 -wegnoigpu alcid=12