---
Ability1: Own Tempo
Ability2: Stamina
BookSprite: SRD-mudsdale-BookSprite.png
BoxSprite: SRD-mudsdale-BoxSprite.png
DexCategory: Draft Horse Pokemon
DexDescription: Hard tempered and resilient. The hooves of this Pokemon stomp through
  concrete, while it is not very fast it can keep a steady pace for days, even when
  dragging weight.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mudbray]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: Inner Focus
HomeSprite: SRD-mudsdale-HomeSprite.png
Image: mudsdale.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rototiller|Rototiller]]'
- - Beginner
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
Number: 750
ShuffleToken: SRD-mudsdale-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 920.0
  Pounds: 2028.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mudsdale-BookSprite.png|wsmall]]
> ![[SRD-mudsdale-HomeSprite.png]]
> ![[SRD-mudsdale-BoxSprite.png|htiny]]
> ![[SRD-mudsdale-ShuffleToken.png|wsmall]]


*Draft Horse Pokemon*
*Hard tempered and resilient. The hooves of this Pokemon stomp through concrete, while it is not very fast it can keep a steady pace for days, even when dragging weight.*

**DexID**:: 0750
**Name**:: Mudsdale
**Type**:: Ground
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Stamina|Stamina]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 8'2" / 2.5m
**Weight**: 2028.3lbs / 920.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Mudbray]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mudsdale.md"
flatten moves as T
where file.path = this.file.path
```
