---
Ability1: Plus
Ability2: Minus
BookSprite: SRD-klinklang-BookSprite.png
BoxSprite: SRD-klinklang-BoxSprite.png
DexCategory: Gear Pokemon
DexDescription: The gear with the red core rotates at high speed for a quick energy
  charge. The mini gears shoot rays through the spikes around it. This inorganic Pokemon
  will trap and crush foes between its gears.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Klang]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Clear Body
HomeSprite: SRD-klinklang-HomeSprite.png
Image: klinklang.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Gear Grind|Gear Grind]]'
- - Amateur
  - '[[SRD-Gear Up|Gear Up]]'
- - Amateur
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shift Gear|Shift Gear]]'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
Number: 601
ShuffleToken: SRD-klinklang-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 81.0
  Pounds: 178.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-klinklang-BookSprite.png|wsmall]]
> ![[SRD-klinklang-HomeSprite.png]]
> ![[SRD-klinklang-BoxSprite.png|htiny]]
> ![[SRD-klinklang-ShuffleToken.png|wsmall]]


*Gear Pokemon*
*The gear with the red core rotates at high speed for a quick energy charge. The mini gears shoot rays through the spikes around it. This inorganic Pokemon will trap and crush foes between its gears.*

**DexID**:: 0601
**Name**:: Klinklang
**Type**:: Steel
**Abilities**:: [[SRD-Plus|Plus]] / [[SRD-Minus|Minus]] ([[SRD-Clear Body|Clear Body]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 178.6lbs / 81.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Klang]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Klinklang.md"
flatten moves as T
where file.path = this.file.path
```
