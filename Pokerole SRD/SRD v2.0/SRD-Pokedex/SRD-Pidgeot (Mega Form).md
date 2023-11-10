---
Ability1: No Guard
Ability2: ''
BookSprite: SRD-pidgeot-mega-form-BookSprite.png
BoxSprite: SRD-pidgeot-mega-form-BoxSprite.png
DexCategory: Bird Pokemon
DexDescription: "With the power of the Mega Stone Pidgeot's flying becomes a blurred\
  \ red stripe in the sky. It won\u2019t stop soaring the skies while in this state\
  \ without tiring or needing to rest for many days at a time."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Pidgeotite
  Kind: Mega
  Pokemon: '[[SRD-Pidgeot]]'
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: ''
HomeSprite: SRD-pidgeot-mega-form-HomeSprite.png
Image: pidgeot-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Mirror Move|Mirror Move]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Roost|Roost]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
Number: 18
ShuffleToken: SRD-pidgeot-mega-form-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 50.5
  Pounds: 111.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pidgeot-mega-form-BookSprite.png|wsmall]]
> ![[SRD-pidgeot-mega-form-HomeSprite.png]]
> ![[SRD-pidgeot-mega-form-BoxSprite.png|htiny]]
> ![[SRD-pidgeot-mega-form-ShuffleToken.png|wsmall]]


*Bird Pokemon*
*With the power of the Mega Stone Pidgeot's flying becomes a blurred red stripe in the sky. It won’t stop soaring the skies while in this state without tiring or needing to rest for many days at a time.*

**DexID**:: 0018M1
**Name**:: Pidgeot (Mega Form)
**Type**:: Normal / Flying
**Abilities**:: [[SRD-No Guard|No Guard]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 111.3lbs / 50.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Pidgeot]] | Mega   | Pidgeotite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pidgeot (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
