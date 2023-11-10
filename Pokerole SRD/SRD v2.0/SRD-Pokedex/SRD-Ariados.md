---
Ability1: Swarm
Ability2: Insomnia
BookSprite: SRD-ariados-BookSprite.png
BoxSprite: SRD-ariados-BoxSprite.png
DexCategory: Long Leg Pokemon
DexDescription: This Pokemon is silent and stealthy. It comes out at night. After
  attaching some silk to its prey, it sets it free. Later, it tracks the silk back
  to the prey and its friends. It can form big colonies in caves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Spinarak]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Sniper
HomeSprite: SRD-ariados-HomeSprite.png
Image: ariados.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Constrict|Constrict]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Amateur
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Spider Web|Spider Web]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Ace
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Ace
  - '[[SRD-Toxic Thread|Toxic Thread]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
Number: 168
ShuffleToken: SRD-ariados-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 33.5
  Pounds: 73.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ariados-BookSprite.png|wsmall]]
> ![[SRD-ariados-HomeSprite.png]]
> ![[SRD-ariados-BoxSprite.png|htiny]]
> ![[SRD-ariados-ShuffleToken.png|wsmall]]


*Long Leg Pokemon*
*This Pokemon is silent and stealthy. It comes out at night. After attaching some silk to its prey, it sets it free. Later, it tracks the silk back to the prey and its friends. It can form big colonies in caves.*

**DexID**:: 0168
**Name**:: Ariados
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Insomnia|Insomnia]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 73.9lbs / 33.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Spinarak]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ariados.md"
flatten moves as T
where file.path = this.file.path
```
