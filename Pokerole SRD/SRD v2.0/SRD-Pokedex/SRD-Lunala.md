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
  - '[[SRD-Moongeist Beam|Moongeist Beam]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Teleport|Teleport]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Night Shade|Night Shade]]'
- - Master
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Master
  - '[[SRD-Moonlight|Moonlight]]'
- - Master
  - '[[SRD-Night Daze|Night Daze]]'
- - Master
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Spite|Spite]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
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
