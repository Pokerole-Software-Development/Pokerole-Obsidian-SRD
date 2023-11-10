---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-metang-BookSprite.png
BoxSprite: SRD-metang-BoxSprite.png
DexCategory: Iron Claw Pokemon
DexDescription: Its two brains are joined by a magnetic nervous system. This allows
  Metang to use psychokinetic powers. It is able to float and move in midair at 60
  mph. To evolve further it will need more brain power.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Beldum]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Metagross]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Light Metal
HomeSprite: SRD-metang-HomeSprite.png
Image: metang.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Meteor Mash|Meteor Mash]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 375
ShuffleToken: SRD-metang-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 202.5
  Pounds: 446.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-metang-BookSprite.png|wsmall]]
> ![[SRD-metang-HomeSprite.png]]
> ![[SRD-metang-BoxSprite.png|htiny]]
> ![[SRD-metang-ShuffleToken.png|wsmall]]


*Iron Claw Pokemon*
*Its two brains are joined by a magnetic nervous system. This allows Metang to use psychokinetic powers. It is able to float and move in midair at 60 mph. To evolve further it will need more brain power.*

**DexID**:: 0375
**Name**:: Metang
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Light Metal|Light Metal]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 446.4lbs / 202.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Beldum]]    | Level  | Medium  |
| To        | [[SRD-Metagross]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Metang.md"
flatten moves as T
where file.path = this.file.path
```
