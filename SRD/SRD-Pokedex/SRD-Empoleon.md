---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-empoleon-BookSprite.png
BoxSprite: SRD-empoleon-BoxSprite.png
DexCategory: Emperor Pokemon
DexDescription: They are regal and arrogant. Their beaks slice apart the drifting
  ice while swimming as fast as a jet boat. They avoid unnecessary fights, but will
  crush and cleave anyone that hurts or threatens its pride.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Prinplup]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Defiant
HomeSprite: SRD-empoleon-HomeSprite.png
Image: empoleon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Peck|Peck]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
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
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
Number: 395
ShuffleToken: SRD-empoleon-ShuffleToken.png
Type1: Water
Type2: Steel
Weight:
  Kilograms: 84.5
  Pounds: 186.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-empoleon-BookSprite.png|wsmall]]
> ![[SRD-empoleon-HomeSprite.png]]
> ![[SRD-empoleon-BoxSprite.png|htiny]]
> ![[SRD-empoleon-ShuffleToken.png|wsmall]]


*Emperor Pokemon*
*They are regal and arrogant. Their beaks slice apart the drifting ice while swimming as fast as a jet boat. They avoid unnecessary fights, but will crush and cleave anyone that hurts or threatens its pride.*

**DexID**:: 0395
**Name**:: Empoleon
**Type**:: Water / Steel
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 186.3lbs / 84.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Prinplup]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Empoleon.md"
flatten moves as T
where file.path = this.file.path
```
