---
Ability1: Pixilate
Ability2: ''
BookSprite: SRD-gardevoir-mega-form-BookSprite.png
BoxSprite: SRD-gardevoir-mega-form-BoxSprite.png
DexCategory: Embrace Pokemon
DexDescription: The power of the Mega Stone makes its senses skyrocket. It is easily
  upset as it can feel the emotions from everyone in a wide radius. Its psychic powers
  are said to distort reality.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Gardevoirite
  Kind: Mega
  Pokemon: '[[SRD-Gardevoir]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-gardevoir-mega-form-HomeSprite.png
Image: gardevoir-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Double Team|Double Team]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Ace
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grudge|Grudge]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 282
ShuffleToken: SRD-gardevoir-mega-form-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 48.4
  Pounds: 106.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gardevoir-mega-form-BookSprite.png|wsmall]]
> ![[SRD-gardevoir-mega-form-HomeSprite.png]]
> ![[SRD-gardevoir-mega-form-BoxSprite.png|htiny]]
> ![[SRD-gardevoir-mega-form-ShuffleToken.png|wsmall]]


*Embrace Pokemon*
*The power of the Mega Stone makes its senses skyrocket. It is easily upset as it can feel the emotions from everyone in a wide radius. Its psychic powers are said to distort reality.*

**DexID**:: 0282M1
**Name**:: Gardevoir (Mega Form)
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Pixilate|Pixilate]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 5'2" / 1.6m
**Weight**: 106.7lbs / 48.4kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   | Item         |
|:----------|:------------------|:-------|:-------------|
| From      | [[SRD-Gardevoir]] | Mega   | Gardevoirite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gardevoir (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
