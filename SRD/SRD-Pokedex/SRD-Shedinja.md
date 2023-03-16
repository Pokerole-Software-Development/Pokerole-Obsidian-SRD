---
Ability1: Wonder Guard
Ability2: ''
BookSprite: SRD-shedinja-BookSprite.png
BoxSprite: SRD-shedinja-BoxSprite.png
DexCategory: Shed Pokemon
DexDescription: "On extremely rare occasions; when Nincada evolves, the empty cocoon\
  \ comes to life. They don\u2019t move, they only float unnaturally around. It is\
  \ said that it will steal the soul of anyone looking directly at them."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Nincada]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-shedinja-HomeSprite.png
Image: shedinja.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Spite|Spite]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Grudge|Grudge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-X-Scissor|X-Scissor]]'
Number: 292
ShuffleToken: SRD-shedinja-ShuffleToken.png
Type1: Bug
Type2: Ghost
Weight:
  Kilograms: 1.2
  Pounds: 2.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shedinja-BookSprite.png|wsmall]]
> ![[SRD-shedinja-HomeSprite.png]]
> ![[SRD-shedinja-BoxSprite.png|htiny]]
> ![[SRD-shedinja-ShuffleToken.png|wsmall]]


*Shed Pokemon*
*On extremely rare occasions; when Nincada evolves, the empty cocoon comes to life. They don’t move, they only float unnaturally around. It is said that it will steal the soul of anyone looking directly at them.*

**DexID**:: 0292
**Name**:: Shedinja
**Type**:: Bug / Ghost
**Abilities**:: [[SRD-Wonder Guard|Wonder Guard]]
**Base HP**:: 1

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 2.6lbs / 1.2kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Nincada]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Shedinja.md"
flatten moves as T
where file.path = this.file.path
```
