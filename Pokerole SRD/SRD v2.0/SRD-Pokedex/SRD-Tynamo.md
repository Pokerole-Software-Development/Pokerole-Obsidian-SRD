---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-tynamo-BookSprite.png
BoxSprite: SRD-tynamo-BoxSprite.png
DexCategory: EleFish Pokemon
DexDescription: "These Pokemon move in schools. They have an electricity-storing organ\
  \ at their sides but they can\u2019t generate their own power. They only discharge\
  \ electricity if they are in danger."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Eelektrik]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-tynamo-HomeSprite.png
Image: tynamo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Charge Beam|Charge Beam]]'
Number: 602
ShuffleToken: SRD-tynamo-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tynamo-BookSprite.png|wsmall]]
> ![[SRD-tynamo-HomeSprite.png]]
> ![[SRD-tynamo-BoxSprite.png|htiny]]
> ![[SRD-tynamo-ShuffleToken.png|wsmall]]


*EleFish Pokemon*
*These Pokemon move in schools. They have an electricity-storing organ at their sides but they can’t generate their own power. They only discharge electricity if they are in danger.*

**DexID**:: 0602
**Name**:: Tynamo
**Type**:: Electric
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Eelektrik]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tynamo.md"
flatten moves as T
where file.path = this.file.path
```
