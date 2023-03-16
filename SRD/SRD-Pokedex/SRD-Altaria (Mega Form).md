---
Ability1: Pixilate
Ability2: ''
BookSprite: SRD-altaria-mega-form-BookSprite.png
BoxSprite: SRD-altaria-mega-form-BoxSprite.png
DexCategory: Humming Pokemon
DexDescription: The power of the Mega Stone awakens a part of it full of wonder. Mega-Alatarias
  can be benevolent or ruthless depending on who they are dealing with. Its lush cloud-wings
  turn dark whenever it gets angry.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Altarianite
  Kind: Mega
  Pokemon: '[[SRD-Altaria]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-altaria-mega-form-HomeSprite.png
Image: altaria-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Swap|Power Swap]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
Number: 334
ShuffleToken: SRD-altaria-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Fairy
Weight:
  Kilograms: 20.6
  Pounds: 45.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-altaria-mega-form-BookSprite.png|wsmall]]
> ![[SRD-altaria-mega-form-HomeSprite.png]]
> ![[SRD-altaria-mega-form-BoxSprite.png|htiny]]
> ![[SRD-altaria-mega-form-ShuffleToken.png|wsmall]]


*Humming Pokemon*
*The power of the Mega Stone awakens a part of it full of wonder. Mega-Alatarias can be benevolent or ruthless depending on who they are dealing with. Its lush cloud-wings turn dark whenever it gets angry.*

**DexID**:: 0334M1
**Name**:: Altaria (Mega Form)
**Type**:: Dragon / Fairy
**Abilities**:: [[SRD-Pixilate|Pixilate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 45.4lbs / 20.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Altaria]] | Mega   | Altarianite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Altaria (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
