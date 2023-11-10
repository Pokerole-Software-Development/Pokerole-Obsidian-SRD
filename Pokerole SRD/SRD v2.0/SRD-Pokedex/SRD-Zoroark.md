---
Ability1: Illusion
Ability2: ''
BookSprite: SRD-zoroark-BookSprite.png
BoxSprite: SRD-zoroark-BoxSprite.png
DexCategory: Illusion Fox Pokemon
DexDescription: "They live in groups, their lair\u2019s entrance is protected with\
  \ their illusions and mirages. They have been known to fool entire towns with their\
  \ tricks. Their illusions can hide their tails now but they remain mute."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Zorua]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-zoroark-HomeSprite.png
Image: zoroark.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Foul Play|Foul Play]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Daze|Night Daze]]'
- - Ace
  - '[[SRD-Imprison|Imprison]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 571
ShuffleToken: SRD-zoroark-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 81.1
  Pounds: 178.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zoroark-BookSprite.png|wsmall]]
> ![[SRD-zoroark-HomeSprite.png]]
> ![[SRD-zoroark-BoxSprite.png|htiny]]
> ![[SRD-zoroark-ShuffleToken.png|wsmall]]


*Illusion Fox Pokemon*
*They live in groups, their lair’s entrance is protected with their illusions and mirages. They have been known to fool entire towns with their tricks. Their illusions can hide their tails now but they remain mute.*

**DexID**:: 0571
**Name**:: Zoroark
**Type**:: Dark
**Abilities**:: [[SRD-Illusion|Illusion]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 178.8lbs / 81.1kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Zorua]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zoroark.md"
flatten moves as T
where file.path = this.file.path
```
