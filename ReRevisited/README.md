# Liero Promode Re-Revisted

A fast, balanced mod based on LieroPromode, adjusted for WebLiero. Less spammy weapons, less particles and quick movement are the main features.
This mod is best played on Arenas-Good mapset, with Extended Maps option on for FFA. 

## A little bit of history

Liero ProMode is a mod, or a TC, for Joosa's Liero game. 
The mod was created by Biernath John and was meant to improve gameplay on open maps. Weapons are more balanced, worm movement faster, aim down restriction was removed, etc. 
Final version of the mod was named Liero Promode Revisited

## Re-Revisted

Webliero, being an online multiplayer game, introduced many game modes other than classic 1v1 mode. FFA is the most popular way of playing nowadays, and this exposed some issues with the Liero ProMode when played in FFA.
Many weapons which are okay or even weak in the game (Chiquita Bomb, Big Nuke) proved to be very strong in FFA when there are mutliple targets available. Other weapons caused unnecessary clutter or were prone to be spammed (mines). Finally some weapons were borderline OP, and most pro players played with a set of gauss, rifle, zimm, laser with little variations. 

Re-Revisited Re-vitits the Revisited and revises some of its weapons, aiming to make the game better suited for frantic Webliero environment.

## How to use

To use the mod:
- download all its files from this folder
- open chat (`enter` by default)
- type `/loadmod` and select both `mod.json5` (this contains "logic" changes of the mod) and `sprites.wlsprt` (this contains gfx changes of the mod)

# Changelog

## 1.2.1 (BETA)

* INCENDIATOR got remodelled to fulfill a different role. Now has limited range and less damage, but bounces. It disappears quickly so shouldn't be too flammable, but allows to reach worms hiding behind a corner. New bouncendiator is super deadly in confined spaces, because it does not disappear on worm hit.

## 1.2.0

This version aims to fix some of the spammy weapons discovered by current meta.

* MINI NUKE got its third stage particles removed entirely, and its second stage particles last a bit shorter. On the upside, it got one more second stage particle to compensate. Overall it now requires much more precision than before.

* CLUSTER POD is now also requiring more precision, having way less spread and also more tight projectile pattern. It now drops 20 pieces instead of 26, since hitting someone with such a dense cloud of 26 particles was a sure death.

* INCENDIATOR also got less spread. Its projectiles now fly almost entirely straight, and ammo has been chopped to two. To compensate, its speed was increased almost twofold.

* GRENADE -> DYNAMITE This change is in the other direction. Previously it was too hard to hit someone flying with the grenade, which made it a total hit or miss - literally. Now its damage has been spread into three explosions to cover a bit more area. This is an experimental change which may backfire, but for now let's see.

* FLAMER - just a small buff by adding a little bit of amm0; otherwise unchanged.


## 1.1.2 (CURRENT RELEASE)

This version aims to fix some imbalance issues disovered in the game.

### 1.1.2 

* SUPER SHOTGUN - still trying to make it useful. Now has very little delay between its shots, tighter spread and 1 detect range in line with well-performing AUTO SHOTGUN. 
* FLAMETHROWER -> FLAMER - Shorter flamer as a pure melee weapon, but with much more damage. Very short clip to compensate, otherwise it would be a totally OP in FFA where people often don't move. The FLAMER a bad opener but a great finisher. It is supposed to be a last weapon to be used in your set, when the enemy is out of his heavy hitters and distance has closed to a minimum. 

### 1.1.1

Projectile weapons' speeds have been increased for quicker overall gameplay and higher usefulness of these:

* CHAINGUN - projectile speed increased 
* MINIGUN - projectile speed increased 
* AUTO SHOTGUN - projectile speed increased, damage reduced slightly to compensate
* SUPER SHOTGUN - projectile speed increased, damage reduced slightly to compensate
* SCATTERGUN - projectile speed increased, spread greatly reduced to compensate

Other changes:

* RIFLE - with growing power of other weapons, its kickback has been returned to original value.
* WINCHESTER - reduced ammo to 4 and increased delay between shots, but now deals 20 damage. This change is an experiment towards "intermediate" weapons between mainline weapons like rifle and finishers like chaingun. As an intermediate weapon, winchester deals close to 3 times the damage or rifle per clip, but cannot kill in one clip. If the player can land 5 shots out of 8 provided by winchester in 2 clips, he will deliver the kill much faster than a RIFLE user. 
* FLAK CANNON - increased damage of direct shot slightly, to put it more in line of general damage output of similar weapons.
* CRACKFIELD - removed; does generally not fit the mod
* ZIMM - reduced its lasting time to 2 seconds to reduce map clutter
* MISSILE - reverted its AOE effect to original ProMode value. MISSILE is strong enough on its own and does not require additional buff. Visually it still has nice boom and smoke, but damage dealt by aoe is very miniscule, up to about 10 damage in short range.

### 1.1.0

* MORTAR - redone; now deals most of its damage with an explosion at the center. There are less particles and they deal less damage and travel shorter. This means mortar needs to be hit very close to the worm to deal relevant damage, but at the other hand, its damage is much more predictable now.
* ACID FAN (new) - Fan returns! My biggest concern with it in the Promode was that while fun, it ultimately did not do much for the game at pro level. Now it deals damage too, meaning it is a good weapon to have in the set for when you need to defend yourself and other weapons are reloading. You can also combine it with something slow to give it a "fan boost". Try with grenades!
* FLAMETHROWER - redone, altough it is an experiment. It now does not disappear on worm hit and should deal roughly similar damage as before. This makes the weapon work a bit differently and might add some variety to the game.
* GRENADE - was underused, so it is buffed a bit. Deals more damage and explodes quicker, but at a cost of slightly less detect range of the explosion.
* GRN LAUNCHER - was underused so it got buffed by reducing delay between shots.
* DARTGUN - was underused so it got buffed by increasing damage significantly.
* LIGHTNING GUN - was a bit too strong, so its damage got very slightly reduced.
* CRACKFIELD - was a bit too strong and easy to use, so it now pushes the worm quicker out of its range. This should reduce overall damage and push the crackfield more into defensive weapon territory.

## 1.0

Generally, the idea was to:
- make each weapon useful, by both nerfing most op ones and buffing weaker ones
- make the game less luck-based by removing or reworking most particle/spam weapons. 

Max reload time is 400 now, like gauss or spikeballs. Some weapons reload quicker but none longer.
Some visuals were changed, but all the sprites and general style did not change. 

direct fire main attack
* RIFLE - Nerfed from killing in 3 shots (34 damage) to killing in 3-plus-a-tap (32 damage). Additionally, its pushback was tuned down significantly.
* BAZOOKA - Added significant AoE range and +1 detect range.
* MINIGUN - Unchanged
* SUPER SHOTGUN - shoots 50 particles now and they are much faster. It is technically possible to kill in two shots.
* CHIQUITA GUN - shoots 4 bananas instead of 3. This means it is somewhat reliable in killing in two shots. 
* ZIMM - Disappears much faster than before.
* GAUSS GUN - Nerfed in damage; still kills in 3 shots but just barely. Previously it dealt ~42-45 damage, now it is ~34-36.
* PROXY MINE - Flies much faster and explodes like a bazooka, leaving no particles.
* DOOMSDAY - Unchanged.
* THROW KNIFE - Slightly buffed in damage and reload speed, but still kills in 5 shots.

direct fire finisher
* INCENDIATOR - +1 ammo, otherwise unchanged
* AUTO SHOTGUN - Replaces shotgun. Greatly increased amount of pellets, ammo and has reduced reload. It is actually worth using now.
* CHAINGUN - Minimally faster projectiles, otherwise unchanged.
* WINCHESTER - Unchanged.
* FLAK CANNON - Its particles are much faster but disappear quickly, so the player cannot spam the map with flak particles anymore.
* LASER - Unchanged.
* DATRGUN - Changed significantly, now does not go through worms and hits normally, so its damage is much more predictable. It also now stays on the ground for a short while. Particularly useful on bunny hops. 
* SCATTERGUN - Increased damage from 2 to 3. This is a very major change, and scattergun is now a viable melee range weapon.
* FLAMETHROWER - Unchanged.
* LIGHTNING GUN - Initially meant to replace solar scorch, but eventually it evolved into being a separate weapon. It deals the same damage as scorch but has very limited range and bounces off the ground.
* SOLAR SCORCH - Unchanged.

indirect fire
* MORTAR - Its particles are much faster and disappear quickly, so the player cannot spam the map with them. Mortar cannot one-shot a worm anymore even on direct hit.
* CLUSTER POD - Increased particle count.
* MINI NUKE - Slightly buffed generally by making it activate faster, having one more bomblet and having flak-like particles.
* SPIKEBALLS - Nerfed by reducing spikes count from 8 to 7, making them less bouncy and disappear much quicker.
* TUPOLEV - Changed significantly. Reloads much faster, drops bombs more uniformly, and most importantly, disappears after dropping 10th bomb.
* MISSILE - Aside from carrying bazooka's nasty AoE warhead, unchanged.
* GRENADE - Replaces explosive. One LARGE blast, capable of killing in two shots, instead of three mediocre dynamite sticks. Cannot hit the worm with it, but explodes very quickly.
* GRN LAUNCHER - Buffed by greatly reducing time between shots. It can now lay a dense obstacle field both in air and on the ground and is somewhat useful.
* CRACKFIELD - Changes crackler (HOOVER CRACK) to be much more predictable and less spammy. Its particles are limited to a circle with clearly defined edges.

---------------
Weapons below were removed from the game.

* CHIQUITA BOMB - Was reworked so each banana dealt bazooka-like damage, but this was too powerful in FFA. Removed.
* LARPA - Staple of liero gameplay, but sadly, wreaks havoc on FFA games due to all the spam. And, honestly, does not work in pro duels. Removed.
* BOUNCY LARPA - Since standard larpa was already guilty of spam, Bouncy Larpa was the first one to be executed. 
* BOOBY TRAP - fun idea, but does not really do anything for the gameplay. Removed.
* MINE - the turd got removed.
* FAN - fun, but does not do anything for pro play really. 
* ACID GUN - I tried combining it with fan but even together, these were worse than just having a flamethrower or minigun.
* MINI ROCKETS - this is actually a decent weapon, but it was too close to doomsday and chaingun and overlapped their functions. 
* NAPALM - it overlaps mortar functionality. I could not think of anything to make it worth staying, so it got removed.

* BIG NUKE - Bouncy larpa at least got to be executed. Big nuke was shot right on the spot.



