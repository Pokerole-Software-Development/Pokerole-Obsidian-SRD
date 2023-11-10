---
Ability1: Snow Cloak
Ability2: ''
BookSprite: SRD-ninetales-alolan-form-BookSprite.png
BoxSprite: SRD-ninetales-alolan-form-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: In old times, Alolan natives revered this Pokemon as a god incarnate.
  It is usually calm and benevolent, but it can be ruthless when disturbed, leaving
  its foes as a cold block of ice in the snow.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Vulpix (Alolan Form)]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Snow Warning
HomeSprite: SRD-ninetales-alolan-form-HomeSprite.png
Image: ninetales-alolan-form.png
Legendary: 'No'
Moves:
- - Amateur
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Moonblast|Moonblast]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Number: 38
ShuffleToken: SRD-ninetales-alolan-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 19.9
  Pounds: 43.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ninetales-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-ninetales-alolan-form-HomeSprite.png]]
> ![[SRD-ninetales-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-ninetales-alolan-form-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*In old times, Alolan natives revered this Pokemon as a god incarnate. It is usually calm and benevolent, but it can be ruthless when disturbed, leaving its foes as a cold block of ice in the snow.*

**DexID**:: 0038A
**Name**:: Ninetales (Alolan Form)
**Type**:: Ice
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Snow Warning|Snow Warning]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 43.9lbs / 19.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Item      |
|:----------|:-----------------------------|:-------|:----------|
| From      | [[SRD-Vulpix (Alolan Form)]] | Stone  | Ice Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ninetales (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
