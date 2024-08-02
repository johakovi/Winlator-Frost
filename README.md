<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator-Frost Logo" />  
</p>

# Winlator@Frost

Winlator@Frost is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64. Originally modified from [Brunodev85](https://github.com/brunodev85/Winlator)

Modded by a student 16 years old from Songkhla province, Thailand.

# Installation

1. Download and install the APK (Winlator@Frost 7.1 V4.apk) from [GitHub Releases](https://github.com/MrPhryaNikFrosty/Winlator-Frost/releases)
2. Launch the app and wait for the installation process to finish

----

[![Play on Youtube](https://img.youtube.com/vi/8PKhmT7B3Xo/1.jpg)](https://www.youtube.com/watch?v=8PKhmT7B3Xo)
[![Play on Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)

----

# Useful Tips

- If you are experiencing performance issues, try changing the preset for Box86/Box64 in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing Wine Mono found in Start Menu -> System Tools.
- If some older games don't open, try adding the environment variable MESA_EXTENSION_MAX_YEAR=2003 in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- If you want to hide the annoying dxvk hud, please removing this env from here
<p align="center">
	<img src="hide_dxvk_hud.png" width="480" height="240" alt="Winlator-Frost Hide DXVK HUD" />  
</p>

# System requirement for Winlator@Frost
- `Turnip` - For `Adreno 6xx and 7xx` only at the moment. `Adreno 735, 732, 720, 710 and 613` are not working. You have to use VirGL if you're using this GPU
- `VirGL` - Universal, all GPU `like Mediatek, Exynos, Kirin, Unisoc, etc`(include unsupport GPU of turnip adreno like in above)` might work with VirGL but you can only play DX9 games
- `LLVMPIPE` - Use this if you want to run software apps `(not for game)`

# Known issue in Winlator@Frost
- ~~Snapdragon 8s gen 3 `Adreno​ 735` container not starting issue~~ (now it's working)
- Some game in Snapdragon 8 gen 3 may not working or have a performance hit
- Some game have a xinput issue which virtual gamepad are not working

# What is the difference between bench and without bench apk? 
- Bench is for the user that have 2 or more winlator. It's suitable for the user to compare other winlator. While, without bench is for the user that don't have/install any winlator yet.

# Like my mod? 
- If you like then give us a star for this repository. Also give us feedback or suggestions in 'pull requests' to help the development for this mod.

# Hate my mod or think other winlator mod are better than mine?
- Yes. Exactly, my mod will become very worst at some device that are not fit with my mod. So you can try other winlator mod that are better than me (like afei, or bla, bla, bla). Remember, I made this winlator just for personal use only but I think it would be good if I share it to other people. But, what can I do if my winlator mod doesn't work properly in your device.

# Credits and Third-party apps
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- PRoot ([proot-me.github.io](https://proot-me.github.io))
- Mesa3D (Turnip, Zink, VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))

Many thanks to [ptitSeb](https://github.com/ptitSeb) (Box86/Box64), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) (Turnip), [alexvorxx](https://github.com/alexvorxx) 
(Mods/Tips) and others.
Thank you to all the people who believe in this project.
