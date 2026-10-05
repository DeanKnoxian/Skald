# Installing Skald

The final 1.0.0 Main File is still being prepared. Use these steps when that file is available on [Skald's Nexus page](https://www.nexusmods.com/skyrimspecialedition/mods/193977).

## Prepare Skyrim

Use the English Steam edition of Skyrim Special Edition, with the Anniversary Upgrade or Anniversary Edition bundle. The installer currently expects Steam game files at **1.7.104.0** and the Anniversary Creation Club content. Skald supplies its own **1.6.1170.0** runtime and matching mod setup for play.

Before installing Skald, start the Steam game once to complete its normal first-run setup. In its Creations menu, download the owned Anniversary content. If content is missing, use **Options > Download all owned Creation Club Creations**, then close the game. Keep those game files available to Wabbajack.

## Choose your folders

Choose an empty **Skald Install Folder** and a separate **Downloads Folder**. Use ordinary folders on a local drive, outside Windows, Program Files, the Steam game folder, Desktop, Documents, OneDrive and other synchronized folders. The downloads may be on a different drive from the installation.

The 1.0.0 installer is approximately **15.28 GB**, the remote mod downloads total about **114.34 GB**, and the installed setup occupies about **177.86 GB**. These sizes use decimal GB.

Allow **115 GB** for the download cache, **at least 300 GB free** at the installation location for installed files and temporary work, and **32 GB** for the outer download and extracted installer. If all three locations share a drive, allow **at least 450 GB free** before starting. These are planning allowances, rather than guaranteed maximums. Keep space for saves and updates. Keeping the downloaded mod archives makes a later reinstall easier.

## Install the Main File

1. Download **Wabbajack 4.2.3.0** from [its official website](https://www.wabbajack.org/).
2. Download the current Skald Main File from Nexus.
3. Extract the outer archive to obtain `Skald.wabbajack`. Keep the supplied instructions with it.
4. Open Wabbajack and choose **Install From Disk**. Select `Skald.wabbajack`.
5. Set the **Installation Location** to your empty Skald Install Folder and the **Download Location** to your chosen Downloads Folder.
6. Complete Wabbajack's Nexus account prompts and start installation. Your Nexus account must have **adult content enabled**. Follow any manual download prompts. Let Wabbajack finish before opening the installed mod organizer.
7. Continue only when Wabbajack reports that installation succeeded.

Use **Wabbajack 4.2.3.0**, the version used for this installer. Do not install the outer archive as an ordinary mod or copy it into Skyrim's Data folder.

## Launch the installed setup

Open `ModOrganizer.exe` inside your Skald Install Folder. Select the **Skald** profile, select the **Skald** executable in the launch list, and press **Run**. That executable starts the included SKSE loader.

Keep the supplied mod priorities, enabled plugins and plugin order. There is no player requirement to sort the list, regenerate animations or rebuild grass and LOD before playing. Start a new character using [STARTUP.md](STARTUP.md).

### Why are some plugins unchecked?

Nine included plugins are deliberately inactive. Keep their supplied state.

| Plugin | Why it is inactive in Skald |
| --- | --- |
| `SkyforgedSteelRemastered.esp` | Its models are already used through Sentinel; enabling the plugin would add duplicate weapon records. |
| `Northern Roads - Additional Roads.esp` | Skald does not use this optional roads module. |
| `TES Arena Amol.esp` | Its town placement and terrain overlap the selected roads and landscape. |
| `Tes Arena NorthKeep.esp` | Its terrain, road navigation and moved references need further integration. |
| `TES Blackmoor.esp` | The required landscape and navigation integration is not included. |
| `Tes Granite Hall.esp` | Its road terrain and Strongholds navigation need further integration. |
| `Tes Pagran Village.esp` | Its terrain, road references and lighting conflict with the selected setup. |
| `Tes Vernim Wood.esp` | Its road landscape and USSEP navigation need further integration. |
| `WarmongerArmory_LeveledList.esp` | Its optional distribution overwrites selected armor and NPC records. The craftable Vanilla/DLC modules remain active. |

## If installation stops

Read the reason shown by Wabbajack before retrying. For a Nexus sign-in or manual download prompt, finish that prompt in Wabbajack. For a missing game or Creation file, check the required Steam version, English language and Anniversary downloads. For insufficient space, free space in the chosen download and install locations before continuing.

If a required mod file is unavailable, check the Skald Nexus page for a release update. Do not replace it with a similarly named archive from an unrelated source.

If the game starts without the Skald setup, close it and check that you used the included Mod Organizer 2, the **Skald** profile and the **Skald** launch entry. When asking for help, include the Skald version and the error message; remove personal paths and account information from shared logs or screenshots.
