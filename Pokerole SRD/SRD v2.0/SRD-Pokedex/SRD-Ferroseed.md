---
Ability1: Iron Barbs
Ability2: ''
BookSprite: SRD-ferroseed-BookSprite.png
BoxSprite: SRD-ferroseed-BoxSprite.png
DexCategory: Thorn Seed Pokemon
DexDescription: They stick their thorns into cave walls and absorb the minerals from
  the rocks. When threatened, they attack by shooting a barrage of spikes, which gives
  them a chance to escape by rolling away.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ferrothorn]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-ferroseed-HomeSprite.png
Image: ferroseed.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 597
ShuffleToken: SRD-ferroseed-ShuffleToken.png
Type1: Grass
Type2: Steel
Weight:
  Kilograms: 18.8
  Pounds: 41.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ferroseed-BookSprite.png|wsmall]]
> ![[SRD-ferroseed-HomeSprite.png]]
> ![[SRD-ferroseed-BoxSprite.png|htiny]]
> ![[SRD-ferroseed-ShuffleToken.png|wsmall]]


*Thorn Seed Pokemon*
*They stick their thorns into cave walls and absorb the minerals from the rocks. When threatened, they attack by shooting a barrage of spikes, which gives them a chance to escape by rolling away.*

**DexID**:: 0597
**Name**:: Ferroseed
**Type**:: Grass / Steel
**Abilities**:: [[SRD-Iron Barbs|Iron Barbs]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 41.4lbs / 18.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Ferrothorn]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ferroseed.md"
flatten moves as T
where file.path = this.file.path
```
