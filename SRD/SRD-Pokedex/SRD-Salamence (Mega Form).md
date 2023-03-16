---
Ability1: Aerilate
Ability2: ''
BookSprite: SRD-salamence-mega-form-BookSprite.png
BoxSprite: SRD-salamence-mega-form-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: "The power of the Mega Stone gives it the nickname \u201CThe blood-soaked\
  \ Crescent\u201D. It is violent and very unpredictable, even turning on their own\
  \ trainer. Many believe it is because its bent wings cause it pain."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Salamencite
  Kind: Mega
  Pokemon: '[[SRD-Salamence]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-salamence-mega-form-HomeSprite.png
Image: salamence-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Fly|Fly]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 373
ShuffleToken: SRD-salamence-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Flying
Weight:
  Kilograms: 112.6
  Pounds: 248.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-salamence-mega-form-BookSprite.png|wsmall]]
> ![[SRD-salamence-mega-form-HomeSprite.png]]
> ![[SRD-salamence-mega-form-BoxSprite.png|htiny]]
> ![[SRD-salamence-mega-form-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*The power of the Mega Stone gives it the nickname “The blood-soaked Crescent”. It is violent and very unpredictable, even turning on their own trainer. Many believe it is because its bent wings cause it pain.*

**DexID**:: 0373M1
**Name**:: Salamence (Mega Form)
**Type**:: Dragon / Flying
**Abilities**:: [[SRD-Aerilate|Aerilate]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 248.2lbs / 112.6kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon           | Kind   | Item        |
|:----------|:------------------|:-------|:------------|
| From      | [[SRD-Salamence]] | Mega   | Salamencite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Salamence (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
