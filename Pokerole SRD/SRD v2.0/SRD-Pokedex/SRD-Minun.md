---
Ability1: Minus
Ability2: ''
BookSprite: SRD-minun-BookSprite.png
BoxSprite: SRD-minun-BoxSprite.png
DexCategory: Cheering Pokemon
DexDescription: "They will cheer their friends with their lives and will keep on cheering\
  \ to their last breath. If a partner is in trouble, this Pokemon will create a curtain\
  \ of sparks on its friend\u2019s side to boost its spirit."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Volt Absorb
HomeSprite: SRD-minun-HomeSprite.png
Image: minun.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Entrainment|Entrainment]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Starter
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Trump Card|Trump Card]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Mimic|Mimic]]'
Number: 312
ShuffleToken: SRD-minun-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 4.2
  Pounds: 9.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-minun-BookSprite.png|wsmall]]
> ![[SRD-minun-HomeSprite.png]]
> ![[SRD-minun-BoxSprite.png|htiny]]
> ![[SRD-minun-ShuffleToken.png|wsmall]]


*Cheering Pokemon*
*They will cheer their friends with their lives and will keep on cheering to their last breath. If a partner is in trouble, this Pokemon will create a curtain of sparks on its friend’s side to boost its spirit.*

**DexID**:: 0312
**Name**:: Minun
**Type**:: Electric
**Abilities**:: [[SRD-Minus|Minus]] ([[SRD-Volt Absorb|Volt Absorb]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.3lbs / 4.2kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Minun.md"
flatten moves as T
where file.path = this.file.path
```
