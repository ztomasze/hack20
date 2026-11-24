# Equipment

## Equipment Slots

Equipment is carried in terms of **slots**. A slot is a composite measure of both weight and bulk. It usually represents about 5 pounds or the volume of your forearm and fist.

* Unless otherwise noted, each item takes up 1 slot.
* Some larger items take up multiple slots.
* Up to 2 small (roughly fist-sized) items can be placed in one slot, such as a pair of daggers.
* Up to 10 tiny (roughly finger-sized) items can be placed in one slot, but only if they are in a container. This can be a mix of items of different types, such as 2 keys, 3 potion vials, 4 candles, and flint & steel in a pouch in the same slot.
* Up to 200 coins or coin-like objects can be carried in one slot if they are in a container. This can include gems, rings, earrings, and similar items of high value. However, hunting around for a ring in a pouch of coins will take a minute; if you want to be able to recover such an item quickly, stow it as a tiny object in a quick slot.

### Encumbrance

Carrying a lot of gear will encumber you:

| Slots Carried | Load | Encumbrance Level | [Speed](combat.md#speed) Effects |
| :---- | :---- | :---- | :---- |
| <= 10+STR | light | unencumbered | None |
| <= 20+STR | medium | encumbered | Speed limited to 1/2 speed |
| <= 30+STR | heavy | heavily encumbered | Speed limited to 1/4 speed (only a step or two) |

* You cannot lift or carry more than 30+STR slots at once.
* Encumbrance limits or caps your speed, rather than directly halving it. This means that the first effect that halves your speed--such as difficult terrain, etc--is not cumulative with encumbrance (and the first two halvings are not cumulative with heavy encumbrance), but any further halving of your speed proceeds normally.
* Much like wearing medium or heavy armor, being encumbered may also affect certain activities--such as stealth, swimming, etc--depending on the nature of the load you are carrying. For example, you usually swim at disadvantage while encumbered, and you will sink if you are heavily encumbered.
* Beyond the first few items you carry, you must place equipment in appropriate containers to be able to carry it, as explained below.

### Worn Items

Worn items are free to carry, within reason. A humanoid is limited to 14 possible worn-item body slots. In particular, this limits the number of magic items of a similar type that you can benefit from.  For example, donning a second ring on the same hand or donning a magic shirt while already wearing a magic kilt grants no effect.

<!-- markdownlint-disable MD004-->
+ 1 x **clothing**: shirt, vest, vestment, dress, kilt, and/or pants
+ 1 x **body**: suit of armor or robe (over clothing)
+ 1 x **pack**: backpack, satchel, or haversack
+ 1 x **purse**: coin purse
<!-- markdownlint-enable MD004 -->

* 1 x **head**: hat, headband, helmet, crown, circlet, or phylactery
* 1 x **eyes**: glasses, lenses, or goggles
* 1 x **throat**: amulet, brooch, medallion, necklace, periapt, or scarab
* 1 x **shoulders**: cloak, cape, or mantle (over body)
* 1 x **arms**: bracers, bracelet, or armband
* 1 x **hands**: a pair of gloves or gauntlets
* 2 x **rings**: one magical ring per hand
* 1 x **waist**: belt or girdle (over body)
* 1 x **feet**: a pair of boots, shoes, sandals, slippers, or socks

When you stow a worn item, it takes up slot space again.

### Quick Slots

You can carry some items strapped to your body such that they are always within fast and easy reach. Examples include weapons and items sheathed at your belt, slung over your shoulder or across your back, or in a side sleeve of your backpack.

* You have 7 quick slots that you can use to store such handy items. You can draw an item from a quick slot as a [quick action](combat.md#quick-actions).
* The specific items you carry at the ready in this way must still be reasonable. For example, carrying seven handy longswords is not really reasonable, but carrying a longbow (2 slots), quiver, two shortswords, belt pouch, and an unlit torch within quick reach is more believable.
* Items currently in your hands do not count against your quick slot limit, but they do count against your total number of carried slots.

### Containers

You must use containers to carry more gear than your worn items slots and quick slots. Also, you can only combine tiny or smaller items into a single slot if they are in a container.

* A container's size represents the minimum amount of space that it takes up when it is carried empty. Once its own contents exceed this size, use the total slot size of its contents as the container's size.
* A container has a capacity, which is the maximum number of slots of equipment that can be placed inside it.
* If a container is in quick slot, you can retrieve items from it as a quick action. Otherwise, it takes a major action to retrieve an item that is stowed in a container.
* Some specialty containers--such as quivers, healing kits, scroll cases, etc--are designed to carry a very specific set or kind of item. This specialization means such containers may allow you to carry more items in them than normal. You can also draw items from a specialty container as a free action if it is in a quick slot.

### Coins

1 gold piece (gp) = 10 silver (sp) = 100 copper (cp).

Some settings may include additional metals, such as platinum (1 pp = 10 gp) or electrum (1 ep = 5 sp).

### Oversized Items

Carrying bulky items gets awkward fast. While exceptions may exist for particularly compact heavy items, in general:

* You can only carry two items that require 2 slots or more, and you cannot place them in a mundane container.
* You can only carry items that require 3 slots or more in your hands, as they are too long or unwieldy to sheathe or strap to you. (You might carry a bit of rope to tie the item to dangle below you while climbing, though.)

## Armor Class

Your **armor class** (AC) determines how difficult you are to hit in combat.

Your AC = armor AC + shield AC + dodge AC + cover AC + untyped bonuses to AC

* **Armor AC:** Start with your highest armor AC or 10 if you are unarmored. For example, while some armor combinations are unreasonable, you might wear a padded gambeson (AC 11) under your plate mail (AC 16). Similarly, you might wear leather armor (AC12) but then receive the Mage Armor spell (AC13). Apply only the single highest armor AC value available to you.
* **Shield AC:** Add your shield AC (if any). Again, apply only your highest shield AC value.
* **Dodge AC:** Add your DEX score, with the following caveats:
  * A positive dodge AC bonus cannot raise your total AC above 15.
  * If your DEX score is negative, reduce the penalty by (armor's AC - 10). For example, if you are wearing leather armor (AC 12) with -3 DEX, your dodge AC is -1, for a total AC of 11.  If you instead wore ring mail or heavier armor (AC 13 or higher), your dodge AC would be 0.
  * Certain class abilities may allow you add other bonuses to dodge AC or change the upper limit of your dodge AC.
* **Cover AC:** Is situational. See [Combat: Cover](combat.md#cover).
* **Other bonuses:** Most often come from [Magic: Bonuses](magic.md#bonuses)

Magically enchanted armor and shields grant their magical bonuses to their respective armor AC or shield AC rather than to your total AC.

### Strength Requirement

Disregarding any magical bonuses on them, the AC granted by a physical armor + physical shield cannot exceed 13 + STR. If you do not meet this requirement, you are encumbered and cannot cast spells.

For example, if you have -3 STR, you cannot wear any armor without penalty. You must have at least +3 STR to wear plate mail, or +5 STR to also carry a metal shield.

### Armor Proficiency

If you are a spellcaster and wear armor or a shield with which you are not proficient, you cannot cast spells.

### Armor

| Armor | Armor AC | Cost (gp) | Type | Slots | Equivalents |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **(unarmored)** | 10 | - | - | - | |
| **Padded** | 11 | 5 | Light | 1\* | _gambeson_, _quilted_ |
| **Leather** | 12 | 10 | Light | 2\* | _jack of plate_ |
| **Ring mail** | 13 | 30 | Medium | 3\* | studded leather, hide, chain shirt, brigandine |
| **Chain mail** | 14 | 75 | Medium | 4\* | scale mail, breastplate, _cuirass_ |
| **Splint mail** | 15 | 150 | Heavy | 5\* | banded mail, half plate |
| **Plate mail** | 16 | 400 | Heavy | 6\* | field plate, full plate |

* Any suit of armor optionally includes a helmet, gloves, and boots of similar material.
* Your armor may impose penalties on certain activities. For example, medium or heavier armor may impose disadvantage on stealth and swimming.  You cannot swim at all in heavy armor.
* Armor only takes up equipment slots when carried, but not when it is worn.

### Shields

See _Weapons_ for more on size.

| Shield | Shield AC | Cost (gp) | Type | Slots | Size | Special rules |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| **Buckler** | 1 | 5 | Light | 1 | 2 | With this small shield strapped to your forearm, you can still use your offhand to manipulate objects. You can make two-handed ranged attacks, such as with a bow or crossbow, or make an offhand unarmed melee attack, but you cannot wield an offhand weapon or make two-handed melee weapon attacks. Can be made of metal or wood. |
| **Wooden** | 1* | 10 | Medium | 1 | 3 | You can clumsily manipulate or carry light items in the same hand you use to wield this round wooden shield, but you cannot wield a weapon in that hand.  When you are hit by a melee attack, you can choose to destroy (sunder) the shield as a triggered action to negate all but 1 damage from that attack. |
| **Metal** | 2 | 20 | Medium | 2 | 4 | This metal kite shield is too heavy to use the hand that wields it for anything else. |
| **Tower** | 4 | 30 | Heavy | 3 | 6 | This tall wooden scutum shield protects you from knee to chin. The shield is too heavy to use the hand that wields it for anything else. |

#### Shield Bash

In a pinch, you can use a medium shield as a primary or offhand weapon.

| Bash attacks | Damage | Properties |
| :---- | :---- | :---- |
| medium shield | d3 | Melee |
| medium spiked shield | d4 | Melee |

## Weapons

Weapons are categorized primarily by their **type**:

* **Melee** - Weapons used to attack adjacent targets in hand-to-hand combat. Use STR when making a melee attack roll (except where otherwise noted).
* **Ranged** - Weapons that are only thrown or that fire a projectile.  Use DEX when making a ranged attack roll (except where otherwise noted).

Weapons are then differentiated by **properties**, which are specific to either melee or ranged weapons.

* A property can increase (+d) or decrease (-d) the weapon's damage die. The damage die progression is: 1, d2, d3, d4, d6, d8, d10, d12.
* A property can adjust the weapon's size.

Some of the most common fantasy medieval weapons are provided as samples of applying these rules. A few of them have special rules. Players can propose additional historical weapons that are not on the table.

### Weapon Proficiency

If you use a weapon for which you lack proficiency, your attack rolls with that weapon are made at -4.

### Weapon Size

To assist in judging relative size and weight, each weapon and shield has a **weapon size**, which ranges from 1 (dagger or buckler) to 6 (a polearm). Each item takes up a number of equipment slots equal to half its size.

## Melee Weapons

The default melee weapon is a one-handed weapon of size 3 that deals d8 damage.

| Property | Adjustments | Description |
| :---- | :---- | :---- |
| **Finesse** | -d damage<br>-1 size | _Prized more for its precision than its damage._ <br><br> You can choose to use DEX in place of STR when making an attack roll with this weapon. |
| **Massive** | d/+d* damage<br>+1 size | _With enough force behind it, this heavy weapon is devastating._ <br><br> Must have the Two-Handed property and no other properties except Simple or Special. If you have a positive STR score, attacks with this weapon deal +d damage. |
| **Reach** | +1 size | _Can attack targets a couple steps away._ <br><br> You may also be able attack over short allies or between allies in front of you. You can ready this weapon to hit a charging creature before they can touch you (if they don't also have reach). |
| **Simple** | -d damage<br>-1 size (soft) | _Readily available tools that can serve as basic weapons._ <br><br> A crude but functional version of this weapon can be crafted for free or acquired even in a village for mere copper pieces. This weapon can pass as a tool where weapons are forbidden. (Size is reduced only if not already reduced by another property.) |
| **Special** | ? | _An unusual weapon._ <br><br> This weapon has custom rules or effects (as stated for the specific weapon). |
| **Throwable** | -d damage<br>-1 size | _Lighter and balanced for effective throwing._ <br><br> You can throw this weapon to make a STR-based ranged attack. Roll normally if the target is within one measure or at disadvantage up to a double measure. |
| **Two-Handed** | +d damage<br>min size 5 | _A large heavy weapon._ <br><br> You must use both hands to wield this weapon. |
| **Versatile** | min size 4 | _A large but balanced weapon that can be used effectively with either one hand or two._ <br><br> If you wield this weapon with both hands, it deals +d damage. (A versatile weapon that has at least one _-d size_ property can sometimes be light, which is min size 3.) |

### Common Melee Weapons

Equivalent weapons listed in parentheses are of a different general type (such as an axe rather than a sword), but are the same mechanically.

| Weapon | Damage | Slots | Size | Properties | Equivalent Weapons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Battleaxe** | 1d8/1d10 | 2 | 4 | Versatile | (bastard sword) |
| **Club** | 1d6 | 1 | 2 | Simple | cudgel, (machete, sickle) |
| **Dagger** | 1d4 | 1/2 | 1 | Finesse, Throwable | knife |
| **Handaxe** | 1d6 | 1 | 2 | Throwable | hatchet, throwing axe |
| **Hammer** | 1d4 | 1 | 2 | Simple, Throwable | throwing hammer, light hammer |
| **Javelin** | 1d4/1d6 | 1 | 3 | Finesse, Throwable, Versatile (light) | shortspear |
| **Lance** | 1d10 | 3 | 6 | Reach, Two-Handed, Special(one-handed when mounted) | |
| **Longsword** | 1d8 | 1 | 3 | | broadsword, falchion, knightly arming sword, sabre |
| **Mace** | 1d8 | 1 | 3 | | military flail, morningstar, war pick |
| **Polearm** | 1d10 | 3 | 6 | Reach, Two-Handed | glaive, longspear, halberd, pike, poleaxe, ranseur, etc |
| **Shortsword** | 1d6 | 1 | 2 | Finesse | cutlas, dirk, kukri, rapier, sai, scimitar, seax |
| **Spear** | 1d6/1d8 | 2 | 4 | Throwable, Versatile | trident |
| **Staff** | 1d4/1d6 | 2 | 4 | Finesse, Simple, Versatile | bo stick |
| **Two-handed sword** | 1d10 | 2 | 5 | Two-Handed | (bardiche), claymore |
| **Warhammer** | 1d8/1d10 | 2 | 4 | Versatile | horseman's pick |

### Uncommon Melee Weapons

| Weapon | Damage | Slots | Size | Properties | Equivalent Weapons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Cane** | 1d6/1d8 | 1 | 3 | Simple, Versatile (light) | shillelagh, walking stick |
| **Greataxe** | 1d10/1d12\* | 3 | 6 | Massive, Two-Handed | (greatsword), (maul) |
| **Greatclub** | 1d8/1d10\* | 2 | 5 | Massive, Simple, Two-Handed | |
| **Quarterstaff** | 1d8 | 2 | 5 | Reach, Simple, Two-Handed | |
| **Sap** | 1d6 | 1 | 2 | Finesse, Special(nonlethal) | |

## Ranged Weapons

The default ranged weapon is either:

* a Thrown weapon of size 1
* a two-handed Reload weapon of size 3.

Reloading weapons accurately fire a projectile up to a double measure. You can target something farther afield at disadvantage. You must have a quiver of appropriate ammunition on hand (or an equivalent container, such as a powder horn and bag of shot or a pouch of sling stones).

| Property | Adjustments | Description |
| :---- | :---- | :---- |
| **Massive** | d/+d* damage<br>+1 size | _With enough force behind it, this heavy weapon is devastating._ <br><br> Must be a two-handed reloading weapon. If you have a positive STR score, attacks with this weapon deal +d damage. |
| **One-Handed** | -d damage<br>-1 size | _Light enough to hold and fire with one hand._ <br><br> While you can fire this reloading weapon with one hand, it still requires two hands to load it. |
| **Reload(free)** | d6 damage | _Load this weapon with ammunition as you fire it._ <br><br> You can draw one piece of ammunition from your quiver as a free action as part of an attack with this weapon. |
| **Reload(quick)** | d8 damage | _Quickly load this weapon with ammunition before you fire it._ <br><br> As a quick action, you can load this weapon with a piece of ammunition. |
| **Reload(minor)** | d8 damage | _Slowly load this weapon with ammunition before you fire it._ <br><br> As a minor action, you can load this weapon with a piece of ammunition. This property typically grants an additional benefit or free property. |
| **Simple** | -d damage<br>-1 size | _Readily available tools that can serve as basic weapons._ <br><br> A crude but functional version of this weapon can be crafted for free or acquired in any village for mere copper pieces. This weapon can pass as a tool where weapons are forbidden. (Size is reduced only if not already reduced by another property.) |
| **Special** | ? | _An unusual weapon._ <br><br> This weapon has custom rules or effects (as stated for the specific weapon). |
| **Thrown** | d4 damage<br>size 1 | _Thrown rather than fired._ <br><br> Throw this weapon with one hand to make a DEX-based ranged attack. Roll normally if the target is within one measure or at disadvantage up to a double measure. |

### Common Ranged Weapons

| Weapon | Damage | Slots | Size | Properties | Equivalent Weapons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Dart** | d4 | 1/2 | 1 | Thrown | throwing knife |
| **Heavy crossbow** | d10 | 2 | 4 | Massive, Reload(minor), Special(ignore Massive's STR requirement) | arbalest |
| **Light crossbow** | d8 | 1 | 3 | Reload(quick) | |
| **Longbow** | d6/d8\* | 2 | 4 | Massive, Reload(free) | |
| **Shortbow** | d6 | 1 | 3 | Reload(free) | |
| **Sling** | d4 | 1 | 2 | One-Handed, Reload(quick), Simple, Special(you can reload with a medium shield in your offhand) | |

### Uncommon Ranged Weapons

| Weapon | Damage | Slots | Size | Properties | Equivalent Weapons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Hand crossbow** | d6 | 1 | 2 | One-Handed, Reload(quick) | |
| **Staff Sling** | d6 | 2 | 4 | Reload(quick), Simple, Special(also counts as a staff) | hoopak |
| **Stone** | d3 | 1/2 | 1 | Simple, Thrown | |

## Improvised Weapons

Sometimes you must attack with what is on hand or use a weapon in a way that it is not designed to be used. Such a "weapon" gains the **Improvised** property: -2d.

Examples:

| Makeshift Weapons | Damage | Properties |
| :---- | :---- | :---- |
| **One-handed:** sharp bone, frying pan, broken sword, rolling pin, table leg | d4 | Improvised, Melee |
| **Two-handed:** chair, barstool | d6 | Improvised, Melee, Two-Handed |
| **Throwable:** rock, throwing a longsword | d3 | Improvised, Melee, Throwable |

If the item is particularly unwieldy, you might also suffer disadvantage on attacks with it (such as when swinging a dead armored goblin by the ankles).

### Nonlethal Attacks

You can make a nonlethal attack with making an improvised weapon attack with a weapon that doesn't draw blood.

* For example, you could attack with a club, the pommel or haft of your weapon, the flat of your blade, or with a weapon that is padded or sheathed.
* You can't non-lethally stab someone with a rapier or shoot them with an arrow (but you might carry arrows tipped with dull lead or hard rubber for this purpose).

If a creature is reduced to 0 HP by a nonlethal attack, they fall unconscious but do not take any wounds or die from that attack.

### Unarmed attacks

When you have no weapon in hand, you can still attack unarmed.

| Unarmed attacks | Damage | Size | Properties |
| :---- | :---- | :---- | :---- |
| punch, kick, choking | d2 | 0 | Melee, Special(nonlethal) |
| gauntlet | d2 | 0 | Melee |
| spiked gauntlet, cestus | d3 | 1 | Melee |
