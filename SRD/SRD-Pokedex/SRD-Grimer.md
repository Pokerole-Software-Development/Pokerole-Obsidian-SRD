---
Ability1: Stench
Ability2: Sticky Hold
BookSprite: SRD-grimer-BookSprite.png
BoxSprite: SRD-grimer-BoxSprite.png
DexCategory: Sludge Pokemon
DexDescription: It was born from polluted sludge in the sea. Grimer's favorite food
  is anything filthy like waste water pumped out from factories. Grime and sludge
  stick to their body making them grow larger over time.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Muk]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Poison Touch
HomeSprite: SRD-grimer-HomeSprite.png
Image: grimer.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Ace
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
Number: 88
ShuffleToken: SRD-grimer-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grimer-BookSprite.png|wsmall]]
> ![[SRD-grimer-HomeSprite.png]]
> ![[SRD-grimer-BoxSprite.png|htiny]]
> ![[SRD-grimer-ShuffleToken.png|wsmall]]


*Sludge Pokemon*
*It was born from polluted sludge in the sea. Grimer's favorite food is anything filthy like waste water pumped out from factories. Grime and sludge stick to their body making them grow larger over time.*

**DexID**:: 0088
**Name**:: Grimer
**Type**:: Poison
**Abilities**:: [[SRD-Stench|Stench]] / [[SRD-Sticky Hold|Sticky Hold]] ([[SRD-Poison Touch|Poison Touch]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon     | Kind   | Speed   |
|:----------|:------------|:-------|:--------|
| To        | [[SRD-Muk]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Grimer.md"
flatten moves as T
where file.path = this.file.path
```
