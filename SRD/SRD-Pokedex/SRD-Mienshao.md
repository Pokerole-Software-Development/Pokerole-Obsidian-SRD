---
Ability1: Inner Focus
Ability2: Regenerator
BookSprite: SRD-mienshao-BookSprite.png
BoxSprite: SRD-mienshao-BoxSprite.png
DexCategory: Martial Arts Pokemon
DexDescription: By the time they evolve they already have many years of experience
  in fighting. They use the long fur on their arms as a whip to strike their opponents
  and will not stop until the foe is defeated.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mienfoo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Reckless
HomeSprite: SRD-mienshao-HomeSprite.png
Image: mienshao.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Amateur
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 620
ShuffleToken: SRD-mienshao-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 35.5
  Pounds: 78.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mienshao-BookSprite.png|wsmall]]
> ![[SRD-mienshao-HomeSprite.png]]
> ![[SRD-mienshao-BoxSprite.png|htiny]]
> ![[SRD-mienshao-ShuffleToken.png|wsmall]]


*Martial Arts Pokemon*
*By the time they evolve they already have many years of experience in fighting. They use the long fur on their arms as a whip to strike their opponents and will not stop until the foe is defeated.*

**DexID**:: 0620
**Name**:: Mienshao
**Type**:: Fighting
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Regenerator|Regenerator]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 78.3lbs / 35.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Mienfoo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mienshao.md"
flatten moves as T
where file.path = this.file.path
```
