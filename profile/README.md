# Solar Dynamics ー Nuclear Option

![Preview](https://github.com/Solar-Dynamics-Nuclear-Option/Assets/blob/main/background/ifrit.png)

## Installation

### Automatic

1. Install [NOMM](https://github.com/Combat787/NOMM).
2. Use NOMM to install all the mods you want.

### Manual

1. Install [BepInEx](https://github.com/BepInEx/BepInEx).
2. Download the latest release from the [Releases](https://github.com/Solar-Dynamics-Nuclear-Option/Template-Project/releases) page.
   1. For normal use, it is recommended to use the standard `<name>-<version>.dll` build.
   2. For debugging, it is recommended to use the `<name>-<version>-Debug.dll` build.
3. Put the DLL in your plugins folder:

```text
NuclearOption/
└── BepInEx/
    └── plugins/
        └── [Mod Name]/
            └── [Mod Assembly].dll
```

![Preview](https://github.com/Solar-Dynamics-Nuclear-Option/Assets/blob/main/background/vagrant.png)

## Bug Reports

Bug reports should be submitted through their repository's respective `Issues` page.

When reporting a problem, include as much of the following relevant information as possible:

* Versions
    * Mod Version
    * Nuclear Option Version
    * BepInEx Version
* Logs
    * Nuclear Option Log
    * BepInEx Log
* Steps to reproduce the problem.
* Other installed mods that may be relevant.

Standard Nuclear Option Log Path:

```text
%HOMEPATH%\AppData\LocalLow\Shockfront\NuclearOption\Player.log
```

Standard BepInEx Log Path:

```text
%PROGRAMFILES(X86)%\Steam\steamapps\common\Nuclear Option\BepInEx\LogOutput.log
```

![Preview](https://github.com/Solar-Dynamics-Nuclear-Option/Assets/blob/main/background/compass.png)

## Credits

| Resource            | Author                   |
|---------------------|--------------------------|
| Nuclear Option      | Shockfront Studios       |
| MonoMod             | 0x0ade                   |
| HarmonyX            | BepInEx                  |
| BepInEx             | BepInEx                  |
