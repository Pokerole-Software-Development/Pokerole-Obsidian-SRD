---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-quilava-BookSprite.png
BoxSprite: SRD-quilava-BoxSprite.png
DexCategory: Volcano Pokemon
DexDescription: It intimidates foes with intense gusts of flames and superheated air.
  Beware if a Quilava turns its back on you, it is planing on using a fire move.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cyndaquil]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Typhlosion]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Flash Fire
HomeSprite: SRD-quilava-HomeSprite.png
Image: quilava.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Howl|Howl]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 156
ShuffleToken: SRD-quilava-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 19.0
  Pounds: 41.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-quilava-BookSprite.png|wsmall]]
> ![[SRD-quilava-HomeSprite.png]]
> ![[SRD-quilava-BoxSprite.png|htiny]]
> ![[SRD-quilava-ShuffleToken.png|wsmall]]


*Volcano Pokemon*
*It intimidates foes with intense gusts of flames and superheated air. Beware if a Quilava turns its back on you, it is planing on using a fire move.*

**DexID**:: 0156
**Name**:: Quilava
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 41.9lbs / 19.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Cyndaquil]]  | Level  | Medium  |
| To        | [[SRD-Typhlosion]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Quilava.md"
flatten moves as T
where file.path = this.file.path
```
