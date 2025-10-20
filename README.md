# [Elin Mod] Action Status

## Description

Display current action status on the status info widget.

Handled scenarios:
- Idle
- Collect (Mining, Woodcutting, Gathering plants)
- Fishing
- Eat
- Play Instrument
- Rest
- Sleep
- Fighting

Does not handle well:
- Click and hold to walk, still shows as idle
- Walk short distances like adjacent tiles
- Distinguish Mining from Woodcutting actions, it's considered as Collect by the game

## Credit

Using template from https://github.com/gottyduke/Elin.Plugins/releases/tag/PluginTemplate
