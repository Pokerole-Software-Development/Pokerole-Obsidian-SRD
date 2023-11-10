---
Ability1: Water Absorb
Ability2: ''
BookSprite: SRD-vaporeon-BookSprite.png
BoxSprite: SRD-vaporeon-BoxSprite.png
DexCategory: Bubble Jet Pokemon
DexDescription: Vaporeon underwent through a strange mutation, it grew fins and gills
  that allow it to live underwater. This Pokemon has the ability to become translucent
  when it dives underwater.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Eevee]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Hydration
HomeSprite: SRD-vaporeon-HomeSprite.png
Image: vaporeon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 134
ShuffleToken: SRD-vaporeon-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 29.0
  Pounds: 63.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vaporeon-BookSprite.png|wsmall]]
> ![[SRD-vaporeon-HomeSprite.png]]
> ![[SRD-vaporeon-BoxSprite.png|htiny]]
> ![[SRD-vaporeon-ShuffleToken.png|wsmall]]


*Bubble Jet Pokemon*
*Vaporeon underwent through a strange mutation, it grew fins and gills that allow it to live underwater. This Pokemon has the ability to become translucent when it dives underwater.*

**DexID**:: 0134
**Name**:: Vaporeon
**Type**:: Water
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 63.9lbs / 29.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item        |
|:----------|:--------------|:-------|:------------|
| From      | [[SRD-Eevee]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vaporeon.md"
flatten moves as T
where file.path = this.file.path
```
