# wazo-calld-globalvars-plugin

Fix global variables accumulation in Asterisk in the long run.

## Installation

```sh
wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-calld-globalvars-plugin"
```

Installing this plugin will restart `wazo-calld`, impacting call processing.

After installing this plugin, global variables will be correctly cleaned up.

This plugin is only useful for Wazo servers before 24.14.

## Uninstallation

```sh
wazo-plugind-cli -c "uninstall wazocommunication/wazo-calld-globalvars"
```
