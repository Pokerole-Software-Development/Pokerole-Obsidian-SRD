---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-chimchar-BookSprite.png
BoxSprite: SRD-chimchar-BoxSprite.png
DexCategory: Chimp Pokemon
DexDescription: They climb sheer cliffs to live at the top of the mountains. Small
  groups of them tend to visit human camping sites to steal food and objects. They
  are playful and will wreak havoc if they want to have fun.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Monferno]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Iron Fist
HomeSprite: SRD-chimchar-HomeSprite.png
Image: chimchar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Facade|Facade]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Slack Off|Slack Off]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 390
ShuffleToken: SRD-chimchar-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 6.2
  Pounds: 13.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chimchar-BookSprite.png|wsmall]]
> ![[SRD-chimchar-HomeSprite.png]]
> ![[SRD-chimchar-BoxSprite.png|htiny]]
> ![[SRD-chimchar-ShuffleToken.png|wsmall]]


*Chimp Pokemon*
*They climb sheer cliffs to live at the top of the mountains. Small groups of them tend to visit human camping sites to steal food and objects. They are playful and will wreak havoc if they want to have fun.*

**DexID**:: 0390
**Name**:: Chimchar
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 13.7lbs / 6.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Monferno]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chimchar.md"
flatten moves as T
where file.path = this.file.path
```
