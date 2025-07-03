# Cupboard

Cupboard is a Rust-style protection plugin designed for Minecraft PvP servers. It allows players to protect their builds and items using a Block of Gold, while still enabling destructive mechanics like TNT raiding — fully configurable for balance and server style.

Supported platforms: Spigot, Bukkit, Paper, Leaves, Folia, Luminol

⸻

Description

This plugin adds a territory protection system similar to Rust. By placing a Block of Gold (the “Cupboard”), players can claim a 19×19×19 cube area around it. Within this area, unauthorized players cannot place or break blocks. Explosives like TNT remain effective (configurable), enabling base raiding while keeping Minecraft’s core mechanics intact.

⸻

Features
	•	Area protection using Block of Gold (19×19×19, centered)
	•	Access control via right-clicking the gold block
	•	Prevent TNT damage in protected areas (configurable)
	•	Prevent Creeper damage in protected areas (enabled by default)
	•	Prevent Nether portals from being:
	•	Blocked by solid blocks
	•	Covered by lava
	•	Used by non-player entities
	•	Customizable Nether portal search radius
	•	PigZombies drop Nether Wart
	•	Configurable world borders
	•	Border can shrink over time
	•	Adjustable scale for Nether and The End
	•	TNT can destroy obsidian, water, and lava (configurable)
	•	Fully translatable via language files

⸻

Protection Details

What is Protected:
	1.	Unauthorized players cannot place or break blocks
	2.	Unauthorized players cannot use stone pressure plates or stone buttons
	3.	Mobs cannot trigger stone pressure plates
	4.	Creepers cannot destroy blocks within the protected area

What is Not Protected:
	1.	Unauthorized players can place TNT, which ignites immediately (configurable)
	2.	Unauthorized players can use:
	•	Wooden pressure plates and buttons
	•	Chests
	•	Armor stands
	3.	TNT can destroy blocks inside the protected area (configurable)

⸻

Commands and Permissions
	•	/kill — Allows players to kill themselves (useful if trapped in a protected area)
	•	No permission system required
	•	Operators in Creative Mode can bypass protections automatically

⸻

Installation
	1.	Download the plugin .jar file
	2.	Place it in the plugins/ folder of your server
	3.	Restart the server
	4.	Edit the config.yml and lang.yml files to adjust settings

⸻

Compatibility

This plugin is tested and compatible with the following platforms:
	•	Spigot
	•	Bukkit
	•	Paper
	•	Leaves
	•	Folia
	•	Luminol

⸻

License

(Specify your license here, e.g., MIT, GPL-3.0, etc.)

⸻

Credits

Developed by [YourNameHere].
Inspired by the territory protection system in Rust.
