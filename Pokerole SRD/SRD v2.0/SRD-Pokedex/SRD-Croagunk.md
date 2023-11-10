---
Ability1: Anticipation
Ability2: Dry Skin
BookSprite: SRD-croagunk-BookSprite.png
BoxSprite: SRD-croagunk-BoxSprite.png
DexCategory: Toxic Mouth Pokemon
DexDescription: It is commonly found in marshes. It inflates the sacks on its cheeks
  and makes croaking sounds. The fluid squeezed from its fingers is poisonous, but
  it is a common ingredient in medicinal ointments.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Toxicroak]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Poison Touch
HomeSprite: SRD-croagunk-HomeSprite.png
Image: croagunk.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Flatter|Flatter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
Number: 453
ShuffleToken: SRD-croagunk-ShuffleToken.png
Type1: Poison
Type2: Fighting
Weight:
  Kilograms: 23.0
  Pounds: 50.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-croagunk-BookSprite.png|wsmall]]
> ![[SRD-croagunk-HomeSprite.png]]
> ![[SRD-croagunk-BoxSprite.png|htiny]]
> ![[SRD-croagunk-ShuffleToken.png|wsmall]]


*Toxic Mouth Pokemon*
*It is commonly found in marshes. It inflates the sacks on its cheeks and makes croaking sounds. The fluid squeezed from its fingers is poisonous, but it is a common ingredient in medicinal ointments.*

**DexID**:: 0453
**Name**:: Croagunk
**Type**:: Poison / Fighting
**Abilities**:: [[SRD-Anticipation|Anticipation]] / [[SRD-Dry Skin|Dry Skin]] ([[SRD-Poison Touch|Poison Touch]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 50.7lbs / 23.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Toxicroak]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Croagunk.md"
flatten moves as T
where file.path = this.file.path
```
