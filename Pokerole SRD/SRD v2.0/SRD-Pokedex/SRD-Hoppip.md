---
Ability1: Chlorophyll
Ability2: Leaf Guard
BookSprite: SRD-hoppip-BookSprite.png
BoxSprite: SRD-hoppip-BoxSprite.png
DexCategory: Cottonweed Pokemon
DexDescription: This Pokemon drifts away by floating in the wind. Even the weakest
  current can lift them up. By the end of the winter you can see them flying above
  cities and fields. This means that spring is coming soon.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Skiploom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Infiltrator
HomeSprite: SRD-hoppip-HomeSprite.png
Image: hoppip.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Synthesis|Synthesis]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Rage Powder|Rage Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Aromatherapy|Aromatherapy]]'
Number: 187
ShuffleToken: SRD-hoppip-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hoppip-BookSprite.png|wsmall]]
> ![[SRD-hoppip-HomeSprite.png]]
> ![[SRD-hoppip-BoxSprite.png|htiny]]
> ![[SRD-hoppip-ShuffleToken.png|wsmall]]


*Cottonweed Pokemon*
*This Pokemon drifts away by floating in the wind. Even the weakest current can lift them up. By the end of the winter you can see them flying above cities and fields. This means that spring is coming soon.*

**DexID**:: 0187
**Name**:: Hoppip
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Skiploom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hoppip.md"
flatten moves as T
where file.path = this.file.path
```
