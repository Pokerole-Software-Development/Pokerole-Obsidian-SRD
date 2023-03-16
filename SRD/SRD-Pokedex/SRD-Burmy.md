---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-burmy-BookSprite.png
BoxSprite: SRD-burmy-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: This Pokemon has adapted to live in the forests, deserts and in the
  city. It makes a cloak with the materials close to it to protect itself from the
  weather. Males evolve into a Mothim and females into a Wormadam.
EventAbilities: ''
Evolutions:
- Evolves: To
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Wormadam (Grass Form)]]'
  Speed: Fast
- Evolves: To
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Wormadam (Steel Form)]]'
  Speed: Fast
- Evolves: To
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Wormadam (Ground Form)]]'
  Speed: Fast
- Evolves: To
  Gender: Male
  Kind: Level
  Pokemon: '[[SRD-Mothim]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Overcoat
HomeSprite: SRD-burmy-HomeSprite.png
Image: burmy.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-String Shot|String Shot]]'
Number: 412
ShuffleToken: SRD-burmy-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 3.4
  Pounds: 7.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-burmy-BookSprite.png|wsmall]]
> ![[SRD-burmy-HomeSprite.png]]
> ![[SRD-burmy-BoxSprite.png|htiny]]
> ![[SRD-burmy-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*This Pokemon has adapted to live in the forests, deserts and in the city. It makes a cloak with the materials close to it to protect itself from the weather. Males evolve into a Mothim and females into a Wormadam.*

**DexID**:: 0412
**Name**:: Burmy
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 7.5lbs / 3.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon                        | Kind   | Speed   | Gender   |
|:----------|:-------------------------------|:-------|:--------|:---------|
| To        | [[SRD-Wormadam (Grass Form)]]  | Level  | Fast    | Female   |
| To        | [[SRD-Wormadam (Steel Form)]]  | Level  | Fast    | Female   |
| To        | [[SRD-Wormadam (Ground Form)]] | Level  | Fast    | Female   |
| To        | [[SRD-Mothim]]                 | Level  | Fast    | Male     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Burmy.md"
flatten moves as T
where file.path = this.file.path
```
