---
Ability1: Aura Break
Ability2: ''
BookSprite: SRD-zygarde-100-BookSprite.png
BoxSprite: SRD-zygarde-100-BoxSprite.png
DexCategory: No Data
DexDescription: The complete form of Zygarde
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Zyguarde cells
  Kind: Special
  Pokemon: '[[SRD-Zygarde Cell]]'
GenderType: N
Height:
  Feet: 14.8
  Meters: 4.5
HiddenAbility: ''
HomeSprite: SRD-zygarde-100-HomeSprite.png
Image: zygarde-100.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Glare|Glare]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Dig|Dig]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Land''s Wrath|Land''s Wrath]]'
- - Master
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Earthquake|Earthquake]]'
- - Master
  - '[[SRD-Camouflage|Camouflage]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Coil|Coil]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Thousand Waves|Thousand Waves]]'
- - Master
  - '[[SRD-Thousand Arrows|Thousand Arrows]]'
- - Master
  - '[[SRD-Core Enforcer|Core Enforcer]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
Number: 718
ShuffleToken: SRD-zygarde-100-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 610.0
  Pounds: 1344.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zygarde-100-BookSprite.png|wsmall]]
> ![[SRD-zygarde-100-HomeSprite.png]]
> ![[SRD-zygarde-100-BoxSprite.png|htiny]]
> ![[SRD-zygarde-100-ShuffleToken.png|wsmall]]


*No Data*
*The complete form of Zygarde*

**DexID**:: 0718F3
**Name**:: Zygarde 100%
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Aura Break|Aura Break]]
**Base HP**:: 11

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 14'8" / 4.5m
**Weight**: 1344.8lbs / 610.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon              | Kind    | Item           |
|:----------|:---------------------|:--------|:---------------|
| From      | [[SRD-Zygarde Cell]] | Special | Zyguarde cells |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Zygarde 100%.md"
flatten moves as T
where file.path = this.file.path
```
