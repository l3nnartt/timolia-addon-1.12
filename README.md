# TimoliaAddon-1.12

[![Build Addon](https://github.com/l3nnartt/TimoliaAddon-1.12/actions/workflows/release.yml/badge.svg)](https://github.com/l3nnartt/TimoliaAddon-1.12/actions/workflows/release.yml)

## Setup Workspace
```
gradlew setupDecompWorkspace 
```
#### Setup for InteliJ
```
gradlew idea
```
#### Setup for Eclipse
```
gradlew eclipse
```
#### Build Addon
```
gradlew build 
```
#### Debug Addon
```
-Dfml.coreMods.load=net.labymod.core.asm.LabyModCoreMod -DdebugMode=true -Daddonresources=addon.json
```
For more information you can check out the LabyMod [documentation](https://docs.labymod.net/pages/create-addons/introduction/).