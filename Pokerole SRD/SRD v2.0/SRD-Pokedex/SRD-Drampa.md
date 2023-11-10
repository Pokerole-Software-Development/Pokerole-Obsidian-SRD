---
Ability1: Berserk
Ability2: Sap Sipper
BookSprite: SRD-drampa-BookSprite.png
BoxSprite: SRD-drampa-BoxSprite.png
DexCategory: Placid Pokemon
DexDescription: They live alone at the top of high mountains but come down in the
  morning to eat berries. It is a caring Pokemon, specially towards children and will
  fiercely protect any children it cares for with tremendous force.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Cloud Nine
HomeSprite: SRD-drampa-HomeSprite.png
Image: drampa.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Glare|Glare]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Fly|Fly]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
Number: 780
ShuffleToken: SRD-drampa-ShuffleToken.png
Type1: Normal
Type2: Dragon
Weight:
  Kilograms: 185.0
  Pounds: 407.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drampa-BookSprite.png|wsmall]]
> ![[SRD-drampa-HomeSprite.png]]
> ![[SRD-drampa-BoxSprite.png|htiny]]
> ![[SRD-drampa-ShuffleToken.png|wsmall]]


*Placid Pokemon*
*They live alone at the top of high mountains but come down in the morning to eat berries. It is a caring Pokemon, specially towards children and will fiercely protect any children it cares for with tremendous force.*

**DexID**:: 0780
**Name**:: Drampa
**Type**:: Normal / Dragon
**Abilities**:: [[SRD-Berserk|Berserk]] / [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Cloud Nine|Cloud Nine]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 407.9lbs / 185.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drampa.md"
flatten moves as T
where file.path = this.file.path
```
