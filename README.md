# Glide // Styled's Vehicle Base

A pack of content and entity classes to add cars, motorcycles, planes, helicopters and tanks to Garry's Mod.

[![GLuaLint](https://github.com/StyledStrike/gmod-glide/actions/workflows/glualint.yml/badge.svg)](https://github.com/FPtje/GLuaFixer)
[![Workshop Page](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-steam-workshop.jross.me%2F3389728250%2Fsubscriptions-text)](https://steamcommunity.com/sharedfiles/filedetails/?id=3389728250)
[![Discord Server](https://img.shields.io/badge/Discord-Discord?style=flat&logo=discord&logoColor=white&color=5662F6)](https://discord.gg/aSecXvMXM2)
[![ko-fi](https://img.shields.io/badge/Support%20me%20on%20Ko--fi-Kofi?style=flat&logo=kofi&logoColor=white&color=FF5E5B
)](https://ko-fi.com/styledstrike)

## Features

- Includes base classes for cars, motorcycles, helicopters, planes and tanks
- Duplicator/Advanced Duplicator 2 support
- You can use the regular sandbox Color tool
- No constraints are used for wheel physics
- Comes with 4 cars, a bus, a ATV, 2 motorcycles, 2 planes and a tank
- First person and GTA-like third person camera
- Players can fall off motorcycles
- Vehicles can set custom player poses per seat
- Editable engine/transmission/traction properties for cars and motorcycles
- Car headlights, reverse lights, break lights and horns
- Separate chassis and engine health
- Some vehicles can switch between weapons
- Some aircraft can deploy flare countermeasures
- Vehicle turrets are lag compensated (currently in a limited fashion)
- All vehicles (except tanks) can be controlled with Wiremod
- Show indicators while driving/flying near the skybox (invisible map walls)

### Player settings

- Camera sensitivity, distance, FOV, and auto-center
- 3 mouse input modes for flying: Point-to-aim (LFS), Control movement directly (WAC) and Free camera (GTA V)
- Custom key binds, manual gear shifting toggle
- Change the volume for land vehicles, aircraft and explosions
- Change the volume of all Glide vehicles when someone is talking on voice chat
- Toggle tips, headlight shadows, automatic headlights, and many others

### SWEPS

- `Vehicle Repair` SWEP, shows the chassis and engine health
- `Homing Launcher` SWEP, can also lock on any player on a seat

### Tools

- Missile Launcher
- Projectile Launcher
- Turret
- Vehicle Material
- Wheel Model
- Water Driving

### Other features

- Many different wheel sounds for different surfaces
- Custom tags when looking at Glide vehicles
- Custom tags when looking at players while driving Glide vehicles
- Lots of optimizations (model LODs, client-side vehicle sounds/animations only play when they are near you, etc)
- Custom notifications system

## Server console variables

### Vehicle damage multipliers

| Command | Description
| --------------------------------- | ------
| `glide_bullet_damage_multiplier` `<number>` | Damage multiplier for bullets hitting Glide vehicles
| `glide_blast_damage_multiplier` `<number>` | Damage multiplier for explosions hitting Glide vehicles
| `glide_physics_damage_multiplier` `<number>` | Damage multiplier taken by Glide vehicles after colliding against other things

### Sandbox limits

| Command | Description
| --------------------------------- | ------
| `sbox_maxglide_vehicles` `<number>` | Max. number of Glide vehicles that one player can have
| `sbox_maxglide_standalone_turrets` `<number>` | Max. number of Glide Turrets that one player can have
| `sbox_maxglide_missile_launchers` `<number>` | Max. number of Glide Missile Launchers that one player can have
| `sbox_maxglide_projectile_launchers` `<number>` | Max. number of Glide Projectile Launchers that one player can have

### Turret tool limits

| Command | Description
| --------------------------------- | ------
| `glide_turret_max_damage` `<number>` | Maximum damage dealt per bullet for Glide Turrets
| `glide_turret_min_delay` `<number>` | Minimum delay allowed for Glide Turrets

### Missile Launcher tool limits

| Command | Description
| --------------------------------- | ------
| `glide_missile_launcher_min_delay` `<number>` | Minimum delay allowed for Glide Missile Launchers
| `glide_missile_launcher_max_lifetime` `<number>` | Maximum missile flight time allowed for Glide Missile Launchers
| `glide_missile_launcher_max_radius` `<number>` | Maximum radius from explosions created by Glide Missile Launchers
| `glide_missile_launcher_max_damage` `<number>` | Maximum damage dealt by explosions from Glide Missile Launchers

### Projectile Launcher tool limits

| Command | Description
| --------------------------------- | ------
| `glide_projectile_launcher_min_delay` `<number>` | Minimum delay allowed for Glide Projectile Launchers
| `glide_projectile_launcher_max_lifetime` `<number>` | Maximum projectile flight time allowed for Glide Projectile Launchers
| `glide_projectile_launcher_max_radius` `<number>` | Maximum radius from explosions created by Glide Projectile Launchers
| `glide_projectile_launcher_max_damage` `<number>` | Maximum damage dealt by explosions from Glide Projectile Launchers

## Contributing

Please follow the [these rules](https://github.com/StyledStrike/gmod-glide/blob/main/.github/pull_request_template.md) before opening pull requests.
