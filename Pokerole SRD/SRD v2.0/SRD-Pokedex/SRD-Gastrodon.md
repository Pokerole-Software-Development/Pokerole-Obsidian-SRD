---
Ability1: Sticky Hold
Ability2: Storm Drain
BookSprite: SRD-gastrodon-BookSprite.png
BoxSprite: SRD-gastrodon-BoxSprite.png
DexCategory: Sea Slug Pokemon
DexDescription: It has a pliable body without any bones. If any part of its body is
  torn off, it will grow back in minutes. There is evidence that it had a hard shell
  on its back for protection in prehistoric times.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shellos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Sand Force
HomeSprite: SRD-gastrodon-HomeSprite.png
Image: gastrodon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Beginner
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Number: 423
ShuffleToken: SRD-gastrodon-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 29.9
  Pounds: 65.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gastrodon-BookSprite.png|wsmall]]
> ![[SRD-gastrodon-HomeSprite.png]]
> ![[SRD-gastrodon-BoxSprite.png|htiny]]
> ![[SRD-gastrodon-ShuffleToken.png|wsmall]]


*Sea Slug Pokemon*
*It has a pliable body without any bones. If any part of its body is torn off, it will grow back in minutes. There is evidence that it had a hard shell on its back for protection in prehistoric times.*

**DexID**:: 0423
**Name**:: Gastrodon
**Type**:: Water / Ground
**Abilities**:: [[SRD-Sticky Hold|Sticky Hold]] / [[SRD-Storm Drain|Storm Drain]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 65.9lbs / 29.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Shellos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gastrodon.md"
flatten moves as T
where file.path = this.file.path
```
