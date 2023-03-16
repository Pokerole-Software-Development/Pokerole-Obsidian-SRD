---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-emboar-BookSprite.png
BoxSprite: SRD-emboar-BoxSprite.png
DexCategory: Mega Fire Pig Pokemon
DexDescription: Although it has a scary exterior, it is a very gentle Pokemon that
  cares deeply for family and friends. It can burst its punches and beard on fire,
  it also shows proficiency on martial arts like Judo.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pignite]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Reckless
HomeSprite: SRD-emboar-HomeSprite.png
Image: emboar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Amateur
  - '[[SRD-Smog|Smog]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
- - Pro
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Number: 500
ShuffleToken: SRD-emboar-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 150.0
  Pounds: 330.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-emboar-BookSprite.png|wsmall]]
> ![[SRD-emboar-HomeSprite.png]]
> ![[SRD-emboar-BoxSprite.png|htiny]]
> ![[SRD-emboar-ShuffleToken.png|wsmall]]


*Mega Fire Pig Pokemon*
*Although it has a scary exterior, it is a very gentle Pokemon that cares deeply for family and friends. It can burst its punches and beard on fire, it also shows proficiency on martial arts like Judo.*

**DexID**:: 0500
**Name**:: Emboar
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 330.7lbs / 150.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Pignite]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Emboar.md"
flatten moves as T
where file.path = this.file.path
```
