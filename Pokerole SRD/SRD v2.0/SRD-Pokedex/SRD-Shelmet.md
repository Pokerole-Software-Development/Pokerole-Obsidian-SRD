---
Ability1: Hydration
Ability2: Shell Armor
BookSprite: SRD-shelmet-BookSprite.png
BoxSprite: SRD-shelmet-BoxSprite.png
DexCategory: Snail Pokemon
DexDescription: When attacked, it defends itself by closing the lid of its shell or
  spits a sticky, poisonous liquid. It competes with Karrablast for food and shelter.
  If it loses its shell the distress may kill it, only those who survive evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Accelgor]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Overcoat
HomeSprite: SRD-shelmet-HomeSprite.png
Image: shelmet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leech Life|Leech Life]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 616
ShuffleToken: SRD-shelmet-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 7.7
  Pounds: 17.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shelmet-BookSprite.png|wsmall]]
> ![[SRD-shelmet-HomeSprite.png]]
> ![[SRD-shelmet-BoxSprite.png|htiny]]
> ![[SRD-shelmet-ShuffleToken.png|wsmall]]


*Snail Pokemon*
*When attacked, it defends itself by closing the lid of its shell or spits a sticky, poisonous liquid. It competes with Karrablast for food and shelter. If it loses its shell the distress may kill it, only those who survive evolve.*

**DexID**:: 0616
**Name**:: Shelmet
**Type**:: Bug
**Abilities**:: [[SRD-Hydration|Hydration]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 17.0lbs / 7.7kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Accelgor]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shelmet.md"
flatten moves as T
where file.path = this.file.path
```
