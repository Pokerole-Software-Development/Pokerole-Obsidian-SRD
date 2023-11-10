---
Ability1: Chlorophyll
Ability2: Leaf Guard
BookSprite: SRD-jumpluff-BookSprite.png
BoxSprite: SRD-jumpluff-BoxSprite.png
DexCategory: Cottonweed Pokemon
DexDescription: It flies along the wind and spreads its cotton-like spores all over
  the world to make more offspring. It is always looking for warm places, if it gets
  caught by a cold front, it will land to find shelter.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Skiploom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Infiltrator
HomeSprite: SRD-jumpluff-HomeSprite.png
Image: jumpluff.png
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
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Ace
  - '[[SRD-U-Turn|U-Turn]]'
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
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
Number: 189
ShuffleToken: SRD-jumpluff-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 3.0
  Pounds: 6.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jumpluff-BookSprite.png|wsmall]]
> ![[SRD-jumpluff-HomeSprite.png]]
> ![[SRD-jumpluff-BoxSprite.png|htiny]]
> ![[SRD-jumpluff-ShuffleToken.png|wsmall]]


*Cottonweed Pokemon*
*It flies along the wind and spreads its cotton-like spores all over the world to make more offspring. It is always looking for warm places, if it gets caught by a cold front, it will land to find shelter.*

**DexID**:: 0189
**Name**:: Jumpluff
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 6.6lbs / 3.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Skiploom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jumpluff.md"
flatten moves as T
where file.path = this.file.path
```
