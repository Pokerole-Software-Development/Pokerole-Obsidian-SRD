---
Ability1: Run Away
Ability2: Pickup
BookSprite: SRD-pachirisu-BookSprite.png
BoxSprite: SRD-pachirisu-BoxSprite.png
DexCategory: EleSquirrel Pokemon
DexDescription: It lives on top of the trees, gathering food for the cold winter months.
  It keeps warm by making fur balls charged with static electricity. Like other electric
  rodents, it stores electricity on its cheek pouches.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Volt Absorb
HomeSprite: SRD-pachirisu-HomeSprite.png
Image: pachirisu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Follow Me|Follow Me]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 417
ShuffleToken: SRD-pachirisu-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 3.9
  Pounds: 8.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pachirisu-BookSprite.png|wsmall]]
> ![[SRD-pachirisu-HomeSprite.png]]
> ![[SRD-pachirisu-BoxSprite.png|htiny]]
> ![[SRD-pachirisu-ShuffleToken.png|wsmall]]


*EleSquirrel Pokemon*
*It lives on top of the trees, gathering food for the cold winter months. It keeps warm by making fur balls charged with static electricity. Like other electric rodents, it stores electricity on its cheek pouches.*

**DexID**:: 0417
**Name**:: Pachirisu
**Type**:: Electric
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Pickup|Pickup]] ([[SRD-Volt Absorb|Volt Absorb]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 8.6lbs / 3.9kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pachirisu.md"
flatten moves as T
where file.path = this.file.path
```
