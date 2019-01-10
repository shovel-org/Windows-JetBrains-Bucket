# Scoop JetBrains bucket [![Build status](https://ci.appveyor.com/api/projects/status/dypffduw38i80p5d?svg=true)](https://ci.appveyor.com/project/Ash258/scoop-jetbrains)

`scoop bucket add JetBrains 'https://github.com/Ash258/Scoop-JetBrains.git'`

Each IDE have all available releases. Pre-release versions do not contains bin property (stable release binaries will not be overriden)

## Portable sufix

- All created files, which are generated (config, system, plugins, log) are moved into each application root folder `persistedConfig`
- Nothing will be saved into system path.

TODO:

- Hub
- MPS
- TeamCity
- UpSource
- Dotpeek
