---
Ability1: Keen Eye
Ability2: Infiltrator
BookSprite: SRD-espurr-BookSprite.png
BoxSprite: SRD-espurr-BoxSprite.png
DexCategory: Restraint Pokemon
DexDescription: The organs that emit its intense psychic power are tucked under its
  ears to keep energy from escaping. It still does not control its power and could
  destroy something without realizing it.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Meowstic]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Own Tempo
HomeSprite: SRD-espurr-HomeSprite.png
Image: espurr.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Covet|Covet]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Ace
  - '[[SRD-Psyshock|Psyshock]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Barrier|Barrier]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 677
ShuffleToken: SRD-espurr-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 3.5
  Pounds: 7.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-espurr-BookSprite.png|wsmall]]
> ![[SRD-espurr-HomeSprite.png]]
> ![[SRD-espurr-BoxSprite.png|htiny]]
> ![[SRD-espurr-ShuffleToken.png|wsmall]]


*Restraint Pokemon*
*The organs that emit its intense psychic power are tucked under its ears to keep energy from escaping. It still does not control its power and could destroy something without realizing it.*

**DexID**:: 0677
**Name**:: Espurr
**Type**:: Psychic
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Own Tempo|Own Tempo]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.7lbs / 3.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Meowstic]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Espurr.md"
flatten moves as T
where file.path = this.file.path
```
