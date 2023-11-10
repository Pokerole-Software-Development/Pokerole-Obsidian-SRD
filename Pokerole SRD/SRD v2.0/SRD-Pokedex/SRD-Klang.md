---
Ability1: Plus
Ability2: Minus
BookSprite: SRD-klang-BookSprite.png
BoxSprite: SRD-klang-BoxSprite.png
DexCategory: Gear Pokemon
DexDescription: Minigear and big gear comprise its body. If the minigear is detached
  it will turn off both gears. It communicates with others by rotating. When its angry
  or afraid, it rotates faster.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Klink]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Klinklang]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Clear Body
HomeSprite: SRD-klang-HomeSprite.png
Image: klang.png
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
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
Number: 600
ShuffleToken: SRD-klang-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 51.0
  Pounds: 112.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-klang-BookSprite.png|wsmall]]
> ![[SRD-klang-HomeSprite.png]]
> ![[SRD-klang-BoxSprite.png|htiny]]
> ![[SRD-klang-ShuffleToken.png|wsmall]]


*Gear Pokemon*
*Minigear and big gear comprise its body. If the minigear is detached it will turn off both gears. It communicates with others by rotating. When its angry or afraid, it rotates faster.*

**DexID**:: 0600
**Name**:: Klang
**Type**:: Steel
**Abilities**:: [[SRD-Plus|Plus]] / [[SRD-Minus|Minus]] ([[SRD-Clear Body|Clear Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 112.4lbs / 51.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Klink]]     | Level  | Medium  |
| To        | [[SRD-Klinklang]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Klang.md"
flatten moves as T
where file.path = this.file.path
```
