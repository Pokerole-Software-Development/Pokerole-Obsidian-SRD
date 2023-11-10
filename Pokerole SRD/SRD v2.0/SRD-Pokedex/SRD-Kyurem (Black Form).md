---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-kyurem-black-form-BookSprite.png
BoxSprite: SRD-kyurem-black-form-BoxSprite.png
DexCategory: No Data
DexDescription: In the Icy mountains at the east of Unova, you can hear the wails
  of a creature suffering as if it missed a part of its very soul. Dark clouds and
  lightning are sure to follow.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Kyurem]]'
GenderType: N
Height:
  Feet: 10.8
  Meters: 3.3
HiddenAbility: ''
HomeSprite: SRD-kyurem-black-form-HomeSprite.png
Image: kyurem-black-form.png
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
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Wish|Wish]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Fusion Bolt|Fusion Bolt]]'
- - Master
  - '[[SRD-Bolt Strike|Bolt Strike]]'
Number: 646
ShuffleToken: SRD-kyurem-black-form-ShuffleToken.png
Type1: Dragon
Type2: Ice
Weight:
  Kilograms: 325.0
  Pounds: 716.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kyurem-black-form-BookSprite.png|wsmall]]
> ![[SRD-kyurem-black-form-HomeSprite.png]]
> ![[SRD-kyurem-black-form-BoxSprite.png|htiny]]
> ![[SRD-kyurem-black-form-ShuffleToken.png|wsmall]]


*No Data*
*In the Icy mountains at the east of Unova, you can hear the wails of a creature suffering as if it missed a part of its very soul. Dark clouds and lightning are sure to follow.*

**DexID**:: 0646F1
**Name**:: Kyurem (Black Form)
**Type**:: Dragon / Ice
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 10'8" / 3.3m
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kyurem (Black Form).md"
flatten moves as T
where file.path = this.file.path
```
