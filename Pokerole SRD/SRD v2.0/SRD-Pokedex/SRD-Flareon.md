---
Ability1: Flash Fire
Ability2: ''
BookSprite: SRD-flareon-BookSprite.png
BoxSprite: SRD-flareon-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: A few have been seen in volcanic areas but just like its counterparts
  is more common to see it being the pet of wealthy people. Its flaming fur is most
  appreciated for its warm glow and silky touch.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Eevee]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Guts
HomeSprite: SRD-flareon-HomeSprite.png
Image: flareon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Detect|Detect]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
Number: 136
ShuffleToken: SRD-flareon-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-flareon-BookSprite.png|wsmall]]
> ![[SRD-flareon-HomeSprite.png]]
> ![[SRD-flareon-BoxSprite.png|htiny]]
> ![[SRD-flareon-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*A few have been seen in volcanic areas but just like its counterparts is more common to see it being the pet of wealthy people. Its flaming fur is most appreciated for its warm glow and silky touch.*

**DexID**:: 0136
**Name**:: Flareon
**Type**:: Fire
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] ([[SRD-Guts|Guts]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item       |
|:----------|:--------------|:-------|:-----------|
| From      | [[SRD-Eevee]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Flareon.md"
flatten moves as T
where file.path = this.file.path
```
