---
Ability1: Swift Swim
Ability2: Rain Dish
BookSprite: SRD-ludicolo-BookSprite.png
BoxSprite: SRD-ludicolo-BoxSprite.png
DexCategory: Carefree Pokemon
DexDescription: Ludicolo starts dancing at the sound of music. Pokemon and people
  will dance as well. They are said to appear when children sing. They love festive
  places and parties.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Lombre]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Own Tempo
HomeSprite: SRD-ludicolo-HomeSprite.png
Image: ludicolo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nature Power|Nature Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Entrainment|Entrainment]]'
Number: 272
ShuffleToken: SRD-ludicolo-ShuffleToken.png
Type1: Water
Type2: Grass
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ludicolo-BookSprite.png|wsmall]]
> ![[SRD-ludicolo-HomeSprite.png]]
> ![[SRD-ludicolo-BoxSprite.png|htiny]]
> ![[SRD-ludicolo-ShuffleToken.png|wsmall]]


*Carefree Pokemon*
*Ludicolo starts dancing at the sound of music. Pokemon and people will dance as well. They are said to appear when children sing. They love festive places and parties.*

**DexID**:: 0272
**Name**:: Ludicolo
**Type**:: Water / Grass
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Rain Dish|Rain Dish]] ([[SRD-Own Tempo|Own Tempo]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Item        |
|:----------|:---------------|:-------|:------------|
| From      | [[SRD-Lombre]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ludicolo.md"
flatten moves as T
where file.path = this.file.path
```
