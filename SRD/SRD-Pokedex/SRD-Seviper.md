---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-seviper-BookSprite.png
BoxSprite: SRD-seviper-BoxSprite.png
DexCategory: Fang Snake Pokemon
DexDescription: "Their hate for the Zangoose has been boiling for so long it\u2019\
  s now a basic instinct. They battle using their sword-edged poisonous tail, hiding\
  \ in tall grass until an unwary prey gets close enough."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 8.9
  Meters: 2.7
HiddenAbility: Infiltrator
HomeSprite: SRD-seviper-HomeSprite.png
Image: seviper.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - Starter
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Poison Tail|Poison Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Glare|Glare]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Belch|Belch]]'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
Number: 336
ShuffleToken: SRD-seviper-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 52.5
  Pounds: 115.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-seviper-BookSprite.png|wsmall]]
> ![[SRD-seviper-HomeSprite.png]]
> ![[SRD-seviper-BoxSprite.png|htiny]]
> ![[SRD-seviper-ShuffleToken.png|wsmall]]


*Fang Snake Pokemon*
*Their hate for the Zangoose has been boiling for so long it’s now a basic instinct. They battle using their sword-edged poisonous tail, hiding in tall grass until an unwary prey gets close enough.*

**DexID**:: 0336
**Name**:: Seviper
**Type**:: Poison
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'9" / 2.7m
**Weight**: 115.7lbs / 52.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Seviper.md"
flatten moves as T
where file.path = this.file.path
```
