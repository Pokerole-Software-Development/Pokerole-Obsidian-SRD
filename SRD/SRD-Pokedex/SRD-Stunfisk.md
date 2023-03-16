---
Ability1: Static
Ability2: Limber
BookSprite: SRD-stunfisk-BookSprite.png
BoxSprite: SRD-stunfisk-BoxSprite.png
DexCategory: Trap Pokemon
DexDescription: It conceals itself in the mud of the seashore, then it waits. When
  prey touch it, it delivers a jolt of electricity. Its skin is very hard and it can
  position itself to keep unhurt even if stepped on by a heavy Pokemon.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sand Veil
HomeSprite: SRD-stunfisk-HomeSprite.png
Image: stunfisk.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Revenge|Revenge]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
Number: 618
ShuffleToken: SRD-stunfisk-ShuffleToken.png
Type1: Ground
Type2: Electric
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stunfisk-BookSprite.png|wsmall]]
> ![[SRD-stunfisk-HomeSprite.png]]
> ![[SRD-stunfisk-BoxSprite.png|htiny]]
> ![[SRD-stunfisk-ShuffleToken.png|wsmall]]


*Trap Pokemon*
*It conceals itself in the mud of the seashore, then it waits. When prey touch it, it delivers a jolt of electricity. Its skin is very hard and it can position itself to keep unhurt even if stepped on by a heavy Pokemon.*

**DexID**:: 0618
**Name**:: Stunfisk
**Type**:: Ground / Electric
**Abilities**:: [[SRD-Static|Static]] / [[SRD-Limber|Limber]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'3" / 0.7m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stunfisk.md"
flatten moves as T
where file.path = this.file.path
```
