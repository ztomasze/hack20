# Classes

There are two base classes: **Warrior** or **Spellcaster**. The **talent** that you choose at first level and the **feats** you choose a later levels will significantly customize your class.

## Warrior

A warrior relies primarily on their martial training, skills, or feats to succeed.

Warriors are proficient with all weapons, all armor, and all shields.

At level 1:

1. Choose one [fighting style](#fighting-styles).
    * This choice will also affect your minimum starting HP.
1. Choose one [warrior talent](#warrior-talents).
1. Start with a minimum HP of 6+CON.
    * Your fighting style choice may modify this.

### Fighting Styles

#### Mighty

The style of fighters and barbarians.

* Add half your STR (rounded down) to damage rolls with melee and throwable [weapons](equipment.md#weapons).
* When you expend a HD to recover HP as part of a short rest, +CON to the result (if your CON is positive).
* Minimum starting HP: +1

#### Intuitive

The style of rangers and monks.

* Add half your WIS (rounded down) to damage rolls with finesse weapons and ranged [weapons](equipment.md#weapons).
* Add your WIS to DEX when computing your dodge [Armor Class](equipment.md#armor-class).
* Minimum starting HP: +0

#### Cunning

The style of swashbucklers, assassins, and rogues.

* _Sneak Attack:_ If you have advantage on an attack roll, if your attack would automatically hit, or if your target is threatened in melee by another adversary while you attack from within one measure (1M) without disadvantage, your attack deals an extra (1d6 + level) damage. To gain this benefit, you must attack with a finesse, thrown, and non-Massive ranged [weapon](equipment.md#weapons), and your target must be a living creature with vital areas that are within reach of your weapon. Undead, constructs, oozes, plants, swarms, incorporeal creatures, and creatures immune to critical hits lack vital areas to attack. You can only sneak attack once per turn (yours or another's).
* Minimum starting HP: -1

### Warrior Talents

| Warrior Talent | Effect |
| :---- | :---- |
| **Battle Master** | If you roll 21+ on your attack roll, you can immediately perform a [Maneuver](combat.md#maneuver) as a minor action. If your attack drops your target to 0 HP, you can instead spend a minor action to make a second attack using the same weapon against another valid target. |
| **Death Dealer** | When you drop a creature of 1 HD or less to 0 HP with a melee attack on your turn, you gain a free melee attack. You can take this free attack at any point later during this turn, even while moving. This talent cannot grant you more free attacks than your level during a single turn. |
| **Expert** | Gain expertise in two [skills](skills.md) that you have proficiency in. |
| **Rage** | Once per scene, you can expend a HD to enter a rage as a quick action or as a reaction when you take damage. This typically involves performing appropriate acts like roaring, stomping, or biting your shield. While raging, you gain +2 STR, advantage on WIS and CHA saves, and +CON to AC (max: AC17). You cannot cast spells, concentrate, take the Defend action, or perform any calm, careful, or focused tasks while raging. Your rage lasts until the end of the scene. It ends early if you fall unconscious, if you choose to end it as a free action, or if you do not make a melee attack or spend a quick action to extend your rage on your turn. |
| **Spellcasting** | You gain a magical tradition and method as per a level 1 Spellcaster, but you do not gain a spellcaster talent. Your effective level for any spellcasting purpose is 1\. You cannot spend more HD than your spellcasting level per day on your spellcasting method. |
| **Talented** | Gain any two feats (warrior or general) that you qualify for. |
| **Weapon Master** | Gain two instances of the Weapon Specialization feat. Whenever you attack with a weapon for which you have Weapon Specialization, you deal an additional +1 damage. |

## Spellcaster

A spellcaster reminds primarily on their magical ability to succeed. See [Magic](magic.md) for more.

At level 1:

1. Choose your [magical tradition](magic.md#tradition).
    * This choice will also determine your weapon and armor proficiencies.
1. Choose your [magical method](magic.md#method).
    * This choice will determine your [MAGIC](magic.md#magic-1) stat and may affect your minimum starting HP.
1. Choose one [spellcaster talent](#spellcaster-talents).
1. Start with a minimum HP of 5+CON.
    * Your magical method choice may modify this.

### Spellcaster Talents

| Spellcaster Talent | Effect |
| :---- | :---- |

<!--
| **Domain Spells** | Work with your GM to define a list of spells, one per tier, that represents your specific arcane school, deity, patron, or other source of magic. You gain each of these spells as an additional spell known when you are able to cast spells of that tier. | |

Feat

Scholar - Gain expertise in two of the following skills: Arcana, History, Nature, Religion | Proficiency |
* Or is knowledge expertise an INT knack?

| **Turn Undead** | You gain an extra cantrip that is equivalent to the spell Turn the Unholy, but it only affects undead.  If you fail to turn at least one creature when you cast it, you cannot cast it again for the remainder of the scene. | Divine tradition |
| **Wild Stride** | Gain the Survival class skill. In addition, passing through non-magical vegetation does not reduce your speed. | Nature tradition |

Theurgy - Second tradition

| **Dark Harvest** | When a creature dies within 1M of you, you can gain MAGIC temp HP as a reaction. | |
| **Soul Burn** | When you draw mana to cast a spell, you can choose to take one or more wounds. Each wound taken this way adds 8 points to your mana pool. | Way (CHA) caster |
| **Spellbook** | You maintain a record of your swapped spells. Can add scrolls. Cast as adhoc spells.  appearance is up to you.  (As with trappings, your choice may have an impact.) | Word (INT) caster |

Familiar | Arcane or Nature tradition |
-->

## Feats

**Limit:** Specifies how many times you can take this feat, with _U_ standing for unlimited.

**Adding a Hit Die to a roll:** For feats that modify a die roll by expending a HD:

* You may see the results of the d20 or damage roll before you decide whether use the feat modify that roll with a HD. If you do not already know the DC that you need to meet, you must decide whether to modify the roll before the GM tells you whether you succeed or fail.
* To modify the roll, roll one unexpended HD and add it to the roll result. If the HD's result is a 5 or higher, the HD is expended.
* You may only add the result of a single HD to a roll.
* Modifying the roll with an HD in this way does not require an additional action.

### General Feats

| General Feat | Effect | Prereq | Limit |
| :---- | :---- | :---- | :---- |
| **Ability Score Improvement** | Gain \+1 to an ability score that you did not already increase this level up. | Level 2+ | U |
| **Cantrip** | Gain one cantrip. Choose whether you use INT, WIS, or CHA for any spellcasting rolls. | | U |
| **Deadly Accuracy** | Add one HD to an attack roll. The HD is expended on a 5 or higher. | | 1 |
| **Dodge** | The max AC you can achieve when adding your dodge AC to your [Armor Class](equipment.md#armor-class) is 15 + level/2 (round down). | Acrobatics, Level 2+ | 1 |
| **Expertise** | Gain expertise in one [skill](skills.md) that you have proficiency in. | Expert | U |
| **Great Fortitude** | Gain a +2 bonus on STR and CON saves. | | 1 |
| **Iron Will** | Gain a +2 bonus on WIS and CHA saves. | | 1 |
| **Lightning Reflexes** | Gain a +2 bonus on DEX saves and initiative rolls. | | 1 |
| **Skill** | Gain proficiency in one [skill](skills.md) of your choice. | | U |

<!--
SPELLCASTER
just convert to general - if it's not something a Spellcasting warrior can do, it's a Talent

| **Subtle Spell** | As a quick action, you can forgo either the verbal or somatic component required to cast spells this turn. As a minor action, you can forgo both. | |

Extra Spell known

Agonizing Blast - Your Eldritch Blast deals damage equal to d3 + level / 2, round down.
or: d6 or d8 damage?

Battlefield Healer - Can cast Cure Damage spells as a minor (rather than major) action. When you cast a spell that restores hit points, +2 to the number of hit points per spell tier. 

-->

### Warrior Feats

| Warrior Feat | Effect | Prereq | Limit |
| :---- | :---- | :---- | :---- |
| **Brawler** | Your [unarmed attack](equipment.md#unarmed-attacks) deals +d damage (d3 or d4 instead of d2 or d3) and you can choose to deal lethal damage. Even if your hands are full, you can make an unarmed attack using a kick, knee, elbow, etc. If both hands are free, you can either gain the benefits of two-weapon fighting or deal both unarmed attack damage dice (2d3 or 2d4) as a single attack. You are considered armed for the purposes of threatening adjacent foes. | | 1 |
| **Burly** | Add your STR to your HP. In addition, when you wear no armor or light armor, you can add your STR to your armor AC to a max of armor AC 13. | | 1 |
| **Deadly Damage** | Add a roll of one (max) unexpended HD to the damage you deal with a weapon attack. The HD is expended on a 5 or higher. | | 1 |
| **Dual Wielder** | When two weapon fighting, your offhand attack penalty is reduced by 2 (usually from -4 to -2). You can draw an offhand weapon as part of the same action you use to draw your primary weapon. | DEX +3 | 1 |
| **Extra Attack** | When you take the Attack action on your turn, you can spend a minor action to make a single additional attack. | Level 5+ | 1 |
| **Improved Spellcasting** | Increase your effective spellcaster level by 1 (including how many HD you can spend per day on spellcasting method effects), and update your POWER and spells known accordingly. You can take this feat a maximum of three times, only at (or after) the levels listed. | Spellcasting talent; Level 3+, 5+, 7+. | 3 |
| **Second Wind** | Once per scene, as a quick action, expend a HD to regain 1d8 (min: CON) HP. | Athletics or Great Fortitude | 1 |
| **Uncanny Dodge** | As a reaction when you take damage, expend a HD to subtract 1d8 (min: DEX, or half of the incoming damage, rounded down) from the damage you are about to take. Expending two HD reduces the damage to 0. You cannot use this ability if you are immobilized. | Acrobatics or Lightning Reflexes | 1 |
| **Weapon Specialization (X)** | Choose one weapon type, such as longbow or shortsword. You gain +1 to attack and damage rolls when you attack with a weapon of that type. Each time you gain a level, you may change the weapon type you have chosen for this feat. | Proficiency in the chosen weapon | U |

<!-- POTENTIAL warrior feats

Blindfight

?Close Quarter Shot - Being threatened in melee does not impose disadvantage on your ranged attack rolls.

Deflect Missiles

Defender - able to shield an adjacent ally

mounted combat - reaction (and Animal Handling(DEX) check?) to negate a hit on your mount; mount or dismount as a quick action; can trample (quick action to direct your mount to attack)

?Rapid Shot - 2 shots per Attack at -2

Sharpshooter - Ignore cover.  Or downgrade cover by 1 step.

Stunning Fist - quick action when you hit with an unarmed attack and expend a HD to force a save vs DC10+WIS or be stunned for a round.  Can't stun constructs, oozes, plants, undead, incorporeal creatures, or creatures immune to critical hits.

| **Extra Attack** | When you make a weapon attack, you can expend a HD to attack again. You can only do this only once per round on your turn. | |
| **Extraordinary Ability** | Choose three cantrips or tier 1 spells. One of these spells can be of tier 2 with some kind of limitation. The spell effects should have trappings subtle enough to have a supernatural explanation (subject to GM approval), and all of them may require some other limitation to activate. You always produce a tiered spell effect by rolling a single HD; if you fail to draw sufficient mana with that HD, it is expended. Your magic ability score can be any ability score appropriate to the effect.  See _Archetypes_ for examples. | **Level 1** |

| ***Magical Dabbler*** | You can activate a scroll, wand, or magic item even if it requires a spell that is not on your spell list or you have no spell list at all. Choose either INT or CHA as the basis of your pseudo-spellcasting ability when you take this talent. | |

Maybe: +Get a random magic item of a category you choose. Each level up, you can acquire a replacement random item, but your previous item then becomes unusable.

Evasion: half damage from area effects provided you are not paralyzed or restrained.  pre: Level 5+, Lighting Reflexes
* See: Uncanny Dodge

Sentinel - ability to hit things that try to leave or move past you

-->

## Levels

You can purchase a new level by spending 1000 XP during a successful long rest.

When you gain a new level, you:

1. **Gain +1 HD**
1. **Reroll your max HP:** Roll (new level)d8 + CON.
    * If the result is higher than your current HP max, replace it.
    * Otherwise, add 1 to your current HP max.
1. **Gain +1 to one ability score**
    * You cannot increase an ability score above the max shown in the table below.
    * Remember to update any derived stats, such as MAGIC or POWER.
1. Warriors get to learn a feat at every level.
1. Spellcasters gain access to a new spell tier at odd levels and gain a feat at every even level.

| Level | Total Hit Dice | Ability Score | Max Ability Score | Warrior | Spellcaster |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **2** | 2d8 | +1 | +5 | **Feat** (warrior or general) | **Feat** (general) |
| **3** | 3d8 | +1 | +5 | **Feat** (warrior or general) | **Spell Tier 2** |
| **4** | 4d8 | +1 | +6 | **Feat** (warrior or general) | **Feat** (general) |
| **5** | 5d8 | +1 | +6 | **Feat** (warrior or general) | **Spell Tier 3** |
| **6** | 6d8 | +1 | +7 | **Feat** (warrior or general) | **Feat** (general) |
| **7** | 7d8 | +1 | +7 | **Feat** (warrior or general) | **Spell Tier 4** |
| **8** | 8d8 | +1 | +8 | **Feat** (warrior or general) | **Feat** (general) |

### Epic Levels

You can continue to adventure after level 8. However, you no longer gain class features.  For this reason, epic levels are denoted as 8.1, 8.2, 8.3, etc.

Each time you gain a new epic level:

1. **Reroll your max HP:** Roll 8d8 + CON.
    * If the result is higher than your current HP max, replace it.
    * Otherwise, add 1 to your current HP max.
1. **Gain +1 HD**
    * This epic HD does not contribute to your HP, but you can expend it to power character features like feats, talents, or spellcasting.

<!--
## Archetypes

The following **archetypes** illustrate how to use the class and feat system to replicate more specific classes from other games or common tropes from other media. These also serve as quickstart way to jump into the game with a specific character type.

-->
