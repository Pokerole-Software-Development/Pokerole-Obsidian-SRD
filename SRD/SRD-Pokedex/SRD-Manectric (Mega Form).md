---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-manectric-mega-form-BookSprite.png
BoxSprite: SRD-manectric-mega-form-BoxSprite.png
DexCategory: Discharge Pokemon
DexDescription: The power of the Mega Stone gives it an insurmountable amount of electricity
  that gives it an explosive velocity, but it is too much for it to bear. Its mane
  grows uncomfortably large, making it moody.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Manectite
  Kind: Mega
  Pokemon: '[[SRD-Manectric]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-manectric-mega-form-HomeSprite.png
Image: manectric-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
Number: 310
ShuffleToken: SRD-manectric-mega-form-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 44.0
  Pounds: 97.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-manectric-mega-form-BookSprite.png|wsmall]]
> ![[SRD-manectric-mega-form-HomeSprite.png]]
> ![[SRD-manectric-mega-form-BoxSprite.png|htiny]]
> ![[SRD-manectric-mega-form-ShuffleToken.png|wsmall]]


*Discharge Pokemon*
*The power of the Mega Stone gives it an insurmountable amount of electricity that gives it an explosive velocity, but it is too much for it to bear. Its mane grows uncomfortably large, making it moody.*

**DexID**:: 0310M1
**Name**:: Manectric (Mega Form)
**Type**:: Electric
**Abilities**:: [[SRD-Intimidate|Intimidate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 97.0lbs / 44.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Item      |
|:----------|:------------------|:-------|:----------|
| From      | [[SRD-Manectric]] | Mega   | Manectite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Manectric (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
