---
Ability1: Own Tempo
Ability2: Technician
BookSprite: SRD-smeargle-BookSprite.png
BoxSprite: SRD-smeargle-BoxSprite.png
DexCategory: Painter Pokemon
DexDescription: A special ink oozes from its tail to mark its territory. They are
  skilled artists, known for painting action scenes from great battles. If they study
  their painting for a long time, they learn those moves.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Moody
HomeSprite: SRD-smeargle-HomeSprite.png
Image: smeargle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sketch|Sketch]]'
Number: 235
ShuffleToken: SRD-smeargle-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 58.0
  Pounds: 127.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-smeargle-BookSprite.png|wsmall]]
> ![[SRD-smeargle-HomeSprite.png]]
> ![[SRD-smeargle-BoxSprite.png|htiny]]
> ![[SRD-smeargle-ShuffleToken.png|wsmall]]


*Painter Pokemon*
*A special ink oozes from its tail to mark its territory. They are skilled artists, known for painting action scenes from great battles. If they study their painting for a long time, they learn those moves.*

**DexID**:: 0235
**Name**:: Smeargle
**Type**:: Normal
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Technician|Technician]] ([[SRD-Moody|Moody]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 127.9lbs / 58.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Smeargle.md"
flatten moves as T
where file.path = this.file.path
```
