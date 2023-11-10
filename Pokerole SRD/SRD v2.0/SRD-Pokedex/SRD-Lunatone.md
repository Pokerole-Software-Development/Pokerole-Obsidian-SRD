---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-lunatone-BookSprite.png
BoxSprite: SRD-lunatone-BoxSprite.png
DexCategory: Meteorite Pokemon
DexDescription: "First found where a meteorite fell. For this reason it\u2019s believed\
  \ it came from space. Its eyes fill people with dread and lure them to sleep. They\
  \ become very active and extremely powerful during full moons."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: ''
HomeSprite: SRD-lunatone-HomeSprite.png
Image: lunatone.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Trick Room|Trick Room]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
Number: 337
ShuffleToken: SRD-lunatone-ShuffleToken.png
Type1: Rock
Type2: Psychic
Weight:
  Kilograms: 168.0
  Pounds: 370.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lunatone-BookSprite.png|wsmall]]
> ![[SRD-lunatone-HomeSprite.png]]
> ![[SRD-lunatone-BoxSprite.png|htiny]]
> ![[SRD-lunatone-ShuffleToken.png|wsmall]]


*Meteorite Pokemon*
*First found where a meteorite fell. For this reason it’s believed it came from space. Its eyes fill people with dread and lure them to sleep. They become very active and extremely powerful during full moons.*

**DexID**:: 0337
**Name**:: Lunatone
**Type**:: Rock / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 370.4lbs / 168.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lunatone.md"
flatten moves as T
where file.path = this.file.path
```
