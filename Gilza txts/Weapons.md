[Link to the ModWorkshop page.](https://modworkshop.net/mod/39854)

[Link to the latest Patch Notes.](https://github.com/irbizzelus/Gilza/releases)

[Link to the General/Skill Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/General_and_Skills.md)

[Link to the Perks Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md)

<p align="right"> Use this icon to view weapon category chapters: <img width="286" height="71"  src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

Stats are updated for Gilza version: 2.6

# General weapon handling updates:
## Recoil: general changes
All weapons' recoil was overall increased. However, first 5 bullets fired from your weapon will have reduced recoil, so firing in short controlled burst is beneficial, especially at longer ranges. Reduced recoil for first 5 bullets does not apply to Shotguns, Snipers, and single shot fire mode Pistols.

Amount of recoil now depends on your weapon's base stability value - stability value that you see whenever you purchase a weapon, before skills/weapon attachments were applied. Lower base stability means higher overall recoil. Because of these changes, 2 weapons with identical stability values after skills/attachments __will__ feel different, if their base stability is different.

Horizontal recoil will now always favor weapons into a certain pre-defined direction - either left or right. Horizontal recoil will never jump from left to right (and vice versa), but the pull to whichever direction, is overall stronger then in the base game.

Weapon attachments and/or skills now affect weapon recoil 2x less. In vanilla upgrading a weapon from 0 to 100 stability with attachments/skills effectively reduced weapon camera recoil by 6x times. Max possible improvement you can get now is 3x. This makes basic stability stat more important when choosing a weapon, and makes it harder to make it into a "laser" gun.

## Recoil: new compensation
Whenever you hold the trigger your weapon's recoil forces your camera to climb up. If you stop holding the trigger, your camera will go down to where-ever you were aiming at the start of the trigger pull. This mechanic is almost completely gone now, because weapons have more overall recoil, and after a lengthy burst your camera would come back down to the floor. 
Compensation still exists for weapons with extremely low recoil however, for the first couple of shots. So, if you are using your weapon in single-fire or firing in short bursts, it will feel better to use for longer ranges.

**Compensation visuals** (GIF's make take some time to load)
| Vanilla PD2 (compensation enabled) | Gilza (compensation disabled) |
| -------- | -------- |
|  ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Weapon_Images/Recoil_With_Compensation.gif)  | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Weapon_Images/Recoil_Without_Compensation.gif)  |

-----

## Hip-fire adjustments:
Recoil during hip-fire now has a 36 stability point penalty, and accuracy during hip-fire now has a 20 accuracy point penalty. Both changes were done to incentivize aiming down sights at mid ranges.  
Technician's "Fire Control" skill can remove both of these penalties.  
While bipoded both of these penalties are ignored.

## Burst-Fire
A new burst-fire mode was added to some weapons, and is available on them by default. Every weapon with burst-fire functionality will have a description with information on the burst-fire mode, like burst bullet count, or if the burst itself may have a different rate of fire during the burst.  
To select burst-fire mode, use your fire mode keybind. Order of fire mode cycling is as follows: single->burst->full auto.  
Burst-Fire has lower overall DPS than full auto fire mode (roughly 25% less DPS), due to slightly increased delays in-between bursts.  
If a skill has a limit to what fire mode it can work with, burst-fire is counted as a separate fire mode - so if such skill does not specify support for burst-fire mode, it does not work with it.

## Fire mode penalties:  
Different fire modes have different accuracy penalties, but single-fire has no penalties at all. These penalties are applied only when your weapon is switched to a specific fire mode - switching your weapon's fire mode during the heist, will negate this penalty, for as long as your weapon's fire mode is set to single-fire. This was done to make fire mode toggling mid match an actually useful mechanic, since you are now incentivized to switch to single-fire for long range (most likely sniper) takedowns. Fire mode penalties are not applied while bipoded.  
* Full-auto fire mode has a -16 accuracy point penalty.
* Burst-fire mode has a -8 point accuracy penalty.
* Volley fire mode has a +20 accuracy bonus, since this fire mode usually adjusts DPS to be lower, and this fire mode is only available on low accuracy weapons.

## Single-fire input buffering
Toggleable option in settings. If you spam your "Fire Weapon" keybind, your inputs will be buffered, and your weapon may automatically fire even if you clicked the button again too soon. This feature is supported for weapons with 150 or more rounds per minute rate of fire.  
In short - while shooting single-fire weapons you will be able to fire them as quickly as possible, without getting the feeling that your mouse inputs do not register.  
This system is also enabled for burst-fire mode.

# General weapon tweaks:
* Weapons' accuracy and stability are no longer affected if you: crouch, jump, walk or sprint.
* DMR kits and some long barrel attachments were converted into "AP kits" that can penetrate shields, body armor and walls, at the cost of ammo pick up.
* All weapons that by default come with armor piercing properties, have reduced ammo pick up compared to their non AP counterparts in the same damage class.
* All weapons that come equipped with underbarrel launchers have 30% less ammo pick up.
* More weapon attachments have descriptions now, and with more details like ammo pick up changes, damage values for damage over time effects, etc.
* A LOT of weapon attachments were rebalanced.
* Mag increasing attachments will now slow down your reload speed.
* Some attachments like Stocks and Foregrips can now speed up your reload speed.
* All scopes no longer have accuracy/stability bonuses - you can choose whichever optic you like the look of more, as long as it fits your concealment requirement.
* Scopes on Sniper rifles will now have "logical" concealment - since snipers are starting with a huge 4x zoom optic, switching to a red dot should give you more concealment, don't you think?
* Every shotgun will now deal a minimal % of it's damage with every shot - the % depends on the shotgun type. To deal full damage all pellets from the shot need to connect to the target. For a more detailed breakdown of new shotgun damage mechanics go to the shotgun tab bellow.

## Improved flashlights
Flashlight texture is improved by Gilza (if you have other mods adjusting this texture, they will most likely conflict, with gilza taking priority).    
Flashlight range increased from 10 to 40 meters, but the flashlight brightness now goes down over distance.    
Initial flashlight glow that comes out of the flashlight attachment is greatly reduced to reduce self-blinding.
Visuals:
| Vanilla | Gilza |
| -------- | -------- |
|  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Weapon_Images/Vanilla%20Flashlight.jpg)  | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Weapon_Images/Gilza%20Flashlight.jpg)  |

# Melee weapons overhaul:
Melee weapon damage that you see in your inventory now represents how much % of enemy's HP your weapon will deal with a swing. This includes charged damage as well. So if you have a melee weapon with 25(50) damage, it will kill an enemy in 4(2) hits.  
Melee weapons now deal 25%-100% minimum damage per hit.

Captain Winters, Bulldozers and bosses take less melee damage.

Bulldozers require this much charge % to be killed:

| Bulldozer Type | Required charge on DW difficulty and bellow | Required charge on DS difficulty |
| -------- | -------- | -------- |
| Standard  | 1200% | 1750% |
| Minigun  | 1750% | 3500% |
|  Headless | 2000% | 4000% |

Additional changes:
1) You can set up a keybind in Gilza's mod options for a "melee only" toggle mode. While in this mode the game automatically charges melee weapons for you, and makes primary attack button the trigger for melee swings. You can cancel this mode by using the same keybind or melee attack button. Additional options, like position of this mode's indicator, it's size and location are also accessible in Gilza's mod options.
2) Almost all melee weapon's timings (and sometimes animations) were tweaked to make them feel smoother, without weird delays after you swing them and can't fire your primary weapon.
3) Melee knockdown now depends on melee weapon's range. More range your melee has, less knockdown it has. It may not always make sense when you look at some melees, but the range statistic is something that you may be used to by playing with certain weapons before, so instead of altering range, knockdown stat was changed instead.
4) Grey and Zeal swats can now be knocked down as easily by melee weapons as their blue SWAT counterparts.
5) Almost all melee charge sounds were removed, due to new charge time mismatching their sounds. To add clarity, new option for melee UI was added to Gilza's options menu and it's enabled by default. This option highlights your total charge progress, and shows you your current melee damage, including active skills. Can be disabled.
6) "Kazaguruma" and "Lumber Lite L2 chainsaw" melee weapons can now deal chainsaw-like melee damage while holding the weapon in front of you. This feature is directly ported from [IREnFIST](https://modworkshop.net/mod/28585), with a few adjustments.
7) Weapon Butt melee now has 31 concealment by default making it the best concealment option. Considering it's mediocre at best damage, this should be a nice option to consider for low detection builds.
8) Melee weapons are now sorted in your inventory by damage from lowest to highest, while the first page is always dedicated to special melee weapon types like poison and electricity.

# Assault rifles:
### General AR updates
* All DMR kits and some long barrel attachments were reworked into "Armor piercing kits" that can penetrate shields, body armor and walls, but ammo pick up while using them is reduced. Affected weapons: Car-4, AK74, AK 7.62, Golden AK 7.62, AMR16, Clarion, Gewehr3, KS12 (upper receiver).
* About a half of all AR's had their rate of fire updated.

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|125 dmg|3|4|Best for crits and "Berserk" skills.|
|155 dmg|2|3|Average rifles, should feel the most similar to vanilla PD2 AR's. This class is based on 150 damage breakpoint, which is important against heavy swats, but it starts with extra 5 damage, so in case you have attachments that reduce your damage by 1, the breakpoint can still be there. With other damage classes losing 1 damage will affect their breakpoints against a certain enemy type. This is a "Noob Friendly" customization option of sorts.|
|200 dmg|2|3|Basically 155 class, but with better anti-dozer potential and less restrictive customization, at a cost of ammo pick up. Benefits heavily if used along with "Overkill", "Body Expertise", "Berserker" or crit skills, due to newly gained breakpoints from them.|
|250 dmg|1|2|Most stable and comfortable time to kill, but poor ammo economy if not accurate.|
|450 dmg|1|1|Usually highest recoil and by far the worst ammo economy. Best combined with ammo related skills. Usage in single-fire mode recommended.|

### New AR attachments
Damage class adjusting ammunition was added to some weapons - this ammunition attachment allows you to change damage class of your weapon. In addition to damage, ammo pick up is adjusted to match new damage class. Other stats may be adjusted as well. Weapons that have received such ammunition: 
* 7.62 Little Friend now has a 5.56 conversion kit
* Byk-1 now has a 5.45 conversion kit
* AMCAR now has RRLP rounds
* Falcon rifle now has 7.62x51mm SP rounds
* Car-4 now has HP rounds
* AK 7.62 and Golden AK 7.62 now have HP rounds
* Cavity 9mm now has 9x19mm QuakeMaker rounds
* KS12 Urban now has 12.7x55mm PS12A rounds

Other attachment updates/additions:
* Gewehr3's CQB and Sniper kits have new updated values: CQB kit now has reduced damage class (200) with increases to other stats, while the Sniper kit acts like an AP kit
* 7.62 Little Friend and Byk-1 now have a High velocity round for their underbarrel launchers - this round increases grenade travel speed by 3x with a 20% ammo pick up cost. Note: only works if you are the lobby host, otherwise reverts itself to standard round stats.
* M308 and Galant rifles now have AP rounds - similar to AP(DMR) kits, but they are categorized as a separate ammunition attachment.

# Shotguns:

### General shotgun updates
* All shotguns now have new damage fall-off. In short: more damage per shot = better damage distance. For more details use "More weapon stats" mod in game.
* All shotguns now always fire 10 pellets per shot.
* Rate of fire was updated for almost every shotgun, and it is now balanced around other shotguns within same damage class.

### New shotgun damage
Shotgun damage in vanilla Payday 2 is always the same if at least one of your shotgun pellets hits an enemy, and its always equal to the damage stat you see in your inventory.  
In most video games, shotgun's damage is spread across every fired pellet. So if you were to hit an enemy, you would deal "shotgun's damage/amount of pellets" per every pellet you hit, so not every hit would deal full damage.  
Gilza uses a new "hybrid" system which adds a "minimal shotgun damage multiplier" property to all shotguns. It ensures that your shotgun will always deal a certain % of it's maximum damage with every shot, but in order to deal maximum damage, you need for all pellets to connect to your target.

For ease of explanation, here is an example: Let's take a shotgun with 10 pellets and max total damage of 200. In vanilla PD2 you would deal 200 damage if at least one of your pellets hits an enemy. In most other games every pellet would deal 20 damage individually.  
With Gilza, this same shotgun will also have a "minimal shotgun damage multiplier" property. This property usually depends on shotguns's damage class, but for the sake of this example let's say for this shotgun it's equal to 0.5.  
Anytime you fire this shotgun, first pellet that hits an enemy, would ALWAYS deal 100 damage. After it, other pellets from the same shot will deal "100/9" or ~11.11 damage.  

This new system ensures that your shotgun can always kill enemies in a set amount of shots, and it also allows for multi-hits to be almost as effective as they are in vanilla Payday 2, since even 1 connected pellet from a shot, will deal at least some % of your shotgun's maximum damage. However at the same time, it makes shotguns slightly less consistent, since you now need for all pellets to connect to deal full damage, and full damage is usually important for kill breakpoints. Yours, and your shotgun's accuracy stat are now even more important than before.

This new damage system still scales with damage drop off.  
As for headshots: if any of your pellets from the same shot connects to the head, your minimal damage will also receive a headshot multiplier. Additional pellets deal extra headshot damage only if they land in the head.  
Shotgun multiplier is different per shotgun class - double barrels for example always have a multiplier of 1, so you only need 1 pellet to connect, additional pellets will deal 0 damage. Because of that, double barrel shotguns will feel the most similar to vanilla PD2 shotguns.

### New damage classes
|Shotgun type|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Minimal shotgun damage multiplier|Notes|
|--------|--------|--------|--------|--------|--------|
|Double barrel|900 dmg|1|1|1|Can one-shot-bodyshot light and heavy swats. One-shot everyone else (except Bulldozers) in the head.|
|Pump-action|450 dmg|1|1|0.8|Slowest, but most reliable of them all. The only type to have new "Breaching" rounds.|
|Semi-auto no mag|325 dmg|1|2|0.67|The in-betweeners. Become 1-1 shots to kill type with "overkill" skill if all pellets connect.|
|Some semi-auto's and full-auto's with mags|160 dmg|2|3|0.5|Spammm. Getting to 161 damage with attachments allows for great new breakpoints with Overkill skill active, and getting to 163 damage with both Overkill and Underdog skills active will improve some breakpoints further.|

### Shotgun ammo
Additional stats, like damage-over-time damage/duration, and ammo pick up changes, are included in game ammo descriptions.

* **Breaching round**: new ammo type for __*primary*__ pump-action shotguns - can open any locked space that OVE9000 saw usually can. Also allows to pen shields and body armor. Can not be used with silencers. Great substitute for the OVER9000 saw if you are running shotgun skills.
* **Buckshot**: doubles your damage, removes extra headshot damage, increases pellet count and allows for body and multi-enemy AP. Built for multi-hit spam.
* **HE Slug**: doubles your damage, but removes extra headshot damage. Shoots explosives. Damage radius fall of was reduced, which leads to enemies in the blast radius receiving more damage. Note: Gilza reduces damage dealt to other players while using any kind of explosive bullets, so using double barrel shotguns with HE ammo should be safe around your teammates.
* **Flechette**: "Pellet" amount reduced to 5. Still provides body armor pen and increased damage range, at the cost of ammo pick up and worse multi-hit potential.
* **AP slugs**: provides same AP and similar range bonuses as in vanilla PD2, but ammo pick up is worse.
* **Dragon's breath**: Reduces amount of pellets to 8. Deals 350 fire damage over a 2.5 second period to any lit target. Activation range and ammo pick up reduced, compared to vanilla.
* **Tombstone slug**: Deals 250 damage over 6 seconds, and stun-locks enemies during full poison duration. Damage is no longer affected by weapon's damage drop off, and always deals full damage. Helpful for low damage class shotguns, and/or vampire-like-regen perks. 

# Light machine guns:

### General LMG updates
* Breakpoints and time to kill were kept the same, except for M60 that now has highest damage per shot but extremely slow rate of fire, allowing for new breakpoints with certain skill combos.
* Accuracy and recoil are extremely poor, but bipoding can help significantly since you get extra accuracy when bipoded compared to vanilla PD2.
* LMG's that can use bipods have generaly more total ammo to allow for better defesnive gameplay.

### New damage drop off introduced
* 80% damage for the first 1.5 meters
* 100% damage for 10 meters after
* Progressive increase in damage for the next 10 meters
* 150% max damage at and after max range
 
Note: LMG's that don't have bipods don't have damage drop-off - they always deal their damage at any range.

### Summary
LMG's will now be better at long range bipoded support, but slightly worse at point blank ranges. All of the changes above should provide a more defensive playstyle, especially if used with new "Slow and Steady" skill.


# Sniper rifles:

### General Sniper updates
* Damage drop-off removed, they now deal same damage regardless of distance.
* Can now one-shot headshot any enemy (except Dozers and cpt. Winters).
* Now balanced around BODYSHOTS, and how many bullets it takes to kill enemies in the body. This makes most snipers a great option for people with lazy aim. (for those who prefer to pop heads, use semi-auto snipers)
* All sniper rifles that come by default with a scope had their conceamnet stat decreased by 1, but all scope attachments will now increase your total concealment instead of reducing it, allowing you to use a holo sight instead of the default scope without losing concealment (because this makes no sense in vanilla).

### New damage classes

|Sniper type|Damage class|BODYshots to kill a light swat|BODYshots to kill a heavy swat|BODYshots to kill a tazer|BODYshots to kill a cloaker|Notes|
|--------|--------|--------|--------|--------|--------|--------|
|Semi-auto |650 dmg|1 |2|2 |3 |The anti-trash (enemy type) rifles. Should be used mostly for headshots.|
|Lever-action |950 dmg|1|1|2|2|Can one tap heavy swats, so you only have to go for headshots on some special enemies.|
|Bolt action |1300 dmg|1|1 |1 |2 |Bolt snipers are slow, but you can one tap bodyshot everyone except for the cloaker, dozer and cpt. Winters. Pretty good, ay?|
|Heavy bolt action |1600 dmg|1|1 |1 |1 |Same as bolt actions, but can one-shot-bodyshot cloakers as well. This class is used for low mag capacity bolt snipers. This class is combined best with "Graze" skill, due to it's new damage multiplier.|
|The 50cal|6500 dmg|1|1|1 |1 |The one and only Dozer-buster. Takes 2 bodyshots to kill a dozer, minigun versions take 4. Double bullet amount for DS difficulty.|

# All akimbo weapons:
### General Akimbo updates
* Stability/accuracy/concealment stats are now copied 1 to 1 from non-akimbo counterparts
* Damage is cut in half compared to non-akimbo counterparts, to compensate for the act of firing two shots at the same time. Otherwise revolvers with 450 damage would waste their ammo in under a minute. Ammo pick up is compensated for this change.
* Whenever you fire akimbo weapons, shots from both guns will land in the same location, and the delay between those 2 shots is removed. This was done to improve overall reliability with akimbo weapons if they are used in semi automatic mode and/or used at longer ranges.
* All akimbos have 1.3x faster rate of fire and 1.5x more total ammo relative to their non-akimbo counterparts.

# Pistols:

### General Pistol updates
* Now have no damage drop-off, which makes them more effective at longer distances than SMG's.
* Rate of fire for all pistols was updated to overall lower values, to compensate more reliable breakpoints, and new pistol skills.

Pistols are now a comfortable alternative for mid ranges, while SMG's are better up close and snipers are better at longer ranges.

### New attachments
* Broomstick's long barrel is now an AP kit.
* Matever .357 revolver (including akimbo version) can now use AP rounds, similar to an AP kit.
* White Streak and Baby Deagle (including akimbo versions) can now use AP rounds, similar to an AP kit. They come in 2 versions - standard and low velocity.

### New damage classes

|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|88 dmg|3|6|Used by Bernetti auto. Spammy.|
|95 dmg|3|5|Most Full auto pistols. Spammy.|
|125 dmg|3|4|Best for crits and "Berserker" skills. |
|155 dmg|2|3|Average, perfect for loud. This class is based on 150 damage breakpoint, which is important against heavy swats, but it starts with extra 5 damage, so in case you have attachments that reduced your damage by 1, the breakpoint can still be there. With other damage classes losing 1 damage will affect their breakpoints against a certain enemy type. This is a "Noob Friendly" customization option of sorts.|
|250 dmg|1|2|Heavy and reliable pistols, best all around if user is accurate.|
|450 dmg|1|1|Revolvers. Ammo related skills recommended.|

The Peacemaker .45 revolver has a damage class of 650, which allows it to one-shot bodyshot light swats, and 2 shot bodyshot tazers without skill investments, it can also hit enemies through each other and can pierce enemy body armor by default. All of this was done to compensate it's god-awful reload speed. It has 10% less ammo pick up than other revolvers, but all other stats are revolver-like.

# Sub machine guns:

### New damage drop off introduced

* 120% damage for the first 1.5 meters
* 100% damage for 6.5 meters after
* Progressive decrease in damage for the next 8 meters
* 50% damage at and after max range

These changes make SMG's a more distinct CQB category. While being extremely effective, both in DPS and ammo economy, at point blank ranges, they will loose their fire power really quickly at longer distances. If you want to have more firepower at range use pistols or snipers.

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|95 dmg|3|5 |Best for Crits. Tend to have high ROF|
|125 dmg|3|4 |Best for Crits and "Berserker" skills.|
|155 dmg|2|3|Average. This class is based on 150 damage breakpoint, which is important against heavy swats, but it starts with extra 5 damage, so in case you have attachments that reduced your damage by 1, the breakpoint can still be there. With other damage classes losing 1 damage will affect their breakpoints against a certain enemy type. This is a "Noob Friendly" customization option of sorts.|
|200 dmg|2|3|Average, but with less restrictive modding. Benefits heavily if used along with "Overkill", "Body Expertise", "Berserker" or crit skills, due to newly gained breakpoints from them.|
|250 dmg|1|2 |Heavy hitters, most reliable option if user is accurate.|

### New attachments
* Kobus90 and it's akimbo version can now use AP rounds.

# Specials:
### Bows/crossbows:
* Added body armor piercing to all bows and crossbows by default.
* Updated damage/accuracy/stability stats, so bows and crossbows would feel slightly more different one from another.
* Both bows and crossbows can now gain benefit from "Body Expertise" skill, allowing you to rely only on bodyshots if you use it.
* Fixed stats for some bows that displayed incorrect information.  

### OVE9000 Saw:
* Allows for reloads at any time.
* Can now always penetrate enemy body armor regardless of skills/attachments.
* No longer deals extra damage with headshots, except for Bulldozers.
* Can now pick up ammo with Saw Massacre (ACED) skill.

### Flamethrowers:
Ammo capacity was reduced, reload speed and damage were increased.  
Secondary flamethrower has identical stats to primary, but with lower ammo pick up.    
Flamethrowers can normaly deal bonus headshot damage, and thanks to Gilza, they can now benefit from the Body Exprertise skill.

Magazines now completely change how flamethrower performs:
|Mag|Stats|Playstyle|
|--------|--------|--------|
|Default|Only 20% chance for afterburn (75% base game), afterburn will deal 300 damage over 2 seconds.|All around an ok choice|
|Rare|Leaves you with only 1 damage, but makes afterburn happen more often. Strongest afterburn damage over longest period of time, with highest amount of damage instances per second|Poke enemies to get them to burn, delaying them and letting them burn out while you are in cover. Best option for regen-on-hit perks, and for a more CC focused playstyle.|
|Well done|Doubles your damage but decreases chances for afterburn. Afterburn also deals really low damage|Be more direct with your flames and don't rely on afterburn at all|

### Miniguns (+Hailstorm):
* Time to kill and breakpoints are identical for headshots, but better for bodyshots due to Gilza's health pool updates.
* Ammo capacity stats changed from 750(mag)/750(total) to 600(mag)/900(total).
* Reload sped up by 20%.
* Ammo pick up altered, and is now different between the two miniguns we have, since one does more damage per bullet then another.
* Hailstorm now has 210/525 ammo, better accuracy/stability stats and no damage drop-off penalties, but it's ability to pierce multiple enemies in volley mode was removed.

Body expertise skill works wonders with these weapons.

### Grenade and rocket launchers (Underbarrels included):
* Overall ammo pick up for all launchers is ~15% lower then in vanilla PD2, but now varies more depending on the grenade launcher and it's damage.
* All grenades now have MUCH more detail in their descriptions. They now include ammo pick up adjustments, damage over time, and other additional properties.
* Piglet launcher received a reload speed buff.
* Basilisk 3V received 2 new attachments that limit it's mag capacity for ease of use, while also providing some other minor stat adjustments.
* Added a high velocity grenade to almost all GL's.

#### Grenade launcher's ammunition with noticeable differences:
* High velocity rounds: New grenade type (not available on Basilisk 3V and Arbiter grenade launchers). Grenade's travel speed is tripled at a cost of 20% ammo pick up. Other stats are identical to standard frag round. NOTE: does not work as a client, because host handles projectiles in PD2 and i can't do anything about it. What i can do, is make your ammo pick up identical to the standard frag round if you are playing as a client, so you wouldn't have to worry about swapping nade types all the time.
* Poison grenades: practically can't kill anything, BUT the damage over time effect is now longer, and during IT'S FULL DURATION enemies are now stun locked in the vomiting animation. This makes poison an extremely effective slow-down/crowd control tool, especially if you use it in chokes, or on enemies that are really far away. Also keeping your grinder/anarchist regen is even easier now. Ammo pick up is extremely low, and max ammo is reduced heavily to compensate new CC power.
* Incendiary grenades: Ammo pick up is reduced by a bit more than in the base game.
* Sting grenades (the shotgun-like one) now provide a higher ammo pick up rate, provide multi-enemy and body AP. They also increase total ammo capacity and reload speed for non-underbarrel launchers. 

# Throwables:
### General updates:
* All "projectile" throwables like knives, shurikens etc. can now penetrate enemy body armor by default.
* All throwables can now be picked up from ammo boxes if you have any perk with 6th common perk card maxed out, but pick up rate is different for every throwable. Pick up rates can be found in throwable descriptions.
* Most stats were left untouched, except for DOT (damage-over-time) effects, and a few throwable projectile weapons to make them more varied (or just usable - looking at you "Ace of Spades" with 40 damage in vanilla).
* All important stats are now included in each throwable's description.

# Custom Weapons Support
Gilza will automatically search for custom weapons and convert their damage stats to work with Gilza's health changes. Beware: some custom weapons may have attachments that change damage/ammo pick up/total max ammo, or other stats in such a way that it will not match Gilza's values well, making them either too good, or bad. I can't do anything about it, other then __manually__ adding support for __every gun individually__. This is planned for future patches.

Custom "special" category weapons are not supported.

Currently supported attachment mods:  
All of FrenchyAU's tacticool attachments packs (250+ attachments). Check Gilza's dependencies & Instructions tab on the [MWS page](https://modworkshop.net/mod/39854) for links.

### Currently supported custom weapons:  
_Assault Rifles_:
* [DT MDRX 7.62x51mm](https://modworkshop.net/mod/35608)
* [HK G3A3 HK79](https://modworkshop.net/mod/23676)
* [M4A1 Grenadier](https://modworkshop.net/mod/37996) and it's [addon](https://modworkshop.net/mod/40785)
* [SKS](https://modworkshop.net/mod/17243)
* [Defiance Blast Rifle](https://modworkshop.net/mod/32588)
* [HK416](https://modworkshop.net/mod/19357)
* [XR-2](https://modworkshop.net/mod/35603)
* [Stoner 63A LMG & AR](https://modworkshop.net/mod/40135) (AR+LMG)
* [SIG Sauer MCX SPEAR/XM7 NGSW-R](https://modworkshop.net/mod/36582)

_SMGs_:
* [Payday 3 Tribune 32](https://modworkshop.net/mod/51546)
* [Typhoon](https://modworkshop.net/mod/36055)
Snipers:
* [L115](https://modworkshop.net/mod/17368)
* [MW2022 Marlin Model 336](https://modworkshop.net/mod/42220)

_Pistols_:
* [MW2022 S&W Model 500](https://modworkshop.net/mod/42438)

_LMG's_:
* [Stoner 63A LMG & AR](https://modworkshop.net/mod/40135) (AR+LMG)
* [Blyspruta MX63 Light Machine Gun](https://modworkshop.net/mod/48405)

_Specials_:
* [HX25 Handheld Grenade Launcher](https://modworkshop.net/mod/21556)
* [Railgun Rorsch MK-1](https://modworkshop.net/mod/22281)


