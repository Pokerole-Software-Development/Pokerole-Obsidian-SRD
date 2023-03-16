---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-magmortar-BookSprite.png
BoxSprite: SRD-magmortar-BoxSprite.png
DexCategory: Blast Pokemon
DexDescription: "Magmortar is extremely rare, if you\u2019re lucky you can find one\
  \ living directly on volcanic craters. It rises the temperature of its body at will\
  \ to the point of bursting into flames. The fire it produces is almost white."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Magmarizer
  Kind: Trade
  Pokemon: '[[SRD-Magmar]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Vital Spirit
HomeSprite: SRD-magmortar-HomeSprite.png
Image: magmortar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 467
ShuffleToken: SRD-magmortar-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 68.0
  Pounds: 149.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magmortar-BookSprite.png|wsmall]]
> ![[SRD-magmortar-HomeSprite.png]]
> ![[SRD-magmortar-BoxSprite.png|htiny]]
> ![[SRD-magmortar-ShuffleToken.png|wsmall]]


*Blast Pokemon*
*Magmortar is extremely rare, if you’re lucky you can find one living directly on volcanic craters. It rises the temperature of its body at will to the point of bursting into flames. The fire it produces is almost white.*

**DexID**:: 0467
**Name**:: Magmortar
**Type**:: Fire
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 149.9lbs / 68.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item       |
|:----------|:---------------|:-------|:-----------|
| From      | [[SRD-Magmar]] | Trade  | Magmarizer |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Magmortar.md"
flatten moves as T
where file.path = this.file.path
```
