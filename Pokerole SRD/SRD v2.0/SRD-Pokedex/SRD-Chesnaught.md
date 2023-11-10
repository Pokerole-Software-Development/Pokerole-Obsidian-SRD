---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-chesnaught-BookSprite.png
BoxSprite: SRD-chesnaught-BoxSprite.png
DexCategory: Spiny Armor Pokemon
DexDescription: These Pokemon are known for taking defensive stances instead of charging
  into battle. Many stories tell how during the old wars, Chesnaught protected their
  allies using their bodies.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Quilladin]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Bulletproof
HomeSprite: SRD-chesnaught-HomeSprite.png
Image: chesnaught.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Needle Arm|Needle Arm]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Spiky Shield|Spiky Shield]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 652
ShuffleToken: SRD-chesnaught-ShuffleToken.png
Type1: Grass
Type2: Fighting
Weight:
  Kilograms: 90.0
  Pounds: 198.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chesnaught-BookSprite.png|wsmall]]
> ![[SRD-chesnaught-HomeSprite.png]]
> ![[SRD-chesnaught-BoxSprite.png|htiny]]
> ![[SRD-chesnaught-ShuffleToken.png|wsmall]]


*Spiny Armor Pokemon*
*These Pokemon are known for taking defensive stances instead of charging into battle. Many stories tell how during the old wars, Chesnaught protected their allies using their bodies.*

**DexID**:: 0652
**Name**:: Chesnaught
**Type**:: Grass / Fighting
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 198.4lbs / 90.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Quilladin]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chesnaught.md"
flatten moves as T
where file.path = this.file.path
```
