
NOT FINISHED YET

:::### Weapon changes:::

#### General:
||
* All DMR kits were reworked into 'Armor Piercing Kits' that can penetrate body armor, shields and walls. Due to technical limitations, they are now categorized as ammunition
* Most mag increasing mods now make your reload speed slower
* Normal grenades should not explode mid air if hit by bullets (Host only)
||

#### Stability rework and weapon performance:
||

### Weapon performance

[color=#ca8f2f]**All weapon categories:**[/color]
* You now suffer from 25% accuracy penalty when shooting while moving (both ADS and hip-fire)

[color=#ca8f2f]**Changes for weapon categories: AR's, SMG's(+akimbo) and LMG's**[/color]
* You can now suffer from 30% accuracy penalty if your weapon is toggled to full-auto fire mode. If you switch to single-fire fire mode during the heist your accuracy will be increased (provides some usage to the switch fire mod keybind, and also makes you feel tacticool)
* You receive 50% bonus to stability if your weapon is toggled to single-fire mode

-----

### Stability rework

[color=#ca8f2f]**Affected weapon categories: AR's, SMG's(+akimbo),LMG's, Full-auto Pistols(+akimbo), Miniguns(including Hailstorm)**[/color]
* Your base stability value now represents how much recoil your weapon will have by default. This amount can be decreased with weapon modifications as usual
* Amount of horizontal recoil was overall reduced
* Horizontal recoil will now also be dependent on base stability. If base stability value starts with number divisible by 2, recoil will lean mostly to the left, and vise versa. (Example: 24 base stability will favour weapon recoil to the left, and 56 will favour it to the right)

[color=#e4df86]**What does this all mean?**[/color]

Base stability value is now going to be more important then amount of stability bonuses you can give to weapons. If some weapon has base stability of <10 its going to be really hard to control even if you get it to 100 stability with mods/skills. However the opposite is also true, where weapons with high base stability will feel like laser beams, and you won't have to worry about getting any stability bonuses for them. 

Horizontal recoil is overall easier to predict.
You will now have to toggle your weapon's fire mode (if it can do that) based on the engagement distance.

Some weapons might feel the same, and others completely different from vanilla. 
And yes, max recoil you can have here is higher then in vanilla (try Amr-16 with no mods for lolz).
||

#### Assault rifles:
||
All DMR kits were reworked into Armour piercing kits that can penetrate shields, body armor and walls, but ammo pick up while using them is halved. 
M308 and galant rifles received AP rounds, that are similar to AP kits, but have better ammo economy.
7.62 little friend AR can be equipped with a 5.56 conversion kit that reduces damage but increases ammo pick up
Car-4 AR can use HP rounds to change it's damage profile from 175 to 210

|Damage profile|Headshots to kill normal swat|Headshots to kill heavy swats|Notes|
|--------|--------|--------|--------|
|105 dmg|2|4|Best for crits|
|146 dmg|2|3|If used with overkill aced, and base damage is increased with mods to 149+ becomes 1-2 bullets to kill type|
|175 dmg|2|3|Basically 146 profile, but with better anti-dozer potential at a cost of total ammo pick up.|
|210 dmg|1|2|Most average, most stable, poor ammo economy if not accurate.|
|420 dmg|1|1|Usually highest recoil and worst ammo economy. Best combined with body expertise/ammo related skills.|
||

#### Shotguns:
||
This one is most interesting in my opinion.
Damage profile depends on shotgun type:

|Shotgun type|Damage profile|Headshots to kill normal swat|Headshots to kill heavy swat|Specialization|
|--------|--------|--------|--------|--------|
|Pump-action|420 dmg|1|1|Most accurate but slowest. Recommended ammo: slug, to pen shields or HE|
|Semi-auto no mag|305 dmg|1|2|The in-betweeners. Become 1-1 bullets to kill type with overkill. Recommended ammo: flechette or tombstone slugs, to not waste as much ammo finishing off low hp targets|
|Semi or full-auto with mag|110 dmg|2|4|Spammm. Recommended ammo: buckshot for better breakpoints with overkill, HE or Dragon's Breath|
|Double barrel|1250 dmg|1|1|Can one-shot-bodyshot normal and heavy swats. One-shot everyone else in the head. Recommended ammo: flechette or slugs.|

All shotguns now have new damage fall-off. For more detail in game, use "More weapon stats" mod. Short descriptions:
- Double barrel's have best range with 50% damage at furthest point.
- Pump action's have 2nd best range after double barrels, but lowest minimal damage of only 20% at furthest point.
- Semi-auto's are just slightly worse then pump actions and their damage is reduced to 33% at furthest point.
- Full-auto's have shortest range but their drop off is longest in terms of % over range. They still deal lowest damage across all distances, but due to this slow drop off, they are more efficient with crits/body expertise at range since their damage is reduced slower then other shotguns. Minimal damage is 50%.


[color=#ca8f2f]*One new ammo type was added for __primary__ pump-action shotguns:*[/color]

**Breaching round**: Can open any locked space that OVE9000 saw usually can. Allows to pen shields, walls and body armor. Damage and damage fall-off are cut significantly.

[color=#ca8f2f]*All shotgun ammo types were reworked:*[/color]

**Buckshot**: now increases damage based on the shotgun category, so all shotguns gain similar in power breakpoint bonuses. Ammo pick up reduced by 20%

**HE Slug**: doubles your damage (but no headshot extra damage). Removes all stability, cuts ammo pick up by 60% and total capacity by 50%

**Flechette**: no longer gives any stat changes. 'Pellet' amount reduced to 5. Reduces ammo pick up by 10%. Provides body armor piercing and 50% damage range

**AP slugs**: removed accuracy and damage stats, cuts total ammo capacity ~40% and ammo pick up by 25%, provides 20% damage range along with armor piercing

**Dragon's breath**: cuts total ammo by 50%, ammo pick up by 80%. Reduces accuracy and amount of pellets from 12 to 6. No extra headshot damage. Distance at which fire can be triggered was reduced from 1400 to 900. Will deal 1180 damage over a 3 second period to any lit target. (Yes, it one-shots all swat's with any shotgun. Higher damaging shotguns can 'one shot' some specials.)

**Tombstone slug**: cuts total ammo by ~35%, and ammo pick up by 20%. Deals roughly 400 damage over 2 seconds. This will allow for all shotguns to benefit from this slug differently, depending on their breakpoints. Best shotgun shell for regen-based perks.

||

#### Light machine guns:
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
