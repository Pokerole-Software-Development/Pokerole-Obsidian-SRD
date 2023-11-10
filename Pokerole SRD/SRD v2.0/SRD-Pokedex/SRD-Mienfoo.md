---
Ability1: Inner Focus
Ability2: Regenerator
BookSprite: SRD-mienfoo-BookSprite.png
BoxSprite: SRD-mienfoo-BoxSprite.png
DexCategory: Martial Arts Pokemon
DexDescription: They gather in small groups around the mountains to train and master
  new techniques. They use their sharp claws to damage their foes. Only those Mienfoo
  that excel at fighting in the group evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mienshao]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Reckless
HomeSprite: SRD-mienfoo-HomeSprite.png
Image: mienfoo.png
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
  - '[[SRD-Quick Guard|Quick Guard]]'
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
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Pro
  - '[[SRD-Feint|Feint]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 619
ShuffleToken: SRD-mienfoo-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 20.0
  Pounds: 44.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mienfoo-BookSprite.png|wsmall]]
> ![[SRD-mienfoo-HomeSprite.png]]
> ![[SRD-mienfoo-BoxSprite.png|htiny]]
> ![[SRD-mienfoo-ShuffleToken.png|wsmall]]


*Martial Arts Pokemon*
*They gather in small groups around the mountains to train and master new techniques. They use their sharp claws to damage their foes. Only those Mienfoo that excel at fighting in the group evolve.*

**DexID**:: 0619
**Name**:: Mienfoo
**Type**:: Fighting
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Regenerator|Regenerator]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 44.1lbs / 20.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Mienshao]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mienfoo.md"
flatten moves as T
where file.path = this.file.path
```
