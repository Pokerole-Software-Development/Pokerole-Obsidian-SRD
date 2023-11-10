---
Ability1: Effect Spore
Ability2: Dry Skin
BookSprite: SRD-parasect-BookSprite.png
BoxSprite: SRD-parasect-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: Their personality changes after evolution since the mushroom takes
  over its mind. Its body is now a husk devoid of nutrients. To survive they cling
  to a tree and absorb the nutrients until the tree dies.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Paras]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Damp
HomeSprite: SRD-parasect-HomeSprite.png
Image: parasect.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Spore|Spore]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 47
ShuffleToken: SRD-parasect-ShuffleToken.png
Type1: Bug
Type2: Grass
Weight:
  Kilograms: 29.5
  Pounds: 65.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-parasect-BookSprite.png|wsmall]]
> ![[SRD-parasect-HomeSprite.png]]
> ![[SRD-parasect-BoxSprite.png|htiny]]
> ![[SRD-parasect-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*Their personality changes after evolution since the mushroom takes over its mind. Its body is now a husk devoid of nutrients. To survive they cling to a tree and absorb the nutrients until the tree dies.*

**DexID**:: 0047
**Name**:: Parasect
**Type**:: Bug / Grass
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] / [[SRD-Dry Skin|Dry Skin]] ([[SRD-Damp|Damp]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 65.0lbs / 29.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Paras]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Parasect.md"
flatten moves as T
where file.path = this.file.path
```
