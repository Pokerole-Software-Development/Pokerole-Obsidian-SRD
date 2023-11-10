---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-bellsprout-BookSprite.png
BoxSprite: SRD-bellsprout-BoxSprite.png
DexCategory: Flower Pokemon
DexDescription: They live in hot and humid places, blending around with the flora.
  It is carnivorous and will try to eat anything smaller than itself. It digests its
  prey with an acid substance on its mouth.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Weepinbell]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Gluttony
HomeSprite: SRD-bellsprout-HomeSprite.png
Image: bellsprout.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
Number: 69
ShuffleToken: SRD-bellsprout-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bellsprout-BookSprite.png|wsmall]]
> ![[SRD-bellsprout-HomeSprite.png]]
> ![[SRD-bellsprout-BoxSprite.png|htiny]]
> ![[SRD-bellsprout-ShuffleToken.png|wsmall]]


*Flower Pokemon*
*They live in hot and humid places, blending around with the flora. It is carnivorous and will try to eat anything smaller than itself. It digests its prey with an acid substance on its mouth.*

**DexID**:: 0069
**Name**:: Bellsprout
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Weepinbell]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bellsprout.md"
flatten moves as T
where file.path = this.file.path
```
