# BedrollTweaker
A mod for The Long Dark

## Mod features:
  * Adjust the warmth and weight of bedrolls and bearskin bedrolls
  * Enable bedrolls to "stack" warmth bonuses
  * Uses accurate warmth bonuses (not a flat value per bedroll)
  * Options to set how many bedrolls can provide extra warmth and how much warmth they provide
  * Fully configurable and modular

  ## Limitations:
  * If you change the the warmth or weight of bedrolls while in-game, you will need to change scene (e.g. go outside/inside) to apply the changes.
  * Compatible with [BlanketMod](https://github.com/ds5678/BlanketMod), but only one mod's settings for Bedroll Warmth & Weight will apply.

## Requirements
[MelonLoader](https://github.com/HerpDerpinstine/MelonLoader/releases/latest/download/MelonLoader.Installer.exe)

[ModSettings](https://github.com/zeobviouslyfakeacc/ModSettings/releases)

## Installation:
1. Download ```BedrollTweaker.dll``` from [releases](https://github.com/GruffCassquatch/BedrollTweaker/releases)
2. Drop ```BedrollTweaker.dll``` into your Mods folder
3. If you are updating from an older version, you may need to delete the ```BedrollTweaker.json``` file from your Mods folder as old json's can cause errors if the mod's Settings have been changed.

## Uninstallation:
Delete ```BedrollTweaker.dll``` and ```BedrollTweaker.json``` from your Mods folder

## Using The Mod:
1. Open the ```Options``` menu
2. Open the ```Mod Settings``` menu
3. Scroll across to the ```Bedroll Tweaker``` menu
4. Choose to Enable or Disable the mod
5. Mod Options:
	* Tweak Bedroll Warmth & Weight: allows you to set the warmth and weight of the standard bedroll.
  * Tweak Bearskin Bedroll Warmth & Weight: allows you to set the warmth and weight of the bearskin bedroll.
	* Bedroll Warmth Stacks:
		* Allows you to receive bonus warmth from additional bedrolls in your inventory. 
		* Applies when using a bed or bedroll.
	* Cap number of Bedrolls:
		* Limit the number of bedrolls that can provide extra warmth.
    * Bedroll warmth bonuses are applied from highest to lowest, so you will always be using the best available
	* Cap Total Warmth Bonus:
		* Limit the total warmth bonus you can receive from all extra bedrolls.
	* Partial Warmth Bonus:
		* Choose to only apply a flat percentage of each additional bedroll's warmth.
    * E.g. set to 50%:  1st extra bedroll provides 50% of its warmth, 2nd provides 50%, 3rd provides 50% etc.
    * This setting is applied BEFORE Diminishing Warmth is calculated.
  * Diminishing Warmth Bonus:
		* Choose to apply a diminishing percentage of each additional bedroll's warmth.
    * E.g. set to 10%: 1st extra bedroll provides 90% of its warmth, 2nd provides 80%, 3rd provides 70% etc.
    * This setting is applied AFTER Partial Warmth is calculated.    
5. Click ```CONFIRM``` to apply your changes or ```BACK``` to exit without applying changes

## Feedback, Questions & Troubleshooting
* I am active on [The Long Dark Modding](https://discord.gg/QvFE7VV4WZ) Discord server
	* **General questions and feedback:** post in my channel #cass
	* **Troubleshooting:** 
		* Post in my channel #cass or in #troubleshooting 
		* Or create an issue here on GitHub if you're not on Discord
