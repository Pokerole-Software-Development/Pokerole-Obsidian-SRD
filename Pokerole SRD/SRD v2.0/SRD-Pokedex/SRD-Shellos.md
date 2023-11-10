---
Ability1: Sticky Hold
Ability2: Storm Drain
BookSprite: SRD-shellos-BookSprite.png
BoxSprite: SRD-shellos-BoxSprite.png
DexCategory: Sea Slug Pokemon
DexDescription: Its shape and coloration change depending on its habitat of salt or
  sweet water. Their body is very soft and squishy but they can stretch long lengths.
  It releases a purple liquid from its body if threatened.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gastrodon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sand Force
HomeSprite: SRD-shellos-HomeSprite.png
Image: shellos.png
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
Number: 422
ShuffleToken: SRD-shellos-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 6.3
  Pounds: 13.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shellos-BookSprite.png|wsmall]]
> ![[SRD-shellos-HomeSprite.png]]
> ![[SRD-shellos-BoxSprite.png|htiny]]
> ![[SRD-shellos-ShuffleToken.png|wsmall]]


*Sea Slug Pokemon*
*Its shape and coloration change depending on its habitat of salt or sweet water. Their body is very soft and squishy but they can stretch long lengths. It releases a purple liquid from its body if threatened.*

**DexID**:: 0422
**Name**:: Shellos
**Type**:: Water
**Abilities**:: [[SRD-Sticky Hold|Sticky Hold]] / [[SRD-Storm Drain|Storm Drain]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 13.9lbs / 6.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Gastrodon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shellos.md"
flatten moves as T
where file.path = this.file.path
```
