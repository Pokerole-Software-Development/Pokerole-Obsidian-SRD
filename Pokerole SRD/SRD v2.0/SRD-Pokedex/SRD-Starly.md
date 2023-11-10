---
Ability1: Keen Eye
Ability2: ''
BookSprite: SRD-starly-BookSprite.png
BoxSprite: SRD-starly-BoxSprite.png
DexCategory: Starling Pokemon
DexDescription: They flock in dozens because they are very weak on their own. They
  live around mountains and fields, chasing Bug Pokemon. Everyone hates their annoying
  and strident singing.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Staravia]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Reckless
HomeSprite: SRD-starly-HomeSprite.png
Image: starly.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Astonish|Astonish]]'
- - Pro
  - '[[SRD-Work Up|Work Up]]'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
Number: 396
ShuffleToken: SRD-starly-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-starly-BookSprite.png|wsmall]]
> ![[SRD-starly-HomeSprite.png]]
> ![[SRD-starly-BoxSprite.png|htiny]]
> ![[SRD-starly-ShuffleToken.png|wsmall]]


*Starling Pokemon*
*They flock in dozens because they are very weak on their own. They live around mountains and fields, chasing Bug Pokemon. Everyone hates their annoying and strident singing.*

**DexID**:: 0396
**Name**:: Starly
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Staravia]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Starly.md"
flatten moves as T
where file.path = this.file.path
```
