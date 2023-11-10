---
Ability1: Refrigerate
Ability2: ''
BookSprite: SRD-aurorus-BookSprite.png
BoxSprite: SRD-aurorus-BoxSprite.png
DexCategory: Tundra Pokemon
DexDescription: It produced a freezing cold mist from the crystals on its sides and
  relied on size to deter predators. It also created tall walls of ice to block them.
  The one restored from the fossil is calm and has adapted well.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Amaura]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 8.9
  Meters: 2.7
HiddenAbility: Snow Warning
HomeSprite: SRD-aurorus-HomeSprite.png
Image: aurorus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Nature Power|Nature Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Encore|Encore]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Discharge|Discharge]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 699
ShuffleToken: SRD-aurorus-ShuffleToken.png
Type1: Rock
Type2: Ice
Weight:
  Kilograms: 225.0
  Pounds: 496.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aurorus-BookSprite.png|wsmall]]
> ![[SRD-aurorus-HomeSprite.png]]
> ![[SRD-aurorus-BoxSprite.png|htiny]]
> ![[SRD-aurorus-ShuffleToken.png|wsmall]]


*Tundra Pokemon*
*It produced a freezing cold mist from the crystals on its sides and relied on size to deter predators. It also created tall walls of ice to block them. The one restored from the fossil is calm and has adapted well.*

**DexID**:: 0699
**Name**:: Aurorus
**Type**:: Rock / Ice
**Abilities**:: [[SRD-Refrigerate|Refrigerate]] ([[SRD-Snow Warning|Snow Warning]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 8'9" / 2.7m
**Weight**: 496.0lbs / 225.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Amaura]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aurorus.md"
flatten moves as T
where file.path = this.file.path
```
