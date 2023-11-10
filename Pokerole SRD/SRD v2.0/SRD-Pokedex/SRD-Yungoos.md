---
Ability1: Stakeout
Ability2: Strong Jaw
BookSprite: SRD-yungoos-BookSprite.png
BoxSprite: SRD-yungoos-BoxSprite.png
DexCategory: Loitering Pokemon
DexDescription: "This Pokemon was brought to Alola in an attempt to eradicate Ratatta.\
  \ It spends all day searching for prey and it\u2019s constantly hungry. when the\
  \ sun sets it falls asleep right where it was standing."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gumshoos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Adaptability
HomeSprite: SRD-yungoos-HomeSprite.png
Image: yungoos.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Super Fang|Super Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Number: 734
ShuffleToken: SRD-yungoos-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yungoos-BookSprite.png|wsmall]]
> ![[SRD-yungoos-HomeSprite.png]]
> ![[SRD-yungoos-BoxSprite.png|htiny]]
> ![[SRD-yungoos-ShuffleToken.png|wsmall]]


*Loitering Pokemon*
*This Pokemon was brought to Alola in an attempt to eradicate Ratatta. It spends all day searching for prey and it’s constantly hungry. when the sun sets it falls asleep right where it was standing.*

**DexID**:: 0734
**Name**:: Yungoos
**Type**:: Normal
**Abilities**:: [[SRD-Stakeout|Stakeout]] / [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Gumshoos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Yungoos.md"
flatten moves as T
where file.path = this.file.path
```
