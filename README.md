<p align="center"> <img width="500" src="resources/ALVR-Grey.svg"/> </p> 

# ALVR - Air Light VR  

[![badge-discord][]][link-discord] [![badge-matrix][]][link-matrix] [![badge-opencollective][]][link-opencollective]  

Stream VR games from your PC to your headset via Wi-Fi.  
This is a fork of [ALVR](https://github.com/polygraphene/ALVR).  

### Direct download of the latest version:  
### [Windows Launcher](https://github.com/alvr-org/ALVR/releases/latest/download/alvr_launcher_windows.zip) | [Linux Launcher](https://github.com/alvr-org/ALVR/releases/latest/download/alvr_launcher_linux.tar.gz)  

## Compatibility  

| VR Headset                  | Support                                                                                 |
| :--------------------------: | :------------------------------------------------------------------------------------: |
| Apple Vision Pro            | :heavy_check_mark: ([store link](https://apps.apple.com/app/alvr/id6479728026))         |
| Quest 1/2/3/3S/Pro           | :heavy_check_mark: ([store link](https://www.meta.com/experiences/7674846229245715) *) |
| Pico Neo 3/4/4 Ultra         | :heavy_check_mark:                                                                     |
| Play For Dream YVR 1/2/MR    | :heavy_check_mark:                                                                     |
| Vive Focus 3/Vision/XR Elite | :heavy_check_mark:                                                                     |
| Lynx R1                      | :heavy_check_mark:                                                                     |
| PhoneVR (smartphone)         | :heavy_check_mark: ** ([repo](https://github.com/PhoneVR-Developers/PhoneVR))          |
| Android/Monado               | :warning: **                                                                           |
| Oculus Go                    | :x: ([old repo](https://github.com/polygraphene/ALVR))                                 |

\* ALVR for Quest 1 is not available through the Meta store.  
\** Only works on some smartphones; not extensively tested.  

| PC OS         | Support                                                                 |
| :------------: | :--------------------------------------------------------------------: |
| Windows 10/11 | :heavy_check_mark: ([store link](https://store.steampowered.com/app/3312710)) |
| Windows XP/7/8| :x:                                                                    |
| Linux         | :heavy_check_mark:***                                                   |
| macOS         | :x:                                                                    |

\*** Please check the wiki for compatibility information.  

### Requirements  

- A supported standalone VR headset (see compatibility table above).  
- SteamVR.  
- High-end gaming PC:  
  - See the OS compatibility table above.  
  - NVIDIA GPU with NVENC support (GTX 1000 series or newer), or an AMD GPU with AMF VCE support, with the latest driver.  
  - On laptops with both an integrated GPU (Intel HD, AMD iGPU) and a dedicated GPU (NVIDIA GTX/RTX, AMD HD/R5/R7), assign the dedicated GPU or "high performance graphics adapter" to ALVR and SteamVR for best performance and compatibility.  
    (NVIDIA: Nvidia Control Panel → 3D Settings → Application Settings; AMD: similar method.)  
- 802.11ac 5 GHz wireless or a wired Ethernet connection:  
  - It is recommended to use 802.11ac 5 GHz for the headset and Ethernet for the PC.  
  - The PC and headset must be connected to the same router (or use a routed connection as described [here](https://github.com/alvr-org/ALVR/wiki/ALVR-v14-and-Above)).  

## Install  

Follow the installation guide [here](https://github.com/alvr-org/ALVR/wiki/Installation-guide).  

## Troubleshooting  

- Please check the [Troubleshooting](https://github.com/alvr-org/ALVR/wiki/Troubleshooting) page, and also [Linux Troubleshooting](https://github.com/alvr-org/ALVR/wiki/Linux-Troubleshooting) if applicable.  
- Configuration recommendations and additional information can be found [here](https://github.com/alvr-org/ALVR/wiki/Information-and-Recommendations).  

## Uninstall  

Open `ALVR Dashboard.exe`, go to the `Installation` tab, and press `Remove firewall rules`.  
Close the ALVR window and delete the ALVR folder.  

## Build from source  

Follow the guide [here](https://github.com/alvr-org/ALVR/wiki/Building-From-Source).  

## License  

ALVR is licensed under the [MIT License](LICENSE).  

## Privacy policy  

ALVR apps do not directly collect any kind of data.  

## Donate  

If you want to support this project, you can donate through our [Open Source Collective account](https://opencollective.com/alvr).  

[badge-discord]: https://img.shields.io/discord/720612397580025886?style=for-the-badge&logo=discord&color=5865F2 "Join us on Discord"  
[link-discord]: https://discord.gg/ALVR  
[badge-matrix]: https://img.shields.io/static/v1?label=chat&message=%23alvr&style=for-the-badge&logo=matrix&color=blueviolet "Join us on Matrix"  
[link-matrix]: https://matrix.to/#/#alvr:ckie.dev?via=ckie.dev  
[badge-opencollective]: https://img.shields.io/opencollective/all/alvr?style=for-the-badge&logo=opencollective&color=79a3e6 "Donate"  
[link-opencollective]: https://opencollective.com/alvr  
