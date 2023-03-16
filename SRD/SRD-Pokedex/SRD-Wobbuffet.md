---
Ability1: Shadow Tag
Ability2: ''
BookSprite: SRD-wobbuffet-BookSprite.png
BoxSprite: SRD-wobbuffet-BoxSprite.png
DexCategory: Patient Pokemon
DexDescription: Wobbuffet looks somewhat deflated until it senses an aggressor, then
  it inflates. It will do nothing besides endure and counter attacks. It always keeps
  its black tail hidden, the reasons are still a mystery.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wynaut]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Telepathy
HomeSprite: SRD-wobbuffet-HomeSprite.png
Image: wobbuffet.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 202
ShuffleToken: SRD-wobbuffet-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 28.5
  Pounds: 62.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wobbuffet-BookSprite.png|wsmall]]
> ![[SRD-wobbuffet-HomeSprite.png]]
> ![[SRD-wobbuffet-BoxSprite.png|htiny]]
> ![[SRD-wobbuffet-ShuffleToken.png|wsmall]]


*Patient Pokemon*
*Wobbuffet looks somewhat deflated until it senses an aggressor, then it inflates. It will do nothing besides endure and counter attacks. It always keeps its black tail hidden, the reasons are still a mystery.*

**DexID**:: 0202
**Name**:: Wobbuffet
**Type**:: Psychic
**Abilities**:: [[SRD-Shadow Tag|Shadow Tag]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 9

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 62.8lbs / 28.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Wynaut]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Wobbuffet.md"
flatten moves as T
where file.path = this.file.path
```
