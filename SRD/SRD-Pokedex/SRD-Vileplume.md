---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-vileplume-BookSprite.png
BoxSprite: SRD-vileplume-BoxSprite.png
DexCategory: Flower Pokemon
DexDescription: "It lives in marshlands and jungles where it\u2019s often mistaken\
  \ for local flora. The air around a Vileplume turns yellow with the powder it releases\
  \ as it walks. The pollen is highly toxic and causes paralysis."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Gloom]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Effect Spore
HomeSprite: SRD-vileplume-HomeSprite.png
Image: vileplume.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 45
ShuffleToken: SRD-vileplume-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 18.6
  Pounds: 41.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vileplume-BookSprite.png|wsmall]]
> ![[SRD-vileplume-HomeSprite.png]]
> ![[SRD-vileplume-BoxSprite.png|htiny]]
> ![[SRD-vileplume-ShuffleToken.png|wsmall]]


*Flower Pokemon*
*It lives in marshlands and jungles where it’s often mistaken for local flora. The air around a Vileplume turns yellow with the powder it releases as it walks. The pollen is highly toxic and causes paralysis.*

**DexID**:: 0045
**Name**:: Vileplume
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Effect Spore|Effect Spore]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 41.0lbs / 18.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item       |
|:----------|:--------------|:-------|:-----------|
| From      | [[SRD-Gloom]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Vileplume.md"
flatten moves as T
where file.path = this.file.path
```
