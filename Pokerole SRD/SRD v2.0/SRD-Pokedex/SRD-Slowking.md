---
Ability1: Oblivious
Ability2: Own Tempo
BookSprite: SRD-slowking-BookSprite.png
BoxSprite: SRD-slowking-BoxSprite.png
DexCategory: Royal Pokemon
DexDescription: It is extremely rare. The Shellder on its head injects a poison that
  made it super intelligent. It takes a lot of interest in learning about Pokemon
  lore and legends. But if Shellder is knocked out it will forget everything.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: King's Rock
  Kind: Trade
  Pokemon: '[[SRD-Slowpoke]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Regenerator
HomeSprite: SRD-slowking-HomeSprite.png
Image: slowking.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Ace
  - '[[SRD-Trump Card|Trump Card]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Brine|Brine]]'
Number: 199
ShuffleToken: SRD-slowking-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 79.5
  Pounds: 175.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowking-BookSprite.png|wsmall]]
> ![[SRD-slowking-HomeSprite.png]]
> ![[SRD-slowking-BoxSprite.png|htiny]]
> ![[SRD-slowking-ShuffleToken.png|wsmall]]


*Royal Pokemon*
*It is extremely rare. The Shellder on its head injects a poison that made it super intelligent. It takes a lot of interest in learning about Pokemon lore and legends. But if Shellder is knocked out it will forget everything.*

**DexID**:: 0199
**Name**:: Slowking
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 175.3lbs / 79.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Slowpoke]] | Trade  | King's Rock |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slowking.md"
flatten moves as T
where file.path = this.file.path
```
