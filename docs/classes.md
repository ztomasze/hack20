# Classes

There are two base classes: **Spellcaster** or **Warrior**.

At first level, the magical **tradition** and spellcasting **method** that you choose as a spellcaster or the **fighting style** and **talent** that you choose as a warrior will significantly customize your class. At later levels, you can can continue to extend your abilities with **feats**.

## Spellcaster

A spellcaster reminds primarily on their magical ability to succeed. See [Magic](magic.md) for more.

At level 1:

1. Choose your [magical tradition](magic.md#tradition).
    * This choice will also determine your weapon and armor proficiencies.
1. Choose your [spellcasting method](magic.md#method).
    * This choice will determine your [MAGIC](magic.md#magic-1) stat and may affect your minimum starting HP.
1. Start with a minimum HP of 5+CON.
    * Your magical method choice may modify this.

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
* When you expend a HD to recover HP, you recover d8+CON if your CON is positive (instead of 1d8, min: CON).
* Minimum starting HP: +1

#### Intuitive

The style of rangers and monks.

* Add half your WIS (rounded down) to damage rolls with finesse weapons and ranged [weapons](equipment.md#weapons).
* Add your WIS to DEX when computing your dodge [Armor Class](equipment.md#armor-class).
* Minimum starting HP: +0

#### Cunning

The style of swashbucklers, assassins, and rogues.

* _Sneak Attack:_ If you have advantage on an attack roll, if your attack would automatically hit, or if your target is threatened in melee by another adversary while you attack from within one measure (1M) without disadvantage, your attack deals an extra (1d6 + level) damage. To gain this benefit, you must attack with a finesse, thrown, or non-Massive ranged [weapon](equipment.md#weapons), and your target must be a living creature with vital areas that are within reach of your weapon. Undead, constructs, oozes, plants, swarms, incorporeal creatures, and creatures immune to critical hits lack vital areas to attack. You can only sneak attack once per turn (yours or another's).
* Minimum starting HP: -1

### Warrior Talents

| Warrior Talent | Effect |
| :---- | :---- |
| **Battle Master** | If you roll 21+ on your attack roll, you can immediately perform either a [Hinder](combat.md#hinder) or [Maneuver](combat.md#maneuver) as a minor action. If your attack drops your target to 0 HP, you can instead spend a minor action to make a second attack using the same weapon against another valid target. |
| **Death Dealer** | When you drop a creature of 1 HD or less to 0 HP with a melee attack on your turn, you gain a free melee attack. You can take this free attack at any point later during this turn, even while moving. This talent cannot grant you more free attacks than your level during a single turn. |
| **Expert** | Gain proficiency in one skill. Gain expertise in two [skills](skills.md) that you have proficiency in. |
| **Rage** | Once per scene, you can expend a HD to enter a rage as a quick action or as a reaction when you take damage. This typically involves performing appropriate acts like roaring, stomping, or biting your shield. While raging, you gain +2 STR, advantage on WIS and CHA saves, and +CON to AC (max: AC17). You cannot cast spells, concentrate, take the Defend action, or perform any calm, careful, or focused tasks while raging. Your rage lasts until the end of the scene. It ends early if you fall unconscious, if you choose to end it as a free action, or if you do not make a melee attack or spend a quick action to extend your rage on your turn. |
| **Spellcasting** | You gain a magical tradition and method as per a level 1 Spellcaster, but you do not gain a spellcaster talent. Your effective level for any spellcasting purpose is 1\. You cannot spend more HD than your spellcasting level per day on your spellcasting method. |
| **Talented** | Gain any two feats (warrior or general) that you qualify for. |
| **Weapon Master** | Gain two instances of the Weapon Specialization feat. Whenever you attack with a weapon for which you have Weapon Specialization, you deal an additional +1 damage. |

## Feats

**Limit:** Specifies how many times you can take this feat. _U_ stands for unlimited.

**Adding a Hit Die to a roll:** For feats that modify a die roll by expending a HD:

* You may see the results of the d20 or damage roll before you decide whether use the feat modify that roll with a HD. If you do not already know the DC that you need to meet, you must decide whether to modify the roll before the GM tells you whether you succeed or fail.
* To modify the roll, roll one unexpended HD and add it to the roll result. If the HD's result is a 5 or higher, the HD is expended.
* You may only add the result of a single HD to a roll.
* Modifying the roll with an HD in this way does not require an additional action.

### General Feats

| General Feat | Effect | Prereq | Limit |
| :---- | :---- | :---- | :---- |
| **Ability Score Improvement** | Gain \+1 to an ability score that you did not already increase this level up. | Level 2+ | U |
| **All Saves** | Gain a +2 bonus on all saves. This bonus does not stack with the bonus granted by any of the listed prerequisite feats. | Great Fortitude, Iron Will, or Lightning Reflexes | 1 |
| **Cantrip** | Gain one cantrip. Choose whether you use INT, WIS, or CHA for any spellcasting rolls. | | U |
| **Deadly Accuracy** | Add one HD to an attack roll. The HD is expended on a 5 or higher. | | 1 |
| **Dodge** | The max AC you can achieve when adding your dodge AC to your [Armor Class](equipment.md#armor-class) is 15 + level/2 (round down). | Acrobatics, Level 2+ | 1 |
| **Expertise** | Gain expertise in one [skill](skills.md) that you have proficiency in. | Expert | U |
| **Great Fortitude** | Gain a +2 bonus on STR and CON saves. | | 1 |
| **Immunity (X)** | You are immune to a given class of effects. Examples and their prerequisites include:<br>&bull; Charm (including compulsions) - Iron Will<br>&bull; Disease - Great Fortitude<br>&bull; Fear - Iron Will<br>&bull; Poison - Great Fortitude<br>Other options may be possible (talk to your GM). | Great Fortitude or Iron Will | U |
| **Iron Will** | Gain a +2 bonus on WIS and CHA saves. | | 1 |
| **Lightning Reflexes** | Gain a +2 bonus on DEX saves and initiative rolls. | | 1 |
| **Skill** | Gain proficiency in one [skill](skills.md) of your choice. | | U |
| **Tough** | Add your STR to your HP. In addition, when you wear no armor or light armor, you can add your STR to your armor AC to a max of armor AC 13. | STR 1+ | 1 |

### Spellcaster Feats

### Warrior Feats

| Warrior Feat | Effect | Prereq | Limit |
| :---- | :---- | :---- | :---- |
| **Brawler** | You gain several benefits when making [unarmed attacks](equipment.md#unarmed-attacks):<br>&bull; You deal +d damage with unarmed attacks and you can choose to deal lethal damage. For example, your barehanded unarmed attack deals d3 and a cestus punch deals d4.<br>&bull; If you have the Intuitive fighting style, your barehanded unarmed attacks gain another +d (to d4).<br>&bull; At level 5, your unarmed attacks gain another +d.<br>&bull; Even if your hands are full, you can make a single unarmed attack using a kick, knee, elbow, etc.<br>&bull; If both your hands are free to punch, you can either gain the benefits of [two-weapon fighting](combat.md#two-weapon-fighting) or make a single unarmed attack with one hand and add the damage die (with no other bonuses) of your offhand.<br>&bull; You are considered armed for the purposes of [threatening](combat.md#threatening) adjacent foes. | | 1 |
| **Deadly Damage** | Add a roll of one (max) unexpended HD to the damage you deal with a weapon attack. The HD is expended on a 5 or higher. | | 1 |
| **Dual Wielder** | When two weapon fighting, your attack penalty reduced by 2 for each hand (usually from -2/-4 to -0/-2). You can draw an offhand weapon as part of the same action you use to draw your primary weapon. | DEX 3+ | 1 |
| **Evasion** | When you are subjected to an effect that allows you to make a DEX save to take only half damage, you instead take no damage if you succeed on the saving throw, and only half damage if you fail. | Acrobatics or Lightning Reflexes; Level 5+ | 1 |
| **Extra Attack** | When you take the Attack action on your turn, you may spend a quick action later this turn to make a single additional attack at -5 using the same weapon. You cannot make a [two-weapon fighting](combat.md#two-weapon-fighting) offhand attack in the same turn. | Level 5+ | 1 |
| **Improved Spellcasting** | Increase your effective spellcaster level by 1 (including how many HD you can spend per day on spellcasting method effects), and update your POWER and spells known accordingly. You can take this feat a maximum of three times, only at (or after) the levels listed. | Spellcasting talent; Level 3+, 5+, 7+. | 3 |
| **Second Wind** | You can expend a HD to regain HP as a minor action.  See [Hit Dice (HD)](stats.md#hit-dice-hd) for more. | Mighty Fighting Style, Athletics, or Great Fortitude | 1 |
| **Uncanny Dodge** | When you are hit by an attack that you can see while you can freely move your body (for example, you are not restrained, encumbered, or immobilized), you can attempt to reduce the damage of the blow. This might manifest as you deflecting an arrow or defensively rolling with the force of a melee attack. As a reaction, you can reduce the damage of such an attack by 1d8+DEX. If you expend a HD when you do this, you retain your reaction. | Acrobatics or Lightning Reflexes | 1 |
| **Weapon Specialization (X)** | Choose one weapon type, such as longbow or shortsword. You gain +1 to attack and damage rolls when you attack with a weapon of that type. Each time you gain a level, you may change the weapon type you have chosen for this feat. | Proficiency in the chosen weapon | U |

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
1. Warriors get to learn a feat (either general or warrior) at every level after first.
1. Spellcasters gain access to a new spell tier at odd levels and gain a feat (general or spellcaster) at every even level.

| Level | Total Hit Dice | Ability Score Increase | Max Ability Score | Warrior | Spellcaster |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | 1d8 | ([generate](stats.md#generating-scores)) | +4 (with racial bonus) | Fighting Style, Talent | Tradition, Method, Spell Tier 1 |
| 2 | 2d8 | +1 | +5 | Feat | Feat |
| 3 | 3d8 | +1 | +5 | Feat | Spell Tier 2 |
| 4 | 4d8 | +1 | +6 | Feat | Feat |
| 5 | 5d8 | +1 | +6 | Feat | Spell Tier 3 |
| 6 | 6d8 | +1 | +7 | Feat | Feat |
| 7 | 7d8 | +1 | +7 | Feat | Spell Tier 4 |
| 8 | 8d8 | +1 | +8 | Feat | Feat |

### Epic Levels

You can continue to adventure after level 8. However, you no longer gain class features.  For this reason, epic levels are denoted as 8.1, 8.2, 8.3, etc.

Each time you gain a new epic level:

1. **Reroll your max HP:** Roll 8d8 + CON.
    * If the result is higher than your current HP max, replace it.
    * Otherwise, add 1 to your current HP max.
1. **Gain +1 HD**
    * This epic HD does not contribute to your HP, but you can expend it to power class features like feats, talents, or spellcasting or to recover HP during a rest.

