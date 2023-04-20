# HP ProBook 650 G1 - OpenCore 0.8.6

This contains the files I used for my [OpenCore](https://github.com/acidanthera/OpenCorePkg) config - I never really got around to removing my SN so here we are.

## Great! How do I use these?

1. Reconsider. You're probably better off following the [Dortania Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) from scratch.

2. If you choose to continue, then cloning the repo and using these `BOOT` and `OC` folders in your EFI should give you a great start. You probably want to read my rationale behind some decisions and experiences in my [r/Hackintosh post](https://dortania.github.io/OpenCore-Install-Guide/) (like Bluetooth being iffy).

3. Put in your own generated SMBIOS info in [config.plist](OC/config.plist) -> PlatformInfo -> Generic, I removed mine because, well, obviously.

> Note: This uses OpenCore 0.8.6, so the configuration now will be slightly different if you choose to go for a newer version.
