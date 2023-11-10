---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-kyurem-white-form-BookSprite.png
BoxSprite: SRD-kyurem-white-form-BoxSprite.png
DexCategory: No Data
DexDescription: In the Icy mountains at the west of Unova, you can hear the wails
  of a creature suffering as if it missed a part of its very soul. Explosions and
  blue fires are sure to follow.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Kyurem]]'
GenderType: N
Height:
  Feet: 11.8
  Meters: 3.6
HiddenAbility: ''
HomeSprite: SRD-kyurem-white-form-HomeSprite.png
Image: kyurem-white-form.png
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
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Wish|Wish]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Fusion Flare|Fusion Flare]]'
- - Master
  - '[[SRD-Blue Flare|Blue Flare]]'
Number: 646
ShuffleToken: SRD-kyurem-white-form-ShuffleToken.png
Type1: Dragon
Type2: Ice
Weight:
  Kilograms: 325.0
  Pounds: 716.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kyurem-white-form-BookSprite.png|wsmall]]
> ![[SRD-kyurem-white-form-HomeSprite.png]]
> ![[SRD-kyurem-white-form-BoxSprite.png|htiny]]
> ![[SRD-kyurem-white-form-ShuffleToken.png|wsmall]]


*No Data*
*In the Icy mountains at the west of Unova, you can hear the wails of a creature suffering as if it missed a part of its very soul. Explosions and blue fires are sure to follow.*

**DexID**:: 0646F2
**Name**:: Kyurem (White Form)
**Type**:: Dragon / Ice
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::9)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 11'8" / 3.6m
**Weight**: 716.5lbs / 325.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Kyurem]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kyurem (White Form).md"
flatten moves as T
where file.path = this.file.path
```
