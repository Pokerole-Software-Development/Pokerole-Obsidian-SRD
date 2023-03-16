---
Ability1: Corrosion
Ability2: ''
BookSprite: SRD-salazzle-BookSprite.png
BoxSprite: SRD-salazzle-BoxSprite.png
DexCategory: Toxic Lizard Pokemon
DexDescription: This Pokemon is Female only. It releases a powerful toxic gas that
  is filled with pheromones that help her keep her reverse harem of Salandit in check.
  This gas can be purified into expensive perfumes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Salandit]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Oblivious
HomeSprite: SRD-salazzle-HomeSprite.png
Image: salazzle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Encore|Encore]]'
- - Ace
  - '[[SRD-Disable|Disable]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Pro
  - '[[SRD-Overheat|Overheat]]'
Number: 758
ShuffleToken: SRD-salazzle-ShuffleToken.png
Type1: Poison
Type2: Fire
Weight:
  Kilograms: 22.2
  Pounds: 48.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-salazzle-BookSprite.png|wsmall]]
> ![[SRD-salazzle-HomeSprite.png]]
> ![[SRD-salazzle-BoxSprite.png|htiny]]
> ![[SRD-salazzle-ShuffleToken.png|wsmall]]


*Toxic Lizard Pokemon*
*This Pokemon is Female only. It releases a powerful toxic gas that is filled with pheromones that help her keep her reverse harem of Salandit in check. This gas can be purified into expensive perfumes.*

**DexID**:: 0758
**Name**:: Salazzle
**Type**:: Poison / Fire
**Abilities**:: [[SRD-Corrosion|Corrosion]] ([[SRD-Oblivious|Oblivious]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 48.9lbs / 22.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Gender   |
|:----------|:-----------------|:-------|:--------|:---------|
| From      | [[SRD-Salandit]] | Level  | Medium  | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Salazzle.md"
flatten moves as T
where file.path = this.file.path
```
