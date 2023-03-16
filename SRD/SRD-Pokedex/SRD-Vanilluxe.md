---
Ability1: Ice Body
Ability2: Snow Warning
BookSprite: SRD-vanilluxe-BookSprite.png
BoxSprite: SRD-vanilluxe-BoxSprite.png
DexCategory: Snowstorm Pokemon
DexDescription: It grew a new head with evolution, and they get along really well.
  They need to drink a lot of water in order to keep cool outside a gelid weather.
  If both heads get angry they will expel a terrible blizzard around.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Vanillish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Weak Armor
HomeSprite: SRD-vanilluxe-HomeSprite.png
Image: vanilluxe.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
Number: 584
ShuffleToken: SRD-vanilluxe-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 57.5
  Pounds: 126.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vanilluxe-BookSprite.png|wsmall]]
> ![[SRD-vanilluxe-HomeSprite.png]]
> ![[SRD-vanilluxe-BoxSprite.png|htiny]]
> ![[SRD-vanilluxe-ShuffleToken.png|wsmall]]


*Snowstorm Pokemon*
*It grew a new head with evolution, and they get along really well. They need to drink a lot of water in order to keep cool outside a gelid weather. If both heads get angry they will expel a terrible blizzard around.*

**DexID**:: 0584
**Name**:: Vanilluxe
**Type**:: Ice
**Abilities**:: [[SRD-Ice Body|Ice Body]] / [[SRD-Snow Warning|Snow Warning]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 126.8lbs / 57.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Vanillish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Vanilluxe.md"
flatten moves as T
where file.path = this.file.path
```
