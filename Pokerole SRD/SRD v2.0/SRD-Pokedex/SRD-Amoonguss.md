---
Ability1: Effect Spore
Ability2: ''
BookSprite: SRD-amoonguss-BookSprite.png
BoxSprite: SRD-amoonguss-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: In ancient times the tip of their caps had two eye-like patterns and
  it made a swaying motion to lure prey to itself, but as they became Pokeball-looking
  few Pokemon fall for it. It is still very venomous, though.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Foongus]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Regenerator
HomeSprite: SRD-amoonguss-HomeSprite.png
Image: amoonguss.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 591
ShuffleToken: SRD-amoonguss-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 10.5
  Pounds: 23.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-amoonguss-BookSprite.png|wsmall]]
> ![[SRD-amoonguss-HomeSprite.png]]
> ![[SRD-amoonguss-BoxSprite.png|htiny]]
> ![[SRD-amoonguss-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*In ancient times the tip of their caps had two eye-like patterns and it made a swaying motion to lure prey to itself, but as they became Pokeball-looking few Pokemon fall for it. It is still very venomous, though.*

**DexID**:: 0591
**Name**:: Amoonguss
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 23.1lbs / 10.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Foongus]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Amoonguss.md"
flatten moves as T
where file.path = this.file.path
```
