---
description: A maid who faithfully serves the Knights of Favonius. She dreams of joining their ranks someday.
---

# Noelle

## **Resources**

* [Noelle Mains Discord](https://discord.gg/kvft4TKFet)
* [Full Noelle Guide: The One-Maid Army](https://keqingmains.com/noelle/)

## ![](../../.gitbook/assets/element_geo%20%281%29.png) Noelle

![](../../.gitbook/assets/character_noelle_wish.png)

## **Base Stats**

| Lv | Base HP | Base ATK | Base DEF | DEF% |
| :--- | :--- | :--- | :--- | :--- |
| 60 | 7953 | 126 | 526 | 15% |
| 60+ | 8490 | 134 | 562 | 15% |
| 70 | 9325 | 148 | 617 | 15% |
| 70+ | 9862 | 156 | 652 | 22.50% |
| 80 | 10698 | 169 | 708 | 22.50% |
| 80+ | 11235 | 178 | 743 | 30% |
| 90 | 12071 | 191 | 799 | 30% |

## **Attacks**

{% tabs %}
{% tab title="Favonious Bladework - Maid" %}
**Normal Attacks**  
Perform up to 4 consecutive strikes.

| String | Talent 9% | Frames | MV/s |
| :--- | :--- | :--- | :--- |
| 1-Hit | 145.36% | 28 | 311.49%/s |
| 2-Hit | 134.77% | 70 | 240.11%/s |
| 3-Hit | 158.47% | 116 | 226.86%/s |
| 4-Hit | 208.4% | 174 | 223.1%/s |

Optimal damage is a 4-hit cancel when hitting all targets or 3-hit cancel when the fourth hit won't hit all enemies.

**Charged Attack**  
Noelle consumes 40 stamina a second to keep spinning. At the end, perform a more powerful slash.

| String | Talent 9% | Frames | MV/s |
| :--- | :--- | :--- | :--- |
| Spin | 93.22% | 311 | 179.85%/s |
| Final hit | 166.22% | 40 | 187.76%/s |

Enemies struck by Noelle's charged attack will be staggered or launched.

**Plunge**  
Plunges from mid-air to strike the ground below, damaging opponents along the path and dealing AoE DMG upon impact.

| Damage Type | Talent 9% |
| :--- | :--- |
| Plunge Impact | 137.03% |
| Low Plunge DMG | 274.01% |
| High Plunge DMG | 342.25% |

Noelle is able to perform dragonstrike, but because of her model, it's difficult to perform by hand without movement speed buffs. However, the characters that increase movement speed do not synergize well with Noelle in normal play. Performing dragonstrike on Noelle via N1 + plunge nets on average, about a 27% increase in DPS compared to N3D.

{% endtab %}

{% tab title="Breastplate" %}
Summons protective stone armor, dealing Geo DMG to surrounding opponents and creating a shield. The shield's DMG Absorption scales based on Noelle's DEF.

The shield has the following properties:  
• When Noelle's Normal and Charged Attacks hit a target, they have a certain chance to regenerate HP for all characters.  
• Possesses 150% DMG Absorption efficiency against all Elemental and Physical DMG.

The amount of HP healed when regeneration is triggered scales based on Noelle's DEF. 

| Attribute | Skill |
| :--- | :--- |
| Skill DMG \(T9%\) | 204% DEF |
| Particles | 0 \(-\) | 
| Frames | - |
| GU | 2U |
| ICD | 3 hit / 2.5s | 
| Snapshot | Dynamic | 
| Damage Element | Geo | 
| Damage Type | Skill |
| Duration | 12s |
| CD | 24s |

| Attribute | Shield | 
| :--- | :--- |
| Base Scaling \(T9%\) | 272% DEF + 1565 | 
| Healing Chance | 58% |
| Healing Scaling \(T9%\) | 36.18% DEF + 209 |
| Elemental Type | Geo | 
| Duration | 12s |

**Notes**
* **Breastplate**'s damage shares standard ICD with **To Be Cleaned** \(C4\). 
* The damage from **To Be Cleaned** \(C4\) is calculated using Noelle’s current attack at the moment the shield breaks.
* When the shield breaks it creates enough hitlag that you can perform a Plunge attack if you jump at the correct time, however unless you purposefully break the shield it can be hard to time correctly.

{% endtab %}

{% tab title="Sweeping Time" %}
Gathering the strength of stone around her weapon, Noelle strikes the opponents surrounding her within a large AoE, dealing Geo DMG. 

Afterwards, Noelle gains the following effects:  
• Larger attack AoE.  
• Converts attack DMG to Geo DMG that cannot be overridden by any other elemental infusion.  
• Increased ATK that scales based on her DEF.

| Attribute | Burst |
| :--- | :--- |
| Burst DMG (T9%) | 114.24% |
| Skill DMG (T9%) | 157.76% |
| ATK Bonus (T9%) | 68% DEF |
| Cast Frames | 111 |
| Energy Frame | 8 |
| CD Frame | 2 |
| GU | 1U |
| ICD | 3 hit / 2.5s | 
| Snapshot | Dynamic | 
| Damage Element | Geo | 
| Damage Type | Burst  |
| Duration | 15s |
| CD | 15s |

**Notes**
* Noelle's infused Normal and Charged Attacks apply 1GU and have standard 3 hit / 2.5s ICD.
* The DEF to ATK conversion is snapshotted when you activate burst so any changes to DEF after burst is used will not affect ATK.
* The two activation damage instances can proc the healing effect from **Breastplate**.

{% endtab %}
{% endtabs %}

## **Ascension Passives**

{% tabs %}
{% tab title="Passive" %}
### **Maid's Knighthood**

When a Perfect Cooking is achieved on a DEF-boosting dish, Noelle has a 12% chance to obtain double the product.
{% endtab %}

{% tab title="Ascension 1" %}
### **Devotion**

When Noelle is in the party but not on the field, this ability triggers automatically when your active character's HP falls below 30%:
Creates a shield for your active character that lasts for 20s and absorbs DMG equal to 400% of Noelle's DEF.  
The shield has a 150% DMG Absorption effectiveness against all Elemental and Physical DMG.  
This effect can only occur once every 60s.

| Attribute | Shield | 
| :--- | :--- |
| Base Scaling | 400% DEF | 
| Elemental Type | Geo | 
| Duration | 20s |
| CD | 60s |

{% endtab %}

{% tab title="Ascension 4" %}
### **Nice and Clean**

Noelle will decrease the CD of **Breastplate** by 1s for every 4 Normal or Charged Attack hits she scores on opponents.
One hit may be counted every 0.1s.

* Hitting multiple opponents with a single attack is only counted as one hit.
{% endtab %}
{% endtabs %}

## **Constellations**

{% tabs %}
{% tab title="C1" %}
### **I Got Your Back**

While **Sweeping Time** and **Breastplate** are both in effect, the chance of Breastplate's healing effects activating is increased to 100%.

{% endtab %}

{% tab title="C2" %}
### **Combat Maid**

Decreases the Stamina Consumption of Noelle's Charged Attacks by 20% and increases her Charged Attack DMG by 15%.

* This is an additive DMG% bonus.

{% endtab %}

{% tab title="C3" %}
### **Invulnerable Maid**

Increases the Level of **Breastplate** by 3.
Maximum upgrade level is 15.

{% endtab %}

{% tab title="C4" %}
### **To Be Cleaned**

When **Breastplate**'s duration expires or it is destroyed by DMG, it will deal 400% ATK of **Geo DMG** to surrounding opponents.

| Attribute | C4 |
| :--- | :--- |
| Skill DMG | 400% |
| GU | - |
| ICD | 3 hit / 2.5s | 
| Snapshot | Dynamic | 
| Damage Element | Geo | 
| Damage Type | Skill |

* C4 shares ICD with Noelle's elemental skill damage.
* The damage from **To Be Cleaned** is calculated using Noelle’s current attack at the moment the shield breaks.

{% endtab %}

{% tab title="C5" %}
### **Favonius Sweeper Master**

Increases the Level of **Sweeping Time** by 3.
Maximum upgrade level is 15.

{% endtab %}

{% tab title="C6" %}
### **Must Be Spotless**

**Sweeping Time** increases Noelle's ATK by an additional 50% of her DEF.  
Additionally, every opponent defeated during the skill's duration adds 1s to the duration, up to 10s.

**Notes**
* Noelle can extend her burst duration at C6 to maximum by being off field at the time it is supposed to expire
* The bonus DEF conversion from **Must Be Spotless** is additive (i.e. it takes the bonus from 56% DEF to 106% DEF at talent level 6).

{% endtab %}
{% endtabs %}

## **Full Talent Values**

{% tabs %}
{% tab title="Favonius Bladework - Maid" %}
### Normal Attacks

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit DMG | 79.12% | 85.56% | 92.00% | 101.20% | 107.64% | 115.00% | 125.12% | 135.24% | 145.36% | 156.40% | 167.44% |
| 2-Hit DMG | 73.36% | 79.33% | 85.30% | 93.83% | 99.80% | 106.62% | 116.01% | 125.39% | 134.77% | 145.01% | 155.25% |
| 3-Hit DMG | 86.26% | 93.28% | 100.30% | 110.33% | 117.35% | 125.37% | 136.41% | 147.44% | 158.47% | 170.51% | 182.55% |
| 4-Hit DMG | 113.43% | 122.67% | 131.90% | 145.09% | 154.32% | 164.87% | 179.38% | 193.89% | 208.40% | 224.23% | 240.06% |

### Charged Attack

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Charged Attack Spinning DMG | 50.74% | 54.87% | 59.00% | 64.90% | 69.03% | 73.75% | 80.24% | 86.73% | 93.22% | 100.30% | 107.38% |
| Charged Attack Final DMG | 90.47% | 97.84% | 105.20% | 115.72% | 123.08% | 131.50% | 143.07% | 154.64% | 166.22% | 178.84% | 191.46% |

**Stamina Cost**: 40/s  
**Max Duration**: 5s

### Plunge

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Plunge DMG | 74.59% | 80.66% | 86.73% | 95.40% | 101.47% | 108.41% | 117.95% | 127.49% | 137.03% | 147.44% | 157.85% |
| Low Plunge DMG | 149.14% | 161.28% | 173.42% | 190.77% | 202.91% | 216.78% | 235.86% | 254.93% | 274.01% | 294.82% | 315.63% |
| High Plunge DMG | 186.29% | 201.45% | 216.62% | 238.28% | 253.44% | 270.77% | 294.60% | 318.42% | 342.25% | 368.25% | 394.24% |

{% endtab %}

{% tab title="Breastplate" %}

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Skill DMG | 120% DEF | 129% DEF | 138% DEF | 150% DEF | 159% DEF | 168% DEF | 180% DEF | 192% DEF | 204% DEF | 216% DEF | 228% DEF | 240% DEF | 255% DEF |
| DMG Absorption Scaling | 160% DEF | 172% DEF | 184% DEF | 200% DEF | 212% DEF | 224% DEF | 240% DEF | 256% DEF | 272% DEF | 288% DEF | 304% DEF | 320% DEF | 340% DEF |
| DMG Absorption Additive | 770 | 847 | 930 | 1020 | 1116 | 1219 | 1328 | 1443 | 1565 | 1694 | 1828 | 1970 | 2117 |
| Healing Scaling | 21.28% DEF | 22.88% DEF | 24.47% DEF | 26.60% DEF | 28.20% DEF | 29.79% DEF | 31.92% DEF | 34.05% DEF | 36.18% DEF | 38.30% DEF | 40.43% DEF | 42.56% DEF | 45.22% DEF |
| Healing Additive | 103 | 113 | 124 | 136 | 149 | 163 | 177 | 193 | 209 | 226 | 244 | 263 | 282 |
| Healing Triggering Chance | 50% | 51% | 52% | 53% | 54% | 55% | 56% | 57% | 58% | 59% | 59% | 60% | 60% |

**Duration**: 12s  
**Cooldown**: 24s

{% endtab %}

{% tab title="Sweeping Time" %}

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Burst DMG | 67.20% | 72.24% | 77.28% | 84.00% | 89.04% | 94.08% | 100.80% | 107.52% | 114.24% | 120.96% | 127.68% | 134.40% | 142.80% |
| Skill DMG | 92.80% | 99.76% | 106.72% | 116.00% | 122.96% | 129.92% | 139.20% | 148.48% | 157.76% | 167.04% | 176.32% | 185.60% | 197.20% |
| ATK Bonus | 40.00% DEF | 43.00% DEF | 46.00% DEF | 50.00% DEF | 53.00% DEF | 56.00% DEF | 60.00% DEF | 64.00% DEF | 68.00% DEF | 72.00% DEF | 76.00% DEF | 80.00% DEF | 85.00% DEF |

**Duration**: 15s  
**Cooldown**: 15s  
**Energy Cost**: 60

{% endtab %}
{% endtabs %}

## Evidence Vault

{% page-ref page="../../evidence/characters/geo/noelle.md" %}

