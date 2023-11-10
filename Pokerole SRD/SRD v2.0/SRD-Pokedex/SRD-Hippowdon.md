---
Ability1: Sand Stream
Ability2: ''
BookSprite: SRD-hippowdon-BookSprite.png
BoxSprite: SRD-hippowdon-BoxSprite.png
DexCategory: Heavyweight Pokemon
DexDescription: It becomes territorial and aggressive after evolving. Its open mouth
  stands over 7 ft. tall. There are records of one that came out of the sand and crushed
  a truck that was passing over its territory.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Hippopotas]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Sand Force
HomeSprite: SRD-hippowdon-HomeSprite.png
Image: hippowdon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Slack Off|Slack Off]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
Number: 450
ShuffleToken: SRD-hippowdon-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 300.0
  Pounds: 661.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hippowdon-BookSprite.png|wsmall]]
> ![[SRD-hippowdon-HomeSprite.png]]
> ![[SRD-hippowdon-BoxSprite.png|htiny]]
> ![[SRD-hippowdon-ShuffleToken.png|wsmall]]


*Heavyweight Pokemon*
*It becomes territorial and aggressive after evolving. Its open mouth stands over 7 ft. tall. There are records of one that came out of the sand and crushed a truck that was passing over its territory.*

**DexID**:: 0450
**Name**:: Hippowdon
**Type**:: Ground
**Abilities**:: [[SRD-Sand Stream|Sand Stream]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 661.4lbs / 300.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Hippopotas]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hippowdon.md"
flatten moves as T
where file.path = this.file.path
```
