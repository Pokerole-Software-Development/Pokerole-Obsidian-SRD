---
Ability1: Cute Charm
Ability2: Competitive
BookSprite: SRD-wigglytuff-BookSprite.png
BoxSprite: SRD-wigglytuff-BoxSprite.png
DexCategory: Balloon Pokemon
DexDescription: Its fur is extremely fine and conveys an image of luxury. Its body
  is soft and rubbery. When angered, it will suck the air and inflate itself to an
  enormous size. It is a favorite pet and a nurse Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Jigglypuff]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Frisk
HomeSprite: SRD-wigglytuff-HomeSprite.png
Image: wigglytuff.png
Legendary: 'No'
Moves:
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
Number: 40
ShuffleToken: SRD-wigglytuff-ShuffleToken.png
Type1: Normal
Type2: Fairy
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wigglytuff-BookSprite.png|wsmall]]
> ![[SRD-wigglytuff-HomeSprite.png]]
> ![[SRD-wigglytuff-BoxSprite.png|htiny]]
> ![[SRD-wigglytuff-ShuffleToken.png|wsmall]]


*Balloon Pokemon*
*Its fur is extremely fine and conveys an image of luxury. Its body is soft and rubbery. When angered, it will suck the air and inflate itself to an enormous size. It is a favorite pet and a nurse Pokemon.*

**DexID**:: 0040
**Name**:: Wigglytuff
**Type**:: Normal / Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Competitive|Competitive]] ([[SRD-Frisk|Frisk]])
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Item       |
|:----------|:-------------------|:-------|:-----------|
| From      | [[SRD-Jigglypuff]] | Stone  | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Wigglytuff.md"
flatten moves as T
where file.path = this.file.path
```
