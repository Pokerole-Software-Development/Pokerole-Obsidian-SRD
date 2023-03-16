---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-popplio-BookSprite.png
BoxSprite: SRD-popplio-BoxSprite.png
DexCategory: Sea Lion Pokemon
DexDescription: A fun-loving Pokemon. It snorts water bubbles from its nose and balances
  them around, it is tenacious and diligent to train. They are agile swimmers and
  prefer acrobatic stunts to move on the ground.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Brionne]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Liquid Voice
HomeSprite: SRD-popplio-HomeSprite.png
Image: popplio.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 728
ShuffleToken: SRD-popplio-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 7.5
  Pounds: 16.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-popplio-BookSprite.png|wsmall]]
> ![[SRD-popplio-HomeSprite.png]]
> ![[SRD-popplio-BoxSprite.png|htiny]]
> ![[SRD-popplio-ShuffleToken.png|wsmall]]


*Sea Lion Pokemon*
*A fun-loving Pokemon. It snorts water bubbles from its nose and balances them around, it is tenacious and diligent to train. They are agile swimmers and prefer acrobatic stunts to move on the ground.*

**DexID**:: 0728
**Name**:: Popplio
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Liquid Voice|Liquid Voice]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 16.5lbs / 7.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Brionne]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Popplio.md"
flatten moves as T
where file.path = this.file.path
```
