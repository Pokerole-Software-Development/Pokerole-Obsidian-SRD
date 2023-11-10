---
Ability1: Steadfast
Ability2: Inner Focus
BookSprite: SRD-riolu-BookSprite.png
BoxSprite: SRD-riolu-BoxSprite.png
DexCategory: Emanation Pokemon
DexDescription: "Scarce in the wild but they have been seen in the mountains. It has\
  \ the ability to see the auras of others, through this power it is capable of sensing\
  \ emotions. It won\u2019t get close to those with selfish intentions."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Lucario]]'
  Stat: Loyalty
  Value: 5
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Prankster
HomeSprite: SRD-riolu-HomeSprite.png
Image: riolu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Aura Sphere|Aura Sphere]]'
Number: 447
ShuffleToken: SRD-riolu-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 20.2
  Pounds: 44.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-riolu-BookSprite.png|wsmall]]
> ![[SRD-riolu-HomeSprite.png]]
> ![[SRD-riolu-BoxSprite.png|htiny]]
> ![[SRD-riolu-ShuffleToken.png|wsmall]]


*Emanation Pokemon*
*Scarce in the wild but they have been seen in the mountains. It has the ability to see the auras of others, through this power it is capable of sensing emotions. It won’t get close to those with selfish intentions.*

**DexID**:: 0447
**Name**:: Riolu
**Type**:: Fighting
**Abilities**:: [[SRD-Steadfast|Steadfast]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 44.5lbs / 20.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Stat    |   Value |
|:----------|:----------------|:-------|:--------|--------:|
| To        | [[SRD-Lucario]] | Stat   | Loyalty |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Riolu.md"
flatten moves as T
where file.path = this.file.path
```
