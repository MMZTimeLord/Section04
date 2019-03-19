# Section04 - Tank Battle

Open world head-to-head tank battle game, with simple AI and Advanced controls in Unreal 4

This is for the C++ and Unreal Course on Udemy.

## Game Design Document (GDD)

### Concept:

Tank Battle is an open-world head-to-head tank combat game.
Terrain will be used for tactical advantage.
The focus will be on flow and feel.

### Rules:

You can move anywhere in the terrain, which is surrounded by mountains.
Both players start with finite health and ammo.
Each direct hit takes away health. Lower health slows movement (tank damaged)
	Later on make sections to be damaged:
		treads on each side: Damage = lower to no movement on that side. Affects maneuverability.
		engine at the back: Damage = slower movement to no movement.
		turret: Damage = slower to no turret traversal speed
		gun: Damage = slower reload time, lower accuracy, ultimately no ability to fire.
The last player standing wins.

### Requirements:

SFX: Gun Firing, Explosion, Barrel Moving, Turret Moving, Engine Sound.
	Later on add sound variations, based on damage on each area.
Static Mesh: Simple Tank Comprising Tracks, Body, Turret and Barrel. (Primitives first)
Textures: Later on we'll want to add for visual flare.
Music: Background music to create tension.
