---
Ability1: Limber
Ability2: ''
BookSprite: SRD-grapploct-BookSprite.png
BoxSprite: SRD-grapploct-BoxSprite.png
DexCategory: Jujitsu Pokemon
DexDescription: A body made up of nothing but muscle makes its tentacles very powerful.
  They come out of the ocean to find opponents to battle, once the fight is over they
  go back into the sea.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Clobbopus]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Technician
HomeSprite: SRD-grapploct-HomeSprite.png
Image: grapploct.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Octolock|Octolock]]'
- - Amateur
  - '[[SRD-Octazooka|Octazooka]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
- - Pro
  - '[[SRD-Liquidation|Liquidation]]'
- - Pro
  - '[[SRD-Brutal Swing|Brutal Swing]]'
Number: 853
ShuffleToken: SRD-grapploct-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 39.0
  Pounds: 86.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grapploct-BookSprite.png|wsmall]]
> ![[SRD-grapploct-HomeSprite.png]]
> ![[SRD-grapploct-BoxSprite.png|htiny]]
> ![[SRD-grapploct-ShuffleToken.png|wsmall]]


*Jujitsu Pokemon*
*A body made up of nothing but muscle makes its tentacles very powerful. They come out of the ocean to find opponents to battle, once the fight is over they go back into the sea.*

**DexID**:: 0853
**Name**:: Grapploct
**Type**:: Fighting
**Abilities**:: [[SRD-Limber|Limber]] ([[SRD-Technician|Technician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 86.0lbs / 39.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Clobbopus]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Grapploct.md"
flatten moves as T
where file.path = this.file.path
```
