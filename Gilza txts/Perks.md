[Link to the ModWorkshop page.](https://modworkshop.net/mod/39854)

[Link to the latest Patch Notes.](https://github.com/irbizzelus/Gilza/releases)

[Link to the General/Skill Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/General_and_Skills.md)

[Link to the Weapons Info page.](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Weapons.md)

<p align="right"> Use this icon to select the perk you are interested in: <img width="286" height="71"  src="https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/main/Gilza_pics/headings_icon.png"> </p>

Stats are updated for DEV patch: 2.5

TODO - make builds which utilize:
* bows/crossbows
* miniguns (non-crit)

# General info:

Gilza's CUSTOM perk decks are located closer to the bottom of the page, right before Copycat, since Copycat now has new cards from Gilza's custom perk decks.

### Gilza rebalance changes
Here are the most important aspects of Gilza's rebalance which you need to know before going through most of the perk updates bellow:
1) Melee damage is now applied as a % of enemy's total health per hit, so a 35 damage melee kills an enemy in 3 hits. Some enemies, like Bulldozers and Bosses, have resistance to melee-%-damage and will take less damage (for example - Bulldozers take 10x less melee damage). This makes melee weapons overall much more effective, but most skills and perks affecting melee were nerfed to compensate.
2) Damage resistance is now combined additively instead of multiplicatively. This affects all damage resistance skills in the game, effectively buffing this statistic, especially if you decide to stack multiple DR skills. Note that max possible damage resistance is only 80%, to avoid "god mode" situations. (Example: in vanilla having 25% DR, 10% DR, and 15% DR would reduce incoming damage by: 100% * 0.75 * 0.9 * 0.85 = 57.375% or about 43% total damage resistance. With Gilza you will instead get 50% damage resistance total with the same combo.)
3) "Underdog" skill activation trigger is now different. In vanilla this skill is based on enemies that are currently hostile to you, but with Gilza this check was replaced with a LOS (line-of-sight) check between you and the enemy, making this skill more consistent for Online play. In addition, instead of activating for 7 seconds, then having a 1 (or more) second cooldown before activating the 7 second buff again, this skill will now endlessly re-activate itself as long as you have required amount of enemies withing your LOS, but the lingering duration was reduced to 5 seconds to compensate. This skill's activation trigger is shared with, and affects some perk cards for: Crew Chief, Infiltrator and Sociopath perk decks.

| Some perk cards have received updates for their descriptions. How different they are depends on severity of misinformation/inaccuracy that vanilla perk description might have had. For the most part, changes are limited to clearing up potential confusion, but sometimes they can also give you more information on how certain aspects of skill actually function. For example, this is how 9th Crew Chief card was re-written. This card works exactly as it does in vanilla, but now it allows you to understand it's mechanics a little better. |
| -------- |
|   ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/New_loc_example_perk.png) |

### General perk information structure
Most perk decks noted bellow will follow this format:
1) Perk name (adjustment amount) - adjustment amount is a scale from 0 to 5 (0-none, 1-least, 5-most) for changes that were done to the perk deck. Keep in mind that all perk decks, even those at 5/5, were updated while trying to keep their theme/bonuses relatively similar to original idea/purpose of the perk deck, at the very least in my personal opinion.
2) Image showcase of the changes - easiest way to go through all the changes.
3) Summary of the changes - usually includes an answer for the question "why?" for most changes. This part may sometimes be split per perk deck card for ease of reading.
4) Additional tips - if perk's rework was significant enough, this is a custom perk deck, or there is some other reason to share them - tips for the perk might appear under this section.
5) Build(s) to try - includes a "barebones" set up with most important skills for each deck (yes, bullseye is almost always there), and at least 1 build to try, in case you don't feel like figuring out a new build, due to how many changes this mod has made. Most builds do not include an in-depth description of weapons and their attachments, because you should figure those out on your own, since Gilza allows for much more variety when it comes down to the weapon selection. Builds themselves are Death Sentence difficulty focused, which will most likely make them work well at lower difficulties as well. Some builds may be specified to be only viable for certain difficulties.

# Neutral/Global cards (4/5):

Cards that every perk deck has.

|  | Updated cards - 2, 4, 6, 8 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Neutral_perk_cards_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Neutral_perk_cards.png)  |

### Changes Summary
Added grenadae pick ups, bag throwing distance bonus, and a small speed boost compared to vanilla, but also removed damage related skills.  
- Card 2: Removed increased headshot damage to make overall balancing easier and more fair for non-maxed out builds. Replaced with passive bonuses from cards 4 (armor movement penalty in vanilla is a typo) and 8.  
- Card 4: Moved armor speed bonus to 2nd neutral card.  
- Card 6: Removed 35% ammo pick up bonus to make overall balancing easier and more fair for non-maxed out builds. Added ability to pick up throwables without investing into fully loaded skill tree, since throwables are not extremely effective. This pick up chance is still extremely low, and is now also balanced by having individual pick up rates for every throwable separately, which can be found in each throwable's description.  
- Card 8: Removed random 5% dmg increase for better balancing. Moved doctor bag bonus to card #2. Added better movement speed and loot bag handling from Transporter and Parkour skills. Those skills were adjusted to compensate.

-----

# Crew Chief (2/5):

| Vanilla (3rd card) | Gilza (3rd card) |
| -------- | -------- |
|  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Crew_Chief_vanilla.png)  | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Crew_Chief.png)  |


### Changes Summary
Adjusted the 3rd card to provide "shouting" bonus to both basic and aced version of inspire. Vanilla description describes the buff as "shouting distance", even though it only affects intimidations and enemy highlights. Now it's both more clear in what it does and does a little extra thing (total max range for inspire is 11.25m now, so not that big of a change). In addition, damage resistance aspects of this perk were buffed both due to global damage resistance update, and because of the shared Underdog skill trigger (for more info on these changes, scroll up to [General info - Gilza rebalance changes](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md#gilza-rebalance-changes)). Build vareity may have improved slighlty, but gameplay is overall untouched.

### Build(s) to try
Barebone skills: ICTV armor is heavily favoured. Hostage taker or First Aid Kits are recommended for health upkeep. Inspire is handy to have if you have points to spare. Bullseye is always needed. Your general buffs are oriented mostly at your teammates, while you just gain passive buffs, which leads to an overall passive playstyle.  

Build 1 (By [Razer125](https://steamcommunity.com/profiles/76561199376033342/)) - Basic Sniper https://pd2builder.netlify.app/?s=xa0HgF00kF0-9010-61d0&p=0&a=6&t=4&d=3  
This is meant to be something that is close to home for the Sniper Crewchief build in vanilla, though with Gilza's gameplay loop you will be relying on your secondary and melee a lot more. But hey, atleast sniping is a lot easier as you only need to aim for the body.  
This build is using all barebone skills - ICTV armor, hostage taker, and inspire. Sniping is favoured due to the passive nature of this perk deck, but you can try to rely on any weapons of your choice, with appropriate skill adjustments to this build.  
Weapons to use:  
1600 damage class sniper rifle with any secondary of your choice. Flashbangs or zapper grenades, depending on heist length. Any melee of your choice, but if you decide to use melee mostly for dozers, 75 damage melee's are the best. 

-----

# Muscle (1/5):

| Vanilla (9th card) | Gilza (9th card) |
| -------- | -------- |
|  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Muscle_vanilla.png) | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Muscle.png)   |

### Changes Summary
Added increased self-healing while playing on DS difficulty. This change was done purely to bump this perk up a bit, since it's already pretty decent, but it's drastic change in effectiveness between DW and DS is a bit too much. Overall gameplay is identical.

### Build(s) to try
Barebone skills: Hostage taker for health regen, which stacks with muscle's natural health regen. Partners in crime for improved total health. Bullseye for armor gating. Up you go aced to get more health after being revived. Depending on how agressive you are, you could opt in for first aid kits, to easier maintain your max health.

Build 1 (By [Razer125](https://steamcommunity.com/profiles/76561199376033342/)) - Crit Muscle https://pd2builder.netlify.app/?s=xkgF0100dg0-6gF00105g0001f0&p=1&a=0&t=4&d=5  
Stay below 25 total detection. A run and gun version of muscle. Focusing armor skills with muscle in general is not a great idea, since most of your survivability comes from your health, which should be imrpoved first.  
Weapons to use:  
Prefered combo: Vulcan Minigun and Bronco revolver with <25 total detection. Alterantively, you can rely on any other fast firing primary weapon with low damage class, bipod-less lmg's are prefered. Secondary Bronco is recommended due to it's ability to gain high concealment, but any reliable secondary that can deal with targets beyond 10 meters will do as well.

-----

# Armorer (0/5):

### Changes Summary
This perk is perfectly fine and does not require any changes, the only reason it's even mentioned here was to avoid questions like "why no armorer here?"

### Build(s) to try
Barebone skills - If you play on Death Sentence difficulty, either run ICTV, or run CTV with frenzy aced to gain 2 tap armor. For difficulties bellow, use any armor you prefer, tho higher armors are favoured, and never forget bullseye (either basic or aced) for armor gating.

Build 1 - Jack of all trades https://pd2builder.netlify.app/?s=090-4xkkFg1380-6580-5h58&p=2&a=6&t=6&d=30  
Ultimate powerhouse able to achieve any task. Spare 1 point you can use however you wish, but getting extra accuracy from stable shot will most likely be best value.   
Weapons to use:  
Use a primary shotgun of your choice, but 155 damage class is recommended due to combination of berserker and overkill, allowing you to gain a massive damage increase. Secondary can be a shotgun to gain benefits from overkill, a SMG to deal with Bulldozers, a high accuracy weapon for long range, or any weapon with shield AP capabilities. 

-----

# Rogue (2/5):

| Vanilla (9th card) | Gilza (9th card) |
| -------- | -------- |
|  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Rogue_vanilla.png)  | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Rogue.png)  |

### Changes Summary
Copycat and Hacker are both just straight upgrades to this deck, so to compensate, this deck is now slighlty more effective in it's own playstyle. Dodge buffs might be extremely small, but do consider that new options in the arful dodger skill sub-tree are also indirectly buffing this deck. Additionally, AP chance can now work well with both new Surefire and Silencer AP skills, instead of being a joke of a bonus.

### Build(s) to try
Barebone skills - Use bullseye to armor gate whenever your armor breaks. You can use First Aid Kits if you want to rely on your health as well, but rogue is not exactly build for health. Additional dodge skills are welcome.

Build 1 - Run and Gun https://pd2builder.netlify.app/?s=09001000810-6j0-4R5O1G0100&p=3&a=0&t=b&d=3  
Ultimate speed build. 90% of the time you will be running, to gain extra 10% dodge, and hip firing with your akimbo smg's to deal damage and armor gate with bullseye. Use silenced weapons to gain 90% total body armor AP chance, since hipfiring akimbos are not exactly known for their accuracy. Botomless pockets and crits will allow you to gain enough damage to avoid running out of ammo, even if your headshot accuracy overall is low. You can also move some skills around to replace unseen strike for body expertise, for more reliable bodyshot damage, but this is up to you.  
Weapons to use:  
Use any akimbo SMG's of your choice, and a high accuracy secondary of your choice. You can use a secondary with shield AP along with accuracy, but due to your high mobility, you should not have any troubles while flanking shields. Use any melee of your choice, 20-25 damage class will most likely fit the best. You can replace your throwable for Ace of Spades as well, since they deal solid damage with crits.

-----

# Hitman (5/5):

|  | Updated cards - 1, 3, 5, 7 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Hitman_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Hitman.png)  |

### Changes Summary
Probably the biggest rework of all vanilla perk decks, because vanilla version is just ass. Armor recovery is a stat that could've been important if default armor recovery timer was 5 or more seconds instead of 3, or if different armors actually altered this timer, but this is not the reality. This rework has only kept the final 9th card the same, because that effect is relatively powerfull, compared to the rest of this deck.  
- Card 1: Now rewards you for landing "badass" kills with throwing knives or melee weapons, to somewhat fullfill the fantasy of John Wick movies, in which anything can be a powerfull weapon in your hands.  
- Card 3: Statistical buffs to akimbos are the same (-16 in vanilla is an error, actual buff is just -8), and the armor recovery bonus was converted into a temporary bonus (like Overkill skill) to keep this aspect of the original perk still present. Limiting trigger to specific weapon types makes it less powerful than if you had it passively at all times from any kill, since this bonus can be increased (in Card 7) and other bonuses were also added, so it would be a bit too good.  
- Card 5: Now provides 5 second of invulnerability with 20 second cooldown (similarly to armorer, effective cooldown is 20-5=15 seconds), if you manage to secure a specific combo. In my experience this combo is extremely difficult to achieve, especially at higher difficulties, which makes the reward that you get balanced, even if you consider the 7th card buff.  
- Card 7: Having a bounty system on a perk deck that is named "Hitman" is just simply cool, this was good enough of a reason to add this. After killing your bounty you will now improve aspects of previous hitman specific perk cards, making the user of this deck more effective than it's vanilla counterpart, but only sometimes, and not for too long, which makes it balanced, while also allowing to keep playing it roughly how you would in vanilla (aka relying purely on recovery).

### Additional info/tips
Use small arm firearms to constantly activate recovery for the passive bonus, use melee/throwables in a pinch for a little bit of armor gating, and if you see a group of enemies clumped up together try to activate the kill combo off of them. Or you can simply play it as you would in vanilla, with only one change to your gameplay - you should seek out your bounty to improve your recovery for a while.

### Build(s) to try
Barebone skills - focus on getting skills for akimbos/smg's/pistols to activate hitman recovery bonus, and preferably melee skills for the combo. Bigger armor is recommended to get the most out of armor recovery/regen bonuses.

Build 1 - Somewhat standard. https://pd2builder.netlify.app/?s=xa0-64V0-9010128T0138&p=4&a=6&t=b&d=3  
Pistols pistols pistols. Spam them as much as you can, since your ammo pick up should not be a problem. Use melee weapons to get to the invlunerability combo.  
Weapons to use:  
Akimbo pistols with 78 damage, And a 125 secondary pistol modded for accuracy to deal with snipers or to kill your bounty target if it's far away. Use silencers on all weapons to gain 50% ap chance on bodyshots. Use throwable knives/axes/cards to activate combo and armor heal. Use a 75 dmg melee, because with basic berserk it will be a reliable oneshot, allowing for relatively easy combos. 

-----

# Crook (2/5):

| Vanilla (9th card) | Gilza (9th card) |
| -------- | -------- |
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Crook_vanilla.png)  |  ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Crook.png)   |

### Changes Summary
Added 75% AP chance to allow for easier stacking of this statistic with Surefire, or Silencer AP skills. This perk deck was significantly improved via indirect buffs to the Ghost's artful dodger sub-tree, allowing you to both gain dodge cheaper, and also gaining armor on dodge from the new tier 4 Revitalised skill. Imrpoved trigger for the Underdog skill also allows you to get 2 tap armor on DS with the standard Balistic Vest, granting you 5 more dodge than the usual HBV you would use on DS.

### Build(s) to try
Barebone skills - Since this deck focuses on dodge and armor you should prioritize similar skills. Bullseye for armor gating is always needed. Surefire aced allows you to gain 100% total ap chance against body armor, so it's a solid option to consider.

Build 1 - Default (DS specific) https://pd2builder.netlify.app/?s=xa004100xc0-90wj1k00g11I&p=5&a=3&t=b&d=3  
2 tap armor and 35 dodge, same as vanilla. Unlike vanilla, this one is cheaper to build, and has additional passive armor gating from basic revitalized. Keep total detection <25.  
Weapons to use:  
Any assault rifle of your choise (lower damage classes prefered) with a silencer, focusing on concelment and accuracy. Secondary flamethrower for shields and decent DPS, or any other low damage class weapon with shield AP. Use melee against bulldozers, and throwables axes/knives/cards to save on ammo.

Build 2 - Bodyshot maniac https://pd2builder.netlify.app/?s=xa000100xc0-6Na000P5g00g150&p=5&a=1&t=b&d=3  
Run and gun sort of build, with 100% ap chance against body armor. Keep total detection <25.   
Weapons to use:  
Any assault rifle of your choise (lower damage classes prefered), focusing on concelment and accuracy. Secondary flamethrower for shields and decent DPS. Use melee against bulldozers, and throwables axes/knives/cards to save on ammo.

-----

# Burglar (3/5):

|  | Updated cards - 3, 5, 7 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Burglar_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Burglar.png)  |

### Changes Summary
All passive stealth bonuses were buffed from 10-20% to 25%. Saving 2.5 seconds on a pager in stealth is still worse than having a Pocket ECM, but at least it doesnt feel nearly as useless anymore. Improvements to the 5th card of the deck allow you to go for the "Hybrid" stealth-loud playstyle much better now, since LBV will now have same exact dodge amount as the 2-Piece Suit, allowing you to gain a little more survivability, and not even losing out on concealment if you equip the Inner Pockets skill. Additionally using silenced weapons will now improve your concealment even more, allowing for much more flexibility when it comes down to weapon vareity.

### Additional info/tips
This is not anything new, but your general playstyle for loud should be sniping most of the time, because enemies will target you less if you stand still, and also target you less if you are further away from enemies than your teammates are. And since enemies will always focus you for a few seconds after you damage them, it is recommended you run one-shotting weapons, and snipers fit this role the best.

### Build(s) to try
Barebone skills - Dodge and/or stealth skills should be prioritized, depending on your playstyle. Bullseye is always required for loud. Skills that imrpove balistic vests are extremely beneficial, since this perk now favours the Light Balistic Vest.  

Build 1 - Backline Sniper https://pd2builder.netlify.app/?s=5O000h009410380-68N9k00g100&p=6&a=1&t=b&d=53  
Stay behind your team and snipe enemies before they get a chance to even shoot at you. Don't forget to stay crouched to gain burglar's benefits. You may replace basic swan song with blodthirst basic if you want an additional option for dealing with bulldozers. You can use any secondary deployable that would fit your current game the best, decide which based on your teammates' loadouts. You can also bring a grenade case if u want to use grenades yourself, instead of throwable axes/knives/cards.  
Weapons to use:  
650 damage class sniper rifle and a 250 damage class secondary SMG in single fire mode, to gain benefits from ammo efficiency. Do not use select fire mode attachments on your SMG, to allow yourself to use full auto against bulldozers. Both weapons should be silenced and your total detection should be <25. Use any high concealment melee of your choice.

-----

# Infiltrator (2/5):

|  | Updated cards - 1, 3, 5, 7 |
| -------- | -------- |
|  Vanilla | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Infiltrator_vanilla.png)  |
|  Gilza | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Infiltrator.png)  |

### Changes Summary
This perk deck is affected by all the important mod updates mentioned in [General info - Gilza rebalance changes](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md#gilza-rebalance-changes) above. Since temporary damage resistance is much easier to both activate and keep, and damage resistance can be stacked much more effectively with other skills, total amount of DR gained from the perk was slighlty reduced. Specific amount is important for a health-based breakpoint on DS, but overall survivability of this perk deck is MUCH better than in vanilla, since your max potential damage resistance is easier to activate, and your total DR is also much higher.

### Additional info/tips
For DS builds - 3 tap is achieved much easier now and even 4 tap is possible. 5+ is possible with maniac/crew cheifs on your team, making this deck absolutely busted in coordinated teams. As long as you have the temporary DR bonus that is.

### Build(s) to try
Barebone skills - ICTV armor, underdog and frenzy aced for stackable damage resistance. Bullseye for armor gating.

Build 1 - DMG resist overload https://pd2builder.netlify.app/?s=010912018N1Q120-610-71I&p=7&a=6&t=j&d=0  
Use bipodable LMG's to gain damage resist while bipoded, and stack a huge amount of damage resistance. You can swap shock and awe aced for bullseye aced if you want to upkeep your position for longer (not recommended for DS difficutly). You can also swap all skills in techician that provide your LMG's a DPS increase for nine lives aced and get 3 points on top, if you feel like your survivability is not high enough, and you would like to get an extra down instead of additional DPS. Partners in crime allows you to gain 2 tap health for DS difficulty, so if you play at lower difficulties you can replace convert skills with anything else.   
Weapons to use:  
Bipodable LMG of your choice, and a secondary SMG for close quaters combat, since LMG's deal reduced damage at point blank. Bipodable LMG's tend to have good enough accuracy to deal with snipers, so the only other option you can go for is a secondary to deal with shields, if you decided to go for aced bullseye instead of aced shock and awe. Use Viper grenades to make teammate revives easier, and try avoid throwing them too often. Use any melee of your choice, but 35+ damage classes are recommended.

-----

# Sociopath (1/5):

| Vanilla (1st card) | Gilza (1st card) |
| -------- | -------- |
|  ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Sociopath_vanilla.png)  | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Sociopath.png) |

### Changes Summary
This perk deck is affected by all the important mod updates mentioned in [General info - Gilza rebalance changes](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza%20txts/Perks.md#gilza-rebalance-changes) above. Except for melee and Underdog trigger, other parts of the deck were untouched, since it's already good enough.

### Additional info/tips
Tip for both vanilla and Gilza - this is not a melee deck, despite how many buffs it gives to melee.

### Build(s) to try
Barebone skills - ICTV armor and melee skills. High burst damage weapons like shotguns and snipers are prefered.  

Build 1 - Shotgunzz. https://pd2builder.netlify.app/?s=010010wt4Xxk0-81010-41c3&p=8&a=6&t=9&d=0  
Use highly damaging shotguns to gain kills reliably every 1 second or so, maintaining high armor level. Use melee to refill your health whenever you need to, and don't be afraid to get up close and personal with enemies.  
Weapons to use:  
900 or 450 damage class primary shotgun, modded for accuracy, with default or flechette ammuntion. Use high DPS secondary shotgun with default ammo as secondary to deal, or help dealing with, bulldozers, if your bloodthirst stacks are low. Try to rely on melee or your throwable javeln when dealing with bulldozers.

-----

# Gambler (5/5):

|  | Updated cards - 1, 3, 5, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Gambler_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Gambler.png)  |

### Changes Summary
Even though this is a full rework, the general idea of "pick up ammo for bonuses" is still here, but with a more "gambly" twist!  
Adjusted all perk cooldowns to be at 4 seconds. Added more elements of random chance by allowing self-damage. Improved supportive capabilities with shorter cooldowns and more consistent healing amounts. Improved survivability by adding dodge to the final card, but also kept it's amount random to match the "Gambling" nature of the perk deck name.

### Additional info/tips
Dodge amount you gain stays with you forever, so you can try to avoid picking up ammo boxes if your dodge chance and health are maxed, to avoid them from rolling negative effects.

### Build(s) to try
Barebone skills - Bullseye for armor gating, and additional dodge and healing skills are highly recommended. Up you go is almost mandatory to avoid instant deaths after revives.

Build 1 - Ultimate ammo guy. https://pd2builder.netlify.app/?s=016V1400c11Q0-82h5g00g100&p=9&a=0&t=j&d=0  
Embrace ammo supportive playstyle. Using ammo bags for yourself will not be required since you already have enough ammo from Fully Loaded and Crits combo, but your teammates might thank you. Keep your total detection <25.    
Weapons to use:  
125 damage class Assault rifle modded for accuracy and concealment, since Designated Marksman skill is already helping you with recoil. 95/125/155 damage class SMG modded for stability and concealment, mostly to melt bulldozers at point blank ranges. Use viper/concussion grenades to help with revives. Any high concealment melee of your choice.

# Grinder (1/5):

| Vanilla (9th card) | Gilza (9th card) |
| -------- | -------- |
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Grinder_vanilla.png)  | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Grinder.png)  |

### Changes Summary
Slighlty improved AP chance (5% big wow) to allow for this stat to work better with other AP skills like Surefire and Silencers AP skills.

### Additional info/tips
For DS specifically - run this deck when you have Crew Chief on your team for the 2 tap health breakpoint with fastest self-healing of all decks in the gamae. Otherwise this deck is still sorta mid tier for DS.

### Build(s) to try
Barebone skills - Bullseye for armor gating, partners in crime for extra health. LBV armor with die hard aced is recommended, since 70 armor helps quite a bit.  

Build 1 - Crits with AP https://pd2builder.netlify.app/?s=wb0914009k00120-6121S000300&p=a&a=1&t=1&d=3  
If silenced weapons are used you will have 85% chance to pierce enemy body armor total, allowing you to play with lazy aim. Keep your regen stacks up as much as you can, to maintain regen immediately after armor break, but don't rely on your health too much while playing on DS difficulty, since you can't get 3 tap health. If you feel confident enough, you can replace up you go with melee skills to help with bulldozers, tho SMG with crits should be more than enough to deal with them.  
Weapons to use:  
<=155 damage class assault rifle modded for accuracy and concealment, recoil may be partially ignored since you get a decent boost to it from designated marksman skill, but don't completely ignore it, since gun oil will increase your rate of fire, affecting your recoil. Weapons with high rate of fire recommended. Use any <=155 damage class SMG as secondary for close quaters combat and to deal with bulldozers. Any high concealment melee of your choice. Keep total detection <25.  

Build 2 - Breacher https://pd2builder.netlify.app/?s=010-694iF1a1W0-410-6j50&p=a&a=1&t=j&d=80  
Ultimate objective build, with a lower focus on survivability and DPS.  
Weapons to use:  
Any primary weapon of your choice. Saw as secondary on heist where saw can be useful, use it in combat as well, since it has very decent ammo pick up now. If you don't think that saw will help on the upcoming heist, swap to any secondary which can help you deal with shields, or any weapon with Damage Over Time effect, to help you upkeep your ginder heals. Use any melee you prefer to deal with bulldozers.

# Yakuza(4/5):

|  | Updated cards - 1, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Yakuza_vanilla.png)  |
|  Gilza | ![](https://github.com/irbizzelus/random-noncode-stuff/blob/main/Gilza_pics/Perk_Images/Yakuza.png)  |

### Changes Summary
Improved anti-healing part of the perk deck by nullifying any healing from any source, except for deployables. Heal on revive is now always set 10%, even on lower difficulties, to imrpove reliability of the deck. Added 3 new effects:
1) Resistance to armor piercing shots (from snipers) - was added to make this deck less risky, since you have to run at low health to gain benefits.
2) Resistance when getting shot from behind (180° behind you) - was added to make the "duck to cover" gameplay less frustrating. You are already required to amost instantly react to your armor being broken and seeking (or ducking in) cover on higher difficulties, being shot from behind when you get flanked makes your "shoot, duck in cover, shoot" gameplay even less powerful than it already is. This feature mostly will help you with running to cover, or avoiding being screwed by flanking enemies, without allowing you to fight back with imrpoved damage resistance.
3) Resistance to armor suppression effect - for those who know what this is: it doesn't happen at all anymore, but total recovery will still be increased by 0.5 seconds when shot. For those who don't know:  
Armor suppression is an effect that applies to you when you are getting shot at, even if you are not getting hit (always applies if you are hit by the shot). If you get supressed while your armor is recovering, the recovery timer is set to it's maximum duration, and then 1 extra second is added on top from suppression. Practically speaking, this effect is always applied to you, because usually when you play you are being shot at all the time, but there are a few instances when you can receive damage without this effect, like melee or fire damage. 1 extra second that is added to your armor recovery from this effect is always equal to 1, because it can not be affected by armor recovery skills. This is why having 25% armor recovery bonus will improve your armor recovery to ((3 * 0.75) + 1 = 3.15) seconds, insead of expected (4 * 0.75 = 3) seconds, when you get shot at. This means that even if your armor recovery bonus was something like 999999%, your armor recovery after being shot would still be 1.00001 seconds long.
New resistance effect that you gain from Yakuza will now reduce this supression effect timer to always be 0.5 seconds instead of 1 second, and will also remove armor recovery timer reset if you got shot at, but did not take any damage, making both swat turret vans and random nearby shots completely irrelevant for your armor recovery.


### Additional info/tips
Gameplay overall is about the same - shoot, duck to cover to recover, shoot. Gained buffs will imrpove this aspect by allowing you to to this faster and more often, while damage resist from behind and additional movement speed will allow you to relocate easier. 

### Build(s) to try
Barebone skills - ICTV armor, frenzy aced for improved damage resistance, especialy from behind, armor recovery skills, and bullseye for armor gating.  

Build 1 - Duck and Sniper https://pd2builder.netlify.app/?s=09002V00cP10-91010-411I&p=b&a=6&t=6&d=3  
Pay close attention to your armor status and duck from and into cover depending on your current armor status. Since your armor regeneration time is extremely quick you can have extremely high out of cover uptime. Also don't be afraid of running away, since your damage resistance to enemies behind you is extremely high. Use molotovs to bring your health as close to 0 as possible to speed up your armor recovery, after you have interacted with a Doctor Bag. Use melee against bulldozers.   
Weapons to use:  
450 or 250 damage class assault rifle. You can use an AP kit on those rifles, allowing you to avoid getting shock and awe, and getting extra 6 skill points, that you probably should invest in melee or survivability skills. Use a 250 secondary SMG in single fire to gain benefits from sharpshooter sub tree skills, you may also sometimes switch to full auto fire mode to deal with bulldozers, but melee should be prefered against them at all times. Use molotovs to bring your health down, and use a 75 damage class melee for bulldozers.

# Ex-president (4/5):

|  | Updated cards - 5, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Ex-president_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Ex-president.png)  |

### Changes Summary
- Card 5: Replaced 15 passive dodge chance (10 in vanilla is a typo, it's actually 15) with new "Static" dodge chance, which can not be adjusted by any skills or armors (yes, ICTV has 20 dodge). This dodge chance allows for all armors to gain extra survivability equally, since you will always trade amount of stored health, which is more important now, for armor. This does bring the 2 Piece suit down, since you can't get 30 passive 40 running dodge anymore, but this is a small price to pay, in my opinion, considering that this version makes literally every other armor usable, depening on your build.  
- Card 7: Added "shield" or "abosrption" mechanic for stored health to imrpove survivability by making stored health take damage first, before your actual health. This allows for low health situations to be less frustrating, since now after your armor is destroyed, even if you were to take damage to your health, stored health will be depleted first instead. Also while at full health you can also get benefits from stored health after your armor breaks.  
- Card 9: To compensate 2 features mentioned above, which generally imrpove your survivability, 9th perk deck card was somewhat nerfed. Vanilla version increases your armor recovery timer's depletion rate by a certain %. So if your timer is at 4 seconds, depending on your armor, this recovery timer may end up being 0.28-1 seconds long after a kill. Despite how good this is, there is 1 issue however: this only applies if your armor is completely broken. New version of this skill is much more reliable since it now applies the bonus to armor recovery until your armor fully recovers, and it's now affected by both your teammates' and your kills. The numbers themselves however are much less powerful than vanilla. The biggest bonus per kill you can get now is -0.25 seconds, and the bonus will also only apply to the armor recovery part of the skill, without altering the armor suppresion 1 second delay, and also having a ceiling to it's bonus of lowest possible recovery timer at 0.8 seconds. But allowing this effect to also be imrpoved by other players' kills this makes it fit better with the other passive aspects of this perk.

This perk is mostly buffed, but still feels pretty balanced, while being much easier to run, since you don't have to run an explosive shotgun to break your armor to heal yourself anymore. Most armors also have new stored health amounts now, which are balanced around DS difficulty and how many 225 hits you can take there while at maxed amount of stored health (based around 2 skills - 10% dmg resist from any source, and Partners in Crime's 30% health boost).

### Additional info/tips
Gameplay is about the same as in vanilla, and can be even more passive now, since you can get armor recovery bonuses from teammates. Damaging yourself with explosives to heal might still be a decent idea in some cases, but relying on it, in my opinion, is not needed at all anymore.

### Build(s) to try
Barebone skills - Bullseye is the only mandatory skill, as this deck has one of the highest variety options, just keep in mind that you can't play agresively with this perk unless your stored health is high/maxed out, since you are vulnerable if you don't have any of it. High dps builds can help you gain this stored health, while high survivability builds can rely on teammates' kills for survival, while providing them with support options like breaching charges, drill skills, ammo etc.

Build 1 (By [Razer125](https://steamcommunity.com/profiles/76561199376033342/)) - Crit Sniper https://pd2builder.netlify.app/?s=1GgFgF00940-9030l0-41d0&p=c&a=1&t=4&d=3  
This build has 7 spare points which you can use to either improve your converted cops with more skills, give yourself minor melee/stability/ammo pick up range buffs, or you can use them to ace low blow and allow yourself to build weapons with a total goal of <25 total detection. Otherwise, keep total detection <5.  
Weapons to use:  
1600 damage class sniper rifle, and any secondary of your choice. Flashbangs or zapper grenades, depending on heist length. Any melee of your choice, but if you mainly use it against Bulldozers, use the 75 damage class.

Build 2 - Crittin' slinger https://pd2builder.netlify.app/?s=09090-4o50-90301S0R0300&p=c&a=1&t=2&d=3  
Silenced pistols that practically have infinite ammo and solid dps. Need i say more?  
Weapons to use:  
Silenced akimbo semi automatic pistols, preferably <=78 damage class. Focus on accuracy and concealment, since pistol recoil overall is decently easy to control. Use a secondary full auto pistol to deal with bulldozers, since this is your best DPS option. Use any throwable you prefer, but default greanades fit the best, to deal with huge squads, especially shield squads. Any concealed melee of your choice. Keep total detection <25.


# Maniac (4/5):

|  | Updated cards - 1, 5, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Maniac_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Maniac.png)  |

### Changes Summary
Replaced vanilla's dual timer set up (one from "stacks on damage gain" and another from "stacks depletion") for a new, more "Maniac" style requirement to keep the damage up. Instead of depleting stacks passively (because you get bored or something?) you will now start to deplete your stacks if you havent seen any action for a while (aka did not deal damage in the last x seconds). Amount of dealt damage to keep the stacks from depleting is irrelevant, so DOT (damage over time) effects are favoured. This also makes upkeep of the max bonus easier, since you just need to shoot something once every few seconds, which shouldn't be too hard. This is balanced by making this timer short (at 3 seconds now). Depletion rate was also increased to compensate ease of upkeep (as in amount of stacks lost per minute compared to vanilla).  
In addition to this change, while playing on DS you can now get 72 damage aborption total on yourself at max stacks. This allows for a much easier 3 tap armor, and even more if combined with Crew Chief or other damage resistance skills.

### Additional info/tips
Poison and other DOT effects are favoured heavily if you want to keep your stacks at max with ease. Do keep in mind that poison is really ammo hungry when making your builds.

### Build(s) to try
Barebone skills - ICTV armor and frenzy aced. With this set up you can maintain 3 tap armor on DS difficulty at max Hysteria stacks. If you play bellow DS difficulty frenzy is not required.

Build 1 (By [Razer125](https://steamcommunity.com/profiles/76561199376033342/)) - Gas Overload https://pd2builder.netlify.app/?s=10-4h00oB1Q380-610-61sz&p=d&a=6&t=j&d=03  
Gas spam. You will cycle your Viper grenades, underbbarrel gas, and secondary grenade launcher with gas. This is the ultimate war crime build, and it wasn't even specifically made because it's funny, but because gas grenades have extremely low ammo pick up, so even with this set up, it could still be a challege to keep at least 1 gas cloud afloat. And you want to keep it up, to maintain maxed maniac stacks indefinetely. Use primary AR to land kills on stunned enemies with easy headshots.  
Weapons to use:  
Specifically little friend 7.62 assault rifle with gas grenades for the underbarrel. Can be replaced by Groza AR with gas underbarrel, but it's a worse option. Use any secondary grenade launcher with gas grenades. Use viper grenade throwable. Cycle those 3. Use 75 melee against bulldozers.

Build 2 - Engineer is engi-here. https://pd2builder.netlify.app/?s=010010006Fh40Z0-610-5g11I&p=d&a=6&t=b&d=70   
Keep your little friends near chokes for free and constant damage, helping you upkeep your Hysteria stacks. Rely on your sentries to shut down shields, and don't forget to refill/repair them. Use melee against any enemy, but do focus on bulldozers.  
Weapons to use:  
Akimbo SMG's or Pistols with lowest total ammo and highest ammo pick up ratio. Secondary pistol with high accuracy and same ratio of total ammo to pick up ratio. The reason you would want to use such weapons, is the fact that sentry guns cost a certain % amount of your total ammo whenever they are deployed. If you use a weapon with low total ammo and high ammo pick up, you would be able to refill one sentry gun equivalent of ammo from much less dropped ammo boxes. Weapons that i prefer: Akimbo bernetti auto pistols and the HOLT 9mm pistol. Any 35+ damage class melee of your choice.

# Anarchist (3/5):

|  | Updated cards - 1, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Anarchist_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Anarchist.png)  |

### Changes Summary
There are only 2 important changes:
1) Armor gating is now achieved easier if you run high end armors instead of low end armors, since bigger armor has shortest time in-between regeneration
2) Chosen armor affects amount and cooldown of the "armor regen on enemy hit" effect from the 9th perk card, and similarly to the first effect it has shorter cooldowns for higher armors

Basically all armors are now flipped. This is a side grade to vanilla version of anarchist, since you can get more armor gating from ICTV than what vanilla anarchist suit allows, but at the same time you can not build crits+zerk set ups anymore, while also slowing you down (movement wise) since you would want to run heavier armor for best armor gating. ICTV is even more braindead on DS in terms of survivability sometimes than vanilla's suit, but the fact that it will take you 3x more time to run to cover if you are caught out in the open compensates itself already.  
Since changes above are mostly focused at DS difficulty where armor gating is important, another small change was made for lower end armors, which favours lower difficulties. Your total amount of armor gain per minute is higher with lower end armors like the suit. This is true for both passive and on-damage effect. So if you prefered to run ICTV anarchist in vanilla on lower difficulties, you can now go for something like a HBV or a suit, to gain movement speed and about the same armor gain per minute.

### Build(s) to try
Barebone skills - Bullseye, and even that one is a maybe, since you don't HAVE to have it to gain armor gating.   
Need this that and that

Build 1 - Heavy weapons guy https://pd2builder.netlify.app/?s=010012006F1Q0-41Y0010-778&p=e&a=6&t=6&d=0  
While bipoded and hitting headshots you can maintain your armor up for a long time, since your damage taken to armor recovered is so heavily tilted in your favour. Aim at around chest are of enemies to deal increased damage from body exertise on bodyshots, and to regain armor on headshots. Since LMG accuracy, even while bipoded, is not grea, you will be able to gain benefits from both skills reliably, on top of having the best passive armor gating from new ICTV anarchist.  
Weapons to use:  
Any bipod'able LMG as primary, and a secondary grenade launcher, preferably with area denial grenades like fire or gas, but default can also work. Rocket launcher secondaries also work. Use any throwable you want, molotovs are best option to activate berserker on yourself, or to bring your health down to the 50% threshold. If you use molotovs, using gas nades in your secondary launcher is a great idea to help with teammate revives.

# Biker (3/5):

|  | Updated cards - 1, 3, 5, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Biker_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Biker.png)  |

### Changes Summary
Added a little bit of armor and health to improve passive survivability and allow for 2 tap armor by default on DS.  
Functionality of the core of the deck is unchanged, "Stack of Regeneration" is a term that i invented for the healing effect you get and the newly re-written description describes how the perk actually works on the back-end, to give players who wish to optimize thier playstyle more information. On top of standard functionality, you will no longer be able to receive, a.k.a. waste, stacks of regeneration while af full armor and health. For the same reason "Overstack Prevention" cooldown was added. While this extremely short cooldown is active, any incoming biker specific heals will be ignored, if you have any amount of armor left. This effect does not affect your total possible amount of healing per minute, since it also gets reduced by 5th and 9th cards, where standard stack of regeneration cooldown is noramly reduced. It's also completely ignored while you have no armor remaining, allowing for as much armor gating as possible. This was added, mostly, to avoid situations where a teammate of yours (or maybe even you) uses a grenade/rocket launcher or a sniper with graze gaining a big multikill on the other side of the map, activating 4 healing cooldowns for you for next ~4 seconds, practically disabling your perk deck untill your cooldowns are done.  
Overall these changes were made to make this deck much more consistent, and it no longer requires infoHUD's of any sort to track your stacks to survive, since you almost always will have stack slots to gain regeneration from.

### Build(s) to try
Barebone skills - ICTV armor is favoured and allows for 2 tap on DS, bullseye for armor gating, and not much else.  

Build 1 - Jack of All Trades https://pd2builder.netlify.app/?s=wb4b50004H1k1a0-610-5g100&p=f&a=6&t=h&d=03  
The ultimate "i don't want to think" or "Generalist" build, which will work in any situation on almost any heist. Avoid maps with big open spaces like Heat Street and Bomb:Forest, but most other maps are fine. Your survivability is relying on your teammates' kills as well as your own, allowing you to armor gate from this perk even when there are no enemies within your view, and also having decent health regen. Using double deployables allows you to be prepared for any team setup and any heist, while fully loaded allows you to use any weapon you want. Swan song can be replaced with bloodthirst to help against bulldozers, but as long as you are using 250 or 450 damage class weapons, bulldozers won't be a huge threat for you, allowing you to mostly use melee against standard units.   
Weapons to use:  
Any weapons you want. 450/250 Assault rifle as a primary is most likely going to fit best due to their DPS and versatility. Akimbo weapons not recommended due to low total ammo amount, which leads to bad ammo bag efficiency. Any melee you want, i myself prefer 35 damage class. Pick your grenades depending on your team's setup, you may need help with crowd control, revives, area denial or just standard explosives for damage. Do not use throwable axes/knives/cards because fully loaded aced allows for effective ammo pick up for explosive throwables.

# Kingpin (0/5):

### Changes Summary
Same as with armorer, this deck is here to let you know that it has no changes. Descriptions were updated for card #1 and #9 to fix incorrect values and let you know that kills refill 1 second for the cooldown.

### Build(s) to try
Barebone skills - Bullseye for armor gating and to bring yourself over the 50% threshold easier. Passive healing from hostage taker could be helpful for lower difficulties, since self healing from damage taken is lower due to lowered damage, compared to DS difficulty.  

Build 1 - Survivalist https://pd2builder.netlify.app/?s=xk0p1000ch0-90101G000pf0&p=g&a=3&t=g&d=5  
Fairly standard kingping gameplay, with unseen strike being your main DPS skill. Since you can force enemies to damage you, while being semi-invulnerable you can activate the damage activation part of the skill, then go to cover for 6 seconds, activate crit boosts, and go on a kill spree to recover your injector. Repeat this cycle endlessly.  
Weapons to use:  
Primary focused on accuracy, secondary focused on DPS or shield AP. Kobus 90 with AP ammunition attachment is a solid option. Any 75 melee to deal with bulldozers, or a 35 melee if either of your weapons has shield AP, to compensate lower ammo pick ups with more melee kills.

# Sicario (1/5):

| Vanilla (1st card) | Gilza (1st card) |
| -------- | -------- |
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Sicario_vanilla.png) | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Sicario.png) |

### Changes Summary
Smokebomb cooldown was reduced from 60 to 45 seconds, since this perk deck is alright.

### Additional info/tips
Do not equip new revitalized skill from tier 4 artfull dodge subtree since it doesn't do anything when you have sicario.

### Build(s) to try
Barebone skills - Since sicario's dodge has extra RNG involved, you should try to rely on your health a bit more, so hostage taker and/or First Aid Kits are solid options. Use bullseye for armor gating as always, and never equip revitalized, because this skill effectively does nothing for sicario.

Build 1 - Supportive Smokey Sniper https://pd2builder.netlify.app/?s=5O5g0V008110-7102h14000h00&p=h&a=0&t=e&d=5  
Use your smoke to help with revives, objectives, or if you feel like situation is threatening enough. Insider assets is a great supportive skill, even if it's not viable on every heist. Aced swan song allows for both clutch moments and great damage bursts. Stockholm syndrome will elavate your survivability if your team did not bring enough doctor bags, and will allow for some additional crowd control if your stacks are high enough.   
Weapons to use:  
Any sniper rifles you prefer, 1600 are perfect for graze due to their breakpoints, but 950 lever actions have one of the best total damage outputs if you only reload them while empty, while using body economy skill. Secondary should be a sniper as well, preferably the North Star, as it allows for best DPS bursts against bulldozers.

# Stoic (2/5):

|  | Updated cards - 1, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Stoic_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Stoic.png)  |

### Changes Summary
Most of the changes are numerical, for the most part reducing effectivness of this perk deck slighlty, specifically for the first card. (Main reason - COPYCAT, second reason - this deck is a bit too good)
- Card 1: Changed direct and indirect damage split from 75% to 70% to increase incoming damage taken. Reduced DOT part of the damage split to 10 seconds from 11.2 (12 is vanilla's inaccuracy) to make DOT go down faster, dealing more damage.
- Card 7: Cooldown gain while at low health reduced from 2 to 1.5 seconds to compensate new threshold of 45%. This skill should now activate much more often, improving survivability as compensation for the nerfs in the first perk card.
- Card 9: Similarly to card 7, this is a compensation for the first card, to make healing slighlty better, since you now take more direct damage, and DOT damage you get is drained faster.

Overall this deck should feel about the same, but you may wanna play it slighlty more carefuly, since you take a bit more damage now.

### Build(s) to try
Barebone skills - First aid kits fit this perk deck the best, so you should almsot always run them. Hostage taker and partners in crime also benefit this deck extremely well.  
Need this that and that

Build 1 - Meta Slave https://pd2builder.netlify.app/?s=0R0H00xk1400380-6305g000100&p=i&a=3&t=c&d=53  
Gilza's revision of classic stoic izhma build.  
Weapons to use:  
155 primary shotgun and a 325 secondary shotgun. Use flechette on the secondary shotgun to deal with snipers. Use tazer or a 35 damage class melee. Secondary deployable can be switched out to anything current heist/lobby requires most. Keep your total detection <25.

# Tag Team (2/5):

|  | Updated cards - 1, 5 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Tag_Team_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Tag_Team.png)  |

### Changes Summary
Removed LOS (line of sight) requirement to the target. Increased amount that the timer is increased by per kill, to keep the effect going for longer easier. Increased max possible damage abosrption, and reduced required amount of kills to get it, to imrpove survivability.  
This deck's main issue is how expensive it is to run well (skill points wise), even though it does work pretty well when it's set up, so not that many changes were needed.

### Build(s) to try
Barebone skills - Bullseye for armor gating, ICTV armor to gain benefits from damage absorption, health buffs from partners in crime, and preferably hostage taker for additional passive regen, if your team doesn't have great DPS.

Build 1 - Shotgun Survivalist https://pd2builder.netlify.app/?s=1G1W00xk6F10-910-6100&p=j&a=6&t=f&d=3  
Fairly simple build, take converts to gain health improvements, and then tag your teammates (preferably human players) to improve your survivability with abosrption and constant health regen.  
Weapons to use:  
Use any shotgun you want as primary, preferably with AP slugs, and if you feel like being supportive you can use breaching rounds with pump action (450 dmg class) shotguns, which allow for shield AP as well. Secondary shotguns focused on DPS are prefered. Use any melee of your choice, zapper would probably work best, if you are confident in your team's abilities of dealing with bulldozers.

# Hacker (2/5):

|  | Updated cards - 1, 5, 7 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Hacker_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Hacker.png)  |

### Changes Summary
Nerfed ECM cooldown to 140 seconds, nerfing it for both stealth and loud.  
Cooldown gain per kill reduced from 6 to 4 seconds. ECM duration in loud increased to 12 seconds to compensate much longer breaks in between uses. Healing gained per kill was increased to compensate longer intervals in-between activations. Temporary dodge now requires 3 kills, and provides the same dodge bonus, but for longer to compensate breaks between uses.  
This perk deck is simply too good, and the main reason for that is just the ECM stun effect. Making ECMs activate less often allows for stun spammibility of this deck to go down, while keeping player survivability at roughly the same level.

### Build(s) to try
Barebone skills - get additional dodge and bulseye for armor gating, rest is up to you.

Build 1 - Default https://pd2builder.netlify.app/?s=1G091400d010-9qBhI000100&p=k&a=0&t=d&d=3  
Keep total detection <5. Use PECM whenever you are either low on health, your temporary dodge is no longer acitve, or when you feel like you are in danger, but don't activate it as frequenty as you would in vanilla, since cooldown is longer.  
Weapons to use:  
Any weapons that benefit from crits (a.k.a. guns with low damage with high rate of fire) and can get you to bellow 5 total detection work great. You can also use bows or crossbows, since they all have useful new breakpoints with crits. If you plan on using bows/crossbows, don't forget to bring additional weapon to deal with snipers. You can also utilize grenade launchers with default explosives, for ease of activation of temporary dodge and healing during the PECM effect. You will most likely struggle getting <5 detection with grenade launchers, but 1-2% sacrifice of dodge may be worth the multi-kill potential of GL's.


# Leech (5/5):

|  | Updated cards - 1, 3, 5, 7, 9 |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Leech_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Leech.png)  |

### Changes Summary
Moved to Support category.  
Probably the furthest from vanilla rework of any deck. Vanilla leech simply has too many things going for it. Is it supposed to be a kingpin replacment with activatable semi god mode? Is it supposed to be a support healing deck like gambler? Is it supposed to be a clutch deck that allows you to pick yourself up and carry your team to victory? This deck simply has too many aspects to make it make sense, while also being both overpowered and braindead easy to use if you combine it with mult-kill weapons like rocket launchers or graze sniper rifles.  
This rework is my atttempt to make this perk deck fulfill more of a supportive role, while keeping most aspects of this deck. But also changing them somewhat significantly.
- Card 1: Increased cooldown from 40 to 80 seconds. Reduced amount of divisible health segments from 5 to 4. Reduced threshold for damage that is required to deplete 2 segments from 200 to 150. Whenever you go down your cooldown will be forced to at least 25 seconds, to prevent you from immedieately reviving yourself to reduce potential clutch moments when deck is maxed at 9/9 cards and to also punish you for not using the cooldown (this actualy makes new buffed Messiah really good with Leech, allowing you to imrpove your cooldown while downed easier). Removed teammate heal on damage taken. Removed invulerability and heal after 2 kills. Replaced both previosuly mentioned removed mechanics with a new one which combines prevous two in a new way. After taking damage you lose 1-2 health segments and then get invulnerability for a short period. Securing a kill during this period can recover 1 health segement and recover health for your teammates. Added new supprotive feature: if you revive a teammate while the Amuple effect is active, when Ampule effect is over you will get healed automatically, to imrpove your survivability. The 25% team heal reduction you have with other Leech players on your team is a vanilla feature that is normaly not mentioned in the description.
- Card 3: Made the last stand mechanic more similar to the Swan Song effect, which does not allow you to heal or use FAK Uppers skill, since this threshold is much harder to get to now, so you need to be punished more if you ever get to it. If you revive a teammate you won't go down after Ampule effect ends even if you were at 0 health, to imrpove the new supportive nature of this deck.
- Card 5: Increased cooldown gain per kill from 1 to 1.5 seconds to compensate longer cooldown. This doesnt fully compensate the cooldown since new cooldown is 2x the vanilla, and the reason for that is new cooldown reduction in card 7.
- Card 7: Reviving teammates reduces Ampule cooldown by 15 seconds. Being revived does the same, to make effective cooldown punishment from going down only 10 seconds long.
- Card 9: Removed 60% health bonus to remove 2 tap health on DS while Ampule effect is not active, to reduce overall survivability. While ampule effect is active max possible amount of segments is now 5 (instead of 10), and amount of healing while getting kills in the invulnerable state is now doubled at 2 segments. This allows you to reliably heal yourself while effect is active on lower difficulties, since you will mostly be taking 1 segment worth of damage, while also allowing you to have a semi god mode on DS difficulty, since you mostly will be both losing and gaining 2 segments. This is still a semi god mode, because you only have a short time period (currently 1 second) to get a kill to recover your health. Heal amount on teammates is increased even more since you will trigger this healing effect less often than vanilla Leech can.

### Additional info/tips
Please, please, please use Painkillers skill on higher difficulties. Bonuses that you get from teammate revives are not incredibly strong, while letting your teammates go down again because they are in a vulnerable position and you don't have this skill is both foolish and not nice. This is a general tip for using Inspire skill, but it applies to this new version of Leech the most.

### Build(s) to try
Barebone skills - You can use FAK's without using hostage taker to heal, or use hostage taker with any other deployable for passive healing. Investing into armor is not recommended since your health bonuses provide big enough bonuses already. Go for mid tier armors, aiming for 70 armor on DS difficutly. Messiah, at least basic, is favoured heavily since it's extremely effective at shortening cooldown while downed. Up you go aced also helps with healing after you go down really well.

Build 1 - Standard - shotgun focused. https://pd2builder.netlify.app/?s=1G0H00xkc10-9010-6H00&p=l&a=3&t=i&d=3  
As always, focus on reviving your team to get your cooldown up. Heals from activation of the ampule and passive regen from hostage taker should be enough sustain. Use Messiah's basic feature of being able to never fully go down to get your cooldown back, or activate it if you need to clutch the situation you are currently in.   
Weapons to use:  
450 or 325 damage class primary shotgun, focused on dealing with multiple enemies, so Donald's Horizontal Leveller is recommended, along with default ammo, focused on stability. Using 450 damage class priamry with breacing rounds can also be considered on some heists. 325 damage class secondary shotgun, focusing on mostly accuracy and DPS (so bigger ROF ones), to deal with snipers and bulldozers. Use slugs if shields are a big problem for you, but i'd recommend using Flechette ammo. Use any melee you prefer. 

# CUSTOM PERK - Brawler:

| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Brawler.png)  |
| -------- |

### Summary
A perk deck focused on melee weapons and team "protection". You are supposed to be your team's meat shield, taking all the damage that you can, while being extremely limited with your weapon choices/usage, and being most efficient with melee weapons both in terms of damage and survivability bonuses.

### Additional info/tips
Focus on melee and survivability skills the most. Do not assume that you have god mode, even if you currently have maxed bonuses. Use a sniper or a similar weapons to deal with snipers/shileds, while running saw and melee as your primary weapons.

### Build(s) to try
Barebone skills - ICTV armor, bullseye is not recommended at all, since passive armor gating you get from melee kills should be enough, but you might have to get it just to unlock ICTV. Frenzy aced is favoured heavily due to low health bonuses of the deck. Melee skills are heavily favoured. Counterstrike is effective to deal with bulldozers, allowing you to stun them just with the basic version. Backfire aced is somewhat required since tazers can screw you over badly. Saw is favoured as well, since it maintains it's ammo pick up, ignoring the ammo pick up debuff that brawler comes with.  

Build 1 - Default https://pd2builder.netlify.app/?s=09090001sz380-8580-421aN&a=6&t=b&d=3  
Relatively close to perfect build with this deck. Take agro from your enemies, deal massive melee damage, use converted cop as an addtional ancor for your defensive bonuses, use counterstrike against cloakers and to stun bulldozers, or even use it as a bonus damage option, if you run melees with less then 50 damage.  
Weapons to use:  
Any 100 accuracy primary that can deal with snields and snipers. So a sniper rifle most likely. Thanatos is probably the best option, to help you shutdown bulldozers, after their face shield plate is gone. Secondary saw is your primary weapon, since it has identicall stats to primary saw. If range is not a problem (on heists like No mercy) you can try double saw setup. Use throwable knifes/axes/cards for close-mid range kills, mostly to proc first regeneration effect. Use 50 or 75 damage class melee weapons for reliable one-shots, or a chainsaw type weapon. You can also use lower damage class melees if you don't mind holding the charge button a bit, or if you want to rely on counterstrike's bonus damage.

Build 2 (By [Razer125](https://steamcommunity.com/profiles/76561199376033342/)) - Cursed Sentry build https://pd2builder.netlify.app/?s=100b0001cN000R0-610-616F&a=6&t=4&d=6  
This build is only cursed in a sense that sentry guns will always take a % of your weapons' total ammo capacity, which brawler already reduces, leading to a situation where literally every weapon now qualifies for the "low total ammo capacity" requirement that sentry builds usualy require. Now you just need to pick weapons with best ammo pick up rates, and you are good to go. Sentries don't really help you that much, ouside of pierceing shields, but they are a solid additional distraction, which helps the theme of the perk of being a meat shield and/or a distractor. Use remaining 1 skill point as you see fit.  
Weapons to use:  
Lowest damage class akimbo pistols for primary and shotgun secondary with dragon's breath ammo for shields. Chainsaw type melee.

# CUSTOM PERK - Speed Junkie:

| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Speed_Junkie.png) |
| -------- |

### Summary
Speed is your life.  
Moving provides you with points to a meter which provides bonuses to dodge, weapon swap speed, weapon reload speed and interaction speeds. Kills fill up this meter as well, and also recover your stamina. You trade almost all of your health for armor, and you gain a little bit of armor when you dodge once a second. More damaged your armor is - more movement speed you get.

### Additional info/tips
One of a few (if not the only) perk deck that actually gets use out of the Running from Death skill. Adrenaline spike is an RNG based temporary effect that gives you practical god mode and increased kill potential, but keep in mind that once it's over you are screwed if you are not in cover. This is the ultimate run and gun perk deck, but it has a flaw - you can't really use text chat since you cant move and use chat, and not moving with this deck is a death sentence.

### Build(s) to try
Barebone skills - Bullseye for armor gating and dodge skills.  

Build 1 - Default (DS difficutly specific) https://pd2builder.netlify.app/?s=xa0-6d0-7h2002l1u0005zc&a=0&t=4&d=3  
Run and gun. Use grenades mostly for revives. Mark special units before melting them. Weapons with silencers can gain AP to make run and gun playstyle's natural inaccuracy from movement more forgiving. Keep total detection <25.   
Weapons to use:  
Any <=250 damage class fully automatic weapons with silencers. Primary should be focused on stability, and secondary on accuracy. Using shield AP is not recommended, since you can flank shields relatively easily. Use melee exclusively against bulldozers or in a pinch. Any melee that can fit the total detection requirement of <25 works. You can use either throwables like knifes/axes/cards to coserve ammo, or use flashbangs/zapper/insideairy nades for crowd control and to help with revives.

Build 2 - Default (Death Wish and bellow difficutlies) https://pd2builder.netlify.app/?s=xa0010009410-5j0003Q1m0005xc&a=1&t=b&d=3  
Run and gun. Use grenades mostly for revives. Weapons with silencers can gain AP to make run and gun playstyle's natural inaccuracy from movement more forgiving. Keep total detection <25. Similar to the build above, but since damage output on DW and below difficulties is not as drastic, you can sacrifice a little bit of DPS and 10% dodge, to get much more reliable armor and armor regen.   
Weapons to use:  
Any <=250 damage class fully automatic weapons with silencers. Primary should be focused on stability, and secondary on accuracy. Using shield AP is not recommended, since you can flank shields relatively easily. Use melee exclusively against bulldozers or in a pinch. Any melee that can fit the total detection requirement of <25 works. You can use either throwables like knifes/axes/cards to coserve ammo, or use flashbangs/zapper/insideairy nades for crowd control and to help with revives.

# CUSTOM PERK - Guardian:

| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Guardian.png) |
| -------- |

### Summary
Stand still to create an area. While inside of your area you (mostly) take less damage and quickly recover health. If you are outside of your area you take more damage and don't heal. Kills you get automatically pick up ammo boxes from killed enemies if you are inside of your area. However you have no armor and you are really slow. Sometimes you just can't have everything.

### Additional info/tips
This is the ultimate camper perk. Snipers and LMG's are favoured heavily, but do as you please. Your armor choice is irrelevant to your survival, but you should pick different armor based on the map that you play on - if you play on smaller sized maps, pick bigger armors to deal more free damage from the richochet "Porcupine" perk card. Never use the suit, since it's always worse than the Light Balistic Vest for this perk deck.

### Build(s) to try
Barebone skills - Partners in crime for bonus health is required. Hostage taker could help with armor regen, especially if you are not inside of your defensive area.

Build 1 - Sniper https://pd2builder.netlify.app/?s=094X2V00410-9010-6p00&a=1&t=b&d=3  
Perfect for utilizing the Vantage point purchasable asset.  
Weapons to use:  
Thanatos or any 1600 damage class sniper for graze as primary. Any secondary sniper you prefer. If you don't have thanatos, north star secondary sniper would be most helpful against bulldozers. Use throwable axes/knives/cards against enemies who got close to you. Use any melee you prefer, but tazer ones would work best.

Build 2 - LMG https://pd2builder.netlify.app/?s=0R0912005g0-61Y001000410350&a=1&t=2&d=5  
A less precise, suppressive fire alternative playstyle. Aim for the body to get the most amount of damage, and try to be as far away from enemies as possible, to gain the most from LMG's damage fall off changes, which make all LMG's deal more damage at further ranges. Use first aid kits to either heal up when your health drops too low while moving around, or just deploy one while already inside of your area for even eaiser health upkeep. Do take into account that FAK's now only heal you for 50% health.  
Weapons to use:  
Any LMG priamry of your choice. Any pistol as secondary, since you can sawp to and from them quickly, while having a reliable mid range weapon. Any decently high damage melee can be used against bulldozers in close quaters situations.

# COPYCAT (4/5):

|  | Updated cards - 1, 3, 5, 7, 9 (every single copy) |
| -------- | -------- |
|  Vanilla | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_first4_vanilla.png)  |
|  Gilza | ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_first4.png)  |

Info on all the 9th card replacements (including 3 new ones from custom perks) are further bellow.

### Changes Summary
Copycat overall is a really good deck, but amount of health you gain from it is simply too good. Gaining 2 tap health on DS with a 2 second invulerability by just having a joker is a bit too good, considering some options you can get from the 9th perk card copies, so some of the neutral aspects (non-copy parts) of the deck were nerfed.  
- Choose a boost for cards 1,3,5,7: Health bonus is reduced from 20% to 15%, to make 2 tap health builds on DS harder to get. Armor and dodge bonuses unchanged. Crouch and bag movement speed bonus was unchanged, but this bonus now also allows to carry more total ammo. This is a niche upgrade, but can be sometimes usefull, when you just simply don't need other upgrades.
- Card 1: Identical
- Card 3: Identical, but the heal bonus is different when using Bullseye skill. This was done in such a way because both of these skills share a cooldown in the code. It is possible to split these timers, but if i did so, all infoHUD's out there will be broken and display incorrect information. This way infoHUD's wont be broken and overall amount per minute is the same, even though you could agrue that this will lead to slighlty less healing since you can't always activate this skill after it's cooldown is over, but thats a small price to pay considering other buffs this perk got.
- Card 5: Identical
- Card 7: Updated the invulnerability effect to activate how you would assume it would activate in vanilla. In vanilla this skill can activate even if your armor is full, wasting the cooldown. Additionally, in vanilla, you can take enough damage for this skill to activate, but you would still go down because your health reached 0 before the skill was activated. Now there is a safety net for this effect, limiting you to just 1 health in such scenarios. To compensate slighlty, this cooldown was increased from 15 to 20 seconds.

### Additional info/tips
Focus on keeping your health above 50% threshold to be able to trigger the invulnerability effect. If you are running 9th copies that don't provide you with additional healing, do not get yourself more health, unless you are using Hostage Taker, because 3rd card always recovers a flat amount of health, and it would be easier to get to 50% threshold from this healing if your max health is not increased.

### Build(s) to try
Barebone skills - Always run bullseye for armor gating, rest is up to you.  

Build 1 - Brawler copy https://pd2builder.netlify.app/?s=1G000100811Q380-62h1i00g150&p=m&c=3-41&a=0&t=h&d=03  
A unique version of copycat that is not available in vanilla. Use Brawler's 9th copy (23/25), and stack all neutral "pick a boost" cards for dodge (3/4). You can use either Doctor bags or Ammo bags as your primary deployable since both are maxed out, but ammo is prefered, since this build doesnt't provide high damage bonuses. Brawler copy card will provide you with the best armor gating in the game, but you need to perfectly time a kill once every 6 seconds to gain this benefit, if you don't actively use melee. This benefit + dodge + health invulerability provides a relatively easy to play, but not the most powerfull playstyle.   
Weapons to use:  
200 damage class silenced Assault Rifle primary focused on accuracy and concealment, and a 200 damage class silenced SMG secondary focused on stability. Weapons with burst fire mode recommended. Any 20-35 damage class melee.

### 9th card copies
Replaced mimicking card's name to always be the name of the copied perk deck, instead of showing the name of the card from the perk deck you are copyng. On top of the fact that this is confusing because you simply can't know all of their names, they are also not always correct, because sometimes a mimicking 9th card can combine bonuses of multiple cards of a perk deck with multiple different names.  
In the same way, mini-icon from the perk deck you are copying will always be whatever the 9th card's icon of that perk is, instead of being based on whichever card of the perk deck you are copying, since this is the icon you normaly see in the invetory scren for selected perk deck.

### 9th copy - Crew Chief
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Crew_Chief.png) |
| -------- |
| This card now provides highest damage resistance of all 9th card copies while providing additonal minor buffs. |

### 9th copy - Muscle
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Muscle.png) |
| -------- |
| One of a few ways to easily get 2 tap health on DS for copycat. Passive health regeneration added for improved health upkeep, but total amount is lower than muscle itself. |

### 9th copy - Armorer
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Armorer.png) |
| -------- |
|  Similarly to vanilla anarchist 9th card copy now provides a damage invlunerability window, at a longer cooldown than the original perk. |

### 9th copy - Rogue
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Rogue.png) |
| -------- |
|  Dodge deck copy now provides dodge bonuses. Techically slighlty better than best in slot dodge in vanilla copycat, but it's fair since you can't get 2 tap health easily anymore. |

### 9th copy - Hitman
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Hitman.png) |
| -------- |
|  Now copies first 2 cards from reworked hitman. New recovery is higher, but is now temporary instead of fully passive. Stability penalty is identical, since vanilla's -16 is incorrect, and it's actualy -8. |

### 9th copy - Crook
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Crook.png) |
| -------- |
|  Crook's effects were indirectly buffed by artful dodger sub tree in ghost, so no new survival effects are needed. This is the only 9th copy card that provides imrpoved AP bonus. |

### 9th copy - Burglar
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Burglar.png) |
| -------- |
| Allows to run LBV with same dodge values as 2 Piece Suit, and allows to create low detection builds easier. Dodge removed, since this is not the key bonus of Burglar. |

### 9th copy - Infiltrator
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Infiltrator.png) |
| -------- |
| The is the only copy card that allows you to deal extra damage with melee weapons. Additional healing is on the stronger side compared to other healing copy cards, allowing for imrpoved sustain, at relatively low risk.  |

### 9th copy - Sociopath
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Sociopath.png) |
| -------- |
| Identicall to vanilla. |

### 9th copy - Gambler
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Gambler.png) |
| -------- |
| Copies first card of reworked gambler, while also providing the ammo share aspect of the perk, to make copy-gambler actually have some supportive capabilities for the team. |

### 9th copy - Grinder
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Grinder.png) |
| -------- |
| Strongest (potential) health regneration of all copy cards, so regen itself was unchanged. Health bonus removed to remove 2 tap health on DS. Weapons with DOT effects recommended. |

### 9th copy - Yakuza
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Yakuza.png) |
| -------- |
| All bonuses are now only active while bellow 50% health to imrpove survivability while bellow the invulnerability threshold, since this copy card does not provide any healing abilities to get to the 50% invulnerability requirement. |

### 9th copy - Ex-president
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Ex-president.png) |
| -------- |
| Identicall to vanilla, doesnt provide any rework related bonuses. Allows for 2 tap health on DS. |

### 9th copy - Maniac
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Maniac.png) |
| -------- |
| Similar to vanilla, since copies are for the same cards as vanilla - first and second. For explanation on why and how first card was reworked, go to maniac tab. Allows for 2 tap health on DS at ~40% stacks. |

### 9th copy - Anarchist
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Anarchist.png) |
| -------- |
| Vanilla cooldown is incorrect and is actually 45 seconds, so techically the cooldown is buffed. Armor gating is better for heavier armors because of the anarchist rework. |

### 9th copy - Biker
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Biker.png) |
| -------- |
| Copies only the first card, just like in vanilla. For details on first card updates go to the Biker tab, but as TLDR: it has more reliable armor gating now. |

### 9th copy - Kingpin
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Kingpin.png) |
| -------- |
| No changes - "1 second cooldown reduction per kill" added to descriptions, since that's how it already works in vanilla. |

### 9th copy - Sicario
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Sicario.png) |
| -------- |
| Copies first card like vanilla, so only change is to the smoke bomb cooldown: 60 to 45 seconds. |

### 9th copy - Stoic
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Stoic.png) |
| -------- |
| Copies the first card. First card in stoic was nerfed to make player take more damage, but with newley reworked invulnerability it is still one of the stongest options for copycat. |

### 9th copy - Tag Team
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Tag_Team.png) |
| -------- |
| Copies the first card. Same as vanilla with no LOS requirement and slighlty bigger effect duration increase per kill. One of the better healing options for copycat. |

### 9th copy - Hacker
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Hacker.png) |
| -------- |
| Copies the first card. Cooldown nerfs are applied. Stun effect is as powerfull as ever. |

### 9th copy - Leech
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Leech.png) |
| -------- |
| Copies the first rewoked card fully + gets the cooldown reduction of 15 seconds on teammate or self revive. Overall great option for semi god mode for difficulties bellow DS, and on DS should be used to either heal up in a pinch, or to revive a teammate while under affect to heal after effect is done. Keep in mind that if your health reaches 0 during the effect you will die, unlike fully upgraded Leech. |

### 9th copy - Brawler
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Brawler.png) |
| -------- |
| Best armor gating option if you use melee weapons, that does not provide any additional healing/sustain bonuses. If you don't use melee, having 1 stack of regeneration active is also decent, since it can armor gate much more often than anarchist, but it doesnt provide a damage invulnerability bonus. |

### 9th copy - Speed Junkie
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Speed_Junkie.png) |
| -------- |
| Highest amound of bous dodge you can get from copy cards, but it's near impossible to reach. |

### 9th copy - Guardian
| ![](https://raw.githubusercontent.com/irbizzelus/random-noncode-stuff/refs/heads/main/Gilza_pics/Perk_Images/Copycat_9_Guardian.png) |
| -------- |
| One of the strongest health healing options which doesnt provide 2 tap health, slows you down, and makes interactions slower. Good option for smaller sized maps. |
