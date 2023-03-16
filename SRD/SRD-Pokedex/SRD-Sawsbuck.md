---
Ability1: Chlorophyll
Ability2: Sap Sipper
BookSprite: SRD-sawsbuck-BookSprite.png
BoxSprite: SRD-sawsbuck-BoxSprite.png
DexCategory: Season Pokemon
DexDescription: The plants growing on its horns change according to the season. They
  live in herds that migrate in search of grass. The leaders of the herd possess magnificent
  horns. They tend to be peaceful creatures.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Deerling]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Serene Grace
HomeSprite: SRD-sawsbuck-HomeSprite.png
Image: sawsbuck.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Camouflage|Camouflage]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Horn Leech|Horn Leech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[SRD-Nature Power|Nature Power]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Number: 586
ShuffleToken: SRD-sawsbuck-ShuffleToken.png
Type1: Normal
Type2: Grass
Weight:
  Kilograms: 92.5
  Pounds: 203.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sawsbuck-BookSprite.png|wsmall]]
> ![[SRD-sawsbuck-HomeSprite.png]]
> ![[SRD-sawsbuck-BoxSprite.png|htiny]]
> ![[SRD-sawsbuck-ShuffleToken.png|wsmall]]


*Season Pokemon*
*The plants growing on its horns change according to the season. They live in herds that migrate in search of grass. The leaders of the herd possess magnificent horns. They tend to be peaceful creatures.*

**DexID**:: 0586
**Name**:: Sawsbuck
**Type**:: Normal / Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Serene Grace|Serene Grace]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 203.9lbs / 92.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Deerling]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sawsbuck.md"
flatten moves as T
where file.path = this.file.path
```
