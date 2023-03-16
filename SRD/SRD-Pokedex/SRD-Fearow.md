---
Ability1: Keen Eye
Ability2: ''
BookSprite: SRD-fearow-BookSprite.png
BoxSprite: SRD-fearow-BoxSprite.png
DexCategory: Beak Pokemon
DexDescription: Fearrows soar around wastelands and fields. It has the stamina to
  fly all day. It is easily annoyed and ill tempered. It attacks using its sharp beak
  to peck and pierce the foes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Spearow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Sniper
HomeSprite: SRD-fearow-HomeSprite.png
Image: fearow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Roost|Roost]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Drill Run|Drill Run]]'
- - Ace
  - '[[SRD-Pluck|Pluck]]'
Number: 22
ShuffleToken: SRD-fearow-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 38.0
  Pounds: 83.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fearow-BookSprite.png|wsmall]]
> ![[SRD-fearow-HomeSprite.png]]
> ![[SRD-fearow-BoxSprite.png|htiny]]
> ![[SRD-fearow-ShuffleToken.png|wsmall]]


*Beak Pokemon*
*Fearrows soar around wastelands and fields. It has the stamina to fly all day. It is easily annoyed and ill tempered. It attacks using its sharp beak to peck and pierce the foes.*

**DexID**:: 0022
**Name**:: Fearow
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 83.8lbs / 38.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Spearow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Fearow.md"
flatten moves as T
where file.path = this.file.path
```
