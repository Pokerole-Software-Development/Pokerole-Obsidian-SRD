---
Ability1: Shell Armor
Ability2: Skill Link
BookSprite: SRD-cloyster-BookSprite.png
BoxSprite: SRD-cloyster-BoxSprite.png
DexCategory: Bivalve Pokemon
DexDescription: If it lives in seas with harsh currents, it will grow larger and sharper
  spikes on its shells than those who live on calm waters. Its shell is extremely
  hard - you would need explosives to try to open it.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shellder]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Overcoat
HomeSprite: SRD-cloyster-HomeSprite.png
Image: cloyster.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Spikes|Spikes]]'
- - Ace
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 91
ShuffleToken: SRD-cloyster-ShuffleToken.png
Type1: Water
Type2: Ice
Weight:
  Kilograms: 132.5
  Pounds: 292.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cloyster-BookSprite.png|wsmall]]
> ![[SRD-cloyster-HomeSprite.png]]
> ![[SRD-cloyster-BoxSprite.png|htiny]]
> ![[SRD-cloyster-ShuffleToken.png|wsmall]]


*Bivalve Pokemon*
*If it lives in seas with harsh currents, it will grow larger and sharper spikes on its shells than those who live on calm waters. Its shell is extremely hard - you would need explosives to try to open it.*

**DexID**:: 0091
**Name**:: Cloyster
**Type**:: Water / Ice
**Abilities**:: [[SRD-Shell Armor|Shell Armor]] / [[SRD-Skill Link|Skill Link]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::9)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 292.1lbs / 132.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Shellder]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cloyster.md"
flatten moves as T
where file.path = this.file.path
```
