---
Ability1: Pickup
Ability2: Frisk
BookSprite: SRD-gourgeist-BookSprite.png
BoxSprite: SRD-gourgeist-BoxSprite.png
DexCategory: Pumpkin Pokemon
DexDescription: They wander in the town streets every new moon. It wraps its prey
  on its arms and sings joyfully as it observes the suffering of the victim. Hearing
  it sing will give you horrible nightmares.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Pumpkaboo]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Insomnia
HomeSprite: SRD-gourgeist-HomeSprite.png
Image: gourgeist.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Trick|Trick]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Trick-Or-Treat|Trick-Or-Treat]]'
- - Beginner
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - Ace
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
Number: 711
ShuffleToken: SRD-gourgeist-ShuffleToken.png
Type1: Ghost
Type2: Grass
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gourgeist-BookSprite.png|wsmall]]
> ![[SRD-gourgeist-HomeSprite.png]]
> ![[SRD-gourgeist-BoxSprite.png|htiny]]
> ![[SRD-gourgeist-ShuffleToken.png|wsmall]]


*Pumpkin Pokemon*
*They wander in the town streets every new moon. It wraps its prey on its arms and sings joyfully as it observes the suffering of the victim. Hearing it sing will give you horrible nightmares.*

**DexID**:: 0711
**Name**:: Gourgeist
**Type**:: Ghost / Grass
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Frisk|Frisk]] ([[SRD-Insomnia|Insomnia]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| From      | [[SRD-Pumpkaboo]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gourgeist.md"
flatten moves as T
where file.path = this.file.path
```
