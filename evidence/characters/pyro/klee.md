# Klee

**Main Page:**

{% page-ref page="../../../characters/pyro/klee.md" %}

## Klee Burst Waves Mechanics

**By:** Ayzel\#7399  
**Added:** 6/11/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/851923227819114496/852776649149513748/transcript-klee-burst-mechanics.html)

**Finding:** Klee's burst has 6 waves, and on each wave, there is a 35% chance for 3 hits to occur, 50% chance for 4 hits to occur, and 15% chance for 5 hits to occur.

**Evidence:**

1] youtube video of 6 waves occurring: [https://youtu.be/ObwKAFrc548](https://youtu.be/ObwKAFrc548)

2] datamine evidence, showing that 3 hits have a 100% chance, one wave has a 50% chance, and another wave has a 30% chance: [https://github.com/Dimbreath/GenshinData/blob/d633c8cfe5f1f383413a1f65f44d9bd018e5f9be/BinOutput/Ability/Temp/AvatarAbilities/ConfigAbility_Avatar_Klee.json#L2320](https://github.com/Dimbreath/GenshinData/blob/d633c8cfe5f1f383413a1f65f44d9bd018e5f9be/BinOutput/Ability/Temp/AvatarAbilities/ConfigAbility_Avatar_Klee.json#L2320)

3] some data collected that about matches the expected distribution of 35%, 50%, 15%: [https://docs.google.com/spreadsheets/d/17grLuz_AbmmpJf3khVSE82p16VADqq1MFU4UWyO1h0c/edit?usp=sharing](https://docs.google.com/spreadsheets/d/17grLuz_AbmmpJf3khVSE82p16VADqq1MFU4UWyO1h0c/edit?usp=sharing)

**Significance:** Explanining how Klee's burst works

## Klee Mine ICD

**By:** Sakuno\#7950 and Steph\#3614  
**Added:** 03/16/2021

**Theory:**  
This is an independent verification of @Steph's findings, that Klee's mines that normally have separate ICD's have trouble applying their pyro application \(for the purpose of breaking elemental shields\) if they detonate on an enemy too quickly i.e. on the same frame.

**Evidence/Method:**  
I detonated all 8 of Klee's mines into a hydro abyss mage using Anemo MC's burst. Then I measured how many U's worth of shield was damaged by counting pixels. Note it takes 24U of pyro to completely break a hydro abyss mage's shield.

1st Attempt: [https://i.imgur.com/mUlLZhI.jpeg](https://i.imgur.com/mUlLZhI.jpeg) note: the anemo also damages the shield. I will make note if it did this. Here it didn't. Frame 1 is always one frame before the first bomb reaches & deals dmg to the abyss mage. on Frame 5 it dealt 2U's worth of pyro damage. Total only 5U of shield damage.

2nd Attempt: [https://i.imgur.com/GmHWMON.jpg](https://i.imgur.com/GmHWMON.jpg) 1U of dmg on frame 2, 2U's worth on frame 4 and 6. Totalling 5U from bombs.

3rd Attempt: [https://i.imgur.com/AYXWLT7.jpg](https://i.imgur.com/AYXWLT7.jpg) Anemo dealt 1U before the bombs reached. 1U on frame 2. 2U on frame 4. 1U on frame 8. Totalling only 4U from bombs.

**Conclusion:**  
If too many mines hit the mage in too short a span you waste the mines' ICDs. Also I could not observe a larger hit to the abyss mage's shield than 2U in one frame.

**Significance:**  
Only a maximum of 2U worth of shield dmg possible in one frame? \(inconclusive\)

Klee can break hydro abyss shields faster by abusing the fact that her mines are on separate ICD's so long as you have a way to gather them. However anemo MC's burst is not the best way for this because the bombs detonate on the mage at the same time, wasting U's. \(you waste 3 to 4 mines worth of dmg\). You are better off holding E as steph suggests. Same with Jean don't tap E, hold E so that the mines gather onto the mage \(also credit Steph\).

### Klee Mines ICD Update

**By:** Steph\#3614  
**Added:** 6/7/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/843884968681668648/851377033031581726/transcript-klee-mines-icd-update.html)

**Editor's Note:** The findings below expands on the findings above, this finding does not invalidate the above entry, but rather investigates a similarly related mechanic.

**Findings:**  
Klee's jumpty dumpty's split mines shares an ICD on pyro application with her normal attacks.

**Evidence:** Frame counting was done on 2 separate conditions

[Condition 1](https://imgur.com/cFw1iqd): Throw klee's jumpty dumpty down, lure cryo abyss mage in, then use Jean's E to gather all 8 bombs into the shield

[Condition 2](https://imgur.com/1cxyfmv): Throw klee's jumpty dumpty down, lure cryo abyss mage in, having 1 split mine to blow off onto the shield, then do a n1 onto the shield.

On both conditions, the very first frame is the frame where the first melt reaction occurs with Klee's split mine

In condition 1, the following data were collected

* Mine 1: frame 1, reaction occurs
* Mine 2: frame 59, no reaction occurs
* Mine 3: frame 71, no reaction occurs
* Mine 4: frame 80, reaction occurs
* Mine 5: frame 86, no reaction occurs
* Mine 6: frame 94, no reaction occurs
* Mine 7: frame 98, reaction occurs
* Mine 8: frame 128, no reaction occurs

In condition 2, the n1 attack connects 72 frames after the first split mine connect and no reaction occurs.

Both of these conditions lines up with the current ICD theory.

**Significance:**  
Klee's jumpty dumpty's split mine might steal some reactions away from Klee's normal string by activating the timer and hit count before normal string lands, or it might also allow Klee to do more reaction using her normal strings by advancing the counter number.

## Failure to proc Klee's talent 'Pounding Surprise' \(Explosive Spark\), if she is swapped out immediately after attacking.

**By:** fid\#6253  
**Added:** 12/22/2020  
Updated: 12/28/2020

**Theory:**  
Klee's talent 'Pounding Surprise' doesn't proc the 50% chance to spawn the 'Explosive Spark' if she's swapped off-field after auto attacking or using her E.

**Evidence:**  
Tested for a few minutes on a world boss, but here's just a short clip.

* [https://youtu.be/0DEbRVl1pXE](https://youtu.be/0DEbRVl1pXE) 
* [https://youtu.be/SGMMKs5lpkI](https://youtu.be/SGMMKs5lpkI) 
* [https://youtu.be/sTtaWS0g1gQ](https://youtu.be/sTtaWS0g1gQ)

**Significance:**  
Should the reverse be true, two grounded walk-cancel AA1s from Klee would allow you to switch characters immediately after the second without any downside. However, as it stands, players looking to maximize the benefit from the talent's charge attack buff will want to look for the proc before swapping, bringing two grounded AA1s closer in-line to - AA1 &gt; AA2 &gt; jump cancel combo. As for why you would want to swap characters frequently from Klee in the first place, that would be to set up reactions manually, or refresh Viridescent Venerer 4pc effect. A rotation could run something like this:

* Klee AAs until Explosive Spark proc
* Sucrose Swirl
* Swap to Cryo/Hydro unit and wait briefly for pyro to elapse naturally due to the swirl shortening its duration before proccing the aura element
* Klee Charge Attack
* Repeat.

## Klee’s Q is snapshotted on Cast

**By:** stellar\#7066  
**Added:** 12/7/2020

**Finding:**  
Klee's burst \(Q\) is snapshotted.

**Evidence:**  
[https://imgur.com/a/8TQUkYU](https://imgur.com/a/8TQUkYU)

**Significance:**  
You can leave Bennett Q after using Klee burst and you also keep other atk% buffs that were enabled before Klee burst.


## How does 2 set Noblesse Oblige interact with C1 Klee?

**By:** fin\#1623  
**Added:** 12/6/2020

**Theory:**  
Does Noblesse affect Klee's c1 procs.

**Finding:**  
Yes they do.

**Evidence:**  
[https://youtu.be/VM6uiOfE8z4](https://youtu.be/VM6uiOfE8z4)

**Significance:**  
2NO + 2 witch might be a viable set for an at least C1 Klee and makes animation cancelling more worth it as it triggers \(Klee’s C1\) by AAing and skills.

## Klee C4 damage

**By:** elijam#7142  
**Added:** 08/07/2021  
 [Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/866108653634846780/873536676675338280/transcript-tcl-damage-type-completion.html)  
 
**Finding:**  
Klee’s C4 damage instance has no ability type scaling tags. 

**Evidence:**  
Testing done by bloodreign616#4766  
Damage is consistent with and without 2NO bonus - [Video](https://www.youtube.com/watch?v=lfrtwB9mZTc)  
No further tests were done given that it is highly unlikely that Klee’s C4 damage is considered NA/CA or skill damage and given that Monochrom9#8058 could find no ability type scaling tags for it in Klee’s ability configs. 

**Significance:**  
Damage calculations for Klee.

## Klee 4CW 3 stacks

**By:** solo#3333  
**Added:** 09/17/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/887521548049715200/888239532028354630/transcript-klee-4cw-3-stacks.html)  
 
**Finding:**  
Spam pressing Klee's E button will trigger 2 stacks of Crimson Witch with one charge of Jumpty Dumpty. Therefore using the second charge within 10s will bring the total CW stacks to 3.

**Evidence:**  
[Imgur](https://imgur.com/RsnPT4c)

**Significance:**  
4CW is better than expected for Klee.

## Klee C6 mechanics

**By:** solo#3333  
**Added:** 09/25/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/887165577691529226/891209626396266516/transcript-klee-c6-mechanics.html)  
 
**Finding:**  
- Klee C6 does not stack with itself (e.g., casting burst again during the 25s will not increase the pyro bonus to +20% total).  
- Klee C6 does snapshot to her own burst, unlike Xiangling.

**Evidence:**  
No stack: [Imgur](https://imgur.com/i7yYGwi)  
Damage calc for burst: (stats screen: [Imgur](https://imgur.com/BxSiIXT)) (set bonus 2pc proof: [Imgur](https://imgur.com/Xn6WOqq))  
(damage screenshot 1277 - [Imgur](https://imgur.com/MqMJuFV)

869 * 1.588 * 0.5 * 0.9 * 2.681 * .768 = 1278.61 (rounding error in game?)  
869 = attack  
1.588 = damage bonus (ascension + c6 active + noblesse 2pc)  
0.5 = enemy defense multiplier  
0.9 = enemy resist multiplier  
2.681 = crit  
.768 = burst lvl 10

**Significance:**  
No value in chain casting burst shenanigans, and Klee C6 does apply to her own burst despite some people saying otherwise. 
