---
Ability1: Illuminate
Ability2: Natural Cure
BookSprite: SRD-starmie-BookSprite.png
BoxSprite: SRD-starmie-BoxSprite.png
DexCategory: Mysterious Pokemon
DexDescription: "This Pokemon has been given the nickname \u201Cthe gem of the sea.\u201D\
  \ It swims through water by spinning its star-shaped body as if it were a propeller\
  \ on a ship. The core at the center glows with different colors."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Staryu]]'
GenderType: N
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Analytic
HomeSprite: SRD-starmie-HomeSprite.png
Image: starmie.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spotlight|Spotlight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
Number: 121
ShuffleToken: SRD-starmie-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 80.0
  Pounds: 176.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-starmie-BookSprite.png|wsmall]]
> ![[SRD-starmie-HomeSprite.png]]
> ![[SRD-starmie-BoxSprite.png|htiny]]
> ![[SRD-starmie-ShuffleToken.png|wsmall]]


*Mysterious Pokemon*
*This Pokemon has been given the nickname “the gem of the sea.” It swims through water by spinning its star-shaped body as if it were a propeller on a ship. The core at the center glows with different colors.*

**DexID**:: 0121
**Name**:: Starmie
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Illuminate|Illuminate]] / [[SRD-Natural Cure|Natural Cure]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 176.4lbs / 80.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Item        |
|:----------|:---------------|:-------|:------------|
| From      | [[SRD-Staryu]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Starmie.md"
flatten moves as T
where file.path = this.file.path
```
