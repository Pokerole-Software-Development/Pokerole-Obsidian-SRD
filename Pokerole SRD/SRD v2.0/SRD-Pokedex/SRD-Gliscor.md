---
Ability1: Hyper Cutter
Ability2: Sand Veil
BookSprite: SRD-gliscor-BookSprite.png
BoxSprite: SRD-gliscor-BoxSprite.png
DexCategory: Fang Scorp Pokemon
DexDescription: Its flight is soundless. It uses its lengthy tail to carry off its
  prey, then uses its long fangs to do the rest. It is more playful than aggressive
  but it is dangerous if you get close to the enormous claws.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Razor Fang
  Kind: Level
  Pokemon: '[[SRD-Gligar]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Poison Heal
HomeSprite: SRD-gliscor-HomeSprite.png
Image: gliscor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Knock Off|Knock Off]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Pro
  - '[[SRD-Cross Poison|Cross Poison]]'
Number: 472
ShuffleToken: SRD-gliscor-ShuffleToken.png
Type1: Ground
Type2: Flying
Weight:
  Kilograms: 42.5
  Pounds: 93.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gliscor-BookSprite.png|wsmall]]
> ![[SRD-gliscor-HomeSprite.png]]
> ![[SRD-gliscor-BoxSprite.png|htiny]]
> ![[SRD-gliscor-ShuffleToken.png|wsmall]]


*Fang Scorp Pokemon*
*Its flight is soundless. It uses its lengthy tail to carry off its prey, then uses its long fangs to do the rest. It is more playful than aggressive but it is dangerous if you get close to the enormous claws.*

**DexID**:: 0472
**Name**:: Gliscor
**Type**:: Ground / Flying
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Sand Veil|Sand Veil]] ([[SRD-Poison Heal|Poison Heal]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 93.7lbs / 42.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item       |
|:----------|:---------------|:-------|:-----------|
| From      | [[SRD-Gligar]] | Level  | Razor Fang |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gliscor.md"
flatten moves as T
where file.path = this.file.path
```
