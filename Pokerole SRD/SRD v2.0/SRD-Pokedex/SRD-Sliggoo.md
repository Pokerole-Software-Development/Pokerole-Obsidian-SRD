---
Ability1: Sap Sipper
Ability2: Hydration
BookSprite: SRD-sliggoo-BookSprite.png
BoxSprite: SRD-sliggoo-BoxSprite.png
DexCategory: Soft Tissue Pokemon
DexDescription: It drives away foes by releasing a sticky and corrosive liquid. Its
  eyes devolved and it became blind, now it uses its four horns to sense sounds and
  smells, rather than using its ears or nose.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Goomy]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Goodra]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Gooey
HomeSprite: SRD-sliggoo-HomeSprite.png
Image: sliggoo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bide|Bide]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rain Dance|Rain Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flail|Flail]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Counter|Counter]]'
Number: 705
ShuffleToken: SRD-sliggoo-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 17.5
  Pounds: 38.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sliggoo-BookSprite.png|wsmall]]
> ![[SRD-sliggoo-HomeSprite.png]]
> ![[SRD-sliggoo-BoxSprite.png|htiny]]
> ![[SRD-sliggoo-ShuffleToken.png|wsmall]]


*Soft Tissue Pokemon*
*It drives away foes by releasing a sticky and corrosive liquid. Its eyes devolved and it became blind, now it uses its four horns to sense sounds and smells, rather than using its ears or nose.*

**DexID**:: 0705
**Name**:: Sliggoo
**Type**:: Dragon
**Abilities**:: [[SRD-Sap Sipper|Sap Sipper]] / [[SRD-Hydration|Hydration]] ([[SRD-Gooey|Gooey]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'6" / 0.8m
**Weight**: 38.6lbs / 17.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Goomy]]  | Level  | Medium  |
| To        | [[SRD-Goodra]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sliggoo.md"
flatten moves as T
where file.path = this.file.path
```
