---
Ability1: Flower Veil
Ability2: ''
BookSprite: SRD-flabebe-BookSprite.png
BoxSprite: SRD-flabebe-BoxSprite.png
DexCategory: Single Bloom Pokemon
DexDescription: This species is female only. They are so tiny it is difficult to spot
  them in the wild. They pick a flower as soon as they are born and it becomes a part
  of their body. These small Pokemon are shy but adorable.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Floette]]'
  Speed: Fast
GenderType: F
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: Symbiosis
HomeSprite: SRD-flabebe-HomeSprite.png
Image: flabebe.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Amateur
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Camouflage|Camouflage]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 669
ShuffleToken: SRD-flabebe-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.1
  Pounds: 0.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-flabebe-BookSprite.png|wsmall]]
> ![[SRD-flabebe-HomeSprite.png]]
> ![[SRD-flabebe-BoxSprite.png|htiny]]
> ![[SRD-flabebe-ShuffleToken.png|wsmall]]


*Single Bloom Pokemon*
*This species is female only. They are so tiny it is difficult to spot them in the wild. They pick a flower as soon as they are born and it becomes a part of their body. These small Pokemon are shy but adorable.*

**DexID**:: 0669
**Name**:: Flabebe
**Type**:: Fairy
**Abilities**:: [[SRD-Flower Veil|Flower Veil]] ([[SRD-Symbiosis|Symbiosis]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 0'3" / 0.1m
**Weight**: 0.2lbs / 0.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Floette]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Flabebe.md"
flatten moves as T
where file.path = this.file.path
```
