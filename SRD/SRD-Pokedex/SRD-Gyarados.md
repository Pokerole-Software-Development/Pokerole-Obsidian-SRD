---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-gyarados-BookSprite.png
BoxSprite: SRD-gyarados-BoxSprite.png
DexCategory: Atrocious Pokemon
DexDescription: "It\u2019s rarely seen in the wild. This huge and vicious Pokemon\
  \ is known for the destruction it leaves in its wake. In ancient literature, there\
  \ is a record of a Gyarados that razed a village when violence flared."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Magikarp]]'
  Speed: Slow
- Evolves: To
  Item: Gyaradosite
  Kind: Mega
  Pokemon: '[[SRD-Gyarados (Mega Form)]]'
GenderType: ''
Height:
  Feet: 21.3
  Meters: 6.5
HiddenAbility: Moxie
HomeSprite: SRD-gyarados-HomeSprite.png
Image: gyarados.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - Beginner
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Number: 130
ShuffleToken: SRD-gyarados-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 235.0
  Pounds: 518.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gyarados-BookSprite.png|wsmall]]
> ![[SRD-gyarados-HomeSprite.png]]
> ![[SRD-gyarados-BoxSprite.png|htiny]]
> ![[SRD-gyarados-ShuffleToken.png|wsmall]]


*Atrocious Pokemon*
*It’s rarely seen in the wild. This huge and vicious Pokemon is known for the destruction it leaves in its wake. In ancient literature, there is a record of a Gyarados that razed a village when violence flared.*

**DexID**:: 0130
**Name**:: Gyarados
**Type**:: Water / Flying
**Abilities**:: [[SRD-Intimidate|Intimidate]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 21'3" / 6.5m
**Weight**: 518.1lbs / 235.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Magikarp]]             | Level  | Slow    |             |
| To        | [[SRD-Gyarados (Mega Form)]] | Mega   |         | Gyaradosite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gyarados.md"
flatten moves as T
where file.path = this.file.path
```
