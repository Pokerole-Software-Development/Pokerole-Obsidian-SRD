---
Ability1: Hydration
Ability2: ''
BookSprite: SRD-manaphy-BookSprite.png
BoxSprite: SRD-manaphy-BoxSprite.png
DexCategory: No Data
DexDescription: It is said that after the war for land and sea was over, a tiny Pokemon
  was born from the bottom of the ocean to bond with all the creatures as a sign of
  peace.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-manaphy-HomeSprite.png
Image: manaphy.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Tail Glow|Tail Glow]]'
- - Master
  - '[[SRD-Bubble|Bubble]]'
- - Master
  - '[[SRD-Water Sport|Water Sport]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Supersonic|Supersonic]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Surf|Surf]]'
- - Master
  - '[[SRD-Heart Swap|Heart Swap]]'
- - Master
  - '[[SRD-Liquidation|Liquidation]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Bounce|Bounce]]'
Number: 490
ShuffleToken: SRD-manaphy-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 1.4
  Pounds: 3.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-manaphy-BookSprite.png|wsmall]]
> ![[SRD-manaphy-HomeSprite.png]]
> ![[SRD-manaphy-BoxSprite.png|htiny]]
> ![[SRD-manaphy-ShuffleToken.png|wsmall]]


*No Data*
*It is said that after the war for land and sea was over, a tiny Pokemon was born from the bottom of the ocean to bond with all the creatures as a sign of peace.*

**DexID**:: 0490
**Name**:: Manaphy
**Type**:: Water
**Abilities**:: [[SRD-Hydration|Hydration]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 1'0" / 0.3m
**Weight**: 3.1lbs / 1.4kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Manaphy.md"
flatten moves as T
where file.path = this.file.path
```
