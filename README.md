# Archipelago-DS3-Downpatching-Guide
This repository was made to preserve the instructions on how to properly downpatch DS3 for use in Archipelago Multiworld Randomizer

# Downpatching Instructions for DS3
- Launch Steam (in online mode)
- Press the Windows Key + R. This will open the Run window.
- Open the Steam console by typing the following string: steam://open/console , Steam should now open in Console Mode.
- Insert the string of the depot you wish to download. For example: download_depot 374320 374321 7552375533020122115. Refer to the table below.
- Steam will now download the depot. Note: There is no progress bar of the download in Steam, but it is still downloading in the background. You can confirm this by checking Steam's network usage in either the Downloads tab in Steam or via Task Manager. You can ignore any other information displayed in console. It is most likely unrelated to the downpatching process.
- Turn off auto-updates in Steam by right-clicking Dark Souls III in your library > Properties > Updates > set "Automatic Updates" to "Only update this game when I launch it" (or change the value for AutoUpdateBehavior to 1 in C:\Program Files (x86)\Steam\steamapps\appmanifest_374320.acf).
- Back up your existing game folder in C:\Program Files (x86)\Steam\steamapps\common\DARK SOULS III.
- Return back to Steam console. Once the download is complete, it should say so along with the temporary local directory in which the depot has been stored. This is usually something like C:\Program Files (x86)\Steam\steamapps\content\app_XXXXXX\depot_XXXXXX. Back up this game folder as well.
- Delete your existing game folder in C:\Program Files (x86)\Steam\steamapps\common\DARK SOULS III, then replace it with your game folder in C:\Program Files (x86)\Steam\steamapps\content\app_XXXXXX\depot_XXXXXX. This is to prevent any errors from additional files (e.g. any modification to the game folder prior to downpatching).
- Back up and delete your save file DS30000.sl2 in AppData. AppData is hidden by default. To locate it, press Windows Key + R, type %appdata% and hit enter or: open File Explorer > View > Hidden Items and follow C:\Users\<your username>\AppData\Roaming\DarkSoulsIII\<numbers>.
- If you did all these steps correctly, you should be able to confirm your game version in the upper left corner after launching Dark Souls III.
