---
Ability1: Power Construct
Ability2: ''
BookSprite: SRD-zygarde-cell-BookSprite.png
BoxSprite: SRD-zygarde-cell-BoxSprite.png
DexCategory: No Data
DexDescription: Only the the cores react to stimuli, the cells remain mostly inanimate.
  They gather in great numbers to create and strengthen Zygarde.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Zyguarde cells
  Kind: Special
  Pokemon: '[[SRD-Zygarde 10%]]'
- Evolves: To
  Item: Zyguarde cells
  Kind: Special
  Pokemon: '[[SRD-Zygarde 50%]]'
- Evolves: To
  Item: Zyguarde cells
  Kind: Special
  Pokemon: '[[SRD-Zygarde 100%]]'
GenderType: N
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-zygarde-cell-HomeSprite.png
Image: zygarde-cell.png
Legendary: 'Yes'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
Number: 718
ShuffleToken: SRD-zygarde-cell-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 0.1
  Pounds: 0.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zygarde-cell-BookSprite.png|wsmall]]
> ![[SRD-zygarde-cell-HomeSprite.png]]
> ![[SRD-zygarde-cell-BoxSprite.png|htiny]]
> ![[SRD-zygarde-cell-ShuffleToken.png|wsmall]]


*No Data*
*Only the the cores react to stimuli, the cells remain mostly inanimate. They gather in great numbers to create and strengthen Zygarde.*

**DexID**:: 0718
**Name**:: Zygarde Cell
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Power Construct|Power Construct]]
**Base HP**:: 1

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::1)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::1) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::1)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::1)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::1)     |

**Height**: 0'7" / 0.2m
**Weight**: 0.2lbs / 0.1kg
**Good Starter**:: No
**Recommended Rank**:: Starter

| Evolves   | Pokemon              | Kind    | Item           |
|:----------|:---------------------|:--------|:---------------|
| To        | [[SRD-Zygarde 10%]]  | Special | Zyguarde cells |
| To        | [[SRD-Zygarde 50%]]  | Special | Zyguarde cells |
| To        | [[SRD-Zygarde 100%]] | Special | Zyguarde cells |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zygarde Cell.md"
flatten moves as T
where file.path = this.file.path
```
