---
Ability1: Rivalry
Ability2: Intimidate
BookSprite: SRD-luxio-BookSprite.png
BoxSprite: SRD-luxio-BoxSprite.png
DexCategory: Spark Pokemon
DexDescription: Female Luxios stay with the pride but males roam in marauding groups,
  trying to become strong enough to make their own pride. Its claws and teeth are
  charged with electricity, approach with caution.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shinx]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Luxray]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Guts
HomeSprite: SRD-luxio-HomeSprite.png
Image: luxio.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Howl|Howl]]'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
Number: 404
ShuffleToken: SRD-luxio-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 30.5
  Pounds: 67.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-luxio-BookSprite.png|wsmall]]
> ![[SRD-luxio-HomeSprite.png]]
> ![[SRD-luxio-BoxSprite.png|htiny]]
> ![[SRD-luxio-ShuffleToken.png|wsmall]]


*Spark Pokemon*
*Female Luxios stay with the pride but males roam in marauding groups, trying to become strong enough to make their own pride. Its claws and teeth are charged with electricity, approach with caution.*

**DexID**:: 0404
**Name**:: Luxio
**Type**:: Electric
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Intimidate|Intimidate]] ([[SRD-Guts|Guts]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 67.2lbs / 30.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Shinx]]  | Level  | Medium  |
| To        | [[SRD-Luxray]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Luxio.md"
flatten moves as T
where file.path = this.file.path
```
