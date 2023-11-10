---
Ability1: Trace
Ability2: Download
BookSprite: SRD-porygon-BookSprite.png
BoxSprite: SRD-porygon-BoxSprite.png
DexCategory: Virtual Pokemon
DexDescription: The first case of a man-made Pokemon created as computer data. It
  is capable of reverting itself into a program in order to enter the cyberspace.
  Its software has a firewall so it cannot be copied.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: 'Upgrade '
  Kind: Trade
  Pokemon: '[[SRD-Porygon2]]'
GenderType: N
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Analytic
HomeSprite: SRD-porygon-HomeSprite.png
Image: porygon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Conversion|Conversion]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Conversion 2|Conversion 2]]'
- - Beginner
  - '[[SRD-Sharpen|Sharpen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Recycle|Recycle]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Ace
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
Number: 137
ShuffleToken: SRD-porygon-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 36.5
  Pounds: 80.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-porygon-BookSprite.png|wsmall]]
> ![[SRD-porygon-HomeSprite.png]]
> ![[SRD-porygon-BoxSprite.png|htiny]]
> ![[SRD-porygon-ShuffleToken.png|wsmall]]


*Virtual Pokemon*
*The first case of a man-made Pokemon created as computer data. It is capable of reverting itself into a program in order to enter the cyberspace. Its software has a firewall so it cannot be copied.*

**DexID**:: 0137
**Name**:: Porygon
**Type**:: Normal
**Abilities**:: [[SRD-Trace|Trace]] / [[SRD-Download|Download]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 80.5lbs / 36.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item    |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Porygon2]] | Trade  | Upgrade |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Porygon.md"
flatten moves as T
where file.path = this.file.path
```
