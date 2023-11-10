---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-surskit-BookSprite.png
BoxSprite: SRD-surskit-BoxSprite.png
DexCategory: Pond Skater Pokemon
DexDescription: Surskit secretes oil from its feet to skate on water. It may be found
  on ponds, lakes and puddles in towns. The tip of its head produces a delicious sugary
  syrup often used in desserts and sweets.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Masquerain]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Rain Dish
HomeSprite: SRD-surskit-HomeSprite.png
Image: surskit.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Sport|Water Sport]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mist|Mist]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Sticky Web|Sticky Web]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
Number: 283
ShuffleToken: SRD-surskit-ShuffleToken.png
Type1: Bug
Type2: Water
Weight:
  Kilograms: 1.7
  Pounds: 3.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-surskit-BookSprite.png|wsmall]]
> ![[SRD-surskit-HomeSprite.png]]
> ![[SRD-surskit-BoxSprite.png|htiny]]
> ![[SRD-surskit-ShuffleToken.png|wsmall]]


*Pond Skater Pokemon*
*Surskit secretes oil from its feet to skate on water. It may be found on ponds, lakes and puddles in towns. The tip of its head produces a delicious sugary syrup often used in desserts and sweets.*

**DexID**:: 0283
**Name**:: Surskit
**Type**:: Bug / Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 3.7lbs / 1.7kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Masquerain]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Surskit.md"
flatten moves as T
where file.path = this.file.path
```
