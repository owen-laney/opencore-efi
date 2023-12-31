## Opencore EFI
These are the files I used to install opencore Ventura on my PC. You can fix the issues listed in the caveats section if you follow the dortaina guide, since these parts are all 100% compatible with MacOS Ventura.
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