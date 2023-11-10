---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-kyurem-BookSprite.png
BoxSprite: SRD-kyurem-BoxSprite.png
DexCategory: No Data
DexDescription: Inside a remote and frozen cave there are some old paintings. They
  depict a giant dragon being thorn apart into a black and white shards Of the rest
  of the picture only shattered fragments of ice remain.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Kyurem (Black Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Kyurem (White Form)]]'
GenderType: N
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: ''
HomeSprite: SRD-kyurem-HomeSprite.png
Image: kyurem.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Glaciate|Glaciate]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Hail|Hail]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Power Split|Power Split]]'
Number: 646
ShuffleToken: SRD-kyurem-ShuffleToken.png
Type1: Dragon
Type2: Ice
Weight:
  Kilograms: 325.0
  Pounds: 716.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kyurem-BookSprite.png|wsmall]]
> ![[SRD-kyurem-HomeSprite.png]]
> ![[SRD-kyurem-BoxSprite.png|htiny]]
> ![[SRD-kyurem-ShuffleToken.png|wsmall]]


*No Data*
*Inside a remote and frozen cave there are some old paintings. They depict a giant dragon being thorn apart into a black and white shards Of the rest of the picture only shattered fragments of ice remain.*

**DexID**:: 0646
**Name**:: Kyurem
**Type**:: Dragon / Ice
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 716.5lbs / 325.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                     | Kind   |
|:----------|:----------------------------|:-------|
| To        | [[SRD-Kyurem (Black Form)]] | Form   |
| To        | [[SRD-Kyurem (White Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kyurem.md"
flatten moves as T
where file.path = this.file.path
```
