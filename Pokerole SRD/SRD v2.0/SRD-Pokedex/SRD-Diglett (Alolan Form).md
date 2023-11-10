---
Ability1: Sand Veil
Ability2: Tangling Hair
BookSprite: SRD-diglett-alolan-form-BookSprite.png
BoxSprite: SRD-diglett-alolan-form-BoxSprite.png
DexCategory: Mole Pokemon
DexDescription: This variant of Diglett is only found in the Alola region. The small
  hairs on its head are used perceive its surroundings while burrowed, do not cut
  them or Diglett will become very sick.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dugtrio (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Sand Force
HomeSprite: SRD-diglett-alolan-form-HomeSprite.png
Image: diglett-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Pro
  - '[[SRD-Thrash|Thrash]]'
Number: 50
ShuffleToken: SRD-diglett-alolan-form-ShuffleToken.png
Type1: Ground
Type2: Steel
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-diglett-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-diglett-alolan-form-HomeSprite.png]]
> ![[SRD-diglett-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-diglett-alolan-form-ShuffleToken.png|wsmall]]


*Mole Pokemon*
*This variant of Diglett is only found in the Alola region. The small hairs on its head are used perceive its surroundings while burrowed, do not cut them or Diglett will become very sick.*

**DexID**:: 0050A
**Name**:: Diglett (Alolan Form)
**Type**:: Ground / Steel
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] / [[SRD-Tangling Hair|Tangling Hair]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| To        | [[SRD-Dugtrio (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Diglett (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
