---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-beldum-BookSprite.png
BoxSprite: SRD-beldum-BoxSprite.png
DexCategory: Iron Ball Pokemon
DexDescription: Beldum uses magnetic pulses to float and communicate. When it finds
  others, they move in perfect unison. It needs to develop a new brain to evolve;
  two of them may merge or it could develop a new one with time.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Metang]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Light Metal
HomeSprite: SRD-beldum-HomeSprite.png
Image: beldum.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Headbutt|Headbutt]]'
Number: 374
ShuffleToken: SRD-beldum-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 95.2
  Pounds: 209.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beldum-BookSprite.png|wsmall]]
> ![[SRD-beldum-HomeSprite.png]]
> ![[SRD-beldum-BoxSprite.png|htiny]]
> ![[SRD-beldum-ShuffleToken.png|wsmall]]


*Iron Ball Pokemon*
*Beldum uses magnetic pulses to float and communicate. When it finds others, they move in perfect unison. It needs to develop a new brain to evolve; two of them may merge or it could develop a new one with time.*

**DexID**:: 0374
**Name**:: Beldum
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Light Metal|Light Metal]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 209.9lbs / 95.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Metang]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Beldum.md"
flatten moves as T
where file.path = this.file.path
```
