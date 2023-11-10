---
Ability1: Clear Body
Ability2: Liquid Ooze
BookSprite: SRD-tentacruel-BookSprite.png
BoxSprite: SRD-tentacruel-BoxSprite.png
DexCategory: Jellyfish Pokemon
DexDescription: Lives in rock formations at the bottom of the ocean. It can grow tentacles
  at will and uses them to immobilize prey. Records exist of a giant Tentacruel that
  sunk a fleet of pirate ships filled with treasure.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tentacool]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Rain Dish
HomeSprite: SRD-tentacruel-HomeSprite.png
Image: tentacruel.png
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
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reflect Type|Reflect Type]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
Number: 73
ShuffleToken: SRD-tentacruel-ShuffleToken.png
Type1: Water
Type2: Poison
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tentacruel-BookSprite.png|wsmall]]
> ![[SRD-tentacruel-HomeSprite.png]]
> ![[SRD-tentacruel-BoxSprite.png|htiny]]
> ![[SRD-tentacruel-ShuffleToken.png|wsmall]]


*Jellyfish Pokemon*
*Lives in rock formations at the bottom of the ocean. It can grow tentacles at will and uses them to immobilize prey. Records exist of a giant Tentacruel that sunk a fleet of pirate ships filled with treasure.*

**DexID**:: 0073
**Name**:: Tentacruel
**Type**:: Water / Poison
**Abilities**:: [[SRD-Clear Body|Clear Body]] / [[SRD-Liquid Ooze|Liquid Ooze]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 5'2" / 1.6m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Tentacool]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tentacruel.md"
flatten moves as T
where file.path = this.file.path
```
