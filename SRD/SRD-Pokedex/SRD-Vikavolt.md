---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-vikavolt-BookSprite.png
BoxSprite: SRD-vikavolt-BoxSprite.png
DexCategory: Stag Beetle Pokemon
DexDescription: "The electricity it shoots through its jaws is very dangerous, it\
  \ zaps bird Pokemon trying to eat it. Its flight is peculiar, for it bends in a\
  \ 90\xB0 angle or flies backwards without a problem."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Charjabug]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-vikavolt-HomeSprite.png
Image: vikavolt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Charge Beam|Charge Beam]]'
Number: 738
ShuffleToken: SRD-vikavolt-ShuffleToken.png
Type1: Bug
Type2: Electric
Weight:
  Kilograms: 45.0
  Pounds: 99.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vikavolt-BookSprite.png|wsmall]]
> ![[SRD-vikavolt-HomeSprite.png]]
> ![[SRD-vikavolt-BoxSprite.png|htiny]]
> ![[SRD-vikavolt-ShuffleToken.png|wsmall]]


*Stag Beetle Pokemon*
*The electricity it shoots through its jaws is very dangerous, it zaps bird Pokemon trying to eat it. Its flight is peculiar, for it bends in a 90° angle or flies backwards without a problem.*

**DexID**:: 0738
**Name**:: Vikavolt
**Type**:: Bug / Electric
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 99.2lbs / 45.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Charjabug]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Vikavolt.md"
flatten moves as T
where file.path = this.file.path
```
