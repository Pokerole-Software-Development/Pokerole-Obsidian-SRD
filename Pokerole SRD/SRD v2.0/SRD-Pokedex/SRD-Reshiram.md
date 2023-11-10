---
Ability1: Turboblaze
Ability2: ''
BookSprite: SRD-reshiram-BookSprite.png
BoxSprite: SRD-reshiram-BoxSprite.png
DexCategory: No Data
DexDescription: "An Incredibly old scroll written in an ancient language, tells about\
  \ a world of truth built by purifying fire. It also tells about a big dispute. The\
  \ rest of the scroll is burned\u2026"
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 10.5
  Meters: 3.2
HiddenAbility: ''
HomeSprite: SRD-reshiram-HomeSprite.png
Image: reshiram.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Fusion Flare|Fusion Flare]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Blue Flare|Blue Flare]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Wish|Wish]]'
- - Master
  - '[[SRD-Fire Pledge|Fire Pledge]]'
- - Master
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
Number: 643
ShuffleToken: SRD-reshiram-ShuffleToken.png
Type1: Dragon
Type2: Fire
Weight:
  Kilograms: 330.0
  Pounds: 727.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-reshiram-BookSprite.png|wsmall]]
> ![[SRD-reshiram-HomeSprite.png]]
> ![[SRD-reshiram-BoxSprite.png|htiny]]
> ![[SRD-reshiram-ShuffleToken.png|wsmall]]


*No Data*
*An Incredibly old scroll written in an ancient language, tells about a world of truth built by purifying fire. It also tells about a big dispute. The rest of the scroll is burned…*

**DexID**:: 0643
**Name**:: Reshiram
**Type**:: Dragon / Fire
**Abilities**:: [[SRD-Turboblaze|Turboblaze]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 10'5" / 3.2m
**Weight**: 727.5lbs / 330.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Reshiram.md"
flatten moves as T
where file.path = this.file.path
```
