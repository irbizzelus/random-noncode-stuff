FILE NOT YET FINISHED

<p align="right"> Use this icon up-top to view weapon category chapters: <img width="40" height="40" src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

# Assault rifles:
### General AR updates
* All DMR kits and some long barrels were reworked into "Armor piercing kits" that can penetrate shields, body armor and walls, but ammo pick up while using them is halved. Affected weapons: Car-4, AK74, AMR16, Gewehr3, KS12 (upper receiver).

### New attachments
* M308 and Galant rifles now have AP rounds - same as AP(DMR) kits, but are categorized as ammuntion
* 7.62 Little Friend now has a 5.56 conversion kit - it reduces damage but increases ammo pick up
* Byk-1 now has a 5.45 conversion kit - it reduces damage but increases ammo pick up
* Car-4, AK 7.62 and Golgen AK 7.62 now have HP rounds - they can be used to update weapon's damage class (which includes ammo pick up)
* 7.62 Little Friend and Byk-1 now have a High velocity round for their underbarrel launchers - increase grenade travel speed by 3x with a 20% ammo pick up cost. Note: only works if you are the lobby host, otherwise reverts itself to standard round stats.
* Gewehr3's CQB and Sniper kits have new updated values, CQB kit now has reduced damage class (200) but increases other stats, while the Sniper kit acts like an AP kit

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|120 dmg|3|4|Best for crits|
|155 dmg|2|3|Average rifles, should feel the most similar to vanilla PD2 AR's|
|200 dmg|2|3|Basically 155 class, but with better anti-dozer potential and less restrictive customization, at a cost of ~10% ammo pick up. Benefits from "Overkill" aced the best, due to damage class upgrade|
|250 dmg|1|2|Most stable and comfortable TTK, but poor ammo economy if not accurate.|
|450 dmg|1|1|Usually highest recoil and worst ammo economy. Best combined with body expertise/ammo related skills.|

# Shotguns:

### General shotgun updates

* All shotguns now have new damage fall-off. For more details use "More weapon stats" mod in game.
* All shotguns now fire 12 pellets per shot.

#### New shotgun damage
Shotgun's damage in the base game spreads it's damage across every pellet you fire. Most shotguns have 8-12 pellets. So if you were to hit an enemy, you would deal "shotgun's damage/amount of pellets" per every pellet you hit, so not every hit would deal full damage.

Now, every shotgun has a minimal damage multiplier, that ensures your shotgun will always deal minimal multiplier damage. So, as example: We have a shotgun with 10 pellets and max total damage of 200. In vanilla PD2 every pellet deals 20 damage, simple enough.

With Gilza, this same shotgun also has a minimal shotgun damage multiplier property, and let's say for this shotgun it's 0.5.
Anytime you fire this shotgun, first pellet that hits an enemy, would ALWAYS deal 100 damage. After it, other pellets from the same shot will deal "100/9" or ~11.11 damage.
This ensures that your shotgun can always kill enemy in (2 in this case) set amount of shots. This damage still scales with damage drop off however, so you can't 2-tap a sniper on the opposite side of the map, they will just receive "minimal damage/2" for the first pellet.

As for headshots: if any of your pellets from the same shot connects to the head, your minimal damage will also receive a headshot multiplier, other pellets deal additional damage only if they land in the head.

Shotgun multiplier is different per shotgun class - double barrels for example always have a multiplier of 1, so you only need 1 pellet to connect, additonal pellets will deal 0 damage.

### New damage classes
|Shotgun type|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Minimal shotgun damage multiplier|Notes|
|--------|--------|--------|--------|--------|--------|
|Double barrel|1000 dmg|1|1|1|Can one-shot-bodyshot normal and heavy swats. One-shot everyone else in the head.|
|Pump-action|450 dmg|1|1|0.67|Slowest of them all. The only type to have new "Breaching" rounds.|
|Semi-auto no mag|325 dmg|1|2|0.5|The in-betweeners. Become 1-1 shots to kill type with overkill skill.|
|Some semi-auto's and full-auto's with mags|100 dmg|3|5|0.35|Spammm. Overkill skill is practically mandatory.|

### Shotgun ammo.
Additional stats, like DOT damage and ammo pick up changes, are included in game in ammo descriptions.

* **Breaching round**: new ammo type for __primary__ pump-action shotguns - can open any locked space that OVE9000 saw usually can. Also allows to pen shields and body armor.
* **Buckshot**: doubles your damage, but removes extra headshot damage.
* **HE Slug**: doubles your damage, but removes extra headshot damage. Shoots explosives. Damage radius fall of was reduced, which leads to enemies in the blast radius receiving more damage. Self-damage to players was also reduced.
* **Flechette**: 'Pellet' amount reduced to 5. Still provides body armor pen and increased damage range.
* **AP slugs**: provides a bit of damage range along with body armor, shields and wall armor piercing.
* **Dragon's breath**: Reduces amount of pellets to 9. No extra headshot damage. Deals 350 fire damage over a 2 second period to any lit target.
* **Tombstone slug**: Deals roughly 120 damage over 3 seconds.

# Light machine guns:

### General LMG updates
* Breakpoints and TTK are kept the same
* Accuracy without a bipod is extremely poor, but you get extra 50% accuracy when bipoded compared to vanilla PD2

### New damage drop off introduced
* 50% damage for the first 2 meters
* 100% damage for 12 meters after
* Progressive increase in damage at 14-36 meters
* 165% max damage after 36 meters

Note: Akron Hc and Campbell LMG's don't have increased damage at range, and Buzzsaw LMG has 2x damage after 36 meters, instead of 1.65x.

### Summary
LMG's will now be better at long range bipoded support, but slightly worse at point blank ranges. All of the changes above should provide a more defending playstyle, especially if used with new "Slow and Steady" skill.


# Sniper rifles:

### General Sniper updates
* Damage drop-off removed, now deal same damage regardless of distance.
* Can now one-shot headshot any enemy (except Dozers and cpt. Winters).
* Now balanced around BODYSHOTS, and how many bullets it takes to kill enemies in the body.

### New damage classes

|Sniper type|Damage profile|BODYshots to kill a light swat|BODYshots to kill a heavy swat|BODYshots to kill a tazer|BODYshots to kill a cloaker|Notes|
|--------|--------|--------|--------|--------|--------|--------|
|Semi-auto |650 dmg|1 |2|2 |3 |The anti-trash (enemy type). Should be used mostly for headshots.|
|Lever-action |950 dmg|1|1|2|2|Can one tap heavy swats, so you only have to go for headshots on some special enemies.|
|Bolt action |1300 dmg|1|1 |1 |2 |Bolt snipers are slow, but you can one tap bodyshot everyone except for the cloaker, dozer and cpt. Winters. Pretty good, ay?|
|Heavy bolt action |1600 dmg|1|1 |1 |1 |Same as bold actions, but can one-shot-bodyshot cloakers as well. This class is used for low mag capacity bolt snipers.|
|The 50cal|6500 dmg|1|1|1 |1 |The one and only Dozer-buster. Takes 2 bodyshots to kill a dozer, minigun versions take 4. Double bullet amount for DS difficulty.|

# All akimbo weapons:
### General Akimbo updates
* Stability/accuracy/concealment stats are now copies 1 to 1 from non-akimbo counterparts
* Damage is cut in half compared to non-akimbo counterparts, to compensate for the act of firing two shots at the same time. Otherwise revolvers with 450 damage would waste their ammo in under a minute. Ammo pick up is compensated for this change.
* Ammo capacity on average is lower then other weapons - you are expected to use Akimbo ammo skills while using these weapons

# Pistols:

### General Pistol updates
* Now have no damage drop-off, which makes them more effective at longer distances then SMG's.
* Base ROF for all full-auto pistols was buffed by 25%. Max ROF with "Gun Nut" skill totals to be the same as without Gilza
* Base ROF for all semi-auto pistols was nerfed by 20%. "Gun Nut" skill makes pistol's ROF same as their vanilla ROF
* Pistols with AP properties, have halved ammo pick up.

With all of the changes above, pistols should now be a really comfortable alternative for mid range as a secondary, while SMG's are better up close and snipers at longer ranges.

### New weapon mods
* Broomstick's long barrel is now an AP kit.
* Matever .357 revolver can now use AP rounds, similar to an AP kit.

### New damage classes

|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|88 dmg|3|6|Bernetti auto|
|95 dmg|3|5|Most Full auto's|
|120 dmg|3|4|Mostly for crits and stealth|
|155 dmg|2|3|Average, perfect for loud|
|250 dmg|1|2|Heavies like Deagle|
|450 dmg|1|1|Revolvers|

Note: the Peacemaker .45 revolver has a damage profile of 650, which allows it to one-shot bodyshot light swats, and 2 shot tazers without skill investments, to compensate it's reload speed. Otherwise has revolver-like ammo pick up and other stats.

# Sub machine guns:

### New damage drop off introduced

* 125% damage for the first 2.5 meters
* 100% damage for 5.5 meters after
* Progressive decrease in damage at 9-40 meters
* 50% max damage after 40 meters

These changes make SMG's a more distinct CQB category. While being extremely effective at closer ranges, they will loose their fire power really quickly at longer distances. If you want to have more firepower at range use pistols or snipers.

### New weapon mods
* Kobus90 can use AP rounds.

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|95 dmg|3|5 |Crits/Stealth. Have high ROF|
|120 dmg|3|4 |Crits/Stealth. Most have high ROF|
|155 dmg|2|3|Average|
|200 dmg|2|3|Average, but with less restrictive modding. 10% less pick up compared to 155 class|
|250 dmg|1|2 |Heavy hitters|

# Specials:
### Bows/crossbows:
* Fixed stats for some bows that displayed incorrect information.
* Added body armor armor peircing to all arrows.
* Updates a few stats, so bows and crossbows would feel slightly more different from each other.

### OVE9000 Saw:
* Allows for reloads at any time.
* All enemies receive 9x damage in-game compared to saw's stat when viewed in the inventory. This was done in such a way due to damage calculations around saw's atachments and unlockable surfaces like metal doors.
* Can now also pick up ammo with Saw Massacre (ACED) skill.

### Flamethrowers:
Ammo capacity was reduced, reload speed and damage were increased.

Magazines now completely change how flamethrower performs:
|Mag|Stats|Playstyle|
|--------|--------|--------|
|Rare|leaves you with only 1 damage, but makes afterburn happen more often. Strongest afterburn damage over longest period of time|Poke enemies to get them to burn, delaying them and letting them burn out while you are in cover|
|Well done|Doubles your damage but decreases chances for afterburn. Afterburn also deals really low damage|Be more direct with your flames and don't rely on afterburn at all|
|Default|Only 20% chance for afterburn (75% base game), afterburn will deal 300 damage over 2 seconds.|All around an ok choice|

Secondary flamethrower has less damage per tick and worse ammo economy.

### Miniguns (+Hailstorm):
* TTK and breakpoints are identical for headshots, but better for bodyshots due to Gilza's health pool updates
* Ammo capacity stats changed from 750(mag)/750(total) to 600(mag)/900(total)
* Reload sped up by 20%
* Ammo pick up reduced, and is now different between the two miniguns we have, since one does more damage per bullet then another.
* Hailstorm now has 210/630 ammo and better accuracy/stability stats. Ammo pick up for it is slightly better then in vanilla as well.

### Grenade and rocket launchers (Underbarrels included):
* Piglet launcher received a reload speed buff.
* Overall ammo pick up for all launchers is ~20% higher then in vanilla PD2, but now varies more depending on the grenade launcher and it's damage.
* All grenades now have MUCH more detail in their descriptions. They now include ammo pick up adjustments, damage over time, and other additional properties.
* Added a high velocity grenade to almost all GL's

#### Grenade launcher's ammunition:
* High velocity rounds: New greande type (not avialable on Basilisk 3V and Arbiter grenade launchers). Grenade's travel speed is tripled at a cost of 20% ammo pick up. Other stats are identicall to standard frag round. NOTE: does not work as a client, because host handles projectiles in PD2 and i can't do anything about it. What i can do, is make your ammo pick up identicall to the standard frag round if you are playing as a client, so you wouldnt have to worry about swapping nade types all the time.
* Poison grenades: practically can't kill anything, BUT the damage over time effect is now 30 seconds, and during the FULL 30 SECOND DURATION enemies are now stun locked in the vomitting animation. This makes poision an extremely effective slow-down tool, escpecially if you use it in chokes, or on enemies that are really far away. Also keeping your grinder/anarchist regen is even easier now.
* Incendiary grenades: Ammo pick up is now reduced even more then in the base game.
