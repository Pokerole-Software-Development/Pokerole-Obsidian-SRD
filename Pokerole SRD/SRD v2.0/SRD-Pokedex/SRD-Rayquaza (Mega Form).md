---
Ability1: Delta Stream
Ability2: ''
BookSprite: SRD-rayquaza-mega-form-BookSprite.png
BoxSprite: SRD-rayquaza-mega-form-BoxSprite.png
DexCategory: No Data
DexDescription: What does the power of the Mega Stone truly entail? Is it the bond
  between a Trainer and their companion? Or is it all about taking a hold of a forbidden
  power?
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Pokeball
  Kind: Mega
  Pokemon: '[[SRD-Rayquaza]]'
GenderType: N
Height:
  Feet: 35.4
  Meters: 10.8
HiddenAbility: ''
HomeSprite: SRD-rayquaza-mega-form-HomeSprite.png
Image: rayquaza-mega-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Twister|Twister]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Fly|Fly]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Dragon Ascent|Dragon Ascent]]'
- - Master
  - '[[SRD-Sky Drop|Sky Drop]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Dig|Dig]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
Number: 384
ShuffleToken: SRD-rayquaza-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Flying
Weight:
  Kilograms: 392.0
  Pounds: 864.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rayquaza-mega-form-BookSprite.png|wsmall]]
> ![[SRD-rayquaza-mega-form-HomeSprite.png]]
> ![[SRD-rayquaza-mega-form-BoxSprite.png|htiny]]
> ![[SRD-rayquaza-mega-form-ShuffleToken.png|wsmall]]


*No Data*
*What does the power of the Mega Stone truly entail? Is it the bond between a Trainer and their companion? Or is it all about taking a hold of a forbidden power?*

**DexID**:: 0384M1
**Name**:: Rayquaza (Mega Form)
**Type**:: Dragon / Flying
**Abilities**:: [[SRD-Delta Stream|Delta Stream]]
**Base HP**:: 11

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::9)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 35'4" / 10.8m
**Weight**: 864.2lbs / 392.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   | Item     |
|:----------|:-----------------|:-------|:---------|
| From      | [[SRD-Rayquaza]] | Mega   | Pokeball |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rayquaza (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
