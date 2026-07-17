# Magic

Magic is used by spellcasting characters to cast spells.  Magic also fuels magic items and is wielded by some monsters.

## Spellcasting

### Spellcasting Stats

When you gain the ability to cast spells, you gain two additional derived [stats](stats.md).

#### MAGIC

Your MAGIC score equals that of the ability score that powers your magic. This is determined by your spellcasting method, described below.

Your MAGIC limits your POWER and determines some spell effects.

#### POWER

Your POWER equals the lesser of your level or your MAGIC, divided by 2, rounded up.  

* For example, if your are level 5 with MAGIC +5 or higher, your POWER is 3.  
* However, if you are level 5 with MAGIC +4, your POWER would be 2.

Your POWER determines the most powerful spells that you can cast and determines some spell effects.

### Spell Tiers

Spells are assigned to **tiers** 0 through 4. You must have POWER greater than or equal to a spell's tier in order to cast that spell.

#### Cantrips

Tier 0 spells are called **cantrips**. They do not require you to draw mana to cast, and so casting them always succeeds.

* The number of cantrips available to a character depends on their class.
* A spellcaster can choose to learn a cantrip in place of Tier 1 spell. However, cantrips acquired by this means are treated as a Tier 1 spell for that spellcaster for purposes of casting costs.

#### Ceremonies

// TODO

## Tradition

Each spellcaster belongs to a magical tradition. This tradition includes the source of their magic, the spells available to them, and the typical trappings of their magic or any mishap effects.  

The available traditions can vary with the campaign setting.

### Source

The source of your magic does much to define the flavor or limitations of your magic.

As a starting default, here are three classic traditions, including the source and flavor of each:

| Tradition | Magical Source | Flavor / Limitations |
| -- | -- | -- |
| **Arcane** | The raw energies latent within reality itself | Tends to be flashy, destructive, or transformative. Cannot heal. |
| **Divine** | Gods or a faith in greater moral powers | Tends to bolster, heal, and aid, but it can be destructive when smiting opposing forces. May channel radiant energy but typically not raw elemental energies. |
| **Nature** | The primal energies of living plants, biomes, and the elemental planes | Tends to support or manipulate living creatures in non-destructive ways, but can summon elemental energies, such as storm or fire, when needed. |

Other traditions might include alchemy, artifice, bardic song, etc.

When defining a new tradition, work with your GM to determine its source, which spells are available from that source, and what its typical trappings are. The default spell list indicates whether a given spell is available to each of the three traditions above.

### Trappings

Trappings primarily describe the cosmetic effects of your magic. For example, the _bolt_ cantrip deals damage at range. What this looks like depends on your trappings: a glowing orb of green light, a fist of fire, a ball of ice, a spinning blade, a spectral serpent that slithers along the ground to the target, a beam of momentarily engulfing shadow, etc.

However, your trappings may occasionally have more substantial consequences. A fire _bolt_ would let you ignite spilled oil, but it would leave a fire-immune demon unharmed. A spinning-blade _bolt_ might let you sever a chandelier rope from across the room, but an ice-ball _bolt_ would not. A lightning-based trapping would produce a bright flash of light, while a thunder-based trapping would be heard far down the hall, even around corners.

Starting with the trappings that are thematically relevant to the source of your magic, your character's unique workings of that magic may further customize those trappings. A spell you know should have the same trappings every time you cast it (unless you adjust the trappings by the same means you would use to learn a new spell).  You can choose to rename a spell to reflect your unique version of it.

### Method

Each spellcaster, regardless of their tradition, has a method that they use to draw and cast their magic.

* You choose your method when you gain the ability to cast spells. You cannot change this choice later.
* Each method is associated with a different mental ability score.  
* All spellcasters start with the same number of spells known to them, but each method has a different means of adding or changing that spell list.

| Method | Ability (MAGIC) | Spellcasting Mechanic | Changes to Spells Known | Starting HP |
| -- | -- | -- | -- | -- |
| The Word | INT | Prepared spell slots | Can add discovered spells to spellbook | -1 |
| The Way | WIS | Spell points prepared from HD | Can commune to swap 1 spell known per day | +0 |
| The Will | CHA | Raw mana drawn directly from HD | Can swap 1 spell known per level up | +1 |

#### The Word (INT)

The Word relies on **inscribed** magic. These inscriptions are derived through ritual, logic, theory, study, lore, and experimentation. While some scholars claim you must have an initial spark to perform any kind of magic, the Word is primarily a learned form of magic. It is the magic found in wizardly colleges, in monastery libraries, and upon the walls of ancient ruins.

**MAGIC:** INT

**Spells known:** The spells you know are prepared from a **spellbook** that you have authored. A spellbook can take many forms: a book, a bundle of notes or scrolls, engraved prayer beads, tattoos, etc.  Your spellbook can only contain spells of a tier that you have sufficient POWER to cast.

Your spellbook contains a number of **original spells** equal to MAGIC+POWER. These are the spells you first learned (and thus know best) plus the spells that you developed through your own research or study. As your MAGIC or POWER increases, you can freely add these new original spells to your spellbook to represent the culmination of your ongoing work. (Mark on your character sheet which of your spells known are original spells.)

You can also add **discovered spells** to your spellbook. These spells typically come from scrolls, spellbooks, or other written versions of a spell, though you might also be taught the spell by another spellcaster who practices the Word of your tradition. To add a discovered spell, you must first decipher the spell (as per scrolls). (This is automatic if the spell's author is present and assisting you.) You can then spend 1 day to practice the spell and scribe it into your own spellbook using your personal notation.

If you should ever lose your spellbook, you can spend 1 day of downtime to reconstruct one, provided you have the necessary materials on hand, such as a blank book, pen, and ink. This reconstructed spellbook contains only your original spells; any discovered spells are lost.  For this reason, most practitioners of the Word keep a backup spellbook in a safe place. It takes 1 hour per spell tier for you to copy a discovered spell from one of your own spellbooks into another.

**Spell slots:** Through their study of arcane sigils, mystical glyphs, and ancient mandalas, practitioners of the Word are able to gather and hold magical energies in symbolic constructs within their minds. This memory palace of spell storage is represented as spell slots. You gain additional spell slots as you level up:

| Level | Tier 1 | Tier 2 | Tier 3 | Tier 4 |
| :-- | :-- | :-- | :-- | :-- |
| **1** | 2 | | | |
| **2** | 4 | | | |
| **3** | 4 | 2 | | |
| **4** | 4 | 3 | | |
| **5** | 4 | 3 | 2 | |
| **6** | 4 | 3 | 3 | |
| **7** | 4 | 3 | 3 | 1 |
| **8** | 4 | 3 | 3 | 2 |

**Preparing spell slots:** You can only prepare the fragile mental constructs of spell energies when you mind is fresh. At end of a long rest, you can empty any occupied spells slots. You can then fill any empty slots with spells from your spellbook.

* You need to be able to read your spellbook with uninterrupted focus over several minutes to do this.
* Each slot represents a separate future casting of a spell.  Therefore, if you expect you may want to cast a given spell more than once, you need to prepare more than one copy (slot) of it.
* You may prepare spells of a lower tier in a slot of a higher tier. For example, you can use a Tier 3 slot to prepare a Tier 2 spell. You might need to do this if have you a low MAGIC score, such that you do not have sufficient POWER to cast spells of your higher tiered slots.
* To indicate your prepared spells on your character sheet, you can draw a small box next to a spell known for each copy of that spell that you have prepared. (You'll then check these boxes off when you cast that prepared spell.)

**Casting a spell:** You can cast any spell that you have prepared in a spell slot.  When you do so, that slot is then emptied. (Check it off on your character sheet.) You cannot prepare another spell in that slot until you have completed a long rest.

**Adhoc casting:** Instead of casting a prepared spell, a practitioner of the Word can scavenge the mental energy stored stored in a spell slot to cast a different spell from their spellbook.  This process is mentally and physically taxing, however.  To do so:

* You must have your spellbook in hand and be able to read it. (Given that you usually must also have a free hand to cast a spell, this is typically a two-handed operation.)
* Casting a spell this way always requires at least a standard action, even if the spell you are casting could normally be cast faster.
* Expend 1 HD and one prepared spell slot.
* You can then cast a spell from your spellbook that is of the same tier as the prepared spell that you expended.

**Features of the Word:** You should use the Word if:

* You want to have a reliable way to cast magic without expending HD
* You want to have the greatest range of possible spells in a day: You can cast anything in your spellbook!
* You want to adventure to seek knowledge and lost lore.

**Example practitioners of the Word:**

* A frazzled bearded wizard, carrying a heavy tome of parchment pages, seeks the 99 lost of spells of Pandalume.
* A druid, bearing a leather tube filled with bark scrolls covered in ogham script, searches for ancient standing stones and engraved dolmens to recover the wisdom of the first druid masters.
* A priest, clutching his prayer book, descends into the gloom of a defiled tomb.
* A grimscribe, bearing the spells of her dark magic inked in black on her own skin, pulls her sleeves down over her arms before stepping from the dark alley.

#### The Way (WIS)

The Way relies on magic **inspired** directly from its source. Practitioners of the Way meditate upon, pray to, or otherwise commune with the wellspring of their magic.  In return, they gain mystical or arcane insights that allow them to reshape reality. While this communion is often physically exhausting, it leaves the practitioner internally thrumming with magical energy, which typically causes them to feel bouyed, ecstatic, or intensely focused. The Way can be taught to some degree, but such learning relies more on long hours of meditative practice or on mental exercises intended to help the neophyte reach beyond logic or reason to connect with a greater truth or power that lies beyond.

**MAGIC:** WIS

**Spells known:** You begin play knowing MAGIC+POWER Tier 1 spells.

At the end of a long rest, you can commune with your magical source:

* This requires several minutes of uninterrupted focus.
* Depending your tradition, a particular ritual, holy symbol, or material focus might be commonly used to shorten the time required to reach the necessary mental state.
* You can then swap one spell known for another spell from your tradition that is of a tier you can cast.

**Spell points (SP):** You cast your spells using spell points, as described below.

**Preparing spell points:** At the end of any rest (short or long), you can commune with your magical source to gather magical energy.

* This process is the same as described above for swapping spells known and can be combined with that effort.
* As part of the communion, you can expend HD to gain spell points.  
  * You gain 4 SP for each HD expended, or 9 SP for each 2 HD expended.  
  * At level 5 and above, you gain +1 SP per HD expended.

The following table shows the maximum SP you can gain at each level if you choose to expend all your available HD at the start of the day:

| All HD @ Level | Spell Points |
| :-- | :-- |
| **1** | 4 |
| **2** | 9 |
| **3** | 13 |
| **4** | 18 |
| **5** | 27 |
| **6** | 33 |
| **7** | 38 |
| **8** | 44 |

**Casting a spell:** To cast a spell you know, you must first pay its spell point cost as part of casting it:

| Tier | SP Cost |
| :-- | :-- |
| **1** | 2 |
| **2** | 3 |
| **3** | 5 |
| **4** | 6 |

**Features of the Way:** You should use the Way if:

* You want a flexible way to reliably cast any spell that you know.
* You want to have the greatest range of spells readily available to you over the course of play: A good night's sleep is all that stands between you and any spell available from your tradition!

**Example practitioners of the Way:**

* A young druid reaches out, becoming one with the Green; then he moves together with the grasses around him to strangle and bind the invaders of this ancient forest.
* A theurge contemplates the Weave that binds all of reality together; by plucking a thread here and tugging another there, she causes fire to blossom in her hand.
* An votary quietly sings hymns of praise to his goddess; he prays that he might understand her will so that she might fortify him to do her bidding in this world.

#### The WILL (CHA)

The Will relies on successfully channeling the raw magic with which the practitioner is **imbued**. Where other spellcasting methods must draw and prepare their magical energy in some way, magic comes readily to those exerting the Will. However, this rush of magic is exhausting to control. It soon wears down its mortal conduit, occasionally breaking free of the spellcaster's control or even eroding their humanity.  

Some practitioners of the Will are born with their magical ability. Perhaps it is innate to their family bloodline, even if it sometimes skips generations.  Or perhaps the spellcaster was touched by a powerful entity or event while in the womb or as a young child, connecting them forever to a particular source of magic. Other practitioners may come to their ability later in life, such as with puberty or through an arcane coming-of-age ritual. Many practitioners of the Will actively seek their powers by way of an oath, pact, or bargain with an inherently magical being, such as a god, celestial, fiend, djinn, fey, dragon, sentient artifact, or distant alien entity. In such cases, the flow of their magic may be contingent upon them continuing to serve or please this patron being.

While guidance may be found on how to contact such a being and gain its power, acquiring magical ability through the Will cannot otherwise be taught. Because its acquisition can rarely be controlled, because it can be dangerous to its wielder and those around them, and because its ultimate source is often either an inscrutable or malicious entity with goals of its own, the Will is the most distrusted method in many societies.

**MAGIC:** CHA

**Spells known:** You begin play knowing MAGIC+POWER Tier 1 spells.  Each time you level up, you can swap one spell known for another spell from your tradition that is of a tier you can cast.

**Hit Dice (HD):** You require no preparation to use your magic. However, you must have at least one unexpended HD to cast a spell of Tier 1 or higher. Once all of your HD are expended, you are too exhausted to channel more magic.

**Casting a spell:** To cast a spell, you must first draw sufficient mana for it:

| Tier | Mana Cost |
| :-- | :-- |
| **1** | 4 |
| **2** | 9 |
| **3** | 15 |
| **4** | 21 |

As you start to cast the spell, roll an unexpended HD to see how many points of mana you draw:

* Once you have drawn sufficient mana, you successfully cast the spell.  Any excess mana is harmlessly dispersed.
* If you a roll a 7 or 8 on the HD (or a 4 on an epic level d4 HD), that HD is expended.
* If you do not yet have enough mana, you can roll an unexpended HD again and add its result to your growing mana pool. Repeat until you have enough mana to cast the spell.
* If the first two HD rolls of a casting attempt are both 1s, you suffer a mishap. (See below.)
* If you expend your last HD before you accumulate enough mana, you fail to cast the spell and your casting action is wasted.

**Mishap type:** When you create your character, choose your mishap type: Backfire or Transformation. See below for more information about both. You cannot change this choice later.

**Features of the Will:** You should use the Will if:

* You have strength in your convictions: Your lists of spells known will be focused and change slowly.
* You are willing to take risks for the power you desire. Your expected spell output is higher than any other method, and you will have days where the magic flows easily and continuously when you call it, turn after turn. However, on other days, you will be found wanting, overcome by the mighty power that flows through you, left weak and trembling with nothing more to give. And, every now and then, you will also risk your humanity, your health, or those around for you for the magnificent power you wield.

**Example practitioners of the Way:**

* A sallow necromancer bears the phylactery of a lich on his arm; over time, he gains more of the lich's power, memories, and personality, yet his skin also slowly dries and withers upon his frame.
* A sorcerer reaches through the Veil to funnel the Winds of Change into the world to dramatic effect; however, sometimes the Winds swirl wildly when called and twist free of the sorcerer's control.
* A paladin prays to her righteous god, channeling its power to smite its enemies and heal the devout; slowly, the paladin grows more stern and radiant, and daily human concerns seem distant and petty compared to basking forever in that divine light.
* A warlock hides the demonic mark of his patron under a buttoned shirt; the demon is hungry for blood and souls, and sometimes the powers it has granted the warlock go astray, harming others rather than those the warlock intended.

### Mishaps

The most common source of mishaps is using the Will to cast spells. However, they can also happen when using scrolls or other magical artifacts.  If a mishap's type is not specified, it is a backfire.

#### Backfire

When you suffer a Backfire, the spell produces an effect other than the one intended. The GM gleefully determines what this means, but it is nearly always bad for you. Examples include:

1. You suffer tier-appropriate damage (usually d8 damage per spell tier)
1. You suffer HD loss as exhaustion (usually 1 + spell tier)
1. The spell affects the wrong target(s), a random target if you were the intended target, or manifests at a different origin point within view
1. The spell morphs into a different or opposite effect (the new effect should still be representative of the same magical tradition)
1. You suffer some unrelated but persistent side-effect (the duration of which varies depending on the severity of the effect)
1. The spell creates innocuous items, or the environment or others around you suffer a side-effect

#### Transformation

When you suffer a Transformation, the spell is still cast successfully. However, the powerful magic coursing through you has left a mark: Gain 1 point of Transformation.

Transformation is typed depending on the nature of its source, such as: corruption (or evil), elemental fire, fey, primal nature, radiant, wild magic, etc.  The specific list varies by campaign.  As you are transformed by that type, your thoughts, personality, and goals begin to shift accordingly. Your body also starts to change, manifesting aspects common to that type.

* At 5 points accumulated within a single type, your transformation becomes apparent to others.
* At 10 points within a single type, your transformation is complete: You lose your humanity. Your character becomes an NPC or monster under the GM's control.

There is no default way to remove points of transformation. Certain rare substances, obscure ceremonies, or wishes may allow some respite.
