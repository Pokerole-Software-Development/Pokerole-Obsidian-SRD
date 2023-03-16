---
Ability1: Flash Fire
Ability2: Flame Body
BookSprite: SRD-lampent-BookSprite.png
BoxSprite: SRD-lampent-BoxSprite.png
DexCategory: Lamp Pokemon
DexDescription: "This ominous Pokemon is very feared. It always arrives at someone\u2019\
  s final moments and steals their spirit. It hangs close to hospitals and other places\
  \ simply waiting. It is said that if it gets your soul you will never rest."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Litwick]]'
  Speed: Medium
- Evolves: To
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Chandelure]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Infiltrator
HomeSprite: SRD-lampent-HomeSprite.png
Image: lampent.png
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
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
Number: 608
ShuffleToken: SRD-lampent-ShuffleToken.png
Type1: Ghost
Type2: Fire
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lampent-BookSprite.png|wsmall]]
> ![[SRD-lampent-HomeSprite.png]]
> ![[SRD-lampent-BoxSprite.png|htiny]]
> ![[SRD-lampent-ShuffleToken.png|wsmall]]


*Lamp Pokemon*
*This ominous Pokemon is very feared. It always arrives at someone’s final moments and steals their spirit. It hangs close to hospitals and other places simply waiting. It is said that if it gets your soul you will never rest.*

**DexID**:: 0608
**Name**:: Lampent
**Type**:: Ghost / Fire
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   | Item       |
|:----------|:-------------------|:-------|:--------|:-----------|
| From      | [[SRD-Litwick]]    | Level  | Medium  |            |
| To        | [[SRD-Chandelure]] | Stone  |         | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lampent.md"
flatten moves as T
where file.path = this.file.path
```
