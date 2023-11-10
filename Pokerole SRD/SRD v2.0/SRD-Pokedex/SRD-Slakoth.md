---
Ability1: Truant
Ability2: ''
BookSprite: SRD-slakoth-BookSprite.png
BoxSprite: SRD-slakoth-BoxSprite.png
DexCategory: Slacker Pokemon
DexDescription: "They laze around 20 hours a day barely eating. Slakoths remain motionless\
  \ no matter what. It\u2019s rare to see this Pokemon doing something, most of them\
  \ never even bother to evolve."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vigoroth]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-slakoth-HomeSprite.png
Image: slakoth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-After You|After You]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
Number: 287
ShuffleToken: SRD-slakoth-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 24.0
  Pounds: 52.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slakoth-BookSprite.png|wsmall]]
> ![[SRD-slakoth-HomeSprite.png]]
> ![[SRD-slakoth-BoxSprite.png|htiny]]
> ![[SRD-slakoth-ShuffleToken.png|wsmall]]


*Slacker Pokemon*
*They laze around 20 hours a day barely eating. Slakoths remain motionless no matter what. It’s rare to see this Pokemon doing something, most of them never even bother to evolve.*

**DexID**:: 0287
**Name**:: Slakoth
**Type**:: Normal
**Abilities**:: [[SRD-Truant|Truant]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 52.9lbs / 24.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Vigoroth]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slakoth.md"
flatten moves as T
where file.path = this.file.path
```
