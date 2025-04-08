# OoT3D D-PAD Free Cam

This project allows all 3DS systems to control the camera in The Legend of Zelda: Ocarina of Time 3D with use of the d-pad. It also add c-stick support as well.

This project is a fork of **Roberto-Nessy**'s **OoT3D_Standalone_Free_Cam** with added d-pad support. Since the d-pad is almost useless in the entire game, I came with this idea to enable non-New 3DS systems to control the camera as well.

This project is still a WIP, and has some issues like:

* The mini-map hides while using d-pad down.
* Do not have JPN region support.
* Since I only had the USA catridge here, the EU patch is not tested.

Future features planned (problably never, since I don't have time):
* Remap the show/hide mini-map button to SELECT (START and SELECT does the same in this game)

# How to Use:
* Find the patch files inside the "Patch Files" folder in this repository. They're divided by regional version of OoT3D (USA/EUR/JP) and by platform, so choose the correct ones.

### 3DS
* Install a recent build of Luma3DS. If you already have Luma3DS, you can upgrade by simply replacing "boot.firm" at the root of your SD card.
* Place the patch files ("code.ips" and "exheader.bin") in the following folder (you may need to create the folder):

| Version | Location | Notes |
|---|---|---|
| USA | /luma/titles/0004000000033500 | |
| JP  | /luma/titles/0004000000033400 | crashes |
| EUR | /luma/titles/0004000000033600 | not testes yet |

* Hold Select while powering on the console to launch the Luma3DS menu. Turn on "Enable game patching". You should only need to do this once, unless if you disable game patching in the future.
* It should work now! If not, you likely need to use a different version of Luma3DS.

### In Game Controls
The free camera's settings can be adjusted with the following button combinations:

* L + R + DPad Up/Down = Increase/Decrease Sensitivity
* L + R + DPad Left/Right = Invert Axes (Neither, Just X, Just Y, Both)

The selected setting will be displayed on the top screen in the upper left briefly after selecting it.
