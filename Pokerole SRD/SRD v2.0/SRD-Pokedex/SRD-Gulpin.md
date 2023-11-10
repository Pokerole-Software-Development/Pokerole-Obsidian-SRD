---
Ability1: Liquid Ooze
Ability2: Sticky Hold
BookSprite: SRD-gulpin-BookSprite.png
BoxSprite: SRD-gulpin-BoxSprite.png
DexCategory: Stomach Pokemon
DexDescription: Gulpin's body is a huge stomach capable of swallowing anything of
  their size. Their fluids can corrode metal. This Pokemon releases hideous and vile
  gases while it digests its food.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Swalot]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Gluttony
HomeSprite: SRD-gulpin-HomeSprite.png
Image: gulpin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - Beginner
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
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
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 316
ShuffleToken: SRD-gulpin-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 10.3
  Pounds: 22.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gulpin-BookSprite.png|wsmall]]
> ![[SRD-gulpin-HomeSprite.png]]
> ![[SRD-gulpin-BoxSprite.png|htiny]]
> ![[SRD-gulpin-ShuffleToken.png|wsmall]]


*Stomach Pokemon*
*Gulpin's body is a huge stomach capable of swallowing anything of their size. Their fluids can corrode metal. This Pokemon releases hideous and vile gases while it digests its food.*

**DexID**:: 0316
**Name**:: Gulpin
**Type**:: Poison
**Abilities**:: [[SRD-Liquid Ooze|Liquid Ooze]] / [[SRD-Sticky Hold|Sticky Hold]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 22.7lbs / 10.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Swalot]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gulpin.md"
flatten moves as T
where file.path = this.file.path
```
