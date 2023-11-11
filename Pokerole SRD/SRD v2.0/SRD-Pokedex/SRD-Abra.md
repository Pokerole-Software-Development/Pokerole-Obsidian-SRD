---
Ability1: Synchronize
Ability2: Inner Focus
BookSprite: SRD-abra-BookSprite.png
BoxSprite: SRD-abra-BoxSprite.png
DexCategory: Psi Pokemon
DexDescription: "They are attracted to the cities and tend to live close to humans.\
  \ Its Psychic abilities are still developing, it can sleep up to 18 hours a day\
  \ or else it won\u2019t be able to use them. When in danger, it teleports away."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kadabra]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Magic Guard
HomeSprite: SRD-abra-HomeSprite.png
Image: abra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mimic|Mimic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Signal Beam|Signal Beam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metronome|Metronome]]'
Number: 63
ShuffleToken: SRD-abra-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-abra-BookSprite.png|wsmall]]
> ![[SRD-abra-HomeSprite.png]]
> ![[SRD-abra-BoxSprite.png|htiny]]
> ![[SRD-abra-ShuffleToken.png|wsmall]]


*Psi Pokemon*
*They are attracted to the cities and tend to live close to humans. Its Psychic abilities are still developing, it can sleep up to 18 hours a day or else it won’t be able to use them. When in danger, it teleports away.*

**DexID**:: 0063
**Name**:: Abra
**Type**:: Psychic
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Magic Guard|Magic Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'0" / 0.9m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Kadabra]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Abra.md"
flatten moves as T
where file.path = this.file.path
```
