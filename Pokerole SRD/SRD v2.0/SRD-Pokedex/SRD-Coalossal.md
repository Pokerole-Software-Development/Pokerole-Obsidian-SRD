---
Ability1: Steam Engine
Ability2: Flame Body
BookSprite: SRD-coalossal-BookSprite.png
BoxSprite: SRD-coalossal-BoxSprite.png
DexCategory: Coal Pokemon
DexDescription: "They are usually calm creatures, if they see you are kind they\u2019\
  ll share their warmth with you but if you enrage one you risk being burned down\
  \ to ashes. They spit tarry substance that is very flammable."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Carkol]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 9.2
  Meters: 2.8
HiddenAbility: Flash Fire
HomeSprite: SRD-coalossal-HomeSprite.png
Image: coalossal.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Flame Charge|Flame Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tar Shot|Tar Shot]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Incinerate|Incinerate]]'
- - Ace
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Ace
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Overheat|Overheat]]'
- - Pro
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Pro
  - '[[SRD-Heavy Slam|Heavy Slam]]'
Number: 839
ShuffleToken: SRD-coalossal-ShuffleToken.png
Type1: Rock
Type2: Fire
Weight:
  Kilograms: 310.5
  Pounds: 684.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-coalossal-BookSprite.png|wsmall]]
> ![[SRD-coalossal-HomeSprite.png]]
> ![[SRD-coalossal-BoxSprite.png|htiny]]
> ![[SRD-coalossal-ShuffleToken.png|wsmall]]


*Coal Pokemon*
*They are usually calm creatures, if they see you are kind they’ll share their warmth with you but if you enrage one you risk being burned down to ashes. They spit tarry substance that is very flammable.*

**DexID**:: 0839
**Name**:: Coalossal
**Type**:: Rock / Fire
**Abilities**:: [[SRD-Steam Engine|Steam Engine]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'2" / 2.8m
**Weight**: 684.5lbs / 310.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Carkol]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Coalossal.md"
flatten moves as T
where file.path = this.file.path
```
