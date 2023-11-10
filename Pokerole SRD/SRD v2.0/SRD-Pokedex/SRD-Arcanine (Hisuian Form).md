---
Ability1: Intimidate
Ability2: Justified
BookSprite: SRD-arcanine-hisuian-form-BookSprite.png
BoxSprite: SRD-arcanine-hisuian-form-BoxSprite.png
DexCategory: Legendary Pokemon
DexDescription: In the ancient land of Hisui there were myths of a might beast made
  of fire and stone. It is believed to have been an Arcanine, but today's specimens
  barly resemble the mighty creatures in the old scrolls.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Growlithe (Hisuian Form)]]'
GenderType: ''
Height:
  Feet: 6.3
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-arcanine-hisuian-form-HomeSprite.png
Image: arcanine-hisuian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Roar|Roar]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Accelerock|Accelerock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Ace
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Ace
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Ace
  - '[[SRD-Work Up|Work Up]]'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Raging Fury|Raging Fury]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Scorching Sands|Scorching Sands]]'
- - Pro
  - '[[SRD-Meteor Beam|Meteor Beam]]'
- - Pro
  - '[[SRD-Wild Charge|Wild Charge]]'
Number: 59
ShuffleToken: SRD-arcanine-hisuian-form-ShuffleToken.png
Type1: Fire
Type2: Rock
Weight:
  Kilograms: 155
  Pounds: 340
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arcanine-hisuian-form-BookSprite.png|wsmall]]
> ![[SRD-arcanine-hisuian-form-HomeSprite.png]]
> ![[SRD-arcanine-hisuian-form-BoxSprite.png|htiny]]
> ![[SRD-arcanine-hisuian-form-ShuffleToken.png|wsmall]]


*Legendary Pokemon*
*In the ancient land of Hisui there were myths of a might beast made of fire and stone. It is believed to have been an Arcanine, but today's specimens barly resemble the mighty creatures in the old scrolls.*

**DexID**:: 0059H
**Name**:: Arcanine (Hisuian Form)
**Type**:: Fire / Rock
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Justified|Justified]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'3" / 1.9m
**Weight**: 340lbs / 155kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                          | Kind   | Item       |
|:----------|:---------------------------------|:-------|:-----------|
| From      | [[SRD-Growlithe (Hisuian Form)]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arcanine (Hisuian Form).md"
flatten moves as T
where file.path = this.file.path
```
