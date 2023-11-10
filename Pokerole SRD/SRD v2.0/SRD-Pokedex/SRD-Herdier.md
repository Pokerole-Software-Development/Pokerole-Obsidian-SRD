---
Ability1: Intimidate
Ability2: Sand Rush
BookSprite: SRD-herdier-BookSprite.png
BoxSprite: SRD-herdier-BoxSprite.png
DexCategory: Loyal Dog Pokemon
DexDescription: "It loyally follows its Trainer\u2019s orders. For ages, they have\
  \ helped Trainers to raise well behaved Pokemon. It has black, cape-like fur that\
  \ is very hard and keeps it protected from the weather."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Lillipup]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Stoutland]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Scrappy
HomeSprite: SRD-herdier-HomeSprite.png
Image: herdier.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lick|Lick]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 507
ShuffleToken: SRD-herdier-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 14.7
  Pounds: 32.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-herdier-BookSprite.png|wsmall]]
> ![[SRD-herdier-HomeSprite.png]]
> ![[SRD-herdier-BoxSprite.png|htiny]]
> ![[SRD-herdier-ShuffleToken.png|wsmall]]


*Loyal Dog Pokemon*
*It loyally follows its Trainer’s orders. For ages, they have helped Trainers to raise well behaved Pokemon. It has black, cape-like fur that is very hard and keeps it protected from the weather.*

**DexID**:: 0507
**Name**:: Herdier
**Type**:: Normal
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Sand Rush|Sand Rush]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 32.4lbs / 14.7kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Lillipup]]  | Level  | Medium  |
| To        | [[SRD-Stoutland]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Herdier.md"
flatten moves as T
where file.path = this.file.path
```
