---
Ability1: Swarm
Ability2: Technician
BookSprite: SRD-scyther-BookSprite.png
BoxSprite: SRD-scyther-BoxSprite.png
DexCategory: Mantis Pokemon
DexDescription: "It\u2019s pretty rare but a few swarms have been seen in the grasslands.\
  \ It tears and shreds prey with its wickedly sharp scythes and very rarely spreads\
  \ its wings to fly. This pokemon is stealthy and aggressive."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Metal Coat
  Kind: Trade
  Pokemon: '[[SRD-Scizor]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Steadfast
HomeSprite: SRD-scyther-HomeSprite.png
Image: scyther.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-False Swipe|False Swipe]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Feint|Feint]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
Number: 123
ShuffleToken: SRD-scyther-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 56.0
  Pounds: 123.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scyther-BookSprite.png|wsmall]]
> ![[SRD-scyther-HomeSprite.png]]
> ![[SRD-scyther-BoxSprite.png|htiny]]
> ![[SRD-scyther-ShuffleToken.png|wsmall]]


*Mantis Pokemon*
*It’s pretty rare but a few swarms have been seen in the grasslands. It tears and shreds prey with its wickedly sharp scythes and very rarely spreads its wings to fly. This pokemon is stealthy and aggressive.*

**DexID**:: 0123
**Name**:: Scyther
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Technician|Technician]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 123.5lbs / 56.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Item       |
|:----------|:---------------|:-------|:-----------|
| To        | [[SRD-Scizor]] | Trade  | Metal Coat |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Scyther.md"
flatten moves as T
where file.path = this.file.path
```
