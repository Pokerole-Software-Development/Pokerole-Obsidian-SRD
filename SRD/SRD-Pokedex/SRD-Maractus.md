---
Ability1: Water Absorb
Ability2: Chlorophyll
BookSprite: SRD-maractus-BookSprite.png
BoxSprite: SRD-maractus-BoxSprite.png
DexCategory: Cactus Pokemon
DexDescription: "If you see a Maractus on the desert, follow it, as they make their\
  \ nests on water oasis. This pacific Pokemon makes a sound similar to a maraca to\
  \ drive away bird Pokemon that prey on it\u2019s seeds and fruit."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Storm Drain
HomeSprite: SRD-maractus-HomeSprite.png
Image: maractus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Spiky Shield|Spiky Shield]]'
- - Beginner
  - '[[SRD-Pin Missile|Pin Missile]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Needle Arm|Needle Arm]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Acupressure|Acupressure]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Worry Seed|Worry Seed]]'
Number: 556
ShuffleToken: SRD-maractus-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-maractus-BookSprite.png|wsmall]]
> ![[SRD-maractus-HomeSprite.png]]
> ![[SRD-maractus-BoxSprite.png|htiny]]
> ![[SRD-maractus-ShuffleToken.png|wsmall]]


*Cactus Pokemon*
*If you see a Maractus on the desert, follow it, as they make their nests on water oasis. This pacific Pokemon makes a sound similar to a maraca to drive away bird Pokemon that prey on it’s seeds and fruit.*

**DexID**:: 0556
**Name**:: Maractus
**Type**:: Grass
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Storm Drain|Storm Drain]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Maractus.md"
flatten moves as T
where file.path = this.file.path
```
