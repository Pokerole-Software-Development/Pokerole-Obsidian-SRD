---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-solrock-BookSprite.png
BoxSprite: SRD-solrock-BoxSprite.png
DexCategory: Meteorite Pokemon
DexDescription: People say it came from space. They release the purest light when
  they get angry. Usually found absorbing solar light during the day, Solrocks can
  emit blinding lights and burning heat while spinning.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-solrock-HomeSprite.png
Image: solrock.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Wonder Room|Wonder Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Pro
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
Number: 338
ShuffleToken: SRD-solrock-ShuffleToken.png
Type1: Rock
Type2: Psychic
Weight:
  Kilograms: 154.0
  Pounds: 339.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-solrock-BookSprite.png|wsmall]]
> ![[SRD-solrock-HomeSprite.png]]
> ![[SRD-solrock-BoxSprite.png|htiny]]
> ![[SRD-solrock-ShuffleToken.png|wsmall]]


*Meteorite Pokemon*
*People say it came from space. They release the purest light when they get angry. Usually found absorbing solar light during the day, Solrocks can emit blinding lights and burning heat while spinning.*

**DexID**:: 0338
**Name**:: Solrock
**Type**:: Rock / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 339.5lbs / 154.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Solrock.md"
flatten moves as T
where file.path = this.file.path
```
