---
Ability1: Hyper Cutter
Ability2: Iron Fist
BookSprite: SRD-crabrawler-BookSprite.png
BoxSprite: SRD-crabrawler-BoxSprite.png
DexCategory: Boxing Pokemon
DexDescription: They can be found on the beach, but as they grow stronger they also
  venture more into the land where they fight for ripe berries. They punch with their
  pincers, which are delicious with butter by the way.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Crabominable]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Anger Point
HomeSprite: SRD-crabrawler-HomeSprite.png
Image: crabrawler.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Crabhammer|Crabhammer]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
Number: 739
ShuffleToken: SRD-crabrawler-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 7.0
  Pounds: 15.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-crabrawler-BookSprite.png|wsmall]]
> ![[SRD-crabrawler-HomeSprite.png]]
> ![[SRD-crabrawler-BoxSprite.png|htiny]]
> ![[SRD-crabrawler-ShuffleToken.png|wsmall]]


*Boxing Pokemon*
*They can be found on the beach, but as they grow stronger they also venture more into the land where they fight for ripe berries. They punch with their pincers, which are delicious with butter by the way.*

**DexID**:: 0739
**Name**:: Crabrawler
**Type**:: Fighting
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Iron Fist|Iron Fist]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 15.4lbs / 7.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon              | Kind   | Speed   |
|:----------|:---------------------|:-------|:--------|
| To        | [[SRD-Crabominable]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Crabrawler.md"
flatten moves as T
where file.path = this.file.path
```
