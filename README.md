# Client
All client-related projects (Launcher, EmuLib, Assembly-CSharp)

## Requirements
- Escape From Tarkov 0.12.5.7292
- Visual Studio 2017
- .NET Framework 4.6.1

## Projects:
- EmuLib: hooking additional functionality into Escape From Tarkov - Not used anymore
- Launcher: a lightweight game launcher for proper starting of Escape From Tarkov with EmuTarkov

## Setup
The repository is self-contained; no setup is required.

## Build
1. Open visual Studio 2017
2. Toolbar -> File -> Project/Solution -> Open Client.sln
3. Toolbar -> Build -> Rebuild Solution
6. Copy `Launcher/bin/<target>/EmuTarkov-Launcher.exe` into `<gamedir>`

## Remarks
- Some referrences are shared across projects. These are located in `Shared/References`.
- EmuLib only works with the obfuscated assembly-csharp provided in `EmuLib/References` as it requires patches and a specialized obfuscation regex for proper hooking. - This is a very old file don't use it
