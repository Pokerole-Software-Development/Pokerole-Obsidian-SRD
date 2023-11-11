---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-cascoon-BookSprite.png
BoxSprite: SRD-cascoon-BoxSprite.png
DexCategory: Cocoon Pokemon
DexDescription: They hide between huge leaves and gaps between branches, if they were
  to move, their evolution would be weaker. Due to this, Cascoon will remain motionless.
  If Wrumple lived in a dark place, it evolves to Cascoon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wurmple]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dustox]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-cascoon-HomeSprite.png
Image: cascoon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electroweb|Electroweb]]'
Number: 268
ShuffleToken: SRD-cascoon-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cascoon-BookSprite.png|wsmall]]
> ![[SRD-cascoon-HomeSprite.png]]
> ![[SRD-cascoon-BoxSprite.png|htiny]]
> ![[SRD-cascoon-ShuffleToken.png|wsmall]]


*Cocoon Pokemon*
*They hide between huge leaves and gaps between branches, if they were to move, their evolution would be weaker. Due to this, Cascoon will remain motionless. If Wrumple lived in a dark place, it evolves to Cascoon.*

**DexID**:: 0268
**Name**:: Cascoon
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Wurmple]] | Level  | Fast    |
| To        | [[SRD-Dustox]]  | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cascoon.md"
flatten moves as T
where file.path = this.file.path
```
