<!-- 
Writing on GitHub Guidance: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github

- Styling text:
	- Bold:                			**Bold text**
	- Italic:              			*Italic text*
	- Strikethrough:				~~Strikethrough text~~
	- Bold and nested italic:		**Bold _Bold Italic_ text**
	- All bold and italic:			*** Bold Italic ***
	- Subscript:					<sub>Subscript text</sub>
	- Superscript:					<sup>Superscript text</super>
	- Underlined:					<ins>Underlined text</ins>

- Quoting text: >
 -->

> [!IMPORTANT]
> **Plugin compatibility**<br/>
> This plugin is only compatible with ***amxmodx 1.9 or higher.*** Support for older versions has been discontinued for ALL my plugins.<br/>
> - *Download [amxmodx 1.9](https://www.amxmodx.org/downloads-new.php) or [amxmodx 1.10](https://www.amxmodx.org/downloads-new.php?branch=master)*

# COD: HitMarkers

![GitHub Created At](https://img.shields.io/github/created-at/LadderGeit/HitMarkers?style=plastic&color=blue)
![GitHub last commit](https://img.shields.io/github/last-commit/LadderGeit/HitMarkers?display_timestamp=committer&style=plastic&color=darkorange)

A simple plugin displaying a symbol inside your crosshair everytime you hit an enemy. This plugin is based on a feature that was introduced for the first time to one of the earlier games of Call of Duty, presumably COD4: MW. The plugin is standard set to display a hitmarker when using any gun. Adjust the cvars to chance how the plugin functions.

## Cvars
```c
register_cvar("hm_hitmarkers", "1");	// Set to 0 to disable hitmarkers
register_cvar("hm_rainbow", "0");	// Set to 1 to enable rainbow hitmarkers
register_cvar("hm_random", "0");	// Set to 1 to enable random hitmarkers
register_cvar("hm_snipers", "0");	// Set to 1 to enable hitmarkers only for snipers
register_cvar("hm_sounds", "0");	// Set to 1 to enable hitmarker sounds
register_cvar("hm_symbol", "x");	// Hitmarker symbol (Requires hm_random "1")
register_cvar("hm_red", "165");		// RGB - Red (Requires hm_rainbow "0")
register_cvar("hm_green", "165");	// RGB - Green (Requires hm_rainbow "0")
register_cvar("hm_blue", "165");	// RGB - Blue (Requires hm_rainbow "0")
register_cvar("hm_dead", "1");		// Sets a different color when victim died.
register_cvar("hm_dead_red", "255");	// RGB Dead - Red (Requires hm_dead "1")
register_cvar("hm_dead_green", "0");	// RGB Dead - Green (Requires hm_dead "1")
register_cvar("hm_dead_blue", "0");	// RGB Dead - Blue (Requires hm_dead "1")
register_cvar("hm_x", "-1.0");		// x pos
register_cvar("hm_y", "-1.0");		// y pos
register_cvar("hm_holdtime", "0.5");	// Hud hold time
```

## Changelog
<details>
<summary>Version list</summary>

- [ ] ~~1.0: First release~~
- [ ] ~~1.1: Added rainbow colors and random symbols customizable by cvars~~
- [ ] ~~1.2: Added sniper-only option~~
- [ ] ~~1.3: Added cvars~~
- [ ] ~~1.4: Added hitmarker sounds customizable by cvars~~
- [ ] ~~1.5: Optimizations + added customizable hitmarker symbols~~
- [ ] ~~1.6: Added functionality for showing a specific color on death~~
- [ ] ~~1.7: Adjusted the plugin to work with all guns on default~~
- [x] 1.8: Adjusted cvar names and added some code readability - [Current Version]

</details>