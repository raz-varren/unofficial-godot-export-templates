# Unofficial Godot Export Templates

Well, as quickly as it was created, this repo is has been made redundant. As of Godot 4.2 the official Godot export templates now include builds for ARM32/ARM64. Since there's really no reason for the bot to keep pushing builds to this repo, I'm going to archive it and shutdown the build bot. I will keep the archive available for anyone who still needs ARM64 export templates for Godot 4.1.x releases.

Export templates for Godot 4.1.x are available on the [releases page](https://github.com/raz-varren/unofficial-godot-export-templates/releases). Follow the instructions below for using them.


## How to use

1. Download the `tpz` file from the [releases page](https://github.com/raz-varren/unofficial-godot-export-templates/releases) for your version of Godot 4.1.x
1. On your game dev machine, open your project and from the menu click `Project -> Export`
1. Under presets click `Add... -> Linux/X11`
1. Click and enable `Embed PCK`
1. You will see errors related to `No export template at the expected path`
1. Click `Manage Export Templates`
1. Click `Install from File`
1. Find and open the `tpz` file you downloaded
1. Close the export template manager
1. Go back to `Project -> Export`
1. Select `Binary Format -> Architecture -> arm64`
1. That's it, you should be able to export `arm64` builds now

