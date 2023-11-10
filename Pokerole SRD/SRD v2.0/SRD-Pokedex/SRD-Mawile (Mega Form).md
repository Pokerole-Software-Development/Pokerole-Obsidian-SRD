---
Ability1: Huge Power
Ability2: ''
BookSprite: SRD-mawile-mega-form-BookSprite.png
BoxSprite: SRD-mawile-mega-form-BoxSprite.png
DexCategory: Deceiver Pokemon
DexDescription: "The power of the Mega Stone makes its back jaws develop a mind of\
  \ their own, they are vicious and won\u2019t release anything they bite until it\u2019\
  s crushed into pieces. They growl and howl in a haunting way."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Mawilite
  Kind: Mega
  Pokemon: '[[SRD-Mawile]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: ''
HomeSprite: SRD-mawile-mega-form-HomeSprite.png
Image: mawile-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Snatch|Snatch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Spit Up|Spit Up]]'
- - Ace
  - '[[SRD-Swallow|Swallow]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
Number: 303
ShuffleToken: SRD-mawile-mega-form-ShuffleToken.png
Type1: Steel
Type2: Fairy
Weight:
  Kilograms: 23.5
  Pounds: 51.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mawile-mega-form-BookSprite.png|wsmall]]
> ![[SRD-mawile-mega-form-HomeSprite.png]]
> ![[SRD-mawile-mega-form-BoxSprite.png|htiny]]
> ![[SRD-mawile-mega-form-ShuffleToken.png|wsmall]]


*Deceiver Pokemon*
*The power of the Mega Stone makes its back jaws develop a mind of their own, they are vicious and won’t release anything they bite until it’s crushed into pieces. They growl and howl in a haunting way.*

**DexID**:: 0303M1
**Name**:: Mawile (Mega Form)
**Type**:: Steel / Fairy
**Abilities**:: [[SRD-Huge Power|Huge Power]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 51.8lbs / 23.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item     |
|:----------|:---------------|:-------|:---------|
| From      | [[SRD-Mawile]] | Mega   | Mawilite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mawile (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
