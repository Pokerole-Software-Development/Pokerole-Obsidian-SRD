---
Ability1: Pickup
Ability2: ''
BookSprite: SRD-phanpy-BookSprite.png
BoxSprite: SRD-phanpy-BoxSprite.png
DexCategory: Long Nose Pokemon
DexDescription: They are affectionate and playful, but their snout is so strong that
  they may hurt others while playing. They dig pits at the edge of rivers and mark
  them so everyone knows that place is taken.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Donphan]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Sand Veil
HomeSprite: SRD-phanpy-HomeSprite.png
Image: phanpy.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Odor Sleuth|Odor Sleuth]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flail|Flail]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slam|Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mud Slap|Mud Slap]]'
Number: 231
ShuffleToken: SRD-phanpy-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 33.5
  Pounds: 73.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-phanpy-BookSprite.png|wsmall]]
> ![[SRD-phanpy-HomeSprite.png]]
> ![[SRD-phanpy-BoxSprite.png|htiny]]
> ![[SRD-phanpy-ShuffleToken.png|wsmall]]


*Long Nose Pokemon*
*They are affectionate and playful, but their snout is so strong that they may hurt others while playing. They dig pits at the edge of rivers and mark them so everyone knows that place is taken.*

**DexID**:: 0231
**Name**:: Phanpy
**Type**:: Ground
**Abilities**:: [[SRD-Pickup|Pickup]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 73.9lbs / 33.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Donphan]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Phanpy.md"
flatten moves as T
where file.path = this.file.path
```
