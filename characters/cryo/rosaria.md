---
description: >-
  A sister of the church, though you wouldn't know it if it weren't for her
  attire. Known for her sharp, cold words and manner, she often works alone.
---

# Rosaria

## ![](../../.gitbook/assets/element_cryo.png) Rosaria

![](../../.gitbook/assets/character_rosaria_wish.png)

## **Base Stats**

| Lv | Base HP | Base ATK | Base DEF | ATK% |
| :--- | :--- | :--- | :--- | :--- |
| 60 | 8096 | 158 | 468 | 12% |
| 60+ | 8643 | 169 | 499 | 12% |
| 70 | 9493 | 185 | 548 | 12% |
| 70+ | 10040 | 196 | 580 | 18% |
| 80 | 10891 | 213 | 629 | 18% |
| 80+ | 11438 | 223 | 661 | 24% |
| 90 | 12289 | 240 | 710 | 24% |

## **Attacks**

{% tabs %}
{% tab title="Spear of the Church" %}
**Normal Attack**  
Rosaria performs up to five consecutive spear strikes.

| String | Talent 6 DMG% | Frames | Motion Value |
| :--- | :--- | :--- | :--- |
| 1-Hit | 76.25% | 10 | 457.5%/s |
| 2-Hit | 75% | 36 | 252.08%/s |
| 3-Hit | 46.25% x2 \(92.5%\) | 81 | 180.56%/s |
| 4-Hit | 101.25% | 115 | 180%/s |
| 5-Hit | 60.5% + 62.5% \(123%\) | 175 | 160.46%/s |

**Charged Attack**  
Rosaria consumes 25 stamina to lunge forward, dealing damage to opponents along the way.

| String | Talent 6 DMG% | Frames | Motion Value |
| :--- | :--- | :--- | :--- |
| N1C | 275% | 89 | 185.39%/s |

**Plunge Attack**  
Rosaria plunges to the ground from mid-air, damaging opponents along the way and dealing AoE damage upon impact.

| Plunge Type | Talent 6 DMG% |
| :--- | :--- |
| Plunge Attack | 92.93% |
| Low Plunge DMG | 185.81% |
| High Plunge DMG | 232.09% |
{% endtab %}

{% tab title="Ravaging Confession" %}
Rosaria swiftly shifts her position to appear behind her opponent, then stabs and slashes them with her polearm, dealing **Cryo** DMG.  
This ability cannot be used to travel behind opponents of a larger build.

| Type | Talent 6 Data |
| :--- | :--- |
| Skill DMG | 81.76% + 190.4% \(272.16%\) |
| Cooldown | 6s |
| Particles | 3 |
| GU | 1A |
| Frames | 65 |
| Motion Value | 251.22%/s |

* Both hits of **Ravaging Confession** apply cryo, and have no ICD, allowing it to double melt
{% endtab %}

{% tab title="Rites of Termination" %}
Rosaria swings her weapon to slash surrounding opponents, then she summons a frigid Ice Lance that strikes the ground. Both actions deal **Cryo** DMG.  
While active, the Ice Lance periodically releases a blast of cold air, dealing **Cryo** DMG to surrounding opponents.

| Effect | Talent 6 Data |
| :--- | :--- |
| Skill DMG | 145.6% + 212.8% \(358.4%\) |
| Ice Lance DoT | 184.8% |
| GU | 1A |
| Duration | 8s |
| Cooldown | 15s |
| Energy Cost | 60 |
| Frames | 74 |
| Motion Value | 290.59%/s |

* **Rites of Termination** snapshots buffs
* Cryo application has no ICD
  * 1A cryo on both damage instances on cast
  * 1A cryo every damage tick, which occurs every 2 seconds
{% endtab %}
{% endtabs %}

## **Ascension Passives**

{% tabs %}
{% tab title="Passive" %}
### **Night Walk**

At night \(18:00-6:00\), increases the Movement Speed of your own party members by 10%. Does not take effect in Domains, Trounce Domains, or Spiral Abyss.  
Not stackable with Passive Talents that provide the exact same effect.
{% endtab %}

{% tab title="Ascension 1" %}
### **Regina Probationum**

When Rosaria strikes an opponent from behind using Ravaging Confession, Rosaria's CRIT RATE increases by 12% for 5s.

* Either damage instance of **Ravaging Confession** can trigger this passive
* This CRIT RATE increase shows up in her stat screen, meaning it can be snapshotted by her A4, **Shadow Samaritan**, and included in the crit sharing
* Rosaria doesn't gain the CRIT RATE bonus unless the use of **Ravaging Confession** lands her behind the enemy
  * meaning, if Rosaria starts her skill behind an enemy, but that enemy turns around to face her before the two hits, she won't get the CRIT RATE bonus
{% endtab %}

{% tab title="Ascension 4" %}
### **Shadow Samaritan**

Casting Rites of Termination increases CRIT RATE of all nearby party members, excluding Rosaria herself, by 15% of Rosaria's CRIT RATE for 10s. CRIT RATE bonus gained this way cannot exceed 15%

* The CRIT RATE shared by **Shadow Samaritan** can be stacked with external CRIT buffs that show up in a character's stat sheet
  * Examples: Hu Tao A1 and Geo MC C1
{% endtab %}
{% endtabs %}

## Constellations

{% tabs %}
{% tab title="C1" %}
### Unholy Revelation

When Rosaria deals a CRIT Hit, her ATK Speed increase by 10% and her Normal Attack DMG increases by 10% for 4s
{% endtab %}

{% tab title="C2" %}
### Land Without Promise

The duration of the Ice Lance created by Rites of Termination is increased by 4s.
{% endtab %}

{% tab title="C3" %}
### The Wages of Sin

Increases the level of Ravaging Confession by 3.
{% endtab %}

{% tab title="C4" %}
### Painful Grace

Ravaging Confession's CRIT Hits regenerate 5 Energy for Rosaria. Can only be triggered once each time Ravaging Confession is cast.
{% endtab %}

{% tab title="C5" %}
### Last Rites

Increases the level of Rites of Termination by 3.
{% endtab %}

{% tab title="C6" %}
### Divine Retribution

Rites of Termination's attack decreases opponent's Physical RES by 20% for 10s.

* This effect can also be triggered by the lance DoT
{% endtab %}
{% endtabs %}

## **Full Talent Values**

{% tabs %}
{% tab title="Spear of the Church" %}
### Normal Attacks

|  | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit DMG | 76.25% | 82.96% | 89.67% | 96.38% | 103.70% | 111.02% |
| 2-Hit DMG | 75% | 81.60% | 88.20% | 94.80% | 102% | 109.20% |
| 3-Hit DMG | 46.25% ×2 | 50.32% ×2 | 54.39% ×2 | 58.46% ×2 | 62.9% ×2 | 67.34% ×2 |
| 4-Hit DMG | 101.25% | 110.16% | 119.07% | 127.98% | 137.70% | 147.42% |
| 5-Hit DMG | 60.5% + 62.5% | 65.82% + 68% | 71.15% + 73.5% | 76.47% + 79% | 82.28% + 85% | 88.09% + 91% |

### Charged Attack

|  | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Charged Attack DMG | 198.75% | 216.24% | 233.73% | 251.22% | 270.30% | 289.38% |

**Stamina Cost**: 25

### Plunge

|  | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Plunge Impact | 92.93% | 101.10% | 109.28% | 117.46% | 126.38% | 135.30% |
| Low Plunge DMG | 185.81% | 202.16% | 218.51% | 234.86% | 252.7% | 270.54% |
| High Plunge DMG | 232.09% | 252.51% | 272.93% | 293.36% | 315.64% | 337.92% |
{% endtab %}

{% tab title="Ravaging Confession" %}
|  | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Skill 1 DMG | 81.76% | 87.6% | 93.44%  | 99.28% | 105.12% | 110.96%  | 116.8%  | 124.1% |
| Skill 2 DMG | 190.4% | 204% | 217.6% | 231.2% | 244.8% | 258.4% | 272% | 289% |

**Cooldown**: 6s
{% endtab %}

{% tab title="Rites of Termination" %}
|  | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Skill 1 DMG | 145.6% | 156%  | 166.4% | 176.8% | 187.2% | 197.6%  | 208% | 221% |
| Skill 2 DMG | 212.8% | 228% | 243.2% | 258.4% | 273.6% | 288.8% | 304% | 323% |
| Ice Lance DoT | 184.80% | 198% | 211.20% | 224.40% | 237.60% | 250.80% | 264% | 280.50% |

**Energy Cost**: 60

**Duration**: 8s

**Cooldown**: 15s
{% endtab %}
{% endtabs %}

## **External Links**

* [Honey Hunters](https://genshin.honeyhunterworld.com/db/char/rosaria/)

**Evidence Vault:**

{% page-ref page="../../evidence/characters/cryo/rosaria.md" %}

