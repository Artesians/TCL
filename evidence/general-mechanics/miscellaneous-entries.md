---
search: false
description: For entries that have little practical use.
---

# Miscellaneous Entries

**Main Page:**

{% page-ref page="../../general-mechanics/miscellaneous-entries.md" %}

## Ded Bird

**By:** Aluminum\#5462, Mcpie\#8672, mol\#3280, JenjenJL\#6582, Kgbeast\#6738, wiremash\#0433  
**Added:** 6/8/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/846170693783912448/851728679427244042/transcript-ded-bird.html)

**Finding:**  
Bird go poof.

At least two of the birds \(one near Azhdaha and one in Guyun\) die very often of drowning, usually before the player even sees them, though their death is also occasionally observed, and they may even sometimes survive.

**Evidence:**

* [Youtube Playlist](https://youtube.com/playlist?list=PLPByPR2TubV5m7ZW71wwTovzkpvBqQA5T) 
* [Best Example](https://cdn.discordapp.com/attachments/846170693783912448/850855100107718746/2021-06-05_22-53-14.mp4)

**Significance:**  
Free fowl. Also whoever is coding the animals is probably trolling.

## Chair Cancelling

**By:** Ayzel\#7399  
**Added:** 5/21/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/840459159656202250/845509708693635072/transcript-chair-cancelling.html)

**Finding:** For some characters, if they use an elemental skill and sit in a chair at the same time \(pressing F and E at the same time for PC users\), while the skill will not activate \(and as such the skill cooldown will not start\), the game will still "treat" the skill as if it activated, which causes effects like Crimson Witch 4-piece to stack.

**Evidence:** [https://youtu.be/6nwbxIwk3Q8](https://youtu.be/6nwbxIwk3Q8)

**Significance:** New theoretical highest DPS ceiling for some units who aren't able to typically stack CW \(like Hu Tao and Xiangling\).

## Electro Tanking

**By:** Aevean Leeow\#1362  
**Added:** 4/27/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/805911524051779615/837034685497606194/transcript-razorbeidouelectrotank.html)

**Theory:** In patch 1.2, Razor and Beidou are the two of the best choices for tanking Electro DMG from an enemy of ANY level, without damage reduction like the reduction provided by Xingqiu's Elemental Skill, with unlimited resources. However, Hu Tao beats them both.

**Evidence:**

Razor has 80% Electro RES and was originally considered to be the best Electro Tank. However, enemy level infinity calcs for each enemy revealed that Beidou was superior at level infinity. The main reason is that there is no good transferrable shield for Electro dmg, as well as the fact that RES caps at 140%. The best Electro shield is Beidou counter, and the best transferrable Electro shield is C1 Beidou, which is around half the size of Beidou counter.

Building Beidou as the tank/shielder in one allows for a much larger shield the more investments there are into HP, though she has less base DEF than razor. Thus, Beidou scales better with HP and Razor scales better with DEF. But due to the nature of the DEF formula, where the benefit of defense decreases with enemy level increases, HP outscales DEF, and thus Beidou should and does outscale Razor.

In order to calculate questions like: When does Beidou outscale Razor? Has Razor been outscaled from the very beginning? and What are the best artifacts/compositions to tank Electro DMG? a program coded in Turing \(available here: [https://pastebin.com/9ZHEnyCU](https://pastebin.com/9ZHEnyCU)\) was used.

**Results:**

For an arbitrary range of levels \(1-100\), assuming optimized builds without damage reduction \(DR\) against Electro damage in the overworld, Razor during his burst is tankier than Beidou holding counter.

For this terribly impractical range of levels, 1 to 100, Razor's best weapon would be whiteblind, a c1 max HP build Beidou for his shield, and an A2 Zhongli to boost his shield%. He would take Thundersoother and Bolide, with 3 DEF% mainstats, 15 HP substats, and 10 DEF substats, prioritizing %HP/DEF substat choice over flat HP/DEF.

In a less optimized setting, Razor benefits more than Beidou as his strongest point is the Electro RES%, which does not need to be built for. Beidou needs HP% to scale both herself and her shield. Thus, even if you totally failed artifact grinding and got a terrible mainstats for Razor like Atk%/Phys%/CR%/CDMG%, with little HP or DEF substats and instead unluckily rolled into Crit Rate or Crit Damage -- _definitely a really bad build in general_ -- Razor would still be tankier than Beidou. However, if the damage is spread out over time in smaller bursts, Beidou can mitigate the damage entirely with her counter more easily than Razor, though if Razor also has a shield he can do the same. If so, in this theoretical scenarios, healing from a support would be incredibly helpful. This is because in general, as long as your HP does not reach 0, regaining HP via healing will tend to make you live longer.

If DR is not banned, Beidou also has a large amount of DR, which scales very well with other sources of DR. In this case, stacking DR via Beidou/Xingqiu/Jean with C6 will eclipse traditional methods of tanking damage, as damage reduction can be stacked to 100%.

Note that these conclusions are accurate only to 1.2. In 1.3, Zhongli's new shield will be stronger than Beidou's C1 shield for Electro damage. In fact, Razor's EHP at enemy level infinity will be greater than Beidou's EHP at enemy level infinity, or vs reaction type or monster skill effect damage. Thus, it is predicted that in 1.3, Razor will be the BiS tank at all enemy levels from 1 to infinity. These predictions are indeed true as of 1.3. Note that at some point in 1.3, the 140% RES cap was removed, and Razor becomes even better.

Nevertheless, everyone in the game gets _absolutely smacked_ by C6 Hu Tao's 200% Elemental Resistance, which makes all of this math pointless.

**Signifiance:** The electro slimes will overtake us soon, and it's necessary to know how best to defend against them.

## Spawn Aura Tanking

**By:** Aevean Leeow\#1362  
**Added:** 05/01/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/804174551801921536/839374739973210122/transcript-spawn-aura-tanking.html)

**Theory:** To tank one hit from an enemy of ∞ level in overworld, without damage reduction eg XQ, certain comps/etc will excel for each damage type.

**Evidence:** Damage reduction from DEF is DEF/\(DEF + 5 _enemyLevel + 500\). This is 0 when enemyLevel = ∞. Thus DEF is negligible and the 'Tank' builds for shield%, RES%, and HP. Viable artifacts are 2-4Miracle, 2Bolide, and 2TS/2LW. Choices have tradeoffs \(eg Miracle is 4_ and thus trades HP for RES\). Shield characters simply max shield scaling stats.

Zhong A2 +25% shield. A4 Diona decreases the enemy atk by 10%, multiplying effective HP by 10/9. C4 Ning +10% element RES. However, Zhong+Ning lose 15% RES from Canopy, meaning only one should be run. Diona, the 2nd best transferable raw Shield behind Zhong, can run Ning, and is superior when element RES% is limited \(dendro\). Pyro/Cryo run Xinyan/Diona due to 2.5x bonus on their shield.

Razor has +80% RES but his BiS Shield C1 Beidou is small, and RES caps at 140%. Thus Beidou is BiS Electro Tank/Shield.

Each viable combination of artis/comp/etc is compared to find these conclusions in this [spreadsheet](https://docs.google.com/spreadsheets/d/1KZicv_Ww7VQKyhl1uvtxJTT0x3Gb-WPOYAxjD3yaUMY/edit#gid=477783156).

**Significance:** Why of course, this is incredibly significant and changes everything. In terms of things to build, Diona is a BiS char on every comp. Electro is the cheapest, as Beidou is both Tank and Shield, but is the most specialized. In general, Jean/Summit Shaper is used in 7/8 comps, while Zhong is used in 5/8 comps.

More Significance to these already earth-shattering, mind-bending calculations, due to the discovery of spawning aura mechanics. Essentially, they ignore Damage Reduction and DEF, which is identical in execution to the previously hypothesized enemies that ignore DR and have a level of infinity, rendering DEF useless. For this reason, atk% debuffs on enemies will also be ignored in calculations. This introduces slightly more practicality to these calculations, though the practicality of this work has already approached infinity so it makes little difference.

Thus, the question posed is no longer how much damage can you tank from a lv infinity enemy without DR. It is, how much damage can you tank from a spawning aura in one hit?

In the first half of the 1.3 update, the Geo rework meant that geo shields would become stronger for non-Geo elements, and weaker against Geo. The implications of this were that while Geo tanking ability became noticably worse, some other elements benefitted greatly. Thanks to Zhongli's new shield totally eclipsing Beidou's C1 shield, Razor became the best Electro tank by far. Due to the new nonspecificity of Geo shields, Geo joined the Hydro and Anemo group, being 72.36% of its former self. In the second half of the 1.3 update, the release of Hu Tao means that her C6 immunity to getting oneshot must also be banned, as it allows her to tank any single hit. However, her state afterwards where she gains +200% RES means she powercreeps every single other tank. Note that the RES cap seems to have been removed, though it is unclear whether it was during Xiao or Hu Tao banner's time period. Furthermore, Hu Tao also has the highest base HP in the game, though this is less significant than her C6 providing +200% RES.

Note that as a result, Electro is no longer the undisputed king of the element you can tank the most of a single hit from a spawning aura. Pyro is now 1st, with Cryo a bit behind at 2nd, with Electro at 3rd. The other placements relative to each other remain unchanged. Hu Tao's excessive amount of RES means that she faces diminishing returns on RES. Pyro has the advantage of having a dedicated non Zhongli shield \(Xinyan\), and so does Cryo, with a bigger shield \(Diona\) as well. Both Electro and Pyro also enjoy their 2set which confers 40% RES. Though Pyro does not have the largest shield, its 40% RES 2set allows it to slightly pull ahead of Cryo, and Cryo is more significantly ahead of Electro. A larger gap also exists between Electro and the rest, due to Electro's 40% RES 2set. Also note that Dendro and Physical have been massively buffed, as it was difficult to acquire RES% for them. Hu Tao has significantly closed the previous gap between these two elements and the rest due to her universal 200% RES buff. Previously, the only source of PHYS RES% was the Protective Canopy Resonance, and the only source of Dendro RES was the Protective Canopy Resonance as well as the Tiny Miracle artifact set.

If MHY told you to pick an damage type to tank the most damage from a level ∞ enemy without damage reduction, the tier list is Pyro &gt; Cryo &gt; Electro &gt; Geo = Hydro = Anemo &gt; Dendro &gt; Physical.

## Climbing the Frostbearing Tree

**By:** Aevean Leeow\#1362  
**Added:** 03/23/2021

**Theory:** Without using any elemental skills/bursts, the glider, or characters/weapons not freely available to every account, is it possible to climb to the peak of the fully grown Frostbearing Tree? The answer is yes.

**Evidence:** Kaeya, a free character, is used. This is not to imply that other free characters cannot climb the tree, and it is highly likely that other characters can also perform this feat. This evidence merely demonstrates that climbing the tree under the previously mentioned limitations is indeed possible. No food buffs/resonances/etc are used.

Step 1. Climb the trunk by holding forward and spamming the jump button. This is precise and can take many attempts. [\(https://www.youtube.com/watch?v=GRvU5e4B7GA](https://www.youtube.com/watch?v=GRvU5e4B7GA)

Step 1.5. Walk and jump up to scale the tree. [https://www.youtube.com/watch?v=OaGtJvQHBdQ](https://www.youtube.com/watch?v=OaGtJvQHBdQ)

Step 2, Step 3. While scaling the tree, the first two obstacles can be "jumped around" from the left, as demonstrated. In fact, carefully walking around the branch is sufficient for step 2. [https://www.youtube.com/watch?v=I8yQ7-Hsv8o](https://www.youtube.com/watch?v=I8yQ7-Hsv8o)

Step 4. Jump to the area just below the peak of the tree. Both the butterfly and the branch can be landed on. This jump is also somewhat precise. [https://www.youtube.com/watch?v=A3L9tU8iDqs](https://www.youtube.com/watch?v=A3L9tU8iDqs)

Step 5. Jump to the peak of the tree from the butterfly. It is possible that normal attacking immediately after landing helps to stay on the branch. This step is very precise, and failing this step may lead to falling to ground level. [https://www.youtube.com/watch?v=kPmyIS7A3SY](https://www.youtube.com/watch?v=kPmyIS7A3SY)

**Significance:** By mastering these skills, you can climb the intimidating heights of the Frostbearing Tree with nothing but your bare hands. No Vision, elemental powers, or even a glider, are necessary. Indeed, rolling for anything is unnecessary, as the free characters provided to any player are adequate, meaning not even whales have an insurmountable advantage. Climbing to the peak of the tree has incredible significance due to the fact that the local surroundings of the Frostbearing Tree are of a generally lower height. Thus, climbing the Frostbearing tree allows you to get the height advantage, and doing so under these limitations means you can perform such strategic maneuvers under the most dire and desperate of situations.

Being at a greater height confers immense benefits. Those at a significant height over others possess a birds-eye view of the battlefield, allowing them to observe their enemies from afar. The great military strategist Sun Tzu once said, "If you know the enemy and know yourself, you need not fear the result of a hundred battles." Furthermore, the advantage of height is not merely backed by military theory. In fact, it is has been a deciding factor throughout history. For example, Obi Wan cleverly defeated Anakin by utilising this intrinsic advantage unique to the high ground.

Also, you can perform a plunging attack off of the tree.

## Cancelling Abilities
Note: This is a merge of 2 tickets

**By:** Ayzel\#7399, sexyeboy69\#4338, Aluminum\#5462  
**Added:** 6/23/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/840459159656202250/845509708693635072/transcript-chair-cancelling.html)  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/842094899204587580/857414437437964348/transcript-all-the-cancelling.html)

**Finding:**  
For some characters, if they use an elemental skill or burst and use a dialogue box at the same time \(pressing F and E at the same time for PC users\), while the skill will not activate \(and as such the skill cooldown will not start\), the game will still "treat" the skill or burst as if it activated, which causes effects like Crimson Witch 4-piece to stack or can trigger effects like 4-piece Noblesse Oblige.

**Evidence:**  
Chair cancel by Ayzel: [Video](https://youtu.be/6nwbxIwk3Q8)   
Talking to NPC cancel by sexyeboy69: [Video Download](https://cdn.discordapp.com/attachments/842094899204587580/842095318639181834/Genshin_Impact_2021-05-12_13-43-52.mp4)  
Poster cancel by Aluminum: [Video Download](https://cdn.discordapp.com/attachments/842094899204587580/842106461378969640/Poggers_poster_cancel.mp4)

**Significance:**  
New theoretical highest DPS ceiling for some units who aren't able to typically stack CW \(like Hu Tao and Xiangling\). Also, can obtain 4-piece Noblesse buff or Keqing's bonus crit rate without actually using the burst.

## Harpastum Cancel

**By:** Episodde#8962  
**Added:** 6/26/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/853961397059059722/858414283258855464/transcript-harpastum-cancel.html)

**Finding:**  
Aiming with the Harpastum Ball gadget allow character to quickly cancel their animation in combat. This cancel is slightly faster than jump/dash cancels. However, the cancel cannot be performed when your character is put into a state where elemental skill is not usable, such as while performing a charge attack.

**Evidence:**  
Harpastum cancel demo: [Video](https://imgur.com/g4VzQqE)  
Harpastum cancel frame counts: [Google Sheets](https://docs.google.com/spreadsheets/d/18m1YqErwXnFxVE6NlGp20yYHKt6byt9gT_OVK6gKsEc/edit)  
Unable to use harpastum cancel during charge attack: [Video](https://imgur.com/1hYi0s0)

**Significance:**  
Because you can use the gadget in combat, holding the skill button while having the Harpastum equipped act as a quick skill animation cancels, that are are quicker than jump cancels, and does not cost stamina like dash cancels. This can potentially help melee character that prefer to not finish their attack combo due to long animation, such as Razor in the open world.

## Hilichurls sleep  

**By:** HailCorporate\#2970  
**Added:** 01/18/2021  

**Finding:**  
Hilichurls sleep.  

**Evidence:**  
[Video of two Hilichurls laying on the ground under a Sunsettia Tree in the outskirts of Mondstadt.](https://www.youtube.com/watch?v=BnZqCBX9iLM)  
All other Audio has been reduced leaving only SFX, which has been increased during editing (Sound Warning: the Hilichurls wake up at the end).  
You can clearly hear both Hilicurls snoring as they enjoy their afternoon nap.  

**Significance:**  
Even the Hilichurls are taking it easy, don't forget to take a break from the game now and then.  


## 4pc Gambler and Sacrificial Weapons Wildlife Interaction  

**By:** Mcpie#8672  
**Added:** 08/17/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/876373145655869460/877095617246167050/transcript-4p-gambler-and-sac-weapon-animals-interaction.html)

**Finding:**  
Sacrificial weapons passives and Gambler 4p effect triggers on fowl and raw meat sources, but does not trigger on critters (entire "Other" category from the archive).

**Evidence:**  
Triggers on (fowl/raw meat sources):  
- Foxes: [Imgur](https://i.imgur.com/ryawqXu.mp4) (displays only 4p gambler)  
- Boars: [Imgur](https://i.imgur.com/3k3R1B1.mp4) (sac sword trigger), [Imgur](https://i.imgur.com/xBzadvR.mp4) (gambler trigger)  
- Birds: [Imgur](https://i.imgur.com/iKMO4MP.mp4) (gambler trigger)  
- Squirrels: [Imgur](https://i.imgur.com/V9ItTY3.mp4) (sac sword trigger)  

Does not trigger on (probably entire "Other" category)  
- Crabs: [Imgur](https://i.imgur.com/S4K0smH.mp4)  
- Lizards: [Imgur](https://i.imgur.com/VikTmNG.mp4)  
- Crystalflies [Imgur](https://i.imgur.com/Uur4EOw.mp4)  
- Fireflies: [Imgur](https://i.imgur.com/VikTmNG.mp4) (very end of video)  

**Significance:**  
Wildlife that act as an interactable item pick-up (material sources) behave differently from  wildlife that drop items (birds and beasts).

## Use any expressions you want in Photo Mode  

**By:** ZyronX#2720  
**Added:** 09/25/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/888535890190811136/891152940641951785/transcript-use-different-expressions-in-photo-mode.html)

**Finding:**  
In high ping environment, switching character take some amount of time. Assuming you switch from A to B. If you use switching duration to enter photo mode, you can use expressions from character A on character B.

**Evidence:**  
[Video](https://youtu.be/Vrq68dozj3k)

**Significance:**  
Smiling Ei UwU

## Narukami Shrine Fortune Slip Probabilities

**By:** mmjacobs\#9588  
**Added:** 11/11/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/896487806543724604/908520683506630697/transcript-narukami-shrine-fortune-slip-probabilities.html)  

**Finding:**  
There are 16 possible fortune slip results, each with a unique lucky item. The probability of each fortune slip result (and therefore each lucky item) is equal. This means that for the 16 possible slip results, each one has a 1/16 chance to be received, or a 6.25% probability.  

Not all fortune slips share the same fortune type however. For example, there is only one fortune slip that is a great misfortune, but there are four fortune slips that are a great fortune. This means that the odds of getting a great fortune is 4 times as likely. The likelihood of each fortune type is the following:
* Great Misfortune = 1/16 = 6.25%
* Misfortune = 2/16 = 12.5%
* Rising Fortune = 2/16 = 12.5%
* Modest Fortune = 4/16 = 25%
* Good Fortune = 3/16 = 18.75%
* Great Fortune = 4/16 = 25%

**Evidence:**  
[Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSctTPheCZ15hBw09qQ5yFAuLuVdGXomDwNGLrE1V1C6ROgTmg/viewform)  
[Data Results](https://docs.google.com/spreadsheets/d/1ghne6fus5oOpFukS33K6hd_XCWIbSzgw9fTglfNChJ8/edit#gid=870834050)  

645 fortune slip results were collected over 1 month, and a histogram of the counts per lucky item was created. When graphed from great misfortune up to great fortune, the counts are roughly even showing no clear trend (see red trendline): [Imgur](https://imgur.com/mAkrj53)    

The lowest occurring item was the Curly Lizard Tail (Great Misfortune) at 5.1%. The highest occurring item was the Fallen Pinecone (Modest Fortune) at 7.8%. Variability in the data is attributed to the natural randomness in the slips: [Imgur](https://imgur.com/DMz5T6D)  

When graphed by fortune type, the modest and great fortunes are the most likely, and the great misfortune is the least likely: [Imgur](https://imgur.com/aQqkUVM)  

**Significance:**  
Getting the "Paimon's Lucky Day!" achievement is significantly easier than the "Just My Luck..." achievement. There is a 25% chance to get the Great Fortune, which means that 50% of people will get the "Paimon's Lucky Day!" by their 3rd slip. There is only a 6.25% chance of getting the Great Misfortune, which means that 50% of people will get the "Just My Luck..." by their 11th slip. This means that most people will be able to get both achievements within two weeks.  

## Fruit can stick to ground when left unattended

**By:** vinsette\#0293

**Added:** 12/13/2021

[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/918035789865156618/919908365172363385/transcript-fruit-changes-on-hitting-ground.html)

**Finding:** Fruit can be affected by Anemo suction as long as it doesn't stay on the ground for too long. Once they have been on the ground for a certain amount of time, nothing will affect it anymore. You can also indefinitely keep fruit in the air with enough Anemo skills, and **even import Mondstadt fruit into Liyue**.

**Evidences:** [Fruit juggle](https://imgur.com/a/FKJoulw)

**Significance:** Don't let your food touch the ground. Also allows for entertainment via juggling when out of content.

## Reactions are Client-side, Damage is Server-side  

**By:** NZPIEFACE\#8439  
**Added:** 12/17/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/917969257504047174/921166808302616627/transcript-reactions-are-client-side-damage-is-server-side.html)

**Finding:** 
* Reactions (and auras) are done client-side.
* Damage and hit requires servers for them to work.
* This applies to their respective triggers as well.

**Evidence:**
Client-side:
* [Sucrose A1](https://youtu.be/ADkMT-1a9qw)
* [Fischl A4](https://youtu.be/is7BsrPfUCM)
* [Electro-charged](https://youtu.be/LjBSOXtd3RU)

Server-side:
* [Sucrose A4](https://youtu.be/rN1zelj3zBw)
* [Raiden E](https://youtu.be/9i_WGm8aUpQ)

## Enemy level vs. average party level

**By:** r.rei\#2844  
**Added:** 12/19/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/920224953935216670/921938746549608480/transcript-enemy-level-vs-average-party-level.html)  

**Findings:**   
* Enemy level colour is based on your highest owned character level, and current team level is irrelevant.
* Enemy defense is based on the difference of level to the character attacking, the colour of enemy level does not affect that. 
* Average party level warning/zone level warning is a lie, only highest level character is accounted for.  

**Evidence:** [Imgur](https://imgur.com/a/0wWvY56)  
First recording Thoma E damage aligns with 2nd damage calculation, proves that enemy level colour indicator has nothing to do with enemy defense calculation: [Imgur](https://imgur.com/a/biAv7pk)

**Significance:**  
* To get rid of "Dangerous Zone" warning, you only need to level one character.
* Enemy level colour is an unreliable indicator.

## All Models Can Roll In Place  
**By:** Mcpie\#8672  
**Added:** 1/10/2022  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/929185933952159755/930084965645967420/transcript-all-models-can-roll-in-place.html)

**Finding:**  
Every character model is capable of rolling in place.  
In order to perform it, you need enough movement speed and then proceed to jump from being idle -> hold W while falling.  

Depending on character model, you need up to:  
* Child female - 10%  
* Adult female - 10%  
* Adult male - 25%  
* Teen male - 35%  
* Teen female - 35%  
movement speed in order to roll. These are upper bounds and it might be possible to roll with lower values but way harder to execute.

**Evidence:**  
* [Adult male](https://youtu.be/5i_AFRe35ck)
* [Adult female](https://youtu.be/nq3rgd3czz8)
* [Teen male](https://youtu.be/enmeL7TYBGY)
* [Teen female](https://youtu.be/nq3rgd3czz8)
* [Child female](https://youtu.be/0kSxjTp96LM)

**Significance:**  
Fluff, but might somehow help out with model differences in the future.
