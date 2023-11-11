---
Ability1: Aura Break
Ability2: Power Construct
BookSprite: SRD-zygarde-10-BookSprite.png
BoxSprite: SRD-zygarde-10-BoxSprite.png
DexCategory: No Data
DexDescription: When 10% of the Zygarde Cells gather, they form this Pokemon, the
  more cells it gathers the more its strength will increase.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Zyguarde cells
  Kind: Special
  Pokemon: '[[SRD-Zygarde Cell]]'
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-zygarde-10-HomeSprite.png
Image: zygarde-10.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Glare|Glare]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dig|Dig]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bind|Bind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Land''s Wrath|Land''s Wrath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Haze|Haze]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Camouflage|Camouflage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Coil|Coil]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thousand Waves|Thousand Waves]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thousand Arrows|Thousand Arrows]]'
Number: 718
ShuffleToken: SRD-zygarde-10-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 33.5
  Pounds: 73.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zygarde-10-BookSprite.png|wsmall]]
> ![[SRD-zygarde-10-HomeSprite.png]]
> ![[SRD-zygarde-10-BoxSprite.png|htiny]]
> ![[SRD-zygarde-10-ShuffleToken.png|wsmall]]


*No Data*
*When 10% of the Zygarde Cells gather, they form this Pokemon, the more cells it gathers the more its strength will increase.*

**DexID**:: 0718F1
**Name**:: Zygarde 10%
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Aura Break|Aura Break]] / [[SRD-Power Construct|Power Construct]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 73.9lbs / 33.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon              | Kind    | Item           |
|:----------|:---------------------|:--------|:---------------|
| From      | [[SRD-Zygarde Cell]] | Special | Zyguarde cells |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zygarde 10%.md"
flatten moves as T
where file.path = this.file.path
```
