---
Ability1: Schooling
Ability2: ''
BookSprite: SRD-wishiwashi-swarm-form-BookSprite.png
BoxSprite: SRD-wishiwashi-swarm-form-BoxSprite.png
DexCategory: Small Fry Pokemon
DexDescription: "A school of Wishiwashi is the demon of the sea. Even Gyarados flee\
  \ in terror when one approaches. Since it is formed by lots of members, it\u2019\
  s impossible to control. They disband after the threat is \u201Cneutralized\u201D\
  ."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Wishiwashi]]'
GenderType: ''
Height:
  Feet: 26.9
  Meters: 8.2
HiddenAbility: ''
HomeSprite: SRD-wishiwashi-swarm-form-HomeSprite.png
Image: wishiwashi-swarm-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[SRD-Brine|Brine]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Pro
  - '[[SRD-Mist|Mist]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 746
ShuffleToken: SRD-wishiwashi-swarm-form-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 78.6
  Pounds: 173.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wishiwashi-swarm-form-BookSprite.png|wsmall]]
> ![[SRD-wishiwashi-swarm-form-HomeSprite.png]]
> ![[SRD-wishiwashi-swarm-form-BoxSprite.png|htiny]]
> ![[SRD-wishiwashi-swarm-form-ShuffleToken.png|wsmall]]


*Small Fry Pokemon*
*A school of Wishiwashi is the demon of the sea. Even Gyarados flee in terror when one approaches. Since it is formed by lots of members, it’s impossible to control. They disband after the threat is “neutralized”.*

**DexID**:: 0746F1
**Name**:: Wishiwashi (Swarm Form)
**Type**:: Water
**Abilities**:: [[SRD-Schooling|Schooling]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 26'9" / 8.2m
**Weight**: 173.3lbs / 78.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon            | Kind   |
|:----------|:-------------------|:-------|
| From      | [[SRD-Wishiwashi]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wishiwashi (Swarm Form).md"
flatten moves as T
where file.path = this.file.path
```
