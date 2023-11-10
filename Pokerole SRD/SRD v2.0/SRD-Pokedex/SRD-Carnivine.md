---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-carnivine-BookSprite.png
BoxSprite: SRD-carnivine-BoxSprite.png
DexCategory: Bug Catcher Pokemon
DexDescription: "It binds itself to trees in marshes. It attracts prey with its sweet-smelling\
  \ drool and gulps them down in one bite. It can take it a whole day to digest a\
  \ single prey but It won\u2019t need to eat for at least a week."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-carnivine-HomeSprite.png
Image: carnivine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bind|Bind]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Power Whip|Power Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 455
ShuffleToken: SRD-carnivine-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 27.0
  Pounds: 59.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-carnivine-BookSprite.png|wsmall]]
> ![[SRD-carnivine-HomeSprite.png]]
> ![[SRD-carnivine-BoxSprite.png|htiny]]
> ![[SRD-carnivine-ShuffleToken.png|wsmall]]


*Bug Catcher Pokemon*
*It binds itself to trees in marshes. It attracts prey with its sweet-smelling drool and gulps them down in one bite. It can take it a whole day to digest a single prey but It won’t need to eat for at least a week.*

**DexID**:: 0455
**Name**:: Carnivine
**Type**:: Grass
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 59.5lbs / 27.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Carnivine.md"
flatten moves as T
where file.path = this.file.path
```
