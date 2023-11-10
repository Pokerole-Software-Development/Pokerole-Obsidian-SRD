---
Ability1: Keen Eye
Ability2: Infiltrator
BookSprite: SRD-meowstic-BookSprite.png
BoxSprite: SRD-meowstic-BoxSprite.png
DexCategory: Constraint Pokemon
DexDescription: The eye patterns on the interior of its ears emit psychic energy.
  It keeps them tightly covered because the power can be overwhelming. Females are
  white in color and more aggressive than the males.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Espurr]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Prankster
HomeSprite: SRD-meowstic-HomeSprite.png
Image: meowstic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mean Look|Mean Look]]'
- - Starter
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Imprison|Imprison]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 678
ShuffleToken: SRD-meowstic-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meowstic-BookSprite.png|wsmall]]
> ![[SRD-meowstic-HomeSprite.png]]
> ![[SRD-meowstic-BoxSprite.png|htiny]]
> ![[SRD-meowstic-ShuffleToken.png|wsmall]]


*Constraint Pokemon*
*The eye patterns on the interior of its ears emit psychic energy. It keeps them tightly covered because the power can be overwhelming. Females are white in color and more aggressive than the males.*

**DexID**:: 0678
**Name**:: Meowstic
**Type**:: Psychic
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Espurr]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meowstic.md"
flatten moves as T
where file.path = this.file.path
```
