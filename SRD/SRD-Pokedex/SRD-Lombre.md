---
Ability1: Swift Swim
Ability2: Rain Dish
BookSprite: SRD-lombre-BookSprite.png
BoxSprite: SRD-lombre-BoxSprite.png
DexCategory: Jolly Pokemon
DexDescription: This nocturnal Pokemon has a mischievous and impish personality. While
  playing pranks on people, Lombres are commonly mistaken for human children. It enjoys
  to startle unaware swimmers.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Lotad]]'
  Speed: Medium
- Evolves: To
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Ludicolo]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Own Tempo
HomeSprite: SRD-lombre-HomeSprite.png
Image: lombre.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Nature Power|Nature Power]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Water Sport|Water Sport]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Knock Off|Knock Off]]'
- - Ace
  - '[[SRD-Uproar|Uproar]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Number: 271
ShuffleToken: SRD-lombre-ShuffleToken.png
Type1: Water
Type2: Grass
Weight:
  Kilograms: 32.5
  Pounds: 71.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lombre-BookSprite.png|wsmall]]
> ![[SRD-lombre-HomeSprite.png]]
> ![[SRD-lombre-BoxSprite.png|htiny]]
> ![[SRD-lombre-ShuffleToken.png|wsmall]]


*Jolly Pokemon*
*This nocturnal Pokemon has a mischievous and impish personality. While playing pranks on people, Lombres are commonly mistaken for human children. It enjoys to startle unaware swimmers.*

**DexID**:: 0271
**Name**:: Lombre
**Type**:: Water / Grass
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Rain Dish|Rain Dish]] ([[SRD-Own Tempo|Own Tempo]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 71.7lbs / 32.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   | Item        |
|:----------|:-----------------|:-------|:--------|:------------|
| From      | [[SRD-Lotad]]    | Level  | Medium  |             |
| To        | [[SRD-Ludicolo]] | Stone  |         | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lombre.md"
flatten moves as T
where file.path = this.file.path
```
