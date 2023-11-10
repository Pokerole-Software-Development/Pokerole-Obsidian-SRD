---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-caterpie-BookSprite.png
BoxSprite: SRD-caterpie-BoxSprite.png
DexCategory: Worm Pokemon
DexDescription: It is very common in the forests. Its voracious appetite compels it
  to devour leaves bigger than itself without hesitation. It releases a foul odor
  from its antennae if it feels threatened.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Metapod]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Run Away
HomeSprite: SRD-caterpie-HomeSprite.png
Image: caterpie.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Electroweb|Electroweb]]'
Number: 10
ShuffleToken: SRD-caterpie-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 2.9
  Pounds: 6.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-caterpie-BookSprite.png|wsmall]]
> ![[SRD-caterpie-HomeSprite.png]]
> ![[SRD-caterpie-BoxSprite.png|htiny]]
> ![[SRD-caterpie-ShuffleToken.png|wsmall]]


*Worm Pokemon*
*It is very common in the forests. Its voracious appetite compels it to devour leaves bigger than itself without hesitation. It releases a foul odor from its antennae if it feels threatened.*

**DexID**:: 0010
**Name**:: Caterpie
**Type**:: Bug
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 6.4lbs / 2.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Metapod]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Caterpie.md"
flatten moves as T
where file.path = this.file.path
```
