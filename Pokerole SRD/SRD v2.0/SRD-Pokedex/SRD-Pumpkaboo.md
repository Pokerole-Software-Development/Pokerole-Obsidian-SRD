---
Ability1: Pickup
Ability2: Frisk
BookSprite: SRD-pumpkaboo-BookSprite.png
BoxSprite: SRD-pumpkaboo-BoxSprite.png
DexCategory: Pumpkin Pokemon
DexDescription: "You can see them dwelling on farms during the autumn season. The\
  \ pumpkin body is inhabited by a spirit trapped in this world. As the sun sets,\
  \ it becomes restless and active. Don\u2019t ever follow their light at night."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Gourgeist]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Insomnia
HomeSprite: SRD-pumpkaboo-HomeSprite.png
Image: pumpkaboo.png
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
Number: 710
ShuffleToken: SRD-pumpkaboo-ShuffleToken.png
Type1: Ghost
Type2: Grass
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pumpkaboo-BookSprite.png|wsmall]]
> ![[SRD-pumpkaboo-HomeSprite.png]]
> ![[SRD-pumpkaboo-BoxSprite.png|htiny]]
> ![[SRD-pumpkaboo-ShuffleToken.png|wsmall]]


*Pumpkin Pokemon*
*You can see them dwelling on farms during the autumn season. The pumpkin body is inhabited by a spirit trapped in this world. As the sun sets, it becomes restless and active. Don’t ever follow their light at night.*

**DexID**:: 0710
**Name**:: Pumpkaboo
**Type**:: Ghost / Grass
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Frisk|Frisk]] ([[SRD-Insomnia|Insomnia]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| To        | [[SRD-Gourgeist]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pumpkaboo.md"
flatten moves as T
where file.path = this.file.path
```
