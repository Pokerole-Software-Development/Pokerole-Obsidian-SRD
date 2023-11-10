---
Ability1: Plus
Ability2: ''
BookSprite: SRD-plusle-BookSprite.png
BoxSprite: SRD-plusle-BoxSprite.png
DexCategory: Cheering Pokemon
DexDescription: They are often seen cheerleading their friends. When someone they
  like does a great job, they shower the field with sparks, but when they lose, Plusle
  cries loudly. This Pokemon drains power from telephone poles.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Lightning Rod
HomeSprite: SRD-plusle-HomeSprite.png
Image: plusle.png
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
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Mimic|Mimic]]'
Number: 311
ShuffleToken: SRD-plusle-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 4.2
  Pounds: 9.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-plusle-BookSprite.png|wsmall]]
> ![[SRD-plusle-HomeSprite.png]]
> ![[SRD-plusle-BoxSprite.png|htiny]]
> ![[SRD-plusle-ShuffleToken.png|wsmall]]


*Cheering Pokemon*
*They are often seen cheerleading their friends. When someone they like does a great job, they shower the field with sparks, but when they lose, Plusle cries loudly. This Pokemon drains power from telephone poles.*

**DexID**:: 0311
**Name**:: Plusle
**Type**:: Electric
**Abilities**:: [[SRD-Plus|Plus]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Plusle.md"
flatten moves as T
where file.path = this.file.path
```
