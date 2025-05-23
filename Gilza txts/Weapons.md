[Link to the ModWorkshop page.](https://modworkshop.net/mod/39854)

[Link to the latest Patch Notes.](https://github.com/irbizzelus/Gilza/releases)

<p align="right"> Use this icon to view weapon category chapters: <img width="286" height="71"  src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

Stats are updated for patch: 2.4.10

# General weapon handling updates:
## Recoil: general changes
All weapons' recoil was overall increased. However, first 5 bullets fired from your weapon will have reduced recoil, so firing in short controlled burst is beneficial, especially at longer ranges. Reduced recoil for first 5 bullets does not apply to Shotguns, Snipers, and single shot fire mode Pistols.

Amount of recoil now depends on your weapon's base stability value - stability value that you see whenever you purchase a weapon, before skills/weapon attachments were applied. Lower base stability means higher overall recoil. Because of these changes, 2 weapons with identical stability values after skills/attachments __will__ feel different, if their base stability is different.

Horizontal recoil will now always favor weapons into a certain pre-defined direction - either left or right. Horizontal recoil will never jump from left to right (and vice versa), but the pull to whichever direction, is overall stronger then in the base game.

Weapon attachments and/or skills now affect weapon recoil 2x less. In vanilla upgrading a weapon from 0 to 100 stability with attachments/skills effectevely reduced weapon camera recoil by 6x times. Max possible imrovement you can get now is 3x. This makes basic stability stat more important when choosing a weapon, and makes it harder to make it into a "laser" gun.

## Recoil: new compensation
Whenever you hold the trigger your weapon's recoil forces your camera to climb up. If you stop holding the trigger, your camera will go down to where-ever you were aiming at the start of the trigger pull. This mechanic is almost completely gone now, because weapons have more overall recoil, and after a lengthy burst your camera would come back down to the floor. 
Compensation still exists for weapons with extremely low recoil however, for the first couple of shots. So, if you are using your weapon in single-fire or firing in short bursts, it will feel better to use for longer ranges.

**Compensation visuals** (GIF's make take some time to load)
| Gilza (compensation disabled) | Vanilla PD2 (compensation enabled) |
| -------- | -------- |
|  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Compensation_off.gif)  | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Compensation_on.gif)  |

-----

## Recoil: Hip-fire
Hip-fire now has a 36 stability point penalty, to incentivize aiming down sights. Technician's "Fire control" skill can remove this penalty.

## Accuracy: Hip-fire
Hip-fire now has a 28 accuracy point penalty, to incentivize aiming down sights. Technician's "Fire control" skill can remove this penalty.

## Accuracy: Full-auto
Full-auto fire mode now has a 28 accuracy point penalty. This penalty is applied only when your weapon is switched to full-auto fire mode - switching your weapon's fire mode during the heist, will negate this penalty, for as long as your weapon's fire mode is set to single-fire.
This penalty is not applied while bipoded.

# General weapon tweaks:
* Weapons' accuracy and stability are no longer affected if you: crouch, jump, walk or sprint
* DMR kits and some long barrels were converted into "AP kits" that can penetrate shields, body armor and walls
* More weapon attachments have descriptions now with more details, like ammo pick up changes, damage values etc.
* A LOT of weapon attachments were rebalanced
* Mag increasing attachments will now slow down your reload speed
* Some attachments like Stocks and Foregrips can now speed up your reload speed
* All scopes don't have accuracy/stability bonuses anymore - you can choose whichever one you like the look of more
* Scopes on Sniper rifles will now have "logical" concealment
* Every shotgun will now deal a minimal % of it's damage with every shot. % depends on the shotgun type. For more info check the shotgun tab.

# Melee weapons overhaul:
Melee weapon damage that you see in your inventory now represents how much % of enemy's HP your weapon will deal with a swing. This includes charged damage as well. So if you have a melee weapon with 25(50) damage, it will kill an enemy in 4(2) hits.

Melee weapons now deal 20%-75% minimum damage per hit.

Some enemies take less melee damage:
* Bulldozers receive _10x_ less melee damage.
* Headless bulldozers receive _15x_ less melee damage.
* Most bosses receive _20x_ less melee damage.
* Winters and his shields receive _2x_ less melee damage.

Melee knockdown now depends on weapon's range. More range your melee has, less knockdown it has. It might not always make sense when you look at some melees, but suppress your instincts in the honor of better balance!

Grey swats can now be knocked down by melee weapons.

Almost all melee charge sounds were removed, due to charge time mismatch. To add clarity, new option for melee UI was added to Gilza's options menu and it's enabled by default.

"Kazaguruma" and "Lumber Lite L2 chainsaw" melee weapons can now deal chainsaw-like melee damage while holding the weapon in front of you. This feature is directly ported from [IREnFIST](https://modworkshop.net/mod/28585).

# Assault rifles:
### General AR updates
* All DMR kits and some long barrels were reworked into "Armor piercing kits" that can penetrate shields, body armor and walls, but ammo pick up while using them is halved. Affected weapons: Car-4, AK74, AK 7.62, Golden AK 7.62, AMR16, Clarion, Gewehr3, KS12 (upper receiver).
* About a third of all AR's had their rate of fire updated

### New attachments
* M308 and Galant rifles now have AP rounds - same as AP(DMR) kits, but they are categorized as ammuntion
* 7.62 Little Friend now has a 5.56 conversion kit - it reduces damage but increases ammo pick up
* Byk-1 now has a 5.45 conversion kit - it reduces damage but increases ammo pick up
* AMCAR now has RRLP rounds - they reduce damage class to 125 and increase ammo pick up
* Falcon rifle now has 7.62x51mm SP rounds - they reduce damage class to 250 and increase ammo pick up
* Car-4, AK 7.62 and Golgen AK 7.62 now have HP rounds - they can be used to upgrade weapon's damage class (which affects ammo pick up)
* 7.62 Little Friend and Byk-1 now have a High velocity round for their underbarrel launchers - increase grenade travel speed by 3x with a 20% ammo pick up cost. Note: only works if you are the lobby host, otherwise reverts itself to standard round stats.
* Gewehr3's CQB and Sniper kits have new updated values: CQB kit now has reduced damage class (200) with increases to other stats, while the Sniper kit acts like an AP kit

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|125 dmg|3|4|Best for crits|
|155 dmg|2|3|Average rifles, should feel the most similar to vanilla PD2 AR's|
|200 dmg|2|3|Basically 155 class, but with better anti-dozer potential and less restrictive customization, at a cost of 15% ammo pick up. Benefits from "Overkill" aced the best, due to damage class upgrade|
|250 dmg|1|2|Most stable and comfortable TTK, but poor ammo economy if not accurate.|
|450 dmg|1|1|Usually highest recoil and worst ammo economy. Best combined with body expertise/ammo related skills.|

# Shotguns:

### General shotgun updates

* All shotguns now have new damage fall-off. In short: more damage per shot = better damage distance. For more details use "More weapon stats" mod in game.
* All shotguns now fire 10 pellets per shot.
* Rate of fire was updated for almost every shotgun, and it is now balanced around other shotguns with same damage class

#### New shotgun damage
Shotgun damage in vanilla Payday 2 is always the same if at least one of your shotgun pellets hits an enemy, and its always equal to the damage stat you see in your invenotry.

In most video games, shotgun's damage is spread across every fired pellet. So if you were to hit an enemy, you would deal "shotgun's damage/amount of pellets" per every pellet you hit, so not every hit would deal full damage.

Gilza uses a new "hybrid" system which adds a "minimal shotgun damage multiplier" property to all shotguns. It ensures that your shotgun will always deal minimal amount of damage per shot, with the rest of the damage being applied with additional pellets.

For ease of explanation, here is an example: Let's take a shotgun with 10 pellets and max total damage of 200. In vanilla PD2 you would deal 200 damage if at least one of your pellets hits an enemy. In most other games every pellet would deal 20 damage individually.

With Gilza, this same shotgun also has a minimal shotgun damage multiplier property. This property depends on shotguns's damage class, but for the sake of this example let's say for this shotgun it's 0.5.
Anytime you fire this shotgun, first pellet that hits an enemy, would ALWAYS deal 100 damage. After it, other pellets from the same shot will deal "100/9" or ~11.11 damage.
This ensures that your shotgun can always kill enemies in a set amount of shots.

This damage still scales with damage drop off however, so enemies on the opposite side of the map will just receive "minimal damage * minimal shotgun damage multiplier" for the first pellet.

As for headshots: if any of your pellets from the same shot connects to the head, your minimal damage will also receive a headshot multiplier. Additional pellets deal extra headshot damage only if they land in the head.

Shotgun multiplier is different per shotgun class - double barrels for example always have a multiplier of 1, so you only need 1 pellet to connect, additonal pellets will deal 0 damage. Because of that, doubel barrel shotguns will feel the most similar to vanilla PD2 shotguns.

### New damage classes
|Shotgun type|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Minimal shotgun damage multiplier|Notes|
|--------|--------|--------|--------|--------|--------|
|Double barrel|900 dmg|1|1|1|Can one-shot-bodyshot light and heavy swats. One-shot everyone else in the head.|
|Pump-action|450 dmg|1|1|0.8|Slowest of them all. The only type to have new "Breaching" rounds.|
|Semi-auto no mag|325 dmg|1|2|0.67|The in-betweeners. Become 1-1 shots to kill type with overkill skill.|
|Some semi-auto's and full-auto's with mags|155 dmg|2|3|0.5|Spammm.|

### Shotgun ammo.
Additional stats, like DOT damage and ammo pick up changes, are included in game in ammo descriptions.

* **Breaching round**: new ammo type for __*primary*__ pump-action shotguns - can open any locked space that OVE9000 saw usually can. Also allows to pen shields and body armor.
* **Buckshot**: doubles your damage, removes extra headshot damage, increased pellet count and allows for body AP. Pure spam.
* **HE Slug**: doubles your damage, but removes extra headshot damage. Shoots explosives. Damage radius fall of was reduced, which leads to enemies in the blast radius receiving more damage. Self-damage to players was also reduced.
* **Flechette**: 'Pellet' amount reduced to 5. Still provides body armor pen and increased damage range.
* **AP slugs**: provides same AP and similar range bonuses as in vanilla PD2, but ammo pick up is worse.
* **Dragon's breath**: Reduces amount of pellets to 8. Deals 350 fire damage over a 2 second period to any lit target.
* **Tombstone slug**: Deals roughly 250 damage over 6 seconds, and stun-locks enemies during full poision duration. Damage is no longer affected by weapon's damage drop off, and always deals full damage. Helpfull for low damage class shotguns, and/or vampire-like-regen perks. 

# Light machine guns:

### General LMG updates
* Breakpoints and TTK are kept the same, except for M60 that has highest damage per shot but extremely slow rate of fire
* Accuracy without a bipod is extremely poor, but you get extra accuracy when bipoded compared to vanilla PD2

### New damage drop off introduced
* 80% damage for the first 1.5 meters
* 100% damage for 10 meters after
* Progressive increase in damage for the next 10 meters
* 150% max damage at and after max range

Notes:
* LMG's that don't have bipods don't have any damage drop-off - they always deal their standard damage.

### Summary
LMG's will now be better at long range bipoded support, but slightly worse at point blank ranges. All of the changes above should provide a more defending playstyle, especially if used with new "Slow and Steady" skill.


# Sniper rifles:

### General Sniper updates
* Damage drop-off removed, now deal same damage regardless of distance.
* Can now one-shot headshot any enemy (except Dozers and cpt. Winters).
* Now balanced around BODYSHOTS, and how many bullets it takes to kill enemies in the body.

### New damage classes

|Sniper type|Damage class|BODYshots to kill a light swat|BODYshots to kill a heavy swat|BODYshots to kill a tazer|BODYshots to kill a cloaker|Notes|
|--------|--------|--------|--------|--------|--------|--------|
|Semi-auto |650 dmg|1 |2|2 |3 |The anti-trash (enemy type) rifles. Should be used mostly for headshots.|
|Lever-action |950 dmg|1|1|2|2|Can one tap heavy swats, so you only have to go for headshots on some special enemies.|
|Bolt action |1300 dmg|1|1 |1 |2 |Bolt snipers are slow, but you can one tap bodyshot everyone except for the cloaker, dozer and cpt. Winters. Pretty good, ay?|
|Heavy bolt action |1600 dmg|1|1 |1 |1 |Same as bolt actions, but can one-shot-bodyshot cloakers as well. This class is used for low mag capacity bolt snipers.|
|The 50cal|6500 dmg|1|1|1 |1 |The one and only Dozer-buster. Takes 2 bodyshots to kill a dozer, minigun versions take 4. Double bullet amount for DS difficulty.|

# All akimbo weapons:
### General Akimbo updates
* Stability/accuracy/concealment stats are now copied 1 to 1 from non-akimbo counterparts
* Damage is cut in half compared to non-akimbo counterparts, to compensate for the act of firing two shots at the same time. Otherwise revolvers with 450 damage would waste their ammo in under a minute. Ammo pick up is compensated for this change.
* Ammo capacity on average is lower then other weapons - you are expected to use Akimbo ammo skills while using these weapons

# Pistols:

### General Pistol updates
* Now have no damage drop-off, which makes them more effective at longer distances then SMG's.
* Base ROF for all full-auto pistols was buffed by 25%. Max ROF with "Gun Nut" skill totals to be the same as without Gilza
* Base ROF for most semi-auto pistols was nerfed by 20%. "Gun Nut" skill makes pistol's ROF same as their vanilla ROF without "Gun Nut"
* Pistols with AP properties, have halved ammo pick up.

With all of the changes above, pistols should now be a really comfortable alternative for mid ranges as a secondary, while SMG's are better up close and snipers at longer ranges.

### New attachments
* Broomstick's long barrel is now an AP kit.
* Matever .357 revolver (including akimbo version) can now use AP rounds, similar to an AP kit.
* White Streak and Baby Deagle (including akimbo versions) can now use AP rounds, similar to an AP kit. They come in 2 versions - standard and low velocity.

### New damage classes

|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|88 dmg|3|6|Bernetti auto|
|95 dmg|3|5|Most Full auto's|
|125 dmg|3|4|Mostly for crits and stealth|
|155 dmg|2|3|Average, perfect for loud|
|250 dmg|1|2|Heavies like Deagle|
|450 dmg|1|1|Revolvers|

Note: the Peacemaker .45 revolver has a damage class of 650, which allows it to one-shot bodyshot light swats, and 2 shot tazers without skill investments, to compensate it's reload speed. Otherwise has revolver-like ammo pick up and other stats.

# Sub machine guns:

### New damage drop off introduced

* 120% damage for the first 1.5 meters
* 100% damage for 5.5 meters after
* Progressive decrease in damage for the next 7 meters
* 50% damage at and after max range

These changes make SMG's a more distinct CQB category. While being extremely effective at closer ranges, they will loose their fire power really quickly at longer distances. If you want to have more firepower at range use pistols or snipers.

### New attachments
* Kobus90 and it's akimbo version can now use AP rounds.

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|95 dmg|3|5 |Crits/Stealth. Have high ROF|
|125 dmg|3|4 |Crits/Stealth. Most have high ROF|
|155 dmg|2|3|Average|
|200 dmg|2|3|Average, but with less restrictive modding. 15% less pick up compared to 155 class. Combines well with "Overkill" aced due to new damage breakpoints|
|250 dmg|1|2 |Heavy hitters|

# Specials:
### Bows/crossbows:
* Fixed stats for some bows that displayed incorrect information.
* Added body armor peircing to all arrows.
* Updates a few stats, so bows and crossbows would feel slightly more different from each other.

### OVE9000 Saw:
* Allows for reloads at any time.
* Can now penetrate body armor regardless of skills/attachments.
* All enemies receive 10x damage in-game compared to saw's stat when viewed in the inventory. This was done in such a way due to damage calculations around saw's atachments and unlockable surfaces like metal doors.
* No longer deals extra damage with headshots to all enemies, except for Bulldozers
* Can now also pick up ammo with Saw Massacre (ACED) skill.

### Flamethrowers:
Ammo capacity was reduced, reload speed and damage were increased.

Magazines now completely change how flamethrower performs:
|Mag|Stats|Playstyle|
|--------|--------|--------|
|Default|Only 20% chance for afterburn (75% base game), afterburn will deal 300 damage over 2 seconds.|All around an ok choice|
|Rare|leaves you with only 1 damage, but makes afterburn happen more often. Strongest afterburn damage over longest period of time, with highest amount of damage instances per second|Poke enemies to get them to burn, delaying them and letting them burn out while you are in cover|
|Well done|Doubles your damage but decreases chances for afterburn. Afterburn also deals really low damage|Be more direct with your flames and don't rely on afterburn at all|

Secondary flamethrower has less damage per tick and worse ammo economy.

### Miniguns (+Hailstorm):
* TTK and breakpoints are identical for headshots, but better for bodyshots due to Gilza's health pool updates
* Ammo capacity stats changed from 750(mag)/750(total) to 600(mag)/900(total)
* Reload sped up by 20%
* Ammo pick up reduced, and is now different between the two miniguns we have, since one does more damage per bullet then another.
* Hailstorm now has 210/630 ammo, better accuracy/stability stats and no damage drop-off penalties. Ammo pick up for it is slightly better then in vanilla as well.

### Grenade and rocket launchers (Underbarrels included):
* Piglet launcher received a reload speed buff
* Basilisk 3V received 2 new attachments that limit it's mag capacity for ease of use, while also providing some other minor stat adjustments
* Overall ammo pick up for all launchers is ~20% higher then in vanilla PD2, but now varies more depending on the grenade launcher and it's damage.
* All grenades now have MUCH more detail in their descriptions. They now include ammo pick up adjustments, damage over time, and other additional properties.
* Added a high velocity grenade to almost all GL's

#### Grenade launcher's ammunition with noticable differenes:
* High velocity rounds: New greande type (not avialable on Basilisk 3V and Arbiter grenade launchers). Grenade's travel speed is tripled at a cost of 20% ammo pick up. Other stats are identicall to standard frag round. NOTE: does not work as a client, because host handles projectiles in PD2 and i can't do anything about it. What i can do, is make your ammo pick up identicall to the standard frag round if you are playing as a client, so you wouldnt have to worry about swapping nade types all the time.
* Poison grenades: practically can't kill anything, BUT the damage over time effect is now longer, and during IT'S FULL DURATION enemies are now stun locked in the vomitting animation. This makes poision an extremely effective slow-down/crowd control tool, escpecially if you use it in chokes, or on enemies that are really far away. Also keeping your grinder/anarchist regen is even easier now. Ammo pick up is much lower then in the base game, and max ammo is reduced.
* Incendiary grenades: Ammo pick up is now reduced even more then in the base game.
* Sting grenades (the shotgun-like one) now provides 250% increased ammo pick up instead of ~150%

# Throwables:
### General updates:
* All "projectile" throwables like knives, shurikens etc. can now penetrate enemy body armor
* All throwables can now be picked up from ammo boxes if you have any perk with 6th common perk card maxed out, but pick up rate is different for every throwable
* All stats left untouched except for DOT (damage-over-time) effects
* All important stats are now included in each throwable's description
