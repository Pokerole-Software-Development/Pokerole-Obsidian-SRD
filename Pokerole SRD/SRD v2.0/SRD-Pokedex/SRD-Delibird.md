---
Ability1: Vital Spirit
Ability2: Hustle
BookSprite: SRD-delibird-BookSprite.png
BoxSprite: SRD-delibird-BoxSprite.png
DexCategory: Delivery Pokemon
DexDescription: Delibird is always carrying food for its chicks and people in need.
  They are related to the image of Santa Claus since they always carry presents for
  their good and naughty kids in their bag-looking tail.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Insomnia
HomeSprite: SRD-delibird-HomeSprite.png
Image: delibird.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Present|Present]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
Number: 225
ShuffleToken: SRD-delibird-ShuffleToken.png
Type1: Ice
Type2: Flying
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-delibird-BookSprite.png|wsmall]]
> ![[SRD-delibird-HomeSprite.png]]
> ![[SRD-delibird-BoxSprite.png|htiny]]
> ![[SRD-delibird-ShuffleToken.png|wsmall]]


*Delivery Pokemon*
*Delibird is always carrying food for its chicks and people in need. They are related to the image of Santa Claus since they always carry presents for their good and naughty kids in their bag-looking tail.*

**DexID**:: 0225
**Name**:: Delibird
**Type**:: Ice / Flying
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]] / [[SRD-Hustle|Hustle]] ([[SRD-Insomnia|Insomnia]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Delibird.md"
flatten moves as T
where file.path = this.file.path
```
