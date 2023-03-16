---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-lugia-BookSprite.png
BoxSprite: SRD-lugia-BoxSprite.png
DexCategory: No Data
DexDescription: Known as the Guardian of the Sea. It used to live in the Brass Tower,
  where Pokemon awoke. Lugia's Myth is linked to the idea that those whose death was
  pure will be reborn in the sea.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 17.1
  Meters: 5.2
HiddenAbility: Multiscale
HomeSprite: SRD-lugia-HomeSprite.png
Image: lugia.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Aeroblast|Aeroblast]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Twister|Twister]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Dive|Dive]]'
Number: 249
ShuffleToken: SRD-lugia-ShuffleToken.png
Type1: Flying
Type2: Psychic
Weight:
  Kilograms: 216.0
  Pounds: 476.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lugia-BookSprite.png|wsmall]]
> ![[SRD-lugia-HomeSprite.png]]
> ![[SRD-lugia-BoxSprite.png|htiny]]
> ![[SRD-lugia-ShuffleToken.png|wsmall]]


*No Data*
*Known as the Guardian of the Sea. It used to live in the Brass Tower, where Pokemon awoke. Lugia's Myth is linked to the idea that those whose death was pure will be reborn in the sea.*

**DexID**:: 0249
**Name**:: Lugia
**Type**:: Flying / Psychic
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Multiscale|Multiscale]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 17'1" / 5.2m
**Weight**: 476.2lbs / 216.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lugia.md"
flatten moves as T
where file.path = this.file.path
```
