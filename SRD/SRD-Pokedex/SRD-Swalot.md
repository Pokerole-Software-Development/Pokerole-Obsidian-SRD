---
Ability1: Liquid Ooze
Ability2: Sticky Hold
BookSprite: SRD-swalot-BookSprite.png
BoxSprite: SRD-swalot-BoxSprite.png
DexCategory: Poison Bag Pokemon
DexDescription: "Swalots spurt toxic fluids from their pores, and once the prey is\
  \ weak, it gets swallowed whole since they have no teeth. They may eat anything\
  \ up to the size of a car\u2019s tire. Do not get too close to them."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gulpin]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Gluttony
HomeSprite: SRD-swalot-HomeSprite.png
Image: swalot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Wring Out|Wring Out]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 317
ShuffleToken: SRD-swalot-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 80.0
  Pounds: 176.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swalot-BookSprite.png|wsmall]]
> ![[SRD-swalot-HomeSprite.png]]
> ![[SRD-swalot-BoxSprite.png|htiny]]
> ![[SRD-swalot-ShuffleToken.png|wsmall]]


*Poison Bag Pokemon*
*Swalots spurt toxic fluids from their pores, and once the prey is weak, it gets swallowed whole since they have no teeth. They may eat anything up to the size of a car’s tire. Do not get too close to them.*

**DexID**:: 0317
**Name**:: Swalot
**Type**:: Poison
**Abilities**:: [[SRD-Liquid Ooze|Liquid Ooze]] / [[SRD-Sticky Hold|Sticky Hold]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 176.4lbs / 80.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Gulpin]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swalot.md"
flatten moves as T
where file.path = this.file.path
```
