---
Ability1: Synchronize
Ability2: Trace
BookSprite: SRD-gardevoir-BookSprite.png
BoxSprite: SRD-gardevoir-BoxSprite.png
DexCategory: Embrace Pokemon
DexDescription: If they sense danger, Gardevoir unleash a wave of psychic energy.
  They can distort this dimension, defy the laws of matter and physics. They risk
  their lives to protect their fellows.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Kirlia]]'
  Speed: Medium
- Evolves: To
  Item: Gardevoirite
  Kind: Mega
  Pokemon: '[[SRD-Gardevoir (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Telepathy
HomeSprite: SRD-gardevoir-HomeSprite.png
Image: gardevoir.png
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
ShuffleToken: SRD-gardevoir-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 48.4
  Pounds: 106.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gardevoir-BookSprite.png|wsmall]]
> ![[SRD-gardevoir-HomeSprite.png]]
> ![[SRD-gardevoir-BoxSprite.png|htiny]]
> ![[SRD-gardevoir-ShuffleToken.png|wsmall]]


*Embrace Pokemon*
*If they sense danger, Gardevoir unleash a wave of psychic energy. They can distort this dimension, defy the laws of matter and physics. They risk their lives to protect their fellows.*

**DexID**:: 0282
**Name**:: Gardevoir
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Trace|Trace]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 106.7lbs / 48.4kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                       | Kind   | Speed   | Item         |
|:----------|:------------------------------|:-------|:--------|:-------------|
| From      | [[SRD-Kirlia]]                | Level  | Medium  |              |
| To        | [[SRD-Gardevoir (Mega Form)]] | Mega   |         | Gardevoirite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gardevoir.md"
flatten moves as T
where file.path = this.file.path
```
