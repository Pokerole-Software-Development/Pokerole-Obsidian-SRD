---
Ability1: Water Absorb
Ability2: Damp
BookSprite: SRD-poliwhirl-BookSprite.png
BoxSprite: SRD-poliwhirl-BoxSprite.png
DexCategory: Tadpole Pokemon
DexDescription: "Though it is skilled at walking, it prefers to live underwater where\
  \ there\u2019s less danger. It sweats to keep its skin moist. Thanks to this, it\
  \ can easily slip out of the clutches of any enemy."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Poliwag]]'
  Speed: Medium
- Evolves: To
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Poliwrath]]'
- Evolves: To
  Item: King's Rock
  Kind: Trade
  Pokemon: '[[SRD-Politoed]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Swift Swim
HomeSprite: SRD-poliwhirl-HomeSprite.png
Image: poliwhirl.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
Number: 61
ShuffleToken: SRD-poliwhirl-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 20.0
  Pounds: 44.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-poliwhirl-BookSprite.png|wsmall]]
> ![[SRD-poliwhirl-HomeSprite.png]]
> ![[SRD-poliwhirl-BoxSprite.png|htiny]]
> ![[SRD-poliwhirl-ShuffleToken.png|wsmall]]


*Tadpole Pokemon*
*Though it is skilled at walking, it prefers to live underwater where there’s less danger. It sweats to keep its skin moist. Thanks to this, it can easily slip out of the clutches of any enemy.*

**DexID**:: 0061
**Name**:: Poliwhirl
**Type**:: Water
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Damp|Damp]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 44.1lbs / 20.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item        |
|:----------|:------------------|:-------|:--------|:------------|
| From      | [[SRD-Poliwag]]   | Level  | Medium  |             |
| To        | [[SRD-Poliwrath]] | Stone  |         | Water Stone |
| To        | [[SRD-Politoed]]  | Trade  |         | King's Rock |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Poliwhirl.md"
flatten moves as T
where file.path = this.file.path
```
