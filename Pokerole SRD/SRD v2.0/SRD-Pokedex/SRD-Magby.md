---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-magby-BookSprite.png
BoxSprite: SRD-magby-BoxSprite.png
DexCategory: Live Coal Pokemon
DexDescription: They inhale and exhale embers from their mouth and nostrils. Their
  body temperature is so hot, they may ignite anything they touch and the floor they
  walk. Magby can be found in volcanoes.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Magmar]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Vital Spirit
HomeSprite: SRD-magby-HomeSprite.png
Image: magby.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Pro
  - '[[SRD-Belch|Belch]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
Number: 240
ShuffleToken: SRD-magby-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 21.4
  Pounds: 47.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magby-BookSprite.png|wsmall]]
> ![[SRD-magby-HomeSprite.png]]
> ![[SRD-magby-BoxSprite.png|htiny]]
> ![[SRD-magby-ShuffleToken.png|wsmall]]


*Live Coal Pokemon*
*They inhale and exhale embers from their mouth and nostrils. Their body temperature is so hot, they may ignite anything they touch and the floor they walk. Magby can be found in volcanoes.*

**DexID**:: 0240
**Name**:: Magby
**Type**:: Fire
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 47.2lbs / 21.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Magmar]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Magby.md"
flatten moves as T
where file.path = this.file.path
```
