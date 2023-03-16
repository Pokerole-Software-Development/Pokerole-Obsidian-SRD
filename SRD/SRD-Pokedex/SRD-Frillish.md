---
Ability1: Water Absorb
Ability2: Cursed Body
BookSprite: SRD-frillish-BookSprite.png
BoxSprite: SRD-frillish-BoxSprite.png
DexCategory: Floating Pokemon
DexDescription: If a Frillish is spotted, all beaches nearby will be closed for the
  day. This Pokemon paralizes a swimming victim and wraps them, dragging them to the
  bottom of the sea. Females have pink shade.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Jellicent]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Damp
HomeSprite: SRD-frillish-HomeSprite.png
Image: frillish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Water Spout|Water Spout]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
Number: 592
ShuffleToken: SRD-frillish-ShuffleToken.png
Type1: Water
Type2: Ghost
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-frillish-BookSprite.png|wsmall]]
> ![[SRD-frillish-HomeSprite.png]]
> ![[SRD-frillish-BoxSprite.png|htiny]]
> ![[SRD-frillish-ShuffleToken.png|wsmall]]


*Floating Pokemon*
*If a Frillish is spotted, all beaches nearby will be closed for the day. This Pokemon paralizes a swimming victim and wraps them, dragging them to the bottom of the sea. Females have pink shade.*

**DexID**:: 0592
**Name**:: Frillish
**Type**:: Water / Ghost
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Cursed Body|Cursed Body]] ([[SRD-Damp|Damp]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Jellicent]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Frillish.md"
flatten moves as T
where file.path = this.file.path
```
