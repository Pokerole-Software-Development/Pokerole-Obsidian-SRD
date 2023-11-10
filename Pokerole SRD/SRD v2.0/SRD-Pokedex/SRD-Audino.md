---
Ability1: Healer
Ability2: Regenerator
BookSprite: SRD-audino-BookSprite.png
BoxSprite: SRD-audino-BoxSprite.png
DexCategory: Hearing Pokemon
DexDescription: "Its auditory sense is astounding, using the feelers on it\u2019s\
  \ ears it can know the health state of others. It is a caring Pokemon with a sweet\
  \ disposition to help, but it is not too common to see in the wild."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Audinite
  Kind: Mega
  Pokemon: '[[SRD-Audino (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Klutz
HomeSprite: SRD-audino-HomeSprite.png
Image: audino.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Beginner
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Secret Power|Secret Power]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Entrainment|Entrainment]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
Number: 531
ShuffleToken: SRD-audino-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 31.0
  Pounds: 68.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-audino-BookSprite.png|wsmall]]
> ![[SRD-audino-HomeSprite.png]]
> ![[SRD-audino-BoxSprite.png|htiny]]
> ![[SRD-audino-ShuffleToken.png|wsmall]]


*Hearing Pokemon*
*Its auditory sense is astounding, using the feelers on it’s ears it can know the health state of others. It is a caring Pokemon with a sweet disposition to help, but it is not too common to see in the wild.*

**DexID**:: 0531
**Name**:: Audino
**Type**:: Normal
**Abilities**:: [[SRD-Healer|Healer]] / [[SRD-Regenerator|Regenerator]] ([[SRD-Klutz|Klutz]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 68.3lbs / 31.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                    | Kind   | Item     |
|:----------|:---------------------------|:-------|:---------|
| To        | [[SRD-Audino (Mega Form)]] | Mega   | Audinite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Audino.md"
flatten moves as T
where file.path = this.file.path
```
