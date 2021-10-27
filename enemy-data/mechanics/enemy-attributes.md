# Enemy Attributes

## Monster Skill Effects

**By:** Steno\#6940 and Yurina Maekawa#6585  
See [Evidence Vault](../../evidence/enemy-data/enemy-attributes.md#in-depth-look-at-monster-skill-effects-in-domains-abyss) for Videos, as well as [Discharge Aura Data](../../evidence/enemy-data/enemy-attributes.md#black-aura-data) for more details

These are the damaging effects that are tied to specific enemies within domains/abyss. As of patch 2.2, there are 7 of these effects, tied to each playable element in the game. Below is a table from the [Genshin Wiki](https://genshin-impact.fandom.com/wiki/Elements#Damage_Abilities_2) that details the effects:

| Name | Element | Effect | Base Multiplier | Cooldown |
| :--- | :---: | :--- | :--- | :--- |
| Pursuing Fireball | ![](../../.gitbook/assets/element_pyro.png) | A fireball will chase the on-field character and deal Pyro damage in a small AoE per second. | 150% | 20s |
| Mist Bubble | ![](../../.gitbook/assets/element_hydro.png) | 8 bubbles appear and deal Hydro dmg on contact. | 300% | 12.5s |
| Lightning Stake | ![](../../.gitbook/assets/element_electro.png) | A lightning V will appear and deal Electro damage on contact every 0.25s. | 60% | 12.5s |
| Ice Cage | ![](../../.gitbook/assets/element_cryo.png) | An ice cage will appear from the ground and deals Cryo damage on contact. | 400% | 12.5s |
| Vacuum Vortex | ![](../../.gitbook/assets/element_anemo.png) | A wind core will appear, dealing Anemo damage per second in a small AoE. Then, the core will explode and deal Anemo damage. | 100%\(DoT\) 300%\(explosion\) | unknown \(can't test for now\) |
| Rumbling Stone | ![](../../.gitbook/assets/element_geo%20%281%29.png) | 2 rock waves will cross the ground and deal Geo damage on contact. | 200% | 15s |
| Discharge | ![](../../.gitbook/assets/discharge_aura.png) | Applies the enemy's element to the player as shockwaves, dealing elemental DMG. | 400% | 15s |

Monster skill effects deal flat damage. The amount of damage dealt scales similarly to transformative reactions, it's based purely off a base multiplier corresponding to each skill effect \(for example, **Ice Cage** and **Discharge** deals twice as much damage as **Rumbling Stone**\). Also, the damage is unaffected by your character level or defense; it will always deal the same amount of damage regardless.

The damage from monster skill effects cannot be reduced by skills like **Xingqiu's E/Q** and **Beidou's Q** that grant damage reduction. This means that comps like Beidou + Xingqiu electro-charge that can usually tank enemy attacks by stacking damage reduction cannot benefit from the damage reduction here.

However, damage from monster skill effects is affected by character resistance and can be negated via shields. This means that while the damage can be shielded, damage reduction skills that normally reduce the amount of shield damage taken will not apply.

Monster skill effects can be taunted. In general, these skill effects target the same thing that the corresponding monster is also targeting. In some cases the target will "snapshot" \(i.e. if the monster changes its target during the effect, the effect will not update\) and in other cases it will not. This mechanic will require further testing, it seems to be inconsistent as of now.

## Mist Bubble

The bubbles spawned can be effectively iframed by swapping characters at the precise moment. However, the hydro bubble will persist on the character that was initially hit for approximately 5 seconds. For more details see: [Mist Bubble iFrame](../../evidence/enemy-data/enemy-attributes.md#mist-bubble-iframe)

## Evidence Vault

{% page-ref page="../../evidence/enemy-data/enemy-attributes.md" %}

