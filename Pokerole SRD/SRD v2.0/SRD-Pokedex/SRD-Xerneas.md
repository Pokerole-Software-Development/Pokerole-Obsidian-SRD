---
Ability1: Fairy Aura
Ability2: ''
BookSprite: SRD-xerneas-BookSprite.png
BoxSprite: SRD-xerneas-BoxSprite.png
DexCategory: No Data
DexDescription: A Kalos legend tells about the eternal struggle between life and death.
  In the story an ancient King tried to obtain eternal life and the power to make
  its loved ones live again.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: ''
HomeSprite: SRD-xerneas-HomeSprite.png
Image: xerneas.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Master
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Master
  - '[[SRD-Ingrain|Ingrain]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Geomancy|Geomancy]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Megahorn|Megahorn]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Psyshock|Psyshock]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
Number: 716
ShuffleToken: SRD-xerneas-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 215.0
  Pounds: 474.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-xerneas-BookSprite.png|wsmall]]
> ![[SRD-xerneas-HomeSprite.png]]
> ![[SRD-xerneas-BoxSprite.png|htiny]]
> ![[SRD-xerneas-ShuffleToken.png|wsmall]]


*No Data*
*A Kalos legend tells about the eternal struggle between life and death. In the story an ancient King tried to obtain eternal life and the power to make its loved ones live again.*

**DexID**:: 0716
**Name**:: Xerneas
**Type**:: Fairy
**Abilities**:: [[SRD-Fairy Aura|Fairy Aura]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 9'8" / 3.0m
**Weight**: 474.0lbs / 215.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Xerneas.md"
flatten moves as T
where file.path = this.file.path
```
