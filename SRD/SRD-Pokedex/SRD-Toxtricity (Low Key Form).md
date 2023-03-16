---
Ability1: Punk Rock
Ability2: Minus
BookSprite: SRD-toxtricity-low-key-form-BookSprite.png
BoxSprite: SRD-toxtricity-low-key-form-BoxSprite.png
DexCategory: Punk Pokemon
DexDescription: "Commonly called \u201CLow Key Form\u201D, its nature determines its\
  \ evolution, If a Toxel is introverted it will evolve to be a chill Toxtricity.\
  \ They emit low pitched sounds and look down on others who try to provoke them."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Toxel]]'
  Special: Introvert
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Technician
HomeSprite: SRD-toxtricity-low-key-form-HomeSprite.png
Image: toxtricity-low-key-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Nuzzle|Nuzzle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Spark|Spark]]'
- - Beginner
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Leer|Leer]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Toxic|Toxic]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Overdrive|Overdrive]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - Ace
  - '[[SRD-Shift Gear|Shift Gear]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Pro
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Pro
  - '[[SRD-Round|Round]]'
Number: 849
ShuffleToken: SRD-toxtricity-low-key-form-ShuffleToken.png
Type1: Electric
Type2: Poison
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-toxtricity-low-key-form-BookSprite.png|wsmall]]
> ![[SRD-toxtricity-low-key-form-HomeSprite.png]]
> ![[SRD-toxtricity-low-key-form-BoxSprite.png|htiny]]
> ![[SRD-toxtricity-low-key-form-ShuffleToken.png|wsmall]]


*Punk Pokemon*
*Commonly called “Low Key Form”, its nature determines its evolution, If a Toxel is introverted it will evolve to be a chill Toxtricity. They emit low pitched sounds and look down on others who try to provoke them.*

**DexID**:: 0849F1
**Name**:: Toxtricity (Low Key Form)
**Type**:: Electric / Poison
**Abilities**:: [[SRD-Punk Rock|Punk Rock]] / [[SRD-Minus|Minus]] ([[SRD-Technician|Technician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   | Speed   | Special   |
|:----------|:--------------|:-------|:--------|:----------|
| From      | [[SRD-Toxel]] | Level  | Slow    | Introvert |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Toxtricity (Low Key Form).md"
flatten moves as T
where file.path = this.file.path
```
