FILE NOT YET FINISHED

<p align="right"> Use this icon up-top to view weapon chapters: <img width="40" height="40" src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

# Assault rifles:
All DMR kits and some long barrels were reworked into "Armour piercing kits" that can penetrate shields, body armor and walls, but ammo pick up while using them is halved.

### New weapon mods
* M308 and Galant rifles now have AP rounds - same as AP(DMR) kits, but are categorized as ammuntion
* 7.62 Little Friend now has a 5.56 conversion kit - it reduces damage but increases ammo pick up
* Byk-1 now has a 5.45 conversion kit - it reduces damage but increases ammo pick up
* Car-4, AK 7.62 and Golgen AK 7.62 now have HP rounds - they can be used to update weapon's damage class (which includes ammo pick up)
* 7.62 Little Friend and Byk-1 now have a High velocity round for their underbarrel launchers - increase grenade travel speed by 3x with a 20% ammo pick up cost. Note: only works if you are the lobby host, otherwise reverts itself to standard round stats.
* Gewehr3's CQB and Sniper kits have new updated values, CQB now reduced damage class () and increases stats, while the Sniper kit acts like an AP kit

### New damage classes
|Damage class|Headshots to kill a light swat|Headshots to kill a heavy swat|Notes|
|--------|--------|--------|--------|
|120 dmg|3|4|Best for crits|
|155 dmg|2|3|Combos well with "Overkill" aced|
|200 dmg|2|3|Basically 155 class, but with better anti-dozer potential and less restrictive customization, at a cost of ~10% ammo pick up|
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

### New damage classes:
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
* **HE Slug**: doubles your damage, but removes extra headshot damage. Shoots explosives. Damage radius fall of was reduced, leading to more enemies in blas radius receiving more damage. Self-damage to players was also reduced.
* **Flechette**: 'Pellet' amount reduced to 5. Still provides body armor pen and increased damage range.
* **AP slugs**: provides a bit of damage range along with body armor, shields and wall armor piercing.
* **Dragon's breath**: Reduces amount of pellets to 9. No extra headshot damage. Deals 350 fire damage over a 2 second period to any lit target.
* **Tombstone slug**: Deals roughly 120 damage over 3 seconds.

# Light machine guns:
||
- Breakpoints and TTK are kept the same
- Now use new stability rework = more recoil
- Ammo pick up reduced
- Accuracy without a bipod is extremely poor, but you get extra 50% accuracy when bipoded compared to vanilla

New damage drop off introduced:
80% damage for the first 1.5 meters
100% damage for 14 meters
Progressive increase in damage from 14-36m
150% damage after 36 meters

LMG's will now be better at long range bipoded support, but slightly worse at point blank ranges (note: Akron Hc and Campbell LMG's don't have increased damage at range, and Buzzsaw LMG has 2x damage after 36 meters, instead of 1.5x)

All of the changes above should provide a more defending playstyle, especially if used with new "Slow and Steady" skill.
||

#### Sniper rifles:
||
Damage drop-off removed, now deal same damage regardless of distance.
__All__ snipers were reworked to one-shot headshot any enemy (except dozers and Winters).
Balanced around BODYSHOTS now, and how many bullets it takes to kill enemies in the body.
Damage profile depends on sniper type:

|Sniper type|Damage profile|BODYshots to kill normal|BODYshots to kill heavy swat|Specialization|
|--------|--------|--------|--------|--------|
|Semi-auto |560 dmg|2 |3 |The basic one, only headshots 1 shot|
|Lever-action |630 dmg|1|2|The anti-trash (enemy type i mean) one. Secondary bolt sniper also uses this dmg profile|
|Bolt action |1260 dmg|1|1 |Kill normal and heavy swats with one shot to the body. Pretty good, ay?|
|Heavy bolt action |1600 dmg|1|1 |Kill normal swat, heavy swat, medics, tazers, and marshal marksmen with one shot to the body. Ammo pick up is lowered by 10%|
|The 50cal|8050 dmg|1|1|Can one-shot-bodyshot anyone. Dozers on DW difficulty take 2 bodyshots to kill, minigun dozers take 4. Double bullet amount for DS difficulty. Ammo pick up is extremely low|

All sniper rifles have __identical ammo pick up.__(except for 50cal and heavy bolt action) Explanation: semi-auto snipers on average are much better when dealing with multiple enemies in a short period of time, thanks to their mag capacity and ROF. Bolt and lever action rifles are worse in this scenario, but due to their bodyshot damage, you don't have to aim for the head all the time, which means your accuracy on average will be higher with them. To summarize: if you are a good shot, semi-auto's will be best weapons of choice, due to their firepower, but if you feel like being lazy, or are not that good of a shot, you can sacrifice DPS to have overall better ammo economy due to less misses.

||

#### All akimbos:
||
Pretty much just copies of their non-akimbo counterparts, with less stability but slightly better ammo pickup. Akimbo SMG's and full auto pistols use new stability rework.
||

#### Specials:
||
Sorry, but ModWorkShop's new version forces me to leave a link here, because of the new character limit per mod page:
https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Special_Weapons.md
||
#### Pistols:
||
__All__ pistols now have no damage drop-off, so they are now more efficient at longer distances then SMG's.
Base ROF for all full-auto pistols was buffed by 25%. (max ROF with gun nut skill totals to be the same as without Gilza)
Base ROF for all semi-auto pistols was nerfed by ~50%
All pistols with AP bullets like 5/7, have reduced ammo pick ups.
Broomstick and Matever .357 revolver can now use AP kit/AP rounds to pen shields, walls and body armor.

With all of the changes above, pistols should now be a really comfortable alternative for mid-long range as a secondary, while SMG's are better up close and snipers at range.

|Damage profile|Headshots to kill normal swat|Headshots to kill heavy swat|Notes|
|--------|--------|--------|--------|
|77 dmg|3|6|Full auto's|
|95 dmg|3|5|Full auto's|
|105 dmg|2|4|Average|
|146 dmg|2|3|Average, can be combined with overkill skill if damage raised to 149 with mods for improved breakpoints|
|210 dmg|1|2|Heavies like Deagle|
|420 dmg|1|1|Revolvers|
|630 dmg|1|1|Can one-shot-body shot normal swat. Used by Peacemaker and Kahn .357 (with a 6 round mag mod) revolvers|
||

#### Sub machine guns:
||
Kobus90 (better known as P90) can use AP rounds.

New damage fall-off introduced:
120% damage for the first 2 meters
100% damage for 7 meters after
Reduction in damage from 9-35 meters
50% damage after 35 meters

These changes make SMG's a more distinct CQB category. While being extremely effective at closer ranges, they will loose their fire power really quickly at longer distances. If you want to have more firepower at range use pistols or snipers.

|Damage profile|Headshots to kill normal swat|Headshots to kill heavy swat|Notes|
|--------|--------|--------|--------|
|95 dmg|3|5 |Concealed with high ROF|
|105 dmg|2|4|Average|
|146 dmg|2|3|Can be combined with overkill skill if damage raised to 149 with mods for improved breakpoints|
|210 dmg|1|2 |Heavy|
||

### Bows/crossbows:
For the most part are balanced around bodyshots like snipers. Explosive shots now deal 2x the damage (since they cant get headshots that deal 3x damage). Heavy bows can one-shot-bodyshot tazers, light bows only normal swats, with one shot headshots on heavy swat.
Projectiles and their damage is handled by the host, so changes here will only be active when you are the host.

### Saws:
Saws now show you their actual ammo, allow for reloads at any time and are more effective against enemies (all enemies receive 9x damage in-game compared to saw's stat when viewed in the inventory). Can now also pick up ammo with Saw Massacre (ACED) skill.

### Flamethrowers:
Basically better now. Ammo capacity was nerfed, reload was slightly buffed, and damage was buffed by a lot. Magazines now completely change how flamethrower performs:
|Mag|Stats|Playstyle|
|--------|--------|--------|
|Rare|leaves you with only 1 damage, but makes afterburn happen more often. Strongest afterburn damage over longest period of time|Poke enemies to get them to burn, delaying them and letting them burn out while you are in cover|
|Well done|Doubles your damage but decreases chances for afterburn. Afterburn also deals really low damage|Be more direct with your flames and don't rely on afterburn at all|
|Default|Only 25% chance for afterburn (75% base game) but afterburn will deal roughly 60% of hp to a normal swat|All around an ok choice|

Secondary flamethrower has less damage and less ammo capacity.

### Miniguns:
Damage breakpoints are identical. 
Ammo stats changed from 750/750 to 600/900
Reload sped up by 20%
Ammo pick up reduced, and is now different in between both miniguns since one does more damage per bullet then another.

Hailstorm now has 210/630 ammo and better accuracy/stability stats. Ammo pick up for it is slightly better then in vanilla as well.

### Rocket launchers:
Damage breakpoints on dozers are the same. Radius was reduced by 25%. Both changes are host-sided.

### Grenade launchers:

Almost all changes here are host-sided. That means that if you are a client and use grenade launchers you won't benefit from damage, blast radius  or velocity changes at all.

All grenade launchers had their blast radius nerfed by roughly 50% but damage increased by 300% to make launchers be less effective against big groups, but more effective against any enemy type.

Overall ammo pick up for all launchers is 20% lower then vanilla PD2.

**Normal grenades:**
Max damage was increased by almost 3 times, but the radius was nerfed to half of vanilla PD2. New "high velocity" grenades were added to gl40, piglet, compact 40mm and china lake. Comparison of normal grenade types:
||Vanilla PD2|Gilza|Gilza High Velocity|
|--------|--------|--------|--------|
|Damage|1000|4000 (enemies have more health so it's 3x the dmg)|4000|
|Radius|350|175|90|
|Velocity|1.25|1.25|3.5 (arbiter in vanilla PD2 is 7)|

**Poison grenades:** nerfed. They now can't really kill anything, at best they will get normal swat to 50% hp, BUT the damage over time effect is now 30 seconds, so keeping your grinder/anarchist regen is even easier. Don't expect to get any kills though. Recommended usage: snipe groups that are far away, so by the time they get to you they have less health.

**Incendiary grenades:** most powerful area denial. Best time to kill. As a con, ammo pick up is almost non-existent.

**Electric nades:** no change.

Also, almost all launchers got reload speed buffs. Especially the piglet.
Launchers that have lower damage then others: Arbiter, Basilisk 3v.
