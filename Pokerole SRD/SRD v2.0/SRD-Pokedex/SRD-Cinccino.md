---
Ability1: Cute Charm
Ability2: Technician
BookSprite: SRD-cinccino-BookSprite.png
BoxSprite: SRD-cinccino-BoxSprite.png
DexCategory: Scarf Pokemon
DexDescription: Their fur feels amazing to the touch. It produces an oil that repels
  dust and prevents static electricity from building up. It loves to be groomed and
  pampered. The fur it sheds is highly valued.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Minccino]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Skill Link
HomeSprite: SRD-cinccino-HomeSprite.png
Image: cinccino.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Tail Slap|Tail Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 573
ShuffleToken: SRD-cinccino-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 7.5
  Pounds: 16.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cinccino-BookSprite.png|wsmall]]
> ![[SRD-cinccino-HomeSprite.png]]
> ![[SRD-cinccino-BoxSprite.png|htiny]]
> ![[SRD-cinccino-ShuffleToken.png|wsmall]]


*Scarf Pokemon*
*Their fur feels amazing to the touch. It produces an oil that repels dust and prevents static electricity from building up. It loves to be groomed and pampered. The fur it sheds is highly valued.*

**DexID**:: 0573
**Name**:: Cinccino
**Type**:: Normal
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Technician|Technician]] ([[SRD-Skill Link|Skill Link]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 16.5lbs / 7.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Minccino]] | Stone  | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cinccino.md"
flatten moves as T
where file.path = this.file.path
```
