# Scoop JetBrains bucket [![Build status](https://img.shields.io/appveyor/ci/Ash258/scoop-Jetbrains/master.svg?style=popout&logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/Ash258/scoop-jetbrains)

`scoop bucket add JetBrains`

Each IDE have all available releases. Pre-release versions do not contains bin property (stable release binaries will not be overriden)

## Portable suffix

- All created files, which are generated (config, system, plugins, log) are moved into each application root `profile` folder
- Nothing will be saved into system path.

TODO:

- Hub
- MPS
- TeamCity
- UpSource

| Application  | Stable |  RC   |  EAP  |
| :----------- | :----: | :---: | :---: |
| CLion        |  ✔ ✔   |  ✔ ✔  |  ✔ ✔  |
| DataGrip     |  ✔ ✔   |  ✔ ✔  |  ✔ ✔  |
| DotCoverCLT  |   ✔    |   ❌   |   ✔   |
| DotMemory    |   ✔    |   ❌   |   ❌   |
| DotMemoryCLT |   ✔    |   ❌   |   ✔   |
