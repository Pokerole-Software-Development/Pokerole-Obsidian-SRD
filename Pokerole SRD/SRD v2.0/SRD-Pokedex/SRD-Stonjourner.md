---
Ability1: Power Spot
Ability2: ''
BookSprite: SRD-stonjourner-BookSprite.png
BoxSprite: SRD-stonjourner-BoxSprite.png
DexCategory: Big Rock Pokemon
DexDescription: They spend almost all their lives immobile, looking as inconspicuous
  rocks, but once a year they gather out of nowhere and form up in a circle. They
  stay in formation for a few days and then disappear overnight.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-stonjourner-HomeSprite.png
Image: stonjourner.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Throw|Rock Throw]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Block|Block]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Tomb|Rock Tomb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gravity|Gravity]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Kick|Mega Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Crash|Heat Crash]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomping Tantrum|Stomping Tantrum]]'
Number: 874
ShuffleToken: SRD-stonjourner-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 520.0
  Pounds: 1146.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stonjourner-BookSprite.png|wsmall]]
> ![[SRD-stonjourner-HomeSprite.png]]
> ![[SRD-stonjourner-BoxSprite.png|htiny]]
> ![[SRD-stonjourner-ShuffleToken.png|wsmall]]


*Big Rock Pokemon*
*They spend almost all their lives immobile, looking as inconspicuous rocks, but once a year they gather out of nowhere and form up in a circle. They stay in formation for a few days and then disappear overnight.*

**DexID**:: 0874
**Name**:: Stonjourner
**Type**:: Rock
**Abilities**:: [[SRD-Power Spot|Power Spot]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 8'2" / 2.5m
**Weight**: 1146.4lbs / 520.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Stonjourner.md"
flatten moves as T
where file.path = this.file.path
```
