---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-registeel-BookSprite.png
BoxSprite: SRD-registeel-BoxSprite.png
DexCategory: No Data
DexDescription: His body was indestructible. A flexible metal out of this world that
  can shrink, expand, made solid or liquid at the speed of thought. Could the myths
  be true?
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Light Metal
HomeSprite: SRD-registeel-HomeSprite.png
Image: registeel.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Amnesia|Amnesia]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lock-On|Lock-On]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Explosion|Explosion]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mimic|Mimic]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Block|Block]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
Number: 379
ShuffleToken: SRD-registeel-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 205.0
  Pounds: 451.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-registeel-BookSprite.png|wsmall]]
> ![[SRD-registeel-HomeSprite.png]]
> ![[SRD-registeel-BoxSprite.png|htiny]]
> ![[SRD-registeel-ShuffleToken.png|wsmall]]


*No Data*
*His body was indestructible. A flexible metal out of this world that can shrink, expand, made solid or liquid at the speed of thought. Could the myths be true?*

**DexID**:: 0379
**Name**:: Registeel
**Type**:: Steel
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Light Metal|Light Metal]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::8)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::8)/(MaxInsight::8)     |

**Height**: 6'2" / 1.9m
**Weight**: 451.9lbs / 205.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Registeel.md"
flatten moves as T
where file.path = this.file.path
```
