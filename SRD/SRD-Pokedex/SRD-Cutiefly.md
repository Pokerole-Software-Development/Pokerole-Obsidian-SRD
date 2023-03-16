---
Ability1: Honey Gather
Ability2: Shield Dust
BookSprite: SRD-cutiefly-BookSprite.png
BoxSprite: SRD-cutiefly-BoxSprite.png
DexCategory: Bee Fly Pokemon
DexDescription: These delicate Pokemon gather by the numbers in flower meadows. They
  are attracted to happy and joyful people, the story says that Cutiefly see their
  auras and they resemble flowers.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ribombee]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: Sweet Veil
HomeSprite: SRD-cutiefly-HomeSprite.png
Image: cutiefly.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Beginner
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Moonblast|Moonblast]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Speed Swap|Speed Swap]]'
Number: 742
ShuffleToken: SRD-cutiefly-ShuffleToken.png
Type1: Bug
Type2: Fairy
Weight:
  Kilograms: 0.2
  Pounds: 0.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cutiefly-BookSprite.png|wsmall]]
> ![[SRD-cutiefly-HomeSprite.png]]
> ![[SRD-cutiefly-BoxSprite.png|htiny]]
> ![[SRD-cutiefly-ShuffleToken.png|wsmall]]


*Bee Fly Pokemon*
*These delicate Pokemon gather by the numbers in flower meadows. They are attracted to happy and joyful people, the story says that Cutiefly see their auras and they resemble flowers.*

**DexID**:: 0742
**Name**:: Cutiefly
**Type**:: Bug / Fairy
**Abilities**:: [[SRD-Honey Gather|Honey Gather]] / [[SRD-Shield Dust|Shield Dust]] ([[SRD-Sweet Veil|Sweet Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'3" / 0.1m
**Weight**: 0.4lbs / 0.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Ribombee]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cutiefly.md"
flatten moves as T
where file.path = this.file.path
```
