---
Ability1: Soundproof
Ability2: Static
BookSprite: SRD-voltorb-BookSprite.png
BoxSprite: SRD-voltorb-BoxSprite.png
DexCategory: Ball Pokemon
DexDescription: They live near factories and electric generators. It bears an uncanny
  and unexplained resemblance to a Pokeball. Since it explodes at the slightest provocation,
  even veteran trainers treat it with caution.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Electrode]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Aftermath
HomeSprite: SRD-voltorb-HomeSprite.png
Image: voltorb.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sonic Boom|Sonic Boom]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Eerie Impulse|Eerie Impulse]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spark|Spark]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Screech|Screech]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge Beam|Charge Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magnet Rise|Magnet Rise]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Explosion|Explosion]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
Number: 100
ShuffleToken: SRD-voltorb-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 10.4
  Pounds: 22.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-voltorb-BookSprite.png|wsmall]]
> ![[SRD-voltorb-HomeSprite.png]]
> ![[SRD-voltorb-BoxSprite.png|htiny]]
> ![[SRD-voltorb-ShuffleToken.png|wsmall]]


*Ball Pokemon*
*They live near factories and electric generators. It bears an uncanny and unexplained resemblance to a Pokeball. Since it explodes at the slightest provocation, even veteran trainers treat it with caution.*

**DexID**:: 0100
**Name**:: Voltorb
**Type**:: Electric
**Abilities**:: [[SRD-Soundproof|Soundproof]] / [[SRD-Static|Static]] ([[SRD-Aftermath|Aftermath]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 22.9lbs / 10.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Electrode]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Voltorb.md"
flatten moves as T
where file.path = this.file.path
```
