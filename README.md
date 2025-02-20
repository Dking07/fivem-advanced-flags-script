# ADVANCED FLAGS SCRIPT [STANDALONE]

## DESCRIPTION

This script allows you to apply custom Advanced Flags to vehicles in FiveM, giving you full control over vehicle handling behaviors. Unlike other scripts, such as [SPEED GAIN FIX](https://github.com/Dking07/fivem-speed-gain-fix), this script enables you to define and apply any Advanced Flags you want.

## KEY FEATURES

* Customizable Advanced Flags: You can define and apply any Advanced Flags to vehicles, allowing you to fine-tune vehicle handling to your liking.

* Preset System: The script supports presets, enabling you to apply specific flags to specific vehicles.

* Blacklist System: You can blacklist certain vehicles from being affected by the script, ensuring that only the desired vehicles have their handling modified.

* Dynamic Application: The script dynamically applies the flags to vehicles as players enter them, ensuring that the changes are always active.

* Efficient Monitoring: The script continuously monitors vehicles to ensure that flags are only applied to valid entities, and it cleans up any references to deleted vehicles.

# HOW IT WORKS

* Configuration: The script is configured via the config.lua file, where you can define:

* Active Flags: The Advanced Flags you want to apply globally or to specific vehicles.

* Blacklist: A list of vehicles that should not be affected by the script.

* Presets: Custom presets that apply specific flags to specific vehicles.

* Flag Application: When a player enters a vehicle, the script checks if the vehicle is eligible for flag application (based on the blacklist or presets). If eligible, it applies the defined Advanced Flags to the vehicle's handling data.

* Monitoring: The script continuously monitors vehicles to ensure that flags are only applied to valid entities and cleans up any references to deleted vehicles.

## GET NOW

* [DOWNLOAD](https://dking.tebex.io/package/6695029)

## HOW TO INSTALL

* [Download](https://keymaster.fivem.net/asset-grants) script;
* Place it in the resources folder;
* Add 'ensure dk_advancedflags' (without quotes) to server.cfg.

### MODIFICATIONS

* Add CCarHandlingData in the SubHandlingData section, like this:
  ```
  <SubHandlingData>
    <Item type="CCarHandlingData">
    </Item>
    <Item type="NULL" />
    <Item type="NULL" />
  </SubHandlingData>
  ```

## CONFIG

* ### You can choose which effects will be applied through the configuration file.
<div align="center">
<img src="https://github.com/Dking07/fivem-backup/blob/main/My%20Scripts/Advanced%20Flags/config.png" width="500px" />
</div>

## DISCORD

### [Dking Warehouse](https://discord.gg/Rw6vjcXspG)

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2025 ©