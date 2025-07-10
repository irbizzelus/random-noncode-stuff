[Link to the ModWorkshop page.](https://modworkshop.net/mod/39854)

[Link to the latest Patch Notes.](https://github.com/irbizzelus/Gilza/releases)

[Link to the Perks Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md)

[Link to the Weapons Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Weapons.md)

<p align="right"> Use this icon to select the section you are looking for: <img width="286" height="71"  src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

Information is up to date with DEV patch: 2.5

Originally inspired by [IREnFIST](https://modworkshop.net/mod/28585) 

# Welcome to Gilza  
("Gilza" is a Russian word for "Bullet casing")  
A Payday 2 weapons/skills/perks rebalance/overhaul. All changes made by this mod are only available to the player who has it installed, without affcting gameplay for other people. It works in online lobbies regardless of if you are client or host. 

### How difficult is this rebalance?
This rebalance is **not** easy. It was made by me - for me, and i consider myself a pretty good FPS player. If you think of yourself as an average/casual player, you may find this mod's tweaks too difficult for you.

### Main goals of this rebalance:
* Make **__ALL__** weapons equally viable across all difficulties - this includes nerfing over-performing weapons.
* Update damage increasing skills to make players rely on them less.
* Provide players with more fun skill/perk combinations for improved build vareity.
* Make every skill useful/less situational.

# General Reballance overview

Detailed information on [weapon](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Weapons.md) and [perk](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md) changes can be found on pages dedicated to them. General updates and skills are written down bellow.  
On this page you can find __ALL__ general and skill related changes this mod makes, including reasons for most of them. It's incredibly long, so if you are here for the first time i recommend checking parts that you are most interested, right after this overview.

#### Enemy changes:
All enemies now have same amount of health on all difficulties, with values being similar to vanilla Death Wish difficulty.  
Headshots now deal 2x damage, with exceptions for some special enemies.

#### Melee rework (important for some skills):
Melee weapons now deal % damage - if your melee has 35 damage, it will deal 35% of enemy's health in one hit. Some enemies are exceptions to this rule.

#### Skills/Perks:
You can check the "Skills Legend" picture on top of the skills section bellow, which summarizes skill rework information - if a skill was updated or not, and how significantly. Check out whatever you think might be interesting :)

Most perks received minor updates to improve their design (mostly on DS difficulty), with only 3 perks gaining "major" updates. Go over general/neutral perk deck cards on the [perk](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md) page, since they apply to all perks.  
Additionaly, 3 new custom perks were added - "Brawler", "Speed Junkie" and "Guardian".

#### Weapon Changes:
<ins>Damage and ammo:</ins>
All guns are now categorized under a "damage class" - most weapons will have a strict base damage value without random fluctuations.
Ammo pick up is now dependent only on weapon damage class, and it is __much much__ worse. You **HAVE** to use both of your weapons, and *even then* you can still run out, especially on lengthy heists. Using melee and throwable weapons is somewhat mandatory, to avoid running out of ammo quickly.

<ins>Recoil:</ins>
Most guns have more recoil.
Recoil camera compensation is almost completely removed.
Weapon recoil now depends on your base stability: weapons with low base stability will have extremely high recoil, and vice versa.

<ins>Handling:</ins>
Weapon accuracy and stability are no longer affected if you: crouch, jump, walk or sprint. However, both accuracy and stability have a penalty if you are firing from the hip. Aiming down sights removes this penalty.
All weapons have an accuracy penalty if used in full-auto fire mode. If you use the select fire keybind to switch weapon to single-fire mode, it will gain it's full accuracy.

Check out the [weapon](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Weapons.md) page for more info.

<ins>__**IMPORTANT**__</ins>: for your first try of the mod make a backup of your save files. If you dislike the mod and choose to remove it, it will __not__ have any issues, and it will __not__ corrupt your save files, BUT you might loose some weapons from your inventory, due to updates in their attachment data.
Also your perks can get reset. Perk reset DOES NOT remove how many perk points you have (points you use to unlock perks), but it might remove your progression, and leave you with all perks at 0/9, forcing you to go through all of them while holding the + button. (use R while on the perks screen to max out a perk quickly)

<ins>__**EVEN MORE IMPORTANT**__</ins>: if you are going to give Gilza a try, check all mods that Gilza requires to function, under "Dependencies and Instructions" tab on the [MWS page](https://modworkshop.net/mod/39854). All mods that are tagged as "optional" are sorted in order of importance, from highest at the top to lowest at the bottom. I recommend getting everything before (but preferably also including) FrenchyAu's weapon attachment packs.


# Global changes

#### Enemies:  
All enemies will now have same amount of health on all difficulties.  
New health values are really close to vanilla Death Wish difficulty, and can be found in the table bellow:  

| Enemy type | Health |  Headshot multiplier |
| -------- | -------- | -------- |
|  Light Swat | 500 | 2 |
|  Heavy Swat | 900 | 2 |
|  Street cop/Sniper | 250 | 2 
|  Shield | 500 | 2 |
|  Medic/Tazer/Marshal sniper | 1250 | 2 |
|  Marshal shield pre-brake | 900 | 2 |
|  Marshal shield post-brake | 2500 | 2 |
|  Cloaker | 1540 | 2.8 |
|  Bulldozer | 12000 | 6 |
|  Minigun Bulldozer | 24000 | 6 |
|  Headless Bulldozer* | 24000 | 1 |
|  Cpt. Winters | 4000 | 4 |

\* - only takes half damage from bullets, to compensate new increased weapon damage. Health unchanged to avoid issues with explosive weapon damage sync.

All Bulldozers on Death Sentence difficulty have 2x health.  
Bosses have different levels of health, headshot multipliers and melee resistances, resembling their stats as close to vanilla as possible.  
This is one of a few changes that make combat easier and more forgiving for players with bad aim, since bodyshots mostly deal more damage.

#### Skills:
#### Damage resistance.
Damage resistance skills are now additive instead of multiplicative.  
In vanilla, if you have two 40% damage resistance skills, they would give you 100 * 0.6 * 0.6 = 36, so 64% damage resistance total. This approach especially hurts if you are trying to stack multiple damage resistance skills.

With Gilza's system there's only 1 problem that needs to be solved: max resist going over 100%. In vanilla it's impossible due to endless multiplications, but with Gilza's approach it would be possible. So to compensate, maximum possible damage resistance value was added: 80%. 

This change also allows you to calculate damage resistances and breakpoints easier.
#### Critical hits

Critical hits will now always deal 2.25x damage, instead of multiplying your damage by enemy's headshot multiplier. This change effectively buffs them, since 80% of enemies you are dealing with have 2x headshot multipliers now. This does however nerf crits against bulldozers, which was the main reason for this change.

#### Other:
Vehicle FOV was changed from base 75 to 90 - you can change it in mod options in game

-----

<ins>**__Important for section bellow:__**</ins> Right click on images to view them in full size by opening them in a new tab if you are having trouble reading them.

# Skills  
*Some skills had their icons and names updated to match new functionality better.*

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Skills%20legend.jpg)

### Mastermind - Medic

| Tier level | Skill | Descrption |  Summary and reasons for the change(s) |
| -------- | -------- | -------- | -------- |
| Tier 4 | Inspire | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png)  |  Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often. |
| Tier 1  | Combat Medic | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Combat%20Medic.png)  | This change keeps up with "Combat medic" idea while not hurting berserker players. |

### Mastermind - Controller

| Tier level | Skill | Descrption |  Summary and reasons for the change(s) |
| -------- | -------- | -------- | -------- |
| Tier 4 | INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png)  |  Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often. |
| Tier 3 |  INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png) | Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often. |
| Tier 3  | INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png) | Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often. |
| Tier 2   | INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png) | Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often.  |
| Tier 2   | INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png) | Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often.  |
| Tier 1  | INSPIRE | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inspire.png)  | Basic version of inspire is barely used, unless you either enjoy shouting at other people to move the fuck up, or a teammate is carrying a heavy objective bag. With this change you should be incentivized to use it more often. |

!!!

#### Tier 4

--

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Stockholm%20Syndrome.png)

A decent upside with an obvious downside. This skill was added to make other adjustments within Controller sub-tree flow better.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Confident.png)

Now focused more on civilian control.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Joker.png)

Split confident skill to make sides of this tree make a bit more sense. Also, the 35% damage penalty is how it works in vanilla - description was updated to make it more clear.

-----

#### Tier 1

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Forced%20friendship.png)

Aced version was always extremely bad for it's cost, so now it's cheap. Converted enemies are now slightly more expensive, since they are pretty good.

!!!

### Mastermind - Sharpshooter

!!!
#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Graze.png)

Damage calculations were updated to remove the need for headshots, and to make this skill's damage more consistent. Minimal trigger distance was added to incentivize sniping.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Aggressive%20reload.png)

This skill does not need any changes, but it's cost was never justifiable to me. With new numbers it's a bit better.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Designated%20marksman.png) 

Now has a new affect that interacts with Gilza's new weapon recoil, otherwise almost untouched.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Slow%20and%20Steady.png)

Buffs slower playstyle, especially with bipod'able weapons.

-----

#### Tier 1

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Stable%20shot.png)

Simplified.

!!!

### Enforcer - Shotgunner

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Overkill.png)

This skill is not required anymore to effectively use shotguns, so it gained a reload speed bonus. Damage was updated for new weapon breakpoints. Increased duration should make aced version of the skill better.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Blast%20Away.png)

Magazine increasing skill from vanilla skill "Close By", was reworked into this one, to let any shotgun get benefits from it, though bonus itself is lower.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Fearmonger.png)

Aced version now provides a similar effect to "Saw Massacre" while using Shotguns. Boost for killing a panicking enemy can be received with any weapon. Note that not every panicking enemy will trigger the boost, but only a specific "full panic" animation. I recommend using the pop up notification to figure out how it looks, you can disable it after.

-----

#### Tier 2


![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Shotgun%20CQB.png)

ADS speed bonus was moved to "Shotgun Expert"

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Shotgun%20Expert.png)

Increased damage is no longer needed. Now provides extra stability and ADS bonuses.

-----

#### Tier 1

--

!!!

### Enforcer - Tank

!!!

#### Tier 4

--

-----

#### Tier 3

--

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Transporter.png)

Compensation for the new global perk card.

-----

#### Tier 1

--

!!!

### Enforcer - Ammo specialist

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Fully%20loaded.png)

Since you now can pick up grenades without this skill, nade pick up was increased compared to vanilla.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Extra%20lead.png)

Bonuses swapped since aced provided much less value then basic.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Saw%20massacare.png)

Aced version now provides ammo pick up for the saw, making it more viable.


-----

#### Tier 2

--

-----

#### Tier 1

--

!!!

### Technician - Engineer

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Tower%20defense.png)

Running 4 sentries is now cheaper to compensate new ammo economy. Aced version is a decent alternative sentry playstyle, especially for DS.

-----

#### Tier 3

--

-----

#### Tier 2

--

-----

#### Tier 1

--

!!!

### Technician - Breacher

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Fire%20Trap.png)

Maximum total duration of firetraps is now 140 seconds longer for one full heist day. Increased range also makes them a more effective area denial tool.

-----

#### Tier 3

--

-----

#### Tier 2

--

-----

#### Tier 1

--

!!!

### Technician - Oppressor

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Body%20expertise.png)

Basic version now provides armor piercing at a reduced damage rate, like "Surefire", but allows you to play with lazy aim. Aced version is a new DPS skill, but has only a few specific breakpoints that can actually work well. Also feels a bit weird, because bodyshots are more effective.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Lock%20n%20Load.png)

In vanilla you get more reload speed on a smaller magazine weapon, even though they already have faster reload speeds. This backwards logic never made sense to me.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Surefire.png)

Aced version now has a 50% damage penalty when dealing damage through body armor. This is a compensation for new weapon effectiveness with bodyshots. Can stack with new "Body Expertise" basic.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Heavy%20impact.png)

Max chances tripled, but new threat requirement was added to make this skill more synergetic with 'loud' weapons.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Fire%20control.png)

This skill was previously improving your hip-fire weapon handling, for some weapons, and compensating penalties for others. Now it only removes penalties that Gilza's weapon handling has.

-----

#### Tier 1

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Steady%20grip.png)

Simplified.

!!!

### Ghost - Shinobi

!!!

#### Tier 4

--

-----

#### Tier 3

--

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Cleaner.png)

Bodybag asset and civilian cleaner costs were moved here to make it more "logical".

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Awareness.png)

Spotter and spycam assets were moved here to make it more "logical".


-----

#### Tier 1

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Inside%20man.png)

Insider assets like keycards and better getaway driver are viable for loud, not just stealth, so if you want to run it for loud builds, it's now super cheap at just 1 skill point instead of 7. This skill is the only one in this tree that is viable in loud now.

!!!

### Ghost - Artful dodger

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Revitalized.png)

New dodge focused skill that will help most dodge builds by providing extra safety, for moments when your armor is broken.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Sneaky%20bastard.png)

This is exactly the same skill from vanilla, but it's now cheaper at tier 3 instead of tier 4. "Dire need" functionality was moved to "Backfire".

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Backfire.png)

Aced version is "Shockproof" aced combined with new electric bullets upgrade. You can now roleplay as the tazer.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Parkour.png)

Basic version's 10% movement speed was moved to general perk cards, so new functionality was added to compensate.

-----

#### Tier 1

--

!!!

### Ghost - Silent killer

!!!

#### Tier 4

Same as Low Blow at Tier 3.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Low%20Blow.png)

Effectiveness was improved thanks to new critical hit damage multiplier.

-----

#### Tier 2

--

-----

#### Tier 1

--

!!!

### Fugitive - Gunslinger

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Bottomless%20Pockets.png)

Now provides increased ammo capacity for small-caliber weapons, and can help both sides of the tree.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Trigger%20happy.png)

Now combines effects of conditional "on-hit" pistol skills into one skill, to make left side of this tree focused on pistols. Effectiveness is slightly reduced.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Double%20trouble.png)

Now provides new bonuses to akimbo weapons, to make right side of this tree focused on akimbo weapons.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Gun%20nut.png)

Magazine capacity was removed, to avoid confusion when using revolvers. Rate of fire effect is smaller, compensating for pistol ROF adjustments. Reload speed moved from skill previously known as "Desperado" to here.

-----

#### Tier 1

--

!!!

### Fugitive - Revenant

!!!

#### Tier 4

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Messiah.png)

This is more of a QOL update to make using this skill easier.

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Swan%20song.png)

Reduced this skill's combat effectiveness by removing infinite ammo, which harms Gilza's ammo economy quite a bit. Improved perk's supportive capabilities with new movement speed penalty avoidance and increased overall duration.

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Running%20from%20Death.png)

Increased duration to improve it's worth.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Up%20you%20go.png)

In vanilla, "Up You Go" aced provides you 40% more health when revived. However, this bonus is applied to the health bonus that is set per difficulty, so to the 10% health you get on mayhem and above. Because of that, you would only receive 14% health when revived with this skill instead of the expected 50%. New version provides a flat % amount of your max health. 7 skill points for 4% extra health is dumb, thus the change.

-----

#### Tier 1

--

!!!

### Fugitive - Brawler

!!!

#### Tier 4

--

-----

#### Tier 3

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Counterstrike.png)

Added damage to improve this skill's worth, especially with melee builds.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Berserker.png)

This is an overall nerf that makes this skill not as reliable. But, as an upside, you can now use healing skills to keep your health at 30% with frenzy or more without it, to avoid being killed by snipers.

Berserk visual screen flash preview: (Color, size, and how exactly it flashes, can be adjusted in Gilza mod options.) [Preview link without downloading.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/new_zerk.gif)
![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/new_zerk.gif?raw=true)

-----

#### Tier 2

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Bloodthirst.png)

Numbers updated to match new melee damage.

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Martial%20arts.png)

New skill to make your melee's feel better.

-----

#### Tier 1

![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/Tough%20guy.png)

This skill now reduced camera shake from melee attacks to make melee playstyles more comfortable.

!!!

-----

:::
### {#f5b12a}(Weapon changes)
:::

### Due to Modworkshop's charachter limit for mod descriptions, i can't fit all the changes on this page. Gilza's weapon changes can be accessed over [here.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Weapons.md)

-----

:::
### {#f5b12a}(Custom Weapons Support)
:::

!!!

This mod will automatically search for custom weapons and convert their damage stats to work with Gilza's health changes. Beware: some custom weapons may have attachments that change damage/ammo pick up or other stats in such a way that it will not match Gilza's values well, making them either too good, or bad. I can't do anything about it, other then __manually__ adding support for __every gun individually__, and that is just tedious.

Currently supported attachment mods:
All of FrenchyAU's tacticool attachments packs (250+ attachments). Check Gilza's dependencies & Instructions tab for links.

Custom "special" weapons are not supported.

!!!

-----

:::
### {#f5b12a}(Additional QOL features)
:::

!!!

* While charging your melee weapons new melee UI will appear showing your charge amount and damage in %. This can be tweaked or disabled in Gilza's mod options.
* You can spoof Gilza's custom perks, to avoid being kicked in public lobbies. Can be disabled in Gilza's mod options.
* You can reset your perk progression to re-acquire perk decks, allowing you to try new custom perk decks without grinding XP to unlock them. This option does not reset amount of perk points you have already earned.

!!!

-----

#### Known issue:
You can crash when entering a heist, while using Jackal SMG or one of the Chimano pistols, with certain attachment combos. This can only happen with weapons that you have modified attachments on before installing Gilza. Remove any gadgets from these weapons, or simply re-purchase them to avoid this issue.

#### Supported languages (depends on your SuperBLT's language):
- English
- Russian - а именно все навыки, перки, описания оружий и элементы меню. Всё остальное может быть на английском.

Enjoy figuring out your new META and please provide feedback if something feels way too powerful.
Good luck, have fun! :D
