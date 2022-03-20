# Project64 - Nintendo 64 Emulator

# Patched version README:

This patched version changes the following:

- Adds 12 MB and 16 MB options for the RAM size.
- Disables the nag screen.
- Changes the following default settings:
  - General settings:
    - "Enable Discord Rich Presence": Changed to False
    - "Hide advanced settings": Changed to False
  - Advanced:
    - "Enable debugger": Changed to True
    - "Always use interpreter core": Changed to True
    - "Check if Project64 is already running": Changed to False
    - "Store game saves in separate folders": Changed to False
    - "Speed display": Changed to True
    - "Show status bar": Changed to True
  - Defaults:
    - "Memory size": Changed to 16 MB
- Removes the Video plugin selection from the welcome screen.
  - The reason for this change is because I don't know where is the GLideN64 plugin.

# Original README:

Project64 is a free and open-source emulator for the Nintendo 64 and Nintendo 64 Disk Drive written in C++ currently for Windows (planned support for other platforms in the future)

## System Requirements

* Operating System
  * Windows XP and later
* CPU
  * Intel or AMD processor with at least SSE2 support
* RAM
  * 512MB or more
* Graphics card
  * DirectX 8 capable (Jabo's Direct3D8)
  * OpenGL 1.1 capable (Project64 Video)
  * OpenGL 3.3 capable (GLideN64)
  
### Stable Builds

Installer for the latest stable release: https://www.pj64-emu.com/windows-downloads

Follow the instructions in the setup window to complete the installation.

Download nightly builds here: https://www.pj64-emu.com/nightly-builds

AppVeyor (Windows x86/x64): [![Build status](https://ci.appveyor.com/api/projects/status/sbtwyhaexslyhgx3?svg=true
)](https://ci.appveyor.com/project/project64/project64/branch/develop)

<sub>Note: x64 builds are **NOT** recommended for regular use. They are incomplete and very experimental. Due to this, x64 builds are currently _slower_ than 32-bit builds.</sub>

## Support

[**Join the official Project64 Discord server**](https://discord.gg/Cg3zquF) to seek help from Project64 developers, contributors, and the community! Please ask questions here first and see if you should open an issue.

### Compiling

```
Visual Studio Community 2015 or later
```

Load .sln project file and compile.

See the [BUILDING.md](https://github.com/project64/project64/blob/develop/BUILDING.md) file for details.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/project64/project64/blob/develop/.github/CONTRIBUTING.md) before contributing, opening issues or pull requests, or for other contributions.

## Versioning

We use semantic versioning for Project64. For the versions available, see the [tags on this repository](https://github.com/project64/project64/tags).

## Author / Contributors

* **Zilmar** - *Current maintainer* - [Zilmar](https://github.com/project64)
* **Jabo** - *Previous contributor* - Jabo
* **Smiff** - *Previous contributor* - Smiff
* **Gent** - *Previous contributor* - Gent

See also the list of [contributors](https://github.com/project64/project64/contributors) who participated in this project.

## License

This project is licensed under the GPLv2 License - see the [LICENSE.md](https://github.com/project64/project64/blob/develop/license.md) file for details.
