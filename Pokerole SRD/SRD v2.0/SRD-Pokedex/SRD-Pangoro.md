---
Ability1: Iron Fist
Ability2: Mold Breaker
BookSprite: SRD-pangoro-BookSprite.png
BoxSprite: SRD-pangoro-BoxSprite.png
DexCategory: Daunting Pokemon
DexDescription: "Although this pokemon has a violent temperament, it won\u2019t put\
  \ up with bullying. It charges ahead and slams its opponents like a berserker, totally\
  \ disregarding its own safety. Its mighty arms can send you flying."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pancham]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Scrappy
HomeSprite: SRD-pangoro-HomeSprite.png
Image: pangoro.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Amateur
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Low Sweep|Low Sweep]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 675
ShuffleToken: SRD-pangoro-ShuffleToken.png
Type1: Fighting
Type2: Dark
Weight:
  Kilograms: 136.0
  Pounds: 299.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pangoro-BookSprite.png|wsmall]]
> ![[SRD-pangoro-HomeSprite.png]]
> ![[SRD-pangoro-BoxSprite.png|htiny]]
> ![[SRD-pangoro-ShuffleToken.png|wsmall]]


*Daunting Pokemon*
*Although this pokemon has a violent temperament, it won’t put up with bullying. It charges ahead and slams its opponents like a berserker, totally disregarding its own safety. Its mighty arms can send you flying.*

**DexID**:: 0675
**Name**:: Pangoro
**Type**:: Fighting / Dark
**Abilities**:: [[SRD-Iron Fist|Iron Fist]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 299.8lbs / 136.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Pancham]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pangoro.md"
flatten moves as T
where file.path = this.file.path
```
