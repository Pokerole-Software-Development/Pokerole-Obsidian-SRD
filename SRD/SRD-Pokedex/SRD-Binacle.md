---
Ability1: Sniper
Ability2: Tough Claws
BookSprite: SRD-binacle-BookSprite.png
BoxSprite: SRD-binacle-BoxSprite.png
DexCategory: Two-Handed Pokemon
DexDescription: "In the shallow sea, two Binacle live inside a hollow rock. If they\
  \ don\u2019t get along, one of them will move to a different rock. They eat the\
  \ sea weed that washes up on the shore and help each other to survive."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Barbaracle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Pickpocket
HomeSprite: SRD-binacle-HomeSprite.png
Image: binacle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Clamp|Clamp]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Razor Shell|Razor Shell]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
Number: 688
ShuffleToken: SRD-binacle-ShuffleToken.png
Type1: Rock
Type2: Water
Weight:
  Kilograms: 31.0
  Pounds: 68.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-binacle-BookSprite.png|wsmall]]
> ![[SRD-binacle-HomeSprite.png]]
> ![[SRD-binacle-BoxSprite.png|htiny]]
> ![[SRD-binacle-ShuffleToken.png|wsmall]]


*Two-Handed Pokemon*
*In the shallow sea, two Binacle live inside a hollow rock. If they don’t get along, one of them will move to a different rock. They eat the sea weed that washes up on the shore and help each other to survive.*

**DexID**:: 0688
**Name**:: Binacle
**Type**:: Rock / Water
**Abilities**:: [[SRD-Sniper|Sniper]] / [[SRD-Tough Claws|Tough Claws]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 68.3lbs / 31.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Barbaracle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Binacle.md"
flatten moves as T
where file.path = this.file.path
```
