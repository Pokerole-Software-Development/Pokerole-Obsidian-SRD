---
Ability1: Water Veil
Ability2: Oblivious
BookSprite: SRD-wailord-BookSprite.png
BoxSprite: SRD-wailord-BoxSprite.png
DexCategory: Float Whale Pokemon
DexDescription: The largest Pokemon known to date. Wailords weight is really light
  so they can dive almost 10,000 feet with one breath. They live in open ocean herding
  fish to swallow in one gulp. They are used to being free.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wailmer]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 47.6
  Meters: 14.5
HiddenAbility: Pressure
HomeSprite: SRD-wailord-HomeSprite.png
Image: wailord.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Noble Roar|Noble Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Water Spout|Water Spout]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
Number: 321
ShuffleToken: SRD-wailord-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 398.0
  Pounds: 877.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wailord-BookSprite.png|wsmall]]
> ![[SRD-wailord-HomeSprite.png]]
> ![[SRD-wailord-BoxSprite.png|htiny]]
> ![[SRD-wailord-ShuffleToken.png|wsmall]]


*Float Whale Pokemon*
*The largest Pokemon known to date. Wailords weight is really light so they can dive almost 10,000 feet with one breath. They live in open ocean herding fish to swallow in one gulp. They are used to being free.*

**DexID**:: 0321
**Name**:: Wailord
**Type**:: Water
**Abilities**:: [[SRD-Water Veil|Water Veil]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Pressure|Pressure]])
**Base HP**:: 11

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 47'6" / 14.5m
**Weight**: 877.4lbs / 398.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Wailmer]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wailord.md"
flatten moves as T
where file.path = this.file.path
```
