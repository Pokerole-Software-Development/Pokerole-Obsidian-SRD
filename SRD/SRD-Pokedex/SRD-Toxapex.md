---
Ability1: Merciless
Ability2: Limber
BookSprite: SRD-toxapex-BookSprite.png
BoxSprite: SRD-toxapex-BoxSprite.png
DexCategory: Brutal Star Pokemon
DexDescription: "It crawls through the ocean floor, using its tentacles as a fortress.\
  \ Its venom has the victim suffering for three days and nights, and even if it\u2019\
  s healed there are aftereffects for it is a powerful toxin."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mareanie]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Regenerator
HomeSprite: SRD-toxapex-HomeSprite.png
Image: toxapex.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Wide Guard|Wide Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baneful Bunker|Baneful Bunker]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swallow|Swallow]]'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Spit Up|Spit Up]]'
Number: 748
ShuffleToken: SRD-toxapex-ShuffleToken.png
Type1: Poison
Type2: Water
Weight:
  Kilograms: 14.5
  Pounds: 32.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-toxapex-BookSprite.png|wsmall]]
> ![[SRD-toxapex-HomeSprite.png]]
> ![[SRD-toxapex-BoxSprite.png|htiny]]
> ![[SRD-toxapex-ShuffleToken.png|wsmall]]


*Brutal Star Pokemon*
*It crawls through the ocean floor, using its tentacles as a fortress. Its venom has the victim suffering for three days and nights, and even if it’s healed there are aftereffects for it is a powerful toxin.*

**DexID**:: 0748
**Name**:: Toxapex
**Type**:: Poison / Water
**Abilities**:: [[SRD-Merciless|Merciless]] / [[SRD-Limber|Limber]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'3" / 0.7m
**Weight**: 32.0lbs / 14.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Mareanie]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Toxapex.md"
flatten moves as T
where file.path = this.file.path
```
