# Damage Formula

## **General Formula for Damage**

$$
\begin{multline*}
Damage = BaseDamage \times  (1 + DamageBonus) \times Crit\\
\times EnemyDefenseModifier\times EnemyResistanceModifier\\
\times AmplifyingReactionBonus\times OtherBonus+TransformativeReaction+Proc
\end{multline*}
$$
## **Base Damage**

$$
BaseDamage =
\begin{cases}
Talent \times Attack + FlatDamage & \text{if, } talent\ scales\ with\ Attack\\
Talent \times Defense + FlatDamage & \text{if, } talent \ scales\ with\ Defense
\end{cases}
$$

$$
Attack = (AttackCharacter + AttackWeapon) \times (1 + AttackBonus) + FlatAttack
$$

$$
Defense = DefenseCharacter \times (1 + DefenseBonus) + FlatDefense
$$

| Formula Variable | Explanation |
| :--- | :--- |
| **Talent** | The damage percentage specified by the talent \(ex: a value of 324% should be inputted as 3.24\). |
| **AttackCharacter** | Character's base attack. |
| **AttackWeapon** | Weapon's base attack. |
| **AttackBonus** | Sum of all percentage-based attack bonuses from artifacts and other sources. |
| **FlatAttack** | Sum of all non-percentage-based attack bonuses from the feather and other sources. |
| **DefenseCharacter** | Charcter's base defense. |
| **DefenseBonus** | Sum of all percentage-based defense bonuses from artifacts and other sources. |
| **FlatDamage** | Extra damage from Zhongli's A4 passive. |
| **DamageBonus** | Sum of all damage increases from elemental goblets, Gladiator's Finale 4-piece bonus, etc, excluding Xingqiu's constellation 4 effect Evilsoother. |

## Critical Hits

$$
Crit=
\begin{cases}
1 + CritDamage & \text{with } min\{100\%,CritRate\}\ probability\\
1 & \text{otherwise }
\end{cases}
$$

$$
AverageCrit = 1 + min\{CritRate,100\%\} \times CritDamage
$$
| Formula Variable | Explanation |
| :--- | :--- |
| **CritRate** | The total crit rate, including the 5% base crit rate and bonuses from artifacts, etc. |
| **CritDamage** | The total crit damage, including the 50% base crit rate and bonuses from artifacts, etc. |

## Enemy Defense

![](https://lh5.googleusercontent.com/XhXkMOeRep9gAktBxQN6VecPOQDwDcuyVL6jVRvyCvRpu5y55uG9_Wf1NLrm9rd6pAu1QEYfgdlIzHfjJRWZ1K3zL6glorl4Fojq98hLHY1YtUwdlcPBeADLqXnWGryTk_YJzNo)
$$
EnemyDefenseModifier = \frac{LvlCharacter + 100}{(LvlCharacter + 100) + (LvlEnemy + 100) \times (1-DefReduction)}
$$
| Formula Variable | Explanation |
| :--- | :--- |
| **LvlCharacter** | The player character's level. |
| **LvlEnemy** | The enemy's level. |
| **DefReduction** | The total defense \(but not resistance\) reduction from effects such as Razor's Constellation 4, Lisa Ascension 4, and Klee Constellation 2. |

## Enemy Resistance

![](https://lh5.googleusercontent.com/cxfHRkejG6vheJgQcYtEMkFRvhR_HyX7joH_aoPl5YxzKl-CIZ2TVsP2ojrnKINLbALXwQBdETrmh-7GmK6QxDljuUNypffw00cI_nOgLGfTuiI9imzWdD941Lr-OIBdYJZl-kk)

$$
Enemy Resistance Modifier =
\begin{cases}
1 - \frac{Resistance}{2} & \text{if, } Resistance \lt 0\\
1 - Resistance & \text{if, } 0 \le Resistance \lt 0.75\\
\frac{1}{4 \times Resistance + 1} & \text{if, } Resistance \ge 0.75
\end{cases}
$$

$$
Resistance = BaseResistance - ResistanceReduction
$$

| Formula Variable | Explanation |
| :--- | :--- |
| **BaseResistance** | The enemy's base resistance to the element of the talent being used. [Check the Genshin Wikia ](https://genshin-impact.fandom.com/wiki/Damage%23Base_Enemy_Resistances%20)for a table of all enemy base elemental resisistances. |
| **ResistanceReduction** | The total resistance reduction of the relevant element from effects such as Superconduct and Viridescent Venerer. |

## Amplifying Reaction Bonus

$$
AmplifyingReactionBonus =
\begin{cases}
2 \times (1 + \frac{2.78 \times EM}{1400 + EM} + ReactionBonus) & \text{if, } triggering\\ 
                                                                & Vaporize\ with\ Hydro\ or\\ 
                                                                & Melt\ with\ Pyro\\
1.5 \times (1 + \frac{2.78 \times EM}{1400 + EM} + ReactionBonus) & \text{if, } triggering\\
                                                                &Vaporize\ with\ Pyro\ or\\
                                                                & Melt\ with\ Cryo\\
1 & \text{otherwise}
\end{cases}
$$

| Formula Variable | Explanation |
| :--- | :--- |
| **EM** | The character's total Elemental Mastery. |
| **ReactionBonus** | Reaction damage bonuses from the Crimson Witch 4-piece set and from Mona's C1 \(for Vaporize\). |

## Other Bonus

![](https://lh4.googleusercontent.com/jUt7AhNKkro5XfTSG3V8XfXvOTFV1_yoQpwPBbz0dkGaC8QiazdbnaHtYw6WHT-E6YfSKSspwGeL5lMK_qCe9xG6hiOI6m9fiJVS2A2zUWs_lV0KIOYoaQI4EdaIn98gOeBSiCU)
$$
OtherBonus =
\begin{cases}
1.5  & \text{if, } Evilsoother\ triggered\\
1 & \text{otherwise}
\end{cases}
$$

| Formula Variable | Explanation |
| :--- | :--- |
| **Evilsoother** | Xingqiu’s Constellation 4 ability and applies a 1.5 buff to his elemental skill |

## Transformative Reaction Bonus

![](https://lh5.googleusercontent.com/RIjoNwqG5NP-KTKkIhVPzdhlhPC5K1DeE1WKZSPXjbc5aJ_BUc67ZznDRR8OL03lSLkCVRXrfWozd9yx3qPRYXhG8AxU-PZT4FL5oWKjvM8E_LuQX1UcUc1uG8IHPlwjxsroUJo)
$$
\begin{multline*}
TransformativeReaction = 
\biggl(
\begin{cases}
4 & \text{if, } triggering\ Overloaded\\
3 & \text{if, } triggering\ Shatter\\
2.4 \times ECTriggers & \text{if, } triggering\ ElectroCharged\\
1.2 & \text{if, } triggering\ Swirl\\
1 & \text{if, } triggering\ Superconduct\\
0 & \text{otherwise}
\end{cases}
\biggr)
\\
\times \bigl( 1 + \frac{6.66 \times EM}{1400 + EM} + ReactionBonus `bigr)\\
\times LevelMultiplier \times EnemyResistanceMultiplier
\end{multline*}
$$

$$
LevelMultiplier \approx 0.0002325 \times LvlCharacter^{3} + 0.05547 \times LvlCharacter^{2} - 0.2523 \times LvlCharacter + 14.74
$$

| Formula Variable | Explanation |
| :--- | :--- |
| **ECTriggers** | The number of times Electro-Charged triggers, and depends on the elemental gauge strength of the hydro and electro elements applied to the enemy. |
| **EM** | The character's total Elemental Mastery. |
| **ReactionBonus** | Includes reaction damage bonuses from the Thundering Fury and Viridescent Venerer 4-piece sets and from Mona's Constellation 1. |
| **LevelMultiplier** | Check the [Genshin Wikia](https://genshin-impact.fandom.com/wiki/Damage#Transformative_Reaction_Damage). |
| **EnemyResistance Multiplier** | Uses the formula above, but for the element of the transformative reaction \(pyro for overloaded, physical for shattered, electro for electro-charged, cryo for superconduct, and the element being swirled for swirl\). |
| **Proc** | The damage dealt by weapon and ability procs when they trigger, such as Prototype Archaic or Xiangling's constellation 2. To calculate this damage, substitute the proc percentage \(e.g. 240% for Prototype Archaic R1\) for Talent in the damage formula. Note that weapon proc effects always deal physical damage, and are therefore affected by physical damage bonuses and physical resistance, even if an elemental attack is used to trigger them. |

By Zakharov\#5645 and \[Neko\]\#3521

