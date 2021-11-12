---
search: false
---

# Hitlag Extension

## Hitlag Extends Elemental Aura Duration <a id="docs-internal-guid-116d1688-7fff-1539-a82f-c218e3de996c"></a>

**By:** BowlSoldier\#3528

**Finding:**  
Elemental Aura durations are affected by hitlag, much like any other enemy debuff.

**Evidence:**

[https://youtu.be/KaqUOpoGiSk](https://youtu.be/KaqUOpoGiSk)

In the first example in the video, there is no hitlag. The Electro aura lasts for 566 frames, or 9.43 seconds.

In the second example, Razor causes as much hitlag as possible. The Electro aura lasts for 11.41 seconds, longer than expected.

**Significance:**  
We can extend aura durations with hitlag to give ourselves more time to cause reactions.

Unfortunately this means a lot of our frame counts of elemental durations will be off by a few frames, because of the hitlag on the moves that apply the element.

## Normal Attack Hitlag can Extend Skill/Burst Duration

**By:** Kourinn\#6001  
**Added:** 5/9/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/835912799343476766/840072673961967646/transcript-hitlag-extension-testing.html)

**Finding:** Normal Attack hitlag can extend the duration of some skills/bursts, such as Xiao's burst.

**Evidence:** [https://youtu.be/2HpPqt7Jh2A](https://youtu.be/2HpPqt7Jh2A)

Timestamps: \(subtract 1:22:00; timestamps are from pre-editing\) [https://docs.google.com/spreadsheets/d/1WAEtYnrrxzRK\_Ik2X4QanFpTJZa-ThVxXFyyTgEkwlc/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1WAEtYnrrxzRK_Ik2X4QanFpTJZa-ThVxXFyyTgEkwlc/edit?usp=sharing)

The duration of Xiao's burst appears to be calculated from the frame the CD starts, which matches with when Xiao's tattoos light up. Extended duration after the CD start is entirely due to hitlag, not remaining animation. Animation may only appear to extend duration because CD start is delayed.

**Significance:** Hitlag extension should be taken into account when simulating skills/bursts such as Xiao's burst, as they cause the skill to last longer.

## Hitlag Extension Caveats

**By:** Kourinn\#6001  
**Added:** 5/9/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/835912799343476766/840072673961967646/transcript-hitlag-extension-testing.html)

**Findings:**

* Deployables \(skills and constructs that stay on the field for a set amount of time\) do NOT have duration extended by normal attack hitlag.
  * The duration is only affected by their own activation hitlag \(i.e. Xiangling's melee hits on her burst\) and single-player world pauses \(menu, character death, etc\).
* The buffs caused by deployables, such as Chongyun's Cryo infusion, do have their durations extended by normal attack hitlag.

**Evidence:**

[_**Bennett Field Buff**_](https://youtu.be/ie34i2e9A8o)

* 00:01:11 - Q press
* 00:01:46 - CD start  
* NA spam \(should add ~1s via hitlag\)  
* 00:13:41 - last heal
* 00:14:01 - AOE fully faded

Q circle lasted 12s

[_**Chongyun Field Buff**_](https://youtu.be/5gx9ReKNVZ0)

* 00:08:53 - E press
* 00:09:28 - E CD Start
* NA Spam \(should add ~1.5s hitlag\)
* 00:19:32 - CD on skill hits 4.9 seconds
* 00:19:39 - AOE fully faded
* 00:21:43 - CD on Chongyun's Skill hits 2.7s \(when the infusion effect _should_ end\)
* 00:21:59 - Infused Weapon effect ends

E circle lasted ~10s; cryo infusion lasted 0.16 seconds longer than expected

_**Xiangling Hitlag Extension**_

[_With Hitlag on Startup_](https://youtu.be/fxvisWyC5lk)

Timestamps:

* 00:26:28 - Q press
* 00:26:47 - Q CD Start, Q hitlag start
* 00:26:54 - Q hitlag end \(7 frames\)
* 00:27:06 - Q hitlag start
* 00:27:13 - Q hitlag end \(7 frames\)
* 00:27:27 - Pyronado Entity spawns
* 00:27:35 - Q hitlag start
* 00:27:42 - Q hitlag end \(7 frames\)
* some NA spam \(should extend Pyronado by ~2s due to hitlag if hitlag were to actually extend pyronado\)
* 00:41:10 - Pyronado Entity disappears, 5.6s CD left
* 00:41:15 - 5.5s cd

Durations:

* from Q press: 14:42
* from CD start: 14:23
* from entity spawn: 13:43

[_Without Hitlag on Startup_](https://youtu.be/e_hR5BT6Ock)

Timestamps:

* 00:15 - Q pressed
* 00:34 - CD started
* 01:02 - Pyronado entity spawned
* 14:45 - Pyronado entity disappears at 5.8s CD left 
* 14:46 - Explosion animation starts

Durations:

* from Q press: 14:30
* from CD start: 14:16
* from entity spawn: 13:44

As shown, in the case of Xiangling, while her hitlag \(on the second melee hit; the skill's cooldown starts _after_ the first hit, so its hitlag has no benefit\) delays the spawn, effectively reducing the cooldown by 6 or 7 frames \(0.100s - 0.117s\), this effect is negligible.

The third melee hit does not matter, since the Pyronado entity has spawned by the third hit, and hitlag does not extend its duration.

**Significance:** Hitlag extension should be ignored when theorycrafting deployables' and Bennett's/Chongyun's buff/infusion uptime.

