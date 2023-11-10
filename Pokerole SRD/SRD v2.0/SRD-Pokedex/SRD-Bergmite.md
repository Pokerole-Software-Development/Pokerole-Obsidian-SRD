---
Ability1: Own Tempo
Ability2: Ice Body
BookSprite: SRD-bergmite-BookSprite.png
BoxSprite: SRD-bergmite-BoxSprite.png
DexCategory: Ice Chunk Pokemon
DexDescription: They live in small herds close to the mountains. It blocks attacks
  with the ice that shields its body and uses cold air to repair any cracks with new
  ice. They are wary of humans as they rarely get to see one.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Avalugg]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sturdy
HomeSprite: SRD-bergmite-HomeSprite.png
Image: bergmite.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sharpen|Sharpen]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 712
ShuffleToken: SRD-bergmite-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 99.5
  Pounds: 219.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bergmite-BookSprite.png|wsmall]]
> ![[SRD-bergmite-HomeSprite.png]]
> ![[SRD-bergmite-BoxSprite.png|htiny]]
> ![[SRD-bergmite-ShuffleToken.png|wsmall]]


*Ice Chunk Pokemon*
*They live in small herds close to the mountains. It blocks attacks with the ice that shields its body and uses cold air to repair any cracks with new ice. They are wary of humans as they rarely get to see one.*

**DexID**:: 0712
**Name**:: Bergmite
**Type**:: Ice
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 219.4lbs / 99.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Avalugg]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bergmite.md"
flatten moves as T
where file.path = this.file.path
```
