---
Ability1: Steam Engine
Ability2: Flame Body
BookSprite: SRD-carkol-BookSprite.png
BoxSprite: SRD-carkol-BoxSprite.png
DexCategory: Coal Pokemon
DexDescription: It rolls its legs, their heavy weight creates parallel trackmarks
  that allow them to travel faster through caves and tunnels. In old times, people
  used Carkol's coal as fuel for they can hold fire for a long time.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rolycoly]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Coalossal]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Flash Fire
HomeSprite: SRD-carkol-HomeSprite.png
Image: carkol.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Pro
  - '[[SRD-Scald|Scald]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 838
ShuffleToken: SRD-carkol-ShuffleToken.png
Type1: Rock
Type2: Fire
Weight:
  Kilograms: 78.0
  Pounds: 172.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-carkol-BookSprite.png|wsmall]]
> ![[SRD-carkol-HomeSprite.png]]
> ![[SRD-carkol-BoxSprite.png|htiny]]
> ![[SRD-carkol-ShuffleToken.png|wsmall]]


*Coal Pokemon*
*It rolls its legs, their heavy weight creates parallel trackmarks that allow them to travel faster through caves and tunnels. In old times, people used Carkol's coal as fuel for they can hold fire for a long time.*

**DexID**:: 0838
**Name**:: Carkol
**Type**:: Rock / Fire
**Abilities**:: [[SRD-Steam Engine|Steam Engine]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 172.0lbs / 78.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Rolycoly]]  | Level  | Medium  |
| To        | [[SRD-Coalossal]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Carkol.md"
flatten moves as T
where file.path = this.file.path
```
