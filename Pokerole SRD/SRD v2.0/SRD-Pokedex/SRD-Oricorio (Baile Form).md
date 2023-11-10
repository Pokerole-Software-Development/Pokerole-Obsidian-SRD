---
Ability1: Dancer
Ability2: ''
BookSprite: SRD-oricorio-baile-form-BookSprite.png
BoxSprite: SRD-oricorio-baile-form-BoxSprite.png
DexCategory: Dancing Pokemon
DexDescription: What was thought to be different species ended up being a single Pokemon.
  Oricorio Baile is an intense and passionate Pokemon, every flap of its wings produces
  embers, its fiery dance has inspired many.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Oricorio (Pom-pom Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Oricorio (Pa''u Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Oricorio (Sensu Form)]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-oricorio-baile-form-HomeSprite.png
Image: oricorio-baile-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Air Cutter|Air Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Revelation Dance|Revelation Dance]]'
- - Ace
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Round|Round]]'
Number: 741
ShuffleToken: SRD-oricorio-baile-form-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 3.4
  Pounds: 7.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-oricorio-baile-form-BookSprite.png|wsmall]]
> ![[SRD-oricorio-baile-form-HomeSprite.png]]
> ![[SRD-oricorio-baile-form-BoxSprite.png|htiny]]
> ![[SRD-oricorio-baile-form-ShuffleToken.png|wsmall]]


*Dancing Pokemon*
*What was thought to be different species ended up being a single Pokemon. Oricorio Baile is an intense and passionate Pokemon, every flap of its wings produces embers, its fiery dance has inspired many.*

**DexID**:: 0741
**Name**:: Oricorio (Baile Form)
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Dancer|Dancer]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 7.5lbs / 3.4kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   |
|:----------|:--------------------------------|:-------|
| To        | [[SRD-Oricorio (Pom-pom Form)]] | Form   |
| To        | [[SRD-Oricorio (Pa'u Form)]]    | Form   |
| To        | [[SRD-Oricorio (Sensu Form)]]   | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Oricorio (Baile Form).md"
flatten moves as T
where file.path = this.file.path
```
