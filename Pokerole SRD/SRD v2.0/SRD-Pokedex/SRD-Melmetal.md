---
Ability1: Iron Fist
Ability2: ''
BookSprite: SRD-melmetal-BookSprite.png
BoxSprite: SRD-melmetal-BoxSprite.png
DexCategory: Hex Nut Pokemon
DexDescription: There is an ancient myth that a Pokemon once taught a group of humans
  how to work the iron, melt it and shape it into tools; but it was punished for this
  and cast away, never to be seen again.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Meltan]]'
  Speed: Unknown
GenderType: N
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-melmetal-HomeSprite.png
Image: melmetal.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Double Iron Bash|Double Iron Bash]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 809
ShuffleToken: SRD-melmetal-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 800.0
  Pounds: 1763.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-melmetal-BookSprite.png|wsmall]]
> ![[SRD-melmetal-HomeSprite.png]]
> ![[SRD-melmetal-BoxSprite.png|htiny]]
> ![[SRD-melmetal-ShuffleToken.png|wsmall]]


*Hex Nut Pokemon*
*There is an ancient myth that a Pokemon once taught a group of humans how to work the iron, melt it and shape it into tools; but it was punished for this and cast away, never to be seen again.*

**DexID**:: 0809
**Name**:: Melmetal
**Type**:: Steel
**Abilities**:: [[SRD-Iron Fist|Iron Fist]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'2" / 2.5m
**Weight**: 1763.7lbs / 800.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Meltan]] | Level  | Unknown |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Melmetal.md"
flatten moves as T
where file.path = this.file.path
```
