---
Ability1: Shadow Shield
Ability2: ''
BookSprite: SRD-lunala-BookSprite.png
BoxSprite: SRD-lunala-BoxSprite.png
DexCategory: No Data
DexDescription: There are legends about a being that shined with the moon, on its
  forehead a third eye that connected to another dimension.
EventAbilities: ''
Evolutions:
- Evolves: From
  Game: Shield
  Kind: Level
  Pokemon: '[[SRD-Cosmoem]]'
GenderType: N
Height:
  Feet: 13.1
  Meters: 4.0
HiddenAbility: ''
HomeSprite: SRD-lunala-HomeSprite.png
Image: lunala.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moongeist Beam|Moongeist Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teleport|Teleport]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Shade|Night Shade]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Ball|Shadow Ball]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonlight|Moonlight]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Daze|Night Daze]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Coat|Magic Coat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonblast|Moonblast]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spite|Spite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reflect|Reflect]]'
Number: 792
ShuffleToken: SRD-lunala-ShuffleToken.png
Type1: Psychic
Type2: Ghost
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lunala-BookSprite.png|wsmall]]
> ![[SRD-lunala-HomeSprite.png]]
> ![[SRD-lunala-BoxSprite.png|htiny]]
> ![[SRD-lunala-ShuffleToken.png|wsmall]]


*No Data*
*There are legends about a being that shined with the moon, on its forehead a third eye that connected to another dimension.*

**DexID**:: 0792
**Name**:: Lunala
**Type**:: Psychic / Ghost
**Abilities**:: [[SRD-Shadow Shield|Shadow Shield]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 13'1" / 4.0m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon         | Kind   | Game   |
|:----------|:----------------|:-------|:-------|
| From      | [[SRD-Cosmoem]] | Level  | Shield |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lunala.md"
flatten moves as T
where file.path = this.file.path
```
