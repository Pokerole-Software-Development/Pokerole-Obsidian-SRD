---
Ability1: Water Absorb
Ability2: Cursed Body
BookSprite: SRD-jellicent-BookSprite.png
BoxSprite: SRD-jellicent-BoxSprite.png
DexCategory: Floating Pokemon
DexDescription: 'Its body is mostly seawater. It feeds on the life energy of its victims.
  It is regal, pompous, and hates orders. The fate of the ships and crew that wander
  into Jellicent''s territory: All sunken, all lost, all vanished.'
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Frillish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Damp
HomeSprite: SRD-jellicent-HomeSprite.png
Image: jellicent.png
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
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Water Spout|Water Spout]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
Number: 593
ShuffleToken: SRD-jellicent-ShuffleToken.png
Type1: Water
Type2: Ghost
Weight:
  Kilograms: 135.0
  Pounds: 297.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jellicent-BookSprite.png|wsmall]]
> ![[SRD-jellicent-HomeSprite.png]]
> ![[SRD-jellicent-BoxSprite.png|htiny]]
> ![[SRD-jellicent-ShuffleToken.png|wsmall]]


*Floating Pokemon*
*Its body is mostly seawater. It feeds on the life energy of its victims. It is regal, pompous, and hates orders. The fate of the ships and crew that wander into Jellicent's territory: All sunken, all lost, all vanished.*

**DexID**:: 0593
**Name**:: Jellicent
**Type**:: Water / Ghost
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Cursed Body|Cursed Body]] ([[SRD-Damp|Damp]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 7'2" / 2.2m
**Weight**: 297.6lbs / 135.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Frillish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jellicent.md"
flatten moves as T
where file.path = this.file.path
```
