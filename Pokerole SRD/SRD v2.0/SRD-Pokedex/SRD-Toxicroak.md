---
Ability1: Anticipation
Ability2: Dry Skin
BookSprite: SRD-toxicroak-BookSprite.png
BoxSprite: SRD-toxicroak-BoxSprite.png
DexCategory: Toxic Mouth Pokemon
DexDescription: The toxin made in its poison sacs is pumped into the knuckle claws
  through tubes down its arms. Its toxins are so powerful that even a scratch from
  its knuckles could be fatal in a few hours.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Croagunk]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Poison Touch
HomeSprite: SRD-toxicroak-HomeSprite.png
Image: toxicroak.png
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
  - '[[SRD-Dual Chop|Dual Chop]]'
Number: 454
ShuffleToken: SRD-toxicroak-ShuffleToken.png
Type1: Poison
Type2: Fighting
Weight:
  Kilograms: 44.4
  Pounds: 97.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-toxicroak-BookSprite.png|wsmall]]
> ![[SRD-toxicroak-HomeSprite.png]]
> ![[SRD-toxicroak-BoxSprite.png|htiny]]
> ![[SRD-toxicroak-ShuffleToken.png|wsmall]]


*Toxic Mouth Pokemon*
*The toxin made in its poison sacs is pumped into the knuckle claws through tubes down its arms. Its toxins are so powerful that even a scratch from its knuckles could be fatal in a few hours.*

**DexID**:: 0454
**Name**:: Toxicroak
**Type**:: Poison / Fighting
**Abilities**:: [[SRD-Anticipation|Anticipation]] / [[SRD-Dry Skin|Dry Skin]] ([[SRD-Poison Touch|Poison Touch]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 97.9lbs / 44.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Croagunk]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Toxicroak.md"
flatten moves as T
where file.path = this.file.path
```
