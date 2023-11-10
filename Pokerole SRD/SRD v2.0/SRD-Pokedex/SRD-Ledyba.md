---
Ability1: Swarm
Ability2: Early Bird
BookSprite: SRD-ledyba-BookSprite.png
BoxSprite: SRD-ledyba-BoxSprite.png
DexCategory: Five Star Pokemon
DexDescription: These timid Pokemon swarm in groups to keep each other warm during
  the winter. It communicates with others through a special scent. They often appear
  covered in the morning dew.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ledian]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Rattled
HomeSprite: SRD-ledyba-HomeSprite.png
Image: ledyba.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Comet Punch|Comet Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swift|Swift]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
Number: 165
ShuffleToken: SRD-ledyba-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 10.8
  Pounds: 23.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ledyba-BookSprite.png|wsmall]]
> ![[SRD-ledyba-HomeSprite.png]]
> ![[SRD-ledyba-BoxSprite.png|htiny]]
> ![[SRD-ledyba-ShuffleToken.png|wsmall]]


*Five Star Pokemon*
*These timid Pokemon swarm in groups to keep each other warm during the winter. It communicates with others through a special scent. They often appear covered in the morning dew.*

**DexID**:: 0165
**Name**:: Ledyba
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 23.8lbs / 10.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Ledian]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ledyba.md"
flatten moves as T
where file.path = this.file.path
```
