# nightconfig4fabric
This is a fabric mod wrapper for Night Config by The Electron Will. It is a library for mod developers to use.

## Description
This mod is an API. It will not do anything without a mod that requires it. For mod developers, this mod contains the Night Config jars needed to create configurations with TOML or JSON.

## Why use Night Config?
* Multiple config format support, including JSON and TOML. YAML and HOCON are additional options but not included in this mod.
* Built in support for configuration defaults and validation with ConfigSpecs
* TOML config format supports comments! Let the users of your mod know what your settings do.


## Mod Development
To utilize Night Config, add the following dependencies to your build:
```gradle
dependencies {
	compile 'com.electronwill.night-config:core:3.6.0'
	compile 'com.electronwill.night-config:toml:3.6.0' // Only needed for TOML config format
	compile 'com.electronwill.night-config:json:3.6.0' // Only needed for JSON config format
}
```
Further information about it's use can be found on the Night Config wiki: https://github.com/TheElectronWill/Night-Config/wiki

Code examples can be found on the Github repository: https://github.com/TheElectronWill/Night-Config
