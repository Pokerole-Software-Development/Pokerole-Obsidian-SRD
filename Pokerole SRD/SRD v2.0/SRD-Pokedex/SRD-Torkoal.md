---
Ability1: White Smoke
Ability2: Drought
BookSprite: SRD-torkoal-BookSprite.png
BoxSprite: SRD-torkoal-BoxSprite.png
DexCategory: Coal Pokemon
DexDescription: They constantly search for coal to add to their shell, digging mountains
  tirelessly because it is the source of their power. If they run out of coal, they
  grow weak. They are commonly found in abandoned coal mines.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Shell Armor
HomeSprite: SRD-torkoal-HomeSprite.png
Image: torkoal.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Number: 324
ShuffleToken: SRD-torkoal-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 80.4
  Pounds: 177.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-torkoal-BookSprite.png|wsmall]]
> ![[SRD-torkoal-HomeSprite.png]]
> ![[SRD-torkoal-BoxSprite.png|htiny]]
> ![[SRD-torkoal-ShuffleToken.png|wsmall]]


*Coal Pokemon*
*They constantly search for coal to add to their shell, digging mountains tirelessly because it is the source of their power. If they run out of coal, they grow weak. They are commonly found in abandoned coal mines.*

**DexID**:: 0324
**Name**:: Torkoal
**Type**:: Fire
**Abilities**:: [[SRD-White Smoke|White Smoke]] / [[SRD-Drought|Drought]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 177.3lbs / 80.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Torkoal.md"
flatten moves as T
where file.path = this.file.path
```
