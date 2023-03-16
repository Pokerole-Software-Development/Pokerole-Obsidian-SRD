---
Ability1: Clear Body
Ability2: Liquid Ooze
BookSprite: SRD-tentacool-BookSprite.png
BoxSprite: SRD-tentacool-BoxSprite.png
DexCategory: Jellyfish Pokemon
DexDescription: It lives in the seas all around the world. They release a toxic ink
  if startled. It is a surprisingly intelligent Pokemon and can use its tentacles
  to briefly establish a link between its mind and another creature.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tentacruel]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Rain Dish
HomeSprite: SRD-tentacool-HomeSprite.png
Image: tentacool.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Constrict|Constrict]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Wrap|Wrap]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Barrier|Barrier]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 72
ShuffleToken: SRD-tentacool-ShuffleToken.png
Type1: Water
Type2: Poison
Weight:
  Kilograms: 45.5
  Pounds: 100.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tentacool-BookSprite.png|wsmall]]
> ![[SRD-tentacool-HomeSprite.png]]
> ![[SRD-tentacool-BoxSprite.png|htiny]]
> ![[SRD-tentacool-ShuffleToken.png|wsmall]]


*Jellyfish Pokemon*
*It lives in the seas all around the world. They release a toxic ink if startled. It is a surprisingly intelligent Pokemon and can use its tentacles to briefly establish a link between its mind and another creature.*

**DexID**:: 0072
**Name**:: Tentacool
**Type**:: Water / Poison
**Abilities**:: [[SRD-Clear Body|Clear Body]] / [[SRD-Liquid Ooze|Liquid Ooze]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 100.3lbs / 45.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Tentacruel]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tentacool.md"
flatten moves as T
where file.path = this.file.path
```
