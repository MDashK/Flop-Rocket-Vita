# Flop-Rocket-Vita
A port/patch to make the game **Flop Rocket** (Android Version) playable on the PSVita.

###

## Disclaimer
**The provided files in this repository do not contain any game files.**

To be able to use the provided patch and actually play the game in your PSVita, **you need to legally acquire the game on the Google Play Store Android platform**.

You can get the game here: [https://play.google.com/store/apps/details?id=com.bscotch.floprocket](https://play.google.com/store/apps/details?id=com.bscotch.floprocket)

## Instructions
1. Download the VPK file that is provided in here, along with the ZIP file containing patch information.
2. Extract the ZIP to a temporary folder.
3. Use your prefered way to acquire the **game.droid** file of the game. The patch is based on version 100.0.33 of the game (current to the date of the release).
4. If you have an APK of the game, open the APK file with WinRAR, WinZIP, 7z or a similar software. You'll notice a lot of files within it.
6. Locate and extract the **game.droid** file and all the **.OGG** files from the **assets** folder.
7. Copy the **game.droid** file into the previously created temporary folder. Make sure the file is placed in the same location as all the other files present in the ZIP.
8. Double click the **apply_patch.bat** file, a command-line window will open and will start patching automatically.
9. Once patching is complete you will find your new **game.win** file in the main folder.
10. Install the VPK file into your PSVita.
11. **Copy the "game.win" file into the "ux0:app/FLOPROCKE/games" folder.** Make sure to replace the dummy file that's present there.
12. **Copy every extracted .OGG file into the "ux0:app/FLOPROCKE/games" folder as well.**
13. (Optional) You can delete the **"main_bgm.ogg"** music file present in there to save some MB of free space.
14. Have Fun!

## Hashes
The hash information of your **original, unaltered Android "game.droid"** file should be:

**MD5**: 23805e428ed1ec5c652cf75b16b6490b

**CRC32**: 175ea41a

The hash information of your **modified, PSVita ready "game.win"** file should be:

**MD5**: 1b321bdf0cd0bdd7acd2a081078c6b77

**CRC32**: dbb3ac55

If these hashes do not match, then something went wrong.

## Things to keep in mind:
1. The game works with button input and with **touchscreen functionality**. In the shop menu, for example, you need to use the touchscreen to scroll the list and buy the items.
2. You can also use all the buttons and paly the game easily using touchscreen. There's a sidewheel on the left (more options in the Pause menu) to turn the ship and touch the screen to throttle.
3. **Start** button will pause the game mid-gameplay, no need to use the "Pause" icon in the touchscreen.
4. The game saves automatically when you purchase items on the shop, lose or exit gameplay, so you can press the PS button and exit the game in the title screen safely.

## Credits
Big Special Thanks to the "Butterscotch Shenanigans" devs for releasing the source code and SilicaAndPina for the GayMaker tool.
