---
Ability1: Swarm
Ability2: Chlorophyll
BookSprite: SRD-leavanny-BookSprite.png
BoxSprite: SRD-leavanny-BoxSprite.png
DexCategory: Nurturing Pokemon
DexDescription: It is a gentle and caring Pokemon. Mostly known for making clothes
  out of leaves and silk for any small pokemon it finds. It warms and protects its
  eggs making nests of fermenting leaves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Swadloon]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Overcoat
HomeSprite: SRD-leavanny-HomeSprite.png
Image: leavanny.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Beginner
  - '[[SRD-False Swipe|False Swipe]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
Number: 542
ShuffleToken: SRD-leavanny-ShuffleToken.png
Type1: Bug
Type2: Grass
Weight:
  Kilograms: 20.5
  Pounds: 45.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-leavanny-BookSprite.png|wsmall]]
> ![[SRD-leavanny-HomeSprite.png]]
> ![[SRD-leavanny-BoxSprite.png|htiny]]
> ![[SRD-leavanny-ShuffleToken.png|wsmall]]


*Nurturing Pokemon*
*It is a gentle and caring Pokemon. Mostly known for making clothes out of leaves and silk for any small pokemon it finds. It warms and protects its eggs making nests of fermenting leaves.*

**DexID**:: 0542
**Name**:: Leavanny
**Type**:: Bug / Grass
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 45.2lbs / 20.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Stat      |   Value |
|:----------|:-----------------|:-------|:----------|--------:|
| From      | [[SRD-Swadloon]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Leavanny.md"
flatten moves as T
where file.path = this.file.path
```
