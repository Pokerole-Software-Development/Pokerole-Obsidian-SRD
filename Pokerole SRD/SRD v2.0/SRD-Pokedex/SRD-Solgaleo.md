---
Ability1: Full Metal Body
Ability2: ''
BookSprite: SRD-solgaleo-BookSprite.png
BoxSprite: SRD-solgaleo-BoxSprite.png
DexCategory: No Data
DexDescription: There are legends about a being that radiated with the sun, on its
  forehead a third eye that connected to another dimension.
EventAbilities: ''
Evolutions:
- Evolves: From
  Game: Sword
  Kind: Level
  Pokemon: '[[SRD-Cosmoem]]'
GenderType: N
Height:
  Feet: 11.2
  Meters: 3.4
HiddenAbility: ''
HomeSprite: SRD-solgaleo-HomeSprite.png
Image: solgaleo.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunsteel Strike|Sunsteel Strike]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teleport|Teleport]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Morning Sun|Morning Sun]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flare Blitz|Flare Blitz]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dazzling Gleam|Dazzling Gleam]]'
Number: 791
ShuffleToken: SRD-solgaleo-ShuffleToken.png
Type1: Psychic
Type2: Steel
Weight:
  Kilograms: 230.0
  Pounds: 507.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-solgaleo-BookSprite.png|wsmall]]
> ![[SRD-solgaleo-HomeSprite.png]]
> ![[SRD-solgaleo-BoxSprite.png|htiny]]
> ![[SRD-solgaleo-ShuffleToken.png|wsmall]]


*No Data*
*There are legends about a being that radiated with the sun, on its forehead a third eye that connected to another dimension.*

**DexID**:: 0791
**Name**:: Solgaleo
**Type**:: Psychic / Steel
**Abilities**:: [[SRD-Full Metal Body|Full Metal Body]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 11'2" / 3.4m
**Weight**: 507.1lbs / 230.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon         | Kind   | Game   |
|:----------|:----------------|:-------|:-------|
| From      | [[SRD-Cosmoem]] | Level  | Sword  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Solgaleo.md"
flatten moves as T
where file.path = this.file.path
```
