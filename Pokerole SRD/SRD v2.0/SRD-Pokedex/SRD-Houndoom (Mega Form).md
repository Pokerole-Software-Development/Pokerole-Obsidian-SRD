---
Ability1: Solar Power
Ability2: ''
BookSprite: SRD-houndoom-mega-form-BookSprite.png
BoxSprite: SRD-houndoom-mega-form-BoxSprite.png
DexCategory: Dark Pokemon
DexDescription: With the power of the Mega Stone its whole body radiates tremendous
  heat, so much that its claws are searing hot and turn red as a result, for this
  reason it can be painful for it to walk or run.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Houndoominite
  Kind: Mega
  Pokemon: '[[SRD-Houndoom]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-houndoom-mega-form-HomeSprite.png
Image: houndoom-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ember|Ember]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Howl|Howl]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roar|Roar]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Inferno|Inferno]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spite|Spite]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
Number: 229
ShuffleToken: SRD-houndoom-mega-form-ShuffleToken.png
Type1: Dark
Type2: Fire
Weight:
  Kilograms: 49.5
  Pounds: 109.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-houndoom-mega-form-BookSprite.png|wsmall]]
> ![[SRD-houndoom-mega-form-HomeSprite.png]]
> ![[SRD-houndoom-mega-form-BoxSprite.png|htiny]]
> ![[SRD-houndoom-mega-form-ShuffleToken.png|wsmall]]


*Dark Pokemon*
*With the power of the Mega Stone its whole body radiates tremendous heat, so much that its claws are searing hot and turn red as a result, for this reason it can be painful for it to walk or run.*

**DexID**:: 0229M1
**Name**:: Houndoom (Mega Form)
**Type**:: Dark / Fire
**Abilities**:: [[SRD-Solar Power|Solar Power]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 109.1lbs / 49.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item          |
|:----------|:-----------------|:-------|:--------------|
| From      | [[SRD-Houndoom]] | Mega   | Houndoominite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Houndoom (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
