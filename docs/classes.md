# Classes

There are two base classes: **Warrior** or **Spellcaster**. The **feats** (**talents** for warriors and **knacks** for spellcasters) that you choose at first level and at each later level will significantly customize your class.

## Warrior

A warrior relies primarily on their martial training, skills, and talents to succeed.

At level 1:

1. Choose a **fighting style**.
1. Choose one starting **talent**.
    * It is recommended you choose a "Level 1" talent, as these cannot be gained later.
1. Minimum starting HP: 6+CON
    * Your fighting style choice may then modify this.

### Fighting Styles

#### Mighty

The style of fighters and barbarians.

* Add half your STR (rounded down) to damage rolls with melee and throwable [weapons](equipment.md#weapons)
* When you expend a HD to recover HP as part of a short rest, you recover a minimum of CON HP.
* Minimum starting HP: +1

#### Intuitive

The style of rangers and monks.

* Add half your WIS (rounded down) to damage rolls with finesse weapons and ranged [weapons](equipment.md#weapons)
* Add your WIS to DEX when applying your DEX to [Armor Class](equipment.md#armor-class).
* Minimum starting HP: +0

#### Cunning

The style of swashbucklers, assassins, and rogues.

* _Sneak Attack:_ If you have advantage on an attack roll, if your attack would automatically hit, or if your target is threatened in melee by another adversary while you attack from within one measure without disadvantage, your attack deals an extra (1d6 + level) damage. To gain this benefit, you must attack with a finesse, thrown, and non-Massive ranged [weapon](equipment.md#weapons), and your target must be a living creature with vulnerable spots that are within reach of your weapon. You can only sneak attack once per turn (yours or another's).
* Minimum starting HP: -1

### Talents

**Prereq:** Talents marked as "Level 1" can only be taken at first level.

**Adding a Hit Die to a roll:** For talents that modify a die roll by expending a HD:

* You can see the results of the roll before you decide whether to expend a HD to add +1d8 to the result.
* If you do not already know the DC that you need to meet, you must decide whether to modify the roll before the GM tells you whether you succeed or fail.
* You may expend more than one HD, one at a time, to modify the current roll. This does not require an additional action.
* If the result of a HD is 1 or 2, the result it added to the roll but the HD is not expended after all. However, you cannot apply that same HD again to the current roll.
* Some talents let you substitute a specific ability score as a minimum value for the d8 rolled.

| Talent | Effect | Prereq |
| :---- | :---- | :---- |
| **Ability Score Improvement** | Gain \+1 to an ability score that you did not already increase this level up. | Level 2+ |
| **Battle Master** | If you roll 21+ on your attack roll, you can immediately perform a combat maneuver as a move. If your attack drops your target to 0 HP, you can instead spend your move to make a second attack using the same weapon against another valid target. | **Level 1** |
| **Boosted Attacks** | Expend a HD to add it to an attack roll. (Min: STR or DEX) | |
| **Boosted Damage** | Expend a HD to add it to damage you deal with a weapon attack. (Min: 5) | |
| **Brawler** | Your unarmed attack deals d4 damage (+2d) and you can choose to deal lethal damage. Even if your hands are full, you can make an unarmed attack using a kick, knee, elbow, etc. If both hands are free, you can either gain the benefits of two-weapon fighting or deal 2d4 damage. | |
| **Dodge** | The max AC you can achieve when adding your DEX to your [Armor Class](equipment.md#armor-class) is 15 + level/2 (round down). | Acrobatics, Level 2+ |
| **Expert** | Gain expertise in two [skills](skills.md) that you have proficiency in. In addition, when you roll a check for a skill you are proficient in, you can expend a HD to turn one of the rolled d20s to a 10. | **Level 1** |
| **Expertise** | Gain expertise in one [skill](skills.md) that you have proficiency in. | |
| **Great Fortitude** | Expend a HD to add it to a STR or CON save. | |
| **Healing Surge** | As a quick action, expend a HD to regain HP equal to the value rolled. (Min: CON) | |
| **Improved Spellcasting** | Increase your effective spellcaster level by 1 (including how many HD you can spend per day on spellcasting method effects), and update your POWER and spells known accordingly. You can take this talent a maximum of three times, only at (or after) the levels listed. | Spellcasting; Level 3+, 5+, 7+. |
| **Iron Will** | Expend a HD to add it to a WIS or CHA save. | |
| **Lightning Reflexes** | Expend a HD to add it to a DEX save or initiative roll. | |
| **Mighty Cleave** | If you are wielding a melee weapon, you can spend your Attack action to make (level) attacks this turn against targets of 1 HD or less. You may make these attacks as you move. | Fighting Style: Mighty |
| **Rage** | Once per scene, you can expend a HD to enter a rage as a minor action. This typically involves appropriate performative acts like roaring, stomping, or biting your shield. While raging, you gain +2 STR, +2 to WIS and CHA saves, and +CON to AC (max: AC17). You cannot cast spells, concentrate, take the Defend action, or perform calm, careful, or focused tasks while raging. Your rage lasts until the end of the scene. It ends early if you fall unconscious, if you choose to end it as a free action, or if you do not make a melee attack or spend a minor action to extend your rage on your turn. | **Level 1** |
| **Skill** | Gain proficiency in one [skill](skills.md) of your choice. | |
| **Spellcasting** | As per a level 1 Spellcaster, you gain a magical tradition and style, but no knack. Your effective level for any spellcasting purpose is 1\. You cannot spend more HD than your spellcasting level on your spellcasting method per day. | **Level 1** |
| **Uncanny Dodge** | As a reaction when you take damage, expend a HD to subtract the value rolled from the damage you are about to take. (Min: DEX or half the incoming damage, rounded down) | |

<!-- POTENTIAL Talents

| **Extra Attack** | When you make a weapon attack, you can expend a HD to attack again. You can only do this only once per round on your turn. | |
| **Extraordinary Ability** | Choose three cantrips or tier 1 spells. One of these spells can be of tier 2 with some kind of limitation. The spell effects should have trappings subtle enough to have a supernatural explanation (subject to GM approval), and all of them may require some other limitation to activate. You always produce a tiered spell effect by rolling a single HD; if you fail to draw sufficient mana with that HD, it is expended. Your magic ability score can be any ability score appropriate to the effect.  See _Archetypes_ for examples. | **Level 1** |

| ***Magical Dabbler*** | You can activate a scroll, wand, or magic item even if it requires a spell that is not on your spell list or you have no spell list at all. Choose either INT or CHA as the basis of your pseudo-spellcasting ability when you take this talent. | |

Maybe: +Get a random magic item of a category you choose. Each level up, you can acquire a replacement random item, but your previous item then becomes unusable.

Evasion: half damage from area effects provided you are not paralyzed or restrained.  pre: Level 5+, Lighting Reflexes
* See: Uncanny Dodge

-->

<!--
## Archetypes

The following **archetypes** illustrate how to use the class and feat system to replicate more specific classes from other games or common tropes from other media. These also serve as quickstart way to jump into the game with a specific character type.

-->
