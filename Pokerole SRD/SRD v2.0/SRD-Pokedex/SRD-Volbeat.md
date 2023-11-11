---
Ability1: Illuminate
Ability2: Swarm
BookSprite: SRD-volbeat-BookSprite.png
BoxSprite: SRD-volbeat-BoxSprite.png
DexCategory: Firelfy Pokemon
DexDescription: The male of its species. Their tail shines bright during the night,
  drawing geometric shapes in the sky. Volbeats live in swarms around clean ponds.
  They are attracted to Illumise's sweet aroma.
EventAbilities: ''
Evolutions: []
GenderType: M
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Prankster
HomeSprite: SRD-volbeat-HomeSprite.png
Image: volbeat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash|Flash]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Team|Double Team]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Glow|Tail Glow]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dizzy Punch|Dizzy Punch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Silver Wind|Silver Wind]]'
Number: 313
ShuffleToken: SRD-volbeat-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 17.7
  Pounds: 39.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-volbeat-BookSprite.png|wsmall]]
> ![[SRD-volbeat-HomeSprite.png]]
> ![[SRD-volbeat-BoxSprite.png|htiny]]
> ![[SRD-volbeat-ShuffleToken.png|wsmall]]


*Firelfy Pokemon*
*The male of its species. Their tail shines bright during the night, drawing geometric shapes in the sky. Volbeats live in swarms around clean ponds. They are attracted to Illumise's sweet aroma.*

**DexID**:: 0313
**Name**:: Volbeat
**Type**:: Bug
**Abilities**:: [[SRD-Illuminate|Illuminate]] / [[SRD-Swarm|Swarm]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 39.0lbs / 17.7kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Volbeat.md"
flatten moves as T
where file.path = this.file.path
```
