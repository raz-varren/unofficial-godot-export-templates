# Unofficial Godot Export Templates

Godot is a great, open source, game engine that supports cross compilation for various platforms out of the box. Unfortunately, while Godot does have support for ARM64, the official Godot export template bundle does not include a set of export templates for ARM64, and building them yourself can be a difficult and time consuming task.

That's what this repo is here to solve. Whenever a new stable version of Godot 4 is released, we automatically compile and publish an unofficial set of ARM64 export templates, bundled with the official Godot export templates for that release.

You can download the latest export template bundle [here](https://github.com/raz-varren/unofficial-godot-export-templates/releases/download/4.1-stable/Godot_unofficial_v4.1-stable_export_templates.tpz). Follow the instructions below for using it. If you are using an older version of Godot 4, you can find the export templates for that version on the [releases page](https://github.com/raz-varren/unofficial-godot-export-templates/releases).


## How to use

1. Download the `tpz` file from the [releases page](https://github.com/raz-varren/unofficial-godot-export-templates/releases) for your version of Godot 4
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

## Build Bot Stuff

- Build Timestamp (UTC): `2023-10-31T15:43:22`
- Release Tag: [4.1-stable](https://github.com/raz-varren/unofficial-godot-export-templates/releases/tag/4.1-stable)
