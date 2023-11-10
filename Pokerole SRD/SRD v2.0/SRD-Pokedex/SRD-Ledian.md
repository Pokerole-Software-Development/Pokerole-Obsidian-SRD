---
Ability1: Swarm
Ability2: Early Bird
BookSprite: SRD-ledian-BookSprite.png
BoxSprite: SRD-ledian-BoxSprite.png
DexCategory: Five Star Pokemon
DexDescription: When the stars flicker in the night sky, it flutters about scattering
  a glowing powder. The spot patterns on its back grow larger or smaller at night
  depending on the number of stars in the sky.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ledyba]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Iron Fist
HomeSprite: SRD-ledian-HomeSprite.png
Image: ledian.png
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
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
Number: 166
ShuffleToken: SRD-ledian-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 35.6
  Pounds: 78.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ledian-BookSprite.png|wsmall]]
> ![[SRD-ledian-HomeSprite.png]]
> ![[SRD-ledian-BoxSprite.png|htiny]]
> ![[SRD-ledian-ShuffleToken.png|wsmall]]


*Five Star Pokemon*
*When the stars flicker in the night sky, it flutters about scattering a glowing powder. The spot patterns on its back grow larger or smaller at night depending on the number of stars in the sky.*

**DexID**:: 0166
**Name**:: Ledian
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 78.5lbs / 35.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Ledyba]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ledian.md"
flatten moves as T
where file.path = this.file.path
```
