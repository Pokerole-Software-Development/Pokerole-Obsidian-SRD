---
Ability1: Hustle
Ability2: Sniper
BookSprite: SRD-remoraid-BookSprite.png
BoxSprite: SRD-remoraid-BoxSprite.png
DexCategory: Jet Pokemon
DexDescription: Remoraid has a remarkable aim with its water gun. This ability is
  used to hunt down flying enemies above the sea. They can be seen clinging into Mantines
  to travel faster.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Octillery]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Moody
HomeSprite: SRD-remoraid-HomeSprite.png
Image: remoraid.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lock-On|Lock-On]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Pro
  - '[[SRD-Dive|Dive]]'
- - Pro
  - '[[SRD-Supersonic|Supersonic]]'
Number: 223
ShuffleToken: SRD-remoraid-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-remoraid-BookSprite.png|wsmall]]
> ![[SRD-remoraid-HomeSprite.png]]
> ![[SRD-remoraid-BoxSprite.png|htiny]]
> ![[SRD-remoraid-ShuffleToken.png|wsmall]]


*Jet Pokemon*
*Remoraid has a remarkable aim with its water gun. This ability is used to hunt down flying enemies above the sea. They can be seen clinging into Mantines to travel faster.*

**DexID**:: 0223
**Name**:: Remoraid
**Type**:: Water
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Sniper|Sniper]] ([[SRD-Moody|Moody]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Octillery]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Remoraid.md"
flatten moves as T
where file.path = this.file.path
```
