---
description: A young lady who has inherited trace amounts of non-human blood. She is the incredibly popular bartender of the Cat’s Tail tavern.
---

# Diona

## **Resources**
* [Full Diona Guide](https://keqingmains.com/diona/)  
* [4 Minute Quick Guide to Diona](https://youtu.be/IWoSkeAFY4o)  
* [Icy Paws Deep Dive](https://docs.google.com/document/d/1GZrscI-X_-CgzavXUbCeELrSumbAqlLqVkkJN1vWKwk/edit?usp=sharing)
* [Icy Paws Sacrifical Bow vs Favonius Bow - Energy Gen & Field Time Efficiency](https://docs.google.com/spreadsheets/d/1rMyjElZHS0PDU4uyJ55bKGsmUVW82ga4xPcDUJSE760/edit#gid=1389539947)

## ![](../../.gitbook/assets/element_cryo.png) Diona

![](../../.gitbook/assets/character_diona_wish.png)

## **Base Stats**

| Lv | Base HP | Base ATK | Base DEF | Cryo DMG% |
| :--- | :--- | :--- | :--- | :--- |
| 60 | 6305 | 140 | 396 | 12% |
| 60+ | 6731 | 149 | 422 | 12% |
| 70 | 7393 | 164 | 464 | 12% |
| 70+ | 7818 | 174 | 491 | 18% |
| 80 | 8481 | 188 | 532 | 18% |
| 80+ | 8907 | 198 | 559 | 24% |
| 90 | 9570 | 212 | 601 | 24% |

## **Attacks**

{% tabs %}
{% tab title="Kätzlein Style" %}
**Normal Attack**  
Perform up to 5 consecutive shots with a bow.

| String | Talent 9% | Frames | MV/s |
| :--- | :--- | :--- | :--- |
| 1-hit | 66.36% | 16 | 248.85%/s |
| 2-Hit | 61.62% | 37 | 207.54%/s |
| 3-Hit | 83.74% | 67 | 189.6%/s |
| 4-Hit | 79% | 101 | 172.7%/s |
| 5-Hit | 98.75% | 152 | 153.74%/s |
| With Recovery | 389.47% | 190 | 122.99%/s |

**Aimed Shot**  
Perform a precise Aimed Shot with increased DMG.  
A fully charged shot will deal Cryo DMG.

| Type | Talent 9% | Frames | MV/s | GU |
| :--- | :--- | :--- | :--- | :--- |
| Aimed Shot | 80.58% | 15 | 322.32%/s | ~ |
| With Recovery | ~ | 23 | 210.21%/s | ~ |
| Fully Charged | 210.8% | 86 | 147.07%/s | 1A |
| With Recovery | ~ | 94 | 134.55%/s | ~ |
| C4 Fully Charged | 210.8% | 50 | 252.96%/s | 1A |
| With Recovery | ~ | 58 | 218.07%/s | ~ |
* Charged Attack frame counts are done using by holding and releasing the Normal Attack button.
* Diona's Fully Charged shots follow a 3 hit/2.5s ICD.
* Diona can cancel her dash early with Aim Toggle. Thus allows her to do quick Charged Attack while still retaining the ability to aim, unlike ARCC which cannot be aimed.

**Plunge Attack**  
Fire a shower of arrows from mid-air before falling striking the ground, dealing AoE DMG.

| Type | Talent 9% |
| :--- | :--- |
| Plunge DMG | 104.41% |
| Low Plunge DMG | 208.77% |
| High Plunge DMG | 260.76% |
{% endtab %}

{% tab title="Icy Paws" %}
Fire **Icy Paws** that deal Cryo DMG to opponents and forms a shield on hit.  
The shield’s DMG Absorption scales based on Diona’s Max HP, and its duration scales off the number of **Icy Paws** that hit their target.

**Press**
* Rapidly fires off 2 **Icy Paws**.

**Hold**
* Dashes back quickly and before firing 5 **Icy Paws**.
* The shield created by a Hold attack will gain a 75% DMG Absorption Bonus.
* The shield has a 250% Cryo DMG Absorption bonus.

| Attribute | Tap | Hold |
| :--- | :--- | :--- |
| Skill DMG \(T9%\) | 71.26% x 2 | 71.26% x 5 |
| Particles | 0~1 \(1:4\) check per paw | 0~1 \(1:4\) check per paw |
| Frames | 15 | 24 |
| GU | 1A | 1A x 2 | 
| ICD | 3 hit / 2.5s | 3 hit / 2.5s |
| Snapshot | Snapshot | Snapshot |
| Damage Element | Cryo | Cryo | 
| Damage Type | Skill | Skill |
| CD | 6s | 15s |

| Attribute | Shield | 
|:--- | :--- |
| Base Scaling | 12.24% Max HP + 1409 | 
| Elemental Type | Cryo | 
| Duration | 2.4s per paw |

**Notes**
* Applies a 1A Cryo Aura for a short duration upon formation and upon swap to a different active character.
* In specific circumstances, Diona's shield will apply 2U of Cryo on swap.
  * For more details see the [full entry](../../evidence/characters/cryo/diona.md#bug-dionas-shield-is-2u-under-specific-circumstances-that-are-guaranteed-on-swap) in Diona's Evidence Vault.
* Icy Paws will not generate a shield if they do not hit something. They will also despawn after a certain amount of time.
* Icy Paws will home on some entities that are not enemies, such as birds in the overworld.
* A deep-dive into how Icy paws work can be found [here](https://docs.google.com/document/d/1GZrscI-X_-CgzavXUbCeELrSumbAqlLqVkkJN1vWKwk/edit?usp=sharing)
  {% endtab %}

{% tab title="Signature Mix" %}
Tosses out a special cold brew that deals AoE Cryo DMG and creates a **Drunken Mist**:

**Drunken Mist:**
* Deals continuous Cryo DMG to opponents within the AoE.
* Continuously regenerates HP of the characters within the AoE.

| Attribute | Burst |
| :--- | :--- |
| Skill DMG \(T9%\) | 136% |
| Cast Frames | 49 |
| Energy Frame | 49 |
| CD Frame | 43 |
| GU | 1A |
| CD | 20s |
| Energy Cost | 80 |

| Attribute | Field |
| :--- |:---|
| Field DMG (T9%) | 89.49% |
| GU | 1A |
| ICD | 3 hits / 2.5s |
| HP Regen | 9.07% Max HP + 1044 |
| Duration | 12s |
| Tick Rate| 2s | 
| C6 Buff Duration | 2s |

**Notes**
* C6 buff applies on swap.
* Her field shares an ICD with the initial hit.
* **Drunken Mist** AoE has a finite vertical range. Characters above or below this vertical range will not receive healing.
* **Drunken Mist** targets an enemy and snapshots the position on cast.
* **Drunken Mist** duration starts when the paws disappear from the field, which is about when the Burst CD reaches ~17.5s.

{% endtab %}
{% endtabs %}

## **Ascension Passives**

{% tabs %}
{% tab title="Passive" %}
### **Complimentary Bar Food**

When a Perfect Cooking is achieved on a dish with restorative effects, there is a 12% chance to obtain double the product.
{% endtab %}

{% tab title="Ascension 1" %}
### **Cat's Tail Secret Menu**

Characters shielded by **Icy paws** have their Movement SPD increased by 10% and their Stamina Consumption decreased by 10%.  

* Ths can stack with other forms of stamina reduction as long as they are not the exact same.  

{% endtab %}

{% tab title="Ascension 4" %}
### **Drunkards' Farce**

Opponents who enter the AoE of **Signature Mix** have 10% decreased ATK for 15s.
{% endtab %}
{% endtabs %}

## **Constellations**

{% tabs %}
{% tab title="C1" %}
### **A Lingering Flavor**

Regenerates 15 Energy for Diona after the effects of **Signature Mix** end.

* There is no range limit as long as Diona is on the same map.

{% endtab %}

{% tab title="C2" %}
### **Shaken, Not Purred**

Increases **Icy Paws**' DMG by 15%, and increases its shield's DMG Absorption by 15%.
Additionally, when paws hit their targets, creates a shield for other nearby characters on the field with 50% of the **Icy Paws** shield's DMG Absorption for 5s.

* This DMG increase is **Additive**.
{% endtab %}

{% tab title="C3" %}
### **A—Another Round?**

Increases the Level of **Signature Mix** by 3.
Maximum upgrade level is 15.

{% endtab %}

{% tab title="C4" %}
### **Wine Industry Slayer**

Within the radius of **Signature Mix**, Diona's charge time for aimed shots is reduced by 60%

{% endtab %}

{% tab title="C5" %}
### **Double Shot, on the Rocks**

Increases the Level of **Icy Paws** by 3.
Maximum upgrade level is 15.

{% endtab %}

{% tab title="C6" %}
### **Cat's Tail Closing Time**

Characters within **Signature Mix**'s radius will gain the following effects based on their HP amounts:
* Increases Incoming Healing Bonus by 30% when HP falls below or is equal to 50%.
* Elemental Mastery increased by 200 when HP is above 50%.

**Notes**
* The Elemental Mastery bonus will apply immediately on swap and linger for 2 seconds.
{% endtab %}
{% endtabs %}

## **Full Talent Values**

{% tabs %}
{% tab title="Kätzlein Style" %}
### Normal Attacks

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit DMG | 36.12% | 39.06% | 42.00% | 46.20% | 49.14% | 52.50% | 57.12% | 61.74% | 66.36% | 71.40% | 77.17% |
| 2-Hit DMG | 33.54% | 36.27% | 39.00% | 42.90% | 45.63% | 48.75% | 53.04% | 57.33% | 61.62% | 66.30% | 71.66% |
| 3-Hit DMG | 45.58% | 49.29% | 53.00% | 58.30% | 62.01% | 66.25% | 72.08% | 77.91% | 83.74% | 90.10% | 97.39% |
| 4-Hit DMG | 43.00% | 46.50% | 50.00% | 55.00% | 58.50% | 62.50% | 68.00% | 73.50% | 79.00% | 85.00% | 91.87% |
| 5-Hit DMG | 53.75% | 58.13% | 62.50% | 68.75% | 73.12% | 78.13% | 85.00% | 91.87% | 98.75% | 106.25% | 114.84% |

### Aimed Shot

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Aimed Shot | 43.86% | 47.43% | 51.00% | 56.10% | 59.67% | 63.75% | 69.36% | 74.97% | 80.58% | 86.70% | 93.71% |
| Fully-Charged Aimed Shot | 124.00% | 133.30% | 142.60% | 155.00% | 164.30% | 173.60% | 186.00% | 198.40% | 210.80% | 223.20% | 236.10% |

### Plunge

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Plunge DMG | 56.83% | 61.45% | 66.08% | 72.69% | 77.31% | 82.60% | 89.87% | 97.14% | 104.41% | 112.34% | 120.27% |
| Low Plunge DMG | 113.63% | 122.88% | 132.13% | 145.35% | 154.59% | 165.16% | 179.70% | 194.23% | 208.77% | 224.62% | 240.48% |
| High Plunge DMG | 141.93% | 153.49% | 165.04% | 181.54% | 193.10% | 206.30% | 224.45% | 242.61% | 260.76% | 280.57% | 300.37% |

{% endtab %}

{% tab title="Icy Paws" %}

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Icy Paw DMG \(per Paw\) | 41.92% | 45.06% | 48.21% | 52.40% | 55.54% | 58.69% | 62.88% | 67.07% | 71.26% | 75.46% | 79.65% | 83.84% | 89.08% |
| Base Shield DMG Absorption Scaling | 7.20% Max HP | 7.74% Max HP | 8.28% Max HP | 9.00% Max HP | 9.54% Max HP | 10.08% Max HP | 10.80% Max HP | 11.52% Max HP | 12.24% Max HP | 12.96% Max HP | 13.68% Max HP | 14.40% Max HP | 15.30% Max HP |
| Base Shield DMG Absorption Additive | 693 | 762 | 837 | 918 | 1005 | 1097 | 1195 | 1299 | 1409 | 1524 | 1646 | 1773 | 1905 |
| Duration \(per Paw\) | 1.8s | 1.9s | 2.0s | 2.1s | 2.2s | 2.3s | 2.4s | 2.4s | 2.4s | 2.4s | 2.4s | 2.4s | 2.4s |

**Press Cooldown**: 6s  
**Holding Cooldown**: 15s

{% endtab %}

{% tab title="Signature Mix" %}

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Skill DMG | 80.00% | 86.00% | 92.00% | 100.00% | 106.00% | 112.00% | 120.00% | 128.00% | 136.00% | 144.00% | 152.00% | 160.00% | 170.00% |
| Continuous Field DMG | 52.64% | 56.59% | 60.54% | 65.80% | 69.75% | 73.70% | 78.96% | 84.22% | 89.49% | 94.75% | 100.02% | 105.28% | 111.86% |
| HP Regeneration Over Time Scaling | 5.34% | 5.74% | 6.14% | 6.67% | 7.07% | 7.47% | 8.00% | 8.54% | 9.07% | 9.60% | 10.14% | 10.67% | 11.34% |
| HP Regeneration Over Time Additive | 513 | 565 | 620 | 680 | 744 | 813 | 885 | 962 | 1044 | 1129 | 1219 | 1313 | 1411 |

**Duration**: 12s  
**Cooldown**: 20s  
**Energy Cost**: 80

{% endtab %}
{% endtabs %}

## Evidence Vault

{% page-ref page="../../evidence/characters/cryo/diona.md" %}

