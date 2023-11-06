---
Ability1: Ripen
Ability2: Gluttony
BookSprite: SRD-applin-BookSprite.png
BoxSprite: SRD-applin-BoxSprite.png
DexCategory: Apple Core Pokemon
DexDescription: "As soon as it\u2019s born this tiny lizard Pokemon, it burrows into\
  \ an apple to protect itself from birds and predators. The apple serves as its food\
  \ source and the flavor of it will determine its evolution."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Tart Apple
  Kind: Item
  Pokemon: '[[SRD-Flapple]]'
- Evolves: To
  Item: Sweet Apple
  Kind: Item
  Pokemon: '[[SRD-Appletun]]'
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Bulletproof
HomeSprite: SRD-applin-HomeSprite.png
Image: applin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Recycle|Recycle]]'
Number: 840
ShuffleToken: SRD-applin-ShuffleToken.png
Type1: Grass
Type2: Dragon
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-applin-BookSprite.png|wsmall]]
> ![[SRD-applin-HomeSprite.png]]
> ![[SRD-applin-BoxSprite.png|htiny]]
> ![[SRD-applin-ShuffleToken.png|wsmall]]


*Apple Core Pokemon*
*As soon as it’s born this tiny lizard Pokemon, it burrows into an apple to protect itself from birds and predators. The apple serves as its food source and the flavor of it will determine its evolution.*

**DexID**:: 0840
**Name**:: Applin
**Type**:: Grass / Dragon
**Abilities**:: [[SRD-Ripen|Ripen]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| To        | [[SRD-Flapple]]  | Item   | Tart Apple  |
| To        | [[SRD-Appletun]] | Item   | Sweet Apple |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Applin.md"
flatten moves as T
where file.path = this.file.path
```
