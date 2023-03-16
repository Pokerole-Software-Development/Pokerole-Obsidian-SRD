---
Ability1: Thick Fat
Ability2: Huge Power
BookSprite: SRD-azumarill-BookSprite.png
BoxSprite: SRD-azumarill-BoxSprite.png
DexCategory: Aquarabbit Pokemon
DexDescription: It stays in water virtually all day long. Its blue fur makes it difficult
  to spot when submerged. Azumarril uses its sensitive ears to locate prey even underwater.
  They are not aggressive and even get close to humans.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Marill]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Sap Sipper
HomeSprite: SRD-azumarill-HomeSprite.png
Image: azumarill.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 184
ShuffleToken: SRD-azumarill-ShuffleToken.png
Type1: Water
Type2: Fairy
Weight:
  Kilograms: 28.5
  Pounds: 62.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-azumarill-BookSprite.png|wsmall]]
> ![[SRD-azumarill-HomeSprite.png]]
> ![[SRD-azumarill-BoxSprite.png|htiny]]
> ![[SRD-azumarill-ShuffleToken.png|wsmall]]


*Aquarabbit Pokemon*
*It stays in water virtually all day long. Its blue fur makes it difficult to spot when submerged. Azumarril uses its sensitive ears to locate prey even underwater. They are not aggressive and even get close to humans.*

**DexID**:: 0184
**Name**:: Azumarill
**Type**:: Water / Fairy
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Huge Power|Huge Power]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 62.8lbs / 28.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Marill]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Azumarill.md"
flatten moves as T
where file.path = this.file.path
```
