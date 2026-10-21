# technexus-releases

Download TechNexus for Windows: the companion app for FIRST Robotics Competition teams at events.
More at [technexus.jerryxf.net](https://technexus.jerryxf.net).

## Structure

Each version has its own folder, with four files:

| File | What it is |
|---|---|
| `TechNexus-windows-x64.msi` | The installer, for most PCs |
| `TechNexus-windows-arm64.msi` | The installer, for ARM PCs such as a Snapdragon Surface |
| `TechNexus-windows-x64.zip` | The app without installing: unzip it and run `TechNexus.exe` |
| `TechNexus-windows-arm64.zip` | The same, for ARM PCs |

`latest/` always holds the newest version's files.

## Installing

With winget:

    winget install Team3990.TechNexus

Or download an installer from `latest/` and run it. It installs for your account only, with no administrator rights needed.
