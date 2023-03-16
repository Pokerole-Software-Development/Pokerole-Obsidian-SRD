---
Ability1: Stench
Ability2: Weak Armor
BookSprite: SRD-garbodor-BookSprite.png
BoxSprite: SRD-garbodor-BoxSprite.png
DexCategory: Trash Heap Pokemon
DexDescription: They absorb garbage to make it part of their bodies and use it to
  produce toxic substances from their finger tips. They like to remain undisturbed
  and produce a terrible smell to repel others.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Trubbish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Aftermath
HomeSprite: SRD-garbodor-HomeSprite.png
Image: garbodor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Recycle|Recycle]]'
- - Beginner
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
Number: 569
ShuffleToken: SRD-garbodor-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 107.3
  Pounds: 236.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-garbodor-BookSprite.png|wsmall]]
> ![[SRD-garbodor-HomeSprite.png]]
> ![[SRD-garbodor-BoxSprite.png|htiny]]
> ![[SRD-garbodor-ShuffleToken.png|wsmall]]


*Trash Heap Pokemon*
*They absorb garbage to make it part of their bodies and use it to produce toxic substances from their finger tips. They like to remain undisturbed and produce a terrible smell to repel others.*

**DexID**:: 0569
**Name**:: Garbodor
**Type**:: Poison
**Abilities**:: [[SRD-Stench|Stench]] / [[SRD-Weak Armor|Weak Armor]] ([[SRD-Aftermath|Aftermath]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 236.6lbs / 107.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Trubbish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Garbodor.md"
flatten moves as T
where file.path = this.file.path
```
