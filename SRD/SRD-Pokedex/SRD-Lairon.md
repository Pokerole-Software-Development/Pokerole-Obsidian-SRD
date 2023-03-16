---
Ability1: Sturdy
Ability2: Rock Head
BookSprite: SRD-lairon-BookSprite.png
BoxSprite: SRD-lairon-BoxSprite.png
DexCategory: Iron Armor Pokemon
DexDescription: Their armors gets stronger by eating iron ores and drinking mineral
  spring water, usually nesting close to ponds. Lairons often attack human miners.
  They are territorial creatures, incredibly stubborn and resilient.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Aron]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Aggron]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Heavy Metal
HomeSprite: SRD-lairon-HomeSprite.png
Image: lairon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Autotomize|Autotomize]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
Number: 305
ShuffleToken: SRD-lairon-ShuffleToken.png
Type1: Steel
Type2: Rock
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lairon-BookSprite.png|wsmall]]
> ![[SRD-lairon-HomeSprite.png]]
> ![[SRD-lairon-BoxSprite.png|htiny]]
> ![[SRD-lairon-ShuffleToken.png|wsmall]]


*Iron Armor Pokemon*
*Their armors gets stronger by eating iron ores and drinking mineral spring water, usually nesting close to ponds. Lairons often attack human miners. They are territorial creatures, incredibly stubborn and resilient.*

**DexID**:: 0305
**Name**:: Lairon
**Type**:: Steel / Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Aron]]   | Level  | Medium  |
| To        | [[SRD-Aggron]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lairon.md"
flatten moves as T
where file.path = this.file.path
```
