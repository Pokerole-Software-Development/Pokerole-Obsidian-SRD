---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-wurmple-BookSprite.png
BoxSprite: SRD-wurmple-BoxSprite.png
DexCategory: Worm Pokemon
DexDescription: It uses the spikes on its rear to peel the trees and feed on their
  sap. Their feet have suction pads to climb easily. Wurmples are plentiful and live
  in forests, but they are often attacked by bird Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Silcoon]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cascoon]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Run Away
HomeSprite: SRD-wurmple-HomeSprite.png
Image: wurmple.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-String Shot|String Shot]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snore|Snore]]'
Number: 265
ShuffleToken: SRD-wurmple-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 3.6
  Pounds: 7.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wurmple-BookSprite.png|wsmall]]
> ![[SRD-wurmple-HomeSprite.png]]
> ![[SRD-wurmple-BoxSprite.png|htiny]]
> ![[SRD-wurmple-ShuffleToken.png|wsmall]]


*Worm Pokemon*
*It uses the spikes on its rear to peel the trees and feed on their sap. Their feet have suction pads to climb easily. Wurmples are plentiful and live in forests, but they are often attacked by bird Pokemon.*

**DexID**:: 0265
**Name**:: Wurmple
**Type**:: Bug
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.9lbs / 3.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Silcoon]] | Level  | Fast    |
| To        | [[SRD-Cascoon]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wurmple.md"
flatten moves as T
where file.path = this.file.path
```
