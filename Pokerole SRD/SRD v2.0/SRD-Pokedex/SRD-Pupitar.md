---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-pupitar-BookSprite.png
BoxSprite: SRD-pupitar-BoxSprite.png
DexCategory: Hard Shell Pokemon
DexDescription: Even in their shell, they are fast, aggressive and extremely destructive.
  They never stay still. This pupa propels itself using a jet of pressurized gas.
  It is bad tempered and very aggressive.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Larvitar]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tyranitar]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-pupitar-HomeSprite.png
Image: pupitar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
Number: 247
ShuffleToken: SRD-pupitar-ShuffleToken.png
Type1: Rock
Type2: Ground
Weight:
  Kilograms: 152.0
  Pounds: 335.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pupitar-BookSprite.png|wsmall]]
> ![[SRD-pupitar-HomeSprite.png]]
> ![[SRD-pupitar-BoxSprite.png|htiny]]
> ![[SRD-pupitar-ShuffleToken.png|wsmall]]


*Hard Shell Pokemon*
*Even in their shell, they are fast, aggressive and extremely destructive. They never stay still. This pupa propels itself using a jet of pressurized gas. It is bad tempered and very aggressive.*

**DexID**:: 0247
**Name**:: Pupitar
**Type**:: Rock / Ground
**Abilities**:: [[SRD-Shed Skin|Shed Skin]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 335.1lbs / 152.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Larvitar]]  | Level  | Slow    |
| To        | [[SRD-Tyranitar]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pupitar.md"
flatten moves as T
where file.path = this.file.path
```
