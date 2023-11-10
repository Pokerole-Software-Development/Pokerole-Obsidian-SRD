---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-palkia-BookSprite.png
BoxSprite: SRD-palkia-BoxSprite.png
DexCategory: No Data
DexDescription: A fantasy book describes a place where space bends in impossible ways
  and the master of that site was a Pokemon with a similar appearance.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 13.8
  Meters: 4.2
HiddenAbility: Telepathy
HomeSprite: SRD-palkia-HomeSprite.png
Image: palkia.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Spacial Rend|Spacial Rend]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Liquidation|Liquidation]]'
Number: 484
ShuffleToken: SRD-palkia-ShuffleToken.png
Type1: Water
Type2: Dragon
Weight:
  Kilograms: 336.0
  Pounds: 740.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-palkia-BookSprite.png|wsmall]]
> ![[SRD-palkia-HomeSprite.png]]
> ![[SRD-palkia-BoxSprite.png|htiny]]
> ![[SRD-palkia-ShuffleToken.png|wsmall]]


*No Data*
*A fantasy book describes a place where space bends in impossible ways and the master of that site was a Pokemon with a similar appearance.*

**DexID**:: 0484
**Name**:: Palkia
**Type**:: Water / Dragon
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 13'8" / 4.2m
**Weight**: 740.8lbs / 336.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Palkia.md"
flatten moves as T
where file.path = this.file.path
```
