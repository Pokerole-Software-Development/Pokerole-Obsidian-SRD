---
Ability1: Vital Spirit
Ability2: Screen Cleaner
BookSprite: SRD-mr-mime-galarian-form-BookSprite.png
BoxSprite: SRD-mr-mime-galarian-form-BoxSprite.png
DexCategory: Barrier Pokemon
DexDescription: Mime Jr. that endure the harsh winter of Galar are able to create
  invisible walls that suddenly turn to ice, as they evolve they start creating ice
  floors that allow them to tap-dance, which they enjoy more than anything.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Mime Jr]]'
  Region: Galar
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mr. Rime]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Ice Body
HomeSprite: SRD-mr-mime-galarian-form-HomeSprite.png
Image: mr-mime-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Ally Switch|Ally Switch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Recycle|Recycle]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Pro
  - '[[SRD-Hail|Hail]]'
Number: 122
ShuffleToken: SRD-mr-mime-galarian-form-ShuffleToken.png
Type1: Ice
Type2: Psychic
Weight:
  Kilograms: 56.8
  Pounds: 125.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mr-mime-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-mr-mime-galarian-form-HomeSprite.png]]
> ![[SRD-mr-mime-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-mr-mime-galarian-form-ShuffleToken.png|wsmall]]


*Barrier Pokemon*
*Mime Jr. that endure the harsh winter of Galar are able to create invisible walls that suddenly turn to ice, as they evolve they start creating ice floors that allow them to tap-dance, which they enjoy more than anything.*

**DexID**:: 0122G
**Name**:: Mr. Mime (Galarian Form)
**Type**:: Ice / Psychic
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]] / [[SRD-Screen Cleaner|Screen Cleaner]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 125.2lbs / 56.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Move   | Region   | Speed   |
|:----------|:-----------------|:-------|:-------|:---------|:--------|
| From      | [[SRD-Mime Jr]]  | Level  | Mimic  | Galar    |         |
| To        | [[SRD-Mr. Rime]] | Level  |        |          | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mr. Mime (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
