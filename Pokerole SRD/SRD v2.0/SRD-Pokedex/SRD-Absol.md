---
Ability1: Pressure
Ability2: Super Luck
BookSprite: SRD-absol-BookSprite.png
BoxSprite: SRD-absol-BoxSprite.png
DexCategory: Disaster Pokemon
DexDescription: 'It is said that this Pokemon can live for 100 years. It has a bad
  reputation: Whenever one is seen, a disaster is soon to follow - earthquakes, forest
  fires and tidal waves. Absols lead a lonely life.'
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Absolite
  Kind: Mega
  Pokemon: '[[SRD-Absol (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Justified
HomeSprite: SRD-absol-HomeSprite.png
Image: absol.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Detect|Detect]]'
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Razor Wind|Razor Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hex|Hex]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
Number: 359
ShuffleToken: SRD-absol-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 47.0
  Pounds: 103.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-absol-BookSprite.png|wsmall]]
> ![[SRD-absol-HomeSprite.png]]
> ![[SRD-absol-BoxSprite.png|htiny]]
> ![[SRD-absol-ShuffleToken.png|wsmall]]


*Disaster Pokemon*
*It is said that this Pokemon can live for 100 years. It has a bad reputation: Whenever one is seen, a disaster is soon to follow - earthquakes, forest fires and tidal waves. Absols lead a lonely life.*

**DexID**:: 0359
**Name**:: Absol
**Type**:: Dark
**Abilities**:: [[SRD-Pressure|Pressure]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Justified|Justified]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 103.6lbs / 47.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                   | Kind   | Item     |
|:----------|:--------------------------|:-------|:---------|
| To        | [[SRD-Absol (Mega Form)]] | Mega   | Absolite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Absol.md"
flatten moves as T
where file.path = this.file.path
```
