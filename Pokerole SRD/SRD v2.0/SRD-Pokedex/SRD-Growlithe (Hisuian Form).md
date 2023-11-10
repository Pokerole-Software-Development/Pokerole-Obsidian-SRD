---
Ability1: Intimidate
Ability2: Justified
BookSprite: SRD-growlithe-hisuian-form-BookSprite.png
BoxSprite: SRD-growlithe-hisuian-form-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: There are records of it's existence on old Hisuian territories, but
  all that remains today are old stone statues of fierce and vigilant pokemon. It
  was said to live in pairs, deep inside the mountains and away from humans.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Arcanine (Hisuian Form)]]'
GenderType: ''
Height:
  Feet: 2.7
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-growlithe-hisuian-form-HomeSprite.png
Image: growlithe-hisuian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Roar|Roar]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Raging Fury|Raging Fury]]'
- - Ace
  - '[[SRD-Drunch|Drunch]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Pro
  - '[[SRD-Dig|Dig]]'
- - Pro
  - '[[SRD-Rock Smash|Rock Smash]]'
Number: 58
ShuffleToken: SRD-growlithe-hisuian-form-ShuffleToken.png
Type1: Fire
Type2: Rock
Weight:
  Kilograms: 25
  Pounds: 50
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-growlithe-hisuian-form-BookSprite.png|wsmall]]
> ![[SRD-growlithe-hisuian-form-HomeSprite.png]]
> ![[SRD-growlithe-hisuian-form-BoxSprite.png|htiny]]
> ![[SRD-growlithe-hisuian-form-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*There are records of it's existence on old Hisuian territories, but all that remains today are old stone statues of fierce and vigilant pokemon. It was said to live in pairs, deep inside the mountains and away from humans.*

**DexID**:: 0058H
**Name**:: Growlithe (Hisuian Form)
**Type**:: Fire / Rock
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Justified|Justified]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'7" / 0.8m
**Weight**: 50lbs / 25kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   | Item       |
|:----------|:--------------------------------|:-------|:-----------|
| To        | [[SRD-Arcanine (Hisuian Form)]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Growlithe (Hisuian Form).md"
flatten moves as T
where file.path = this.file.path
```
