---
Ability1: Flash Fire
Ability2: Flame Body
BookSprite: SRD-litwick-BookSprite.png
BoxSprite: SRD-litwick-BoxSprite.png
DexCategory: Candle Pokemon
DexDescription: Its flame is usually out, but it starts burning whenever it absorbs
  the life force from others. They trick lost people into thinking they are helping
  them find their way in the dark but those who follow them never return.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lampent]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Infiltrator
HomeSprite: SRD-litwick-HomeSprite.png
Image: litwick.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Minimize|Minimize]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Curse|Curse]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
Number: 607
ShuffleToken: SRD-litwick-ShuffleToken.png
Type1: Ghost
Type2: Fire
Weight:
  Kilograms: 3.1
  Pounds: 6.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-litwick-BookSprite.png|wsmall]]
> ![[SRD-litwick-HomeSprite.png]]
> ![[SRD-litwick-BoxSprite.png|htiny]]
> ![[SRD-litwick-ShuffleToken.png|wsmall]]


*Candle Pokemon*
*Its flame is usually out, but it starts burning whenever it absorbs the life force from others. They trick lost people into thinking they are helping them find their way in the dark but those who follow them never return.*

**DexID**:: 0607
**Name**:: Litwick
**Type**:: Ghost / Fire
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 6.8lbs / 3.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Lampent]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Litwick.md"
flatten moves as T
where file.path = this.file.path
```
