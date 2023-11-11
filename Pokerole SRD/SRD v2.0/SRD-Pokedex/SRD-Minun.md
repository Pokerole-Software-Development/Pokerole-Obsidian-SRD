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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Entrainment|Entrainment]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nuzzle|Nuzzle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spark|Spark]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Encore|Encore]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Copycat|Copycat]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder|Thunder]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trump Card|Trump Card]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Kiss|Sweet Kiss]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mimic|Mimic]]'
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
