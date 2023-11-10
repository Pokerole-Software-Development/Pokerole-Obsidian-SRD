---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-carbink-BookSprite.png
BoxSprite: SRD-carbink-BoxSprite.png
DexCategory: Jewel Pokemon
DexDescription: "It\u2019s occasionally found at drilling zones and excavations in\
  \ caves. Born from temperature and pressure deep underground, it shoots beams from\
  \ the stone in its head. They can live for hundreds of years."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sturdy
HomeSprite: SRD-carbink-HomeSprite.png
Image: carbink.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Beginner
  - '[[SRD-Sharpen|Sharpen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Guard Split|Guard Split]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
- - Pro
  - '[[SRD-Safeguard|Safeguard]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
Number: 703
ShuffleToken: SRD-carbink-ShuffleToken.png
Type1: Rock
Type2: Fairy
Weight:
  Kilograms: 5.7
  Pounds: 12.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-carbink-BookSprite.png|wsmall]]
> ![[SRD-carbink-HomeSprite.png]]
> ![[SRD-carbink-BoxSprite.png|htiny]]
> ![[SRD-carbink-ShuffleToken.png|wsmall]]


*Jewel Pokemon*
*It’s occasionally found at drilling zones and excavations in caves. Born from temperature and pressure deep underground, it shoots beams from the stone in its head. They can live for hundreds of years.*

**DexID**:: 0703
**Name**:: Carbink
**Type**:: Rock / Fairy
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 1'0" / 0.3m
**Weight**: 12.6lbs / 5.7kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Carbink.md"
flatten moves as T
where file.path = this.file.path
```
