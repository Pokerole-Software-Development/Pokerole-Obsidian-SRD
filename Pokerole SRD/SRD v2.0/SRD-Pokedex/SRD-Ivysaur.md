---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-ivysaur-BookSprite.png
BoxSprite: SRD-ivysaur-BoxSprite.png
DexCategory: Seed Pokemon
DexDescription: There is a bud on this Pokemon's back. To support its weight, Ivysaur's
  legs and trunk grow thick and strong. It becomes kind of a loner after evolving
  and may stray away from its group to take sunbaths.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bulbasaur]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Venusaur]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Chlorophyll
HomeSprite: SRD-ivysaur-HomeSprite.png
Image: ivysaur.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Worry Seed|Worry Seed]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grass Pledge|Grass Pledge]]'
Number: 2
ShuffleToken: SRD-ivysaur-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ivysaur-BookSprite.png|wsmall]]
> ![[SRD-ivysaur-HomeSprite.png]]
> ![[SRD-ivysaur-BoxSprite.png|htiny]]
> ![[SRD-ivysaur-ShuffleToken.png|wsmall]]


*Seed Pokemon*
*There is a bud on this Pokemon's back. To support its weight, Ivysaur's legs and trunk grow thick and strong. It becomes kind of a loner after evolving and may stray away from its group to take sunbaths.*

**DexID**:: 0002
**Name**:: Ivysaur
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Bulbasaur]] | Level  | Medium  |
| To        | [[SRD-Venusaur]]  | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ivysaur.md"
flatten moves as T
where file.path = this.file.path
```
