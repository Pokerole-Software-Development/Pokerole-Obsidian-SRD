---
Ability1: Mold Breaker
Ability2: ''
BookSprite: SRD-ampharos-mega-form-BookSprite.png
BoxSprite: SRD-ampharos-mega-form-BoxSprite.png
DexCategory: Light Pokemon
DexDescription: With the power of the Mega Stone the dormant dragon genes it has are
  awakened. Its wool grows back as a silky mane that flows and floats with the electricity
  its body is discharging.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Ampharosite
  Kind: Mega
  Pokemon: '[[SRD-Ampharos]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-ampharos-mega-form-HomeSprite.png
Image: ampharos-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Amateur
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 181
ShuffleToken: SRD-ampharos-mega-form-ShuffleToken.png
Type1: Electric
Type2: Dragon
Weight:
  Kilograms: 61.5
  Pounds: 135.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ampharos-mega-form-BookSprite.png|wsmall]]
> ![[SRD-ampharos-mega-form-HomeSprite.png]]
> ![[SRD-ampharos-mega-form-BoxSprite.png|htiny]]
> ![[SRD-ampharos-mega-form-ShuffleToken.png|wsmall]]


*Light Pokemon*
*With the power of the Mega Stone the dormant dragon genes it has are awakened. Its wool grows back as a silky mane that flows and floats with the electricity its body is discharging.*

**DexID**:: 0181M1
**Name**:: Ampharos (Mega Form)
**Type**:: Electric / Dragon
**Abilities**:: [[SRD-Mold Breaker|Mold Breaker]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 135.6lbs / 61.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Ampharos]] | Mega   | Ampharosite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ampharos (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
