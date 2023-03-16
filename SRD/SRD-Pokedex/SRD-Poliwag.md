---
Ability1: Water Absorb
Ability2: Damp
BookSprite: SRD-poliwag-BookSprite.png
BoxSprite: SRD-poliwag-BoxSprite.png
DexCategory: Tadpole Pokemon
DexDescription: They are most common near ponds and lakes during the summer. Its legs
  take some weeks to develop after it hatches, making it inept at walking. It is,
  however, a very fast swimmer.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Poliwhirl]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Swift Swim
HomeSprite: SRD-poliwag-HomeSprite.png
Image: poliwag.png
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
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
Number: 60
ShuffleToken: SRD-poliwag-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 12.4
  Pounds: 27.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-poliwag-BookSprite.png|wsmall]]
> ![[SRD-poliwag-HomeSprite.png]]
> ![[SRD-poliwag-BoxSprite.png|htiny]]
> ![[SRD-poliwag-ShuffleToken.png|wsmall]]


*Tadpole Pokemon*
*They are most common near ponds and lakes during the summer. Its legs take some weeks to develop after it hatches, making it inept at walking. It is, however, a very fast swimmer.*

**DexID**:: 0060
**Name**:: Poliwag
**Type**:: Water
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Damp|Damp]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 27.3lbs / 12.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Poliwhirl]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Poliwag.md"
flatten moves as T
where file.path = this.file.path
```
