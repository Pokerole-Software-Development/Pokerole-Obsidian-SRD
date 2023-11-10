---
Ability1: Battle Armor
Ability2: ''
BookSprite: SRD-type-null-BookSprite.png
BoxSprite: SRD-type-null-BoxSprite.png
DexCategory: Synthetic Pokemon
DexDescription: A synthetic Pokemon made by the Aether Foundation. Currently only
  three specimens exist in cryogenic stasis, but they are deemed too dangerous even
  with a limiter helmet on. They must never be reanimated.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-type-null-HomeSprite.png
Image: type-null.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Razor Wind|Razor Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Pro
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[SRD-Heal Block|Heal Block]]'
Number: 772
ShuffleToken: SRD-type-null-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 120.5
  Pounds: 265.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-type-null-BookSprite.png|wsmall]]
> ![[SRD-type-null-HomeSprite.png]]
> ![[SRD-type-null-BoxSprite.png|htiny]]
> ![[SRD-type-null-ShuffleToken.png|wsmall]]


*Synthetic Pokemon*
*A synthetic Pokemon made by the Aether Foundation. Currently only three specimens exist in cryogenic stasis, but they are deemed too dangerous even with a limiter helmet on. They must never be reanimated.*

**DexID**:: 0772
**Name**:: Type Null
**Type**:: Normal
**Abilities**:: [[SRD-Battle Armor|Battle Armor]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'2" / 1.9m
**Weight**: 265.7lbs / 120.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Type Null.md"
flatten moves as T
where file.path = this.file.path
```
