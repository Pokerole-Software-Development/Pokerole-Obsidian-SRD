---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-decidueye-BookSprite.png
BoxSprite: SRD-decidueye-BoxSprite.png
DexCategory: Arrow Quill Pokemob
DexDescription: This Pokemon can shoot its own feathers as arrows in just a split
  of second. They are usually calm and collected but they are easily startled if taken
  by surprise. It is very rare as most of them are extinct.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dartrix]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Long Reach
HomeSprite: SRD-decidueye-HomeSprite.png
Image: decidueye.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leafage|Leafage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - Amateur
  - '[[SRD-Spirit Shackle|Spirit Shackle]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 724
ShuffleToken: SRD-decidueye-ShuffleToken.png
Type1: Grass
Type2: Ghost
Weight:
  Kilograms: 36.6
  Pounds: 80.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-decidueye-BookSprite.png|wsmall]]
> ![[SRD-decidueye-HomeSprite.png]]
> ![[SRD-decidueye-BoxSprite.png|htiny]]
> ![[SRD-decidueye-ShuffleToken.png|wsmall]]


*Arrow Quill Pokemob*
*This Pokemon can shoot its own feathers as arrows in just a split of second. They are usually calm and collected but they are easily startled if taken by surprise. It is very rare as most of them are extinct.*

**DexID**:: 0724
**Name**:: Decidueye
**Type**:: Grass / Ghost
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Long Reach|Long Reach]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 80.7lbs / 36.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Dartrix]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Decidueye.md"
flatten moves as T
where file.path = this.file.path
```
