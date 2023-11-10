---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-prinplup-BookSprite.png
BoxSprite: SRD-prinplup-BoxSprite.png
DexCategory: Penguin Pokemon
DexDescription: "Prinplups hunt in icy seas. They live solitary lives because they\
  \ cannot stand company and will never form a group or a team. They believe they\
  \ are the most important thing in the world, it\u2019s almost irritating."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Piplup]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Empoleon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Defiant
HomeSprite: SRD-prinplup-HomeSprite.png
Image: prinplup.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Peck|Peck]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mist|Mist]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 394
ShuffleToken: SRD-prinplup-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 23.0
  Pounds: 50.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-prinplup-BookSprite.png|wsmall]]
> ![[SRD-prinplup-HomeSprite.png]]
> ![[SRD-prinplup-BoxSprite.png|htiny]]
> ![[SRD-prinplup-ShuffleToken.png|wsmall]]


*Penguin Pokemon*
*Prinplups hunt in icy seas. They live solitary lives because they cannot stand company and will never form a group or a team. They believe they are the most important thing in the world, it’s almost irritating.*

**DexID**:: 0394
**Name**:: Prinplup
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 50.7lbs / 23.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Piplup]]   | Level  | Medium  |
| To        | [[SRD-Empoleon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Prinplup.md"
flatten moves as T
where file.path = this.file.path
```
