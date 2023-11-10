---
Ability1: Pickup
Ability2: Gluttony
BookSprite: SRD-linoone-BookSprite.png
BoxSprite: SRD-linoone-BoxSprite.png
DexCategory: Rushing Pokemon
DexDescription: Linoones are always running at full speed, but they can only do so
  in straight lines. They find it very difficult to deal with a curved road. They
  excel at hunting but tend to eat a lot to recover from their tiring runs.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Zigzagoon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Quick Feet
HomeSprite: SRD-linoone-HomeSprite.png
Image: linoone.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 264
ShuffleToken: SRD-linoone-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 32.5
  Pounds: 71.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-linoone-BookSprite.png|wsmall]]
> ![[SRD-linoone-HomeSprite.png]]
> ![[SRD-linoone-BoxSprite.png|htiny]]
> ![[SRD-linoone-ShuffleToken.png|wsmall]]


*Rushing Pokemon*
*Linoones are always running at full speed, but they can only do so in straight lines. They find it very difficult to deal with a curved road. They excel at hunting but tend to eat a lot to recover from their tiring runs.*

**DexID**:: 0264
**Name**:: Linoone
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 71.7lbs / 32.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Zigzagoon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Linoone.md"
flatten moves as T
where file.path = this.file.path
```
