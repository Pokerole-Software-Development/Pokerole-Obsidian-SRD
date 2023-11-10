---
Ability1: Shell Armor
Ability2: Skill Link
BookSprite: SRD-shellder-BookSprite.png
BoxSprite: SRD-shellder-BoxSprite.png
DexCategory: Bivalve Pokemon
DexDescription: "It lives at the bottom of the sea and rivers. It feeds on algae but\
  \ it\u2019s attracted to sweet substances. When frightened it will shut its clam\
  \ and lock it to be almost impossible to open."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cloyster]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Overcoat
HomeSprite: SRD-shellder-HomeSprite.png
Image: shellder.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - Amateur
  - '[[SRD-Withdraw|Withdraw]]'
- - Amateur
  - '[[SRD-Leer|Leer]]'
- - Amateur
  - '[[SRD-Clamp|Clamp]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Razor Shell|Razor Shell]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
Number: 90
ShuffleToken: SRD-shellder-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shellder-BookSprite.png|wsmall]]
> ![[SRD-shellder-HomeSprite.png]]
> ![[SRD-shellder-BoxSprite.png|htiny]]
> ![[SRD-shellder-ShuffleToken.png|wsmall]]


*Bivalve Pokemon*
*It lives at the bottom of the sea and rivers. It feeds on algae but it’s attracted to sweet substances. When frightened it will shut its clam and lock it to be almost impossible to open.*

**DexID**:: 0090
**Name**:: Shellder
**Type**:: Water
**Abilities**:: [[SRD-Shell Armor|Shell Armor]] / [[SRD-Skill Link|Skill Link]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Cloyster]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shellder.md"
flatten moves as T
where file.path = this.file.path
```
