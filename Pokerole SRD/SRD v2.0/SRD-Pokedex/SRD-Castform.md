---
Ability1: Forecast
Ability2: ''
BookSprite: SRD-castform-BookSprite.png
BoxSprite: SRD-castform-BoxSprite.png
DexCategory: Weather Pokemon
DexDescription: This Pokemon reacts to the weather by changing its type and looks.
  It can also change the weather at will. When there is a drought, farmers lure them
  with small hanging dolls to ask them for rain.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-castform-HomeSprite.png
Image: castform.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Reflect Type|Reflect Type]]'
Number: 351
ShuffleToken: SRD-castform-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 0.8
  Pounds: 1.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-castform-BookSprite.png|wsmall]]
> ![[SRD-castform-HomeSprite.png]]
> ![[SRD-castform-BoxSprite.png|htiny]]
> ![[SRD-castform-ShuffleToken.png|wsmall]]


*Weather Pokemon*
*This Pokemon reacts to the weather by changing its type and looks. It can also change the weather at will. When there is a drought, farmers lure them with small hanging dolls to ask them for rain.*

**DexID**:: 0351
**Name**:: Castform
**Type**:: Normal
**Abilities**:: [[SRD-Forecast|Forecast]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 1.8lbs / 0.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Castform.md"
flatten moves as T
where file.path = this.file.path
```
