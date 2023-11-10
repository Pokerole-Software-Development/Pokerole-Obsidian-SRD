---
Ability1: Gluttony
Ability2: Flash Fire
BookSprite: SRD-heatmor-BookSprite.png
BoxSprite: SRD-heatmor-BoxSprite.png
DexCategory: Anteater Pokemon
DexDescription: "It draws in air through its tail, then transforms it into fire and\
  \ uses it like a tongue. You can see them defending Durant\u2019s colonies from\
  \ predators so they can be the only ones who can eat them."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: White Smoke
HomeSprite: SRD-heatmor-HomeSprite.png
Image: heatmor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Incinerate|Incinerate]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Fire Lash|Fire Lash]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stockpile|Stockpile]]'
- - Ace
  - '[[SRD-Swallow|Swallow]]'
- - Ace
  - '[[SRD-Spit Up|Spit Up]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Number: 631
ShuffleToken: SRD-heatmor-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 58.0
  Pounds: 127.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-heatmor-BookSprite.png|wsmall]]
> ![[SRD-heatmor-HomeSprite.png]]
> ![[SRD-heatmor-BoxSprite.png|htiny]]
> ![[SRD-heatmor-ShuffleToken.png|wsmall]]


*Anteater Pokemon*
*It draws in air through its tail, then transforms it into fire and uses it like a tongue. You can see them defending Durant’s colonies from predators so they can be the only ones who can eat them.*

**DexID**:: 0631
**Name**:: Heatmor
**Type**:: Fire
**Abilities**:: [[SRD-Gluttony|Gluttony]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-White Smoke|White Smoke]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 127.9lbs / 58.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Heatmor.md"
flatten moves as T
where file.path = this.file.path
```
