---
Ability1: Pickup
Ability2: Gluttony
BookSprite: SRD-zigzagoon-BookSprite.png
BoxSprite: SRD-zigzagoon-BoxSprite.png
DexCategory: Tiny Raccoon Pokemon
DexDescription: They are extremely curious and want to know all about everything.
  Due to their innate curiosity, they usually find hidden objects. Sometimes they
  play dead to avoid being attacked.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Linoone]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Quick Feet
HomeSprite: SRD-zigzagoon-HomeSprite.png
Image: zigzagoon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 263
ShuffleToken: SRD-zigzagoon-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 17.5
  Pounds: 38.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zigzagoon-BookSprite.png|wsmall]]
> ![[SRD-zigzagoon-HomeSprite.png]]
> ![[SRD-zigzagoon-BoxSprite.png|htiny]]
> ![[SRD-zigzagoon-ShuffleToken.png|wsmall]]


*Tiny Raccoon Pokemon*
*They are extremely curious and want to know all about everything. Due to their innate curiosity, they usually find hidden objects. Sometimes they play dead to avoid being attacked.*

**DexID**:: 0263
**Name**:: Zigzagoon
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 38.6lbs / 17.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Linoone]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Zigzagoon.md"
flatten moves as T
where file.path = this.file.path
```
