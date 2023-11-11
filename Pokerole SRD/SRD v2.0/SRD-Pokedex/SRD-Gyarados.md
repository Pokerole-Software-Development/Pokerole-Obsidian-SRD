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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rage|Dragon Rage]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Fang|Ice Fang]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thrash|Thrash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Dance|Dragon Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bounce|Bounce]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gyarados.md"
flatten moves as T
where file.path = this.file.path
```
