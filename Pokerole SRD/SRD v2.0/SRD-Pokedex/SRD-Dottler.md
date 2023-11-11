---
Ability1: Swarm
Ability2: Compound Eyes
BookSprite: SRD-dottler-BookSprite.png
BoxSprite: SRD-dottler-BoxSprite.png
DexCategory: Radome Pokemon
DexDescription: "It grows into its final stage inside a hard shell. It barely moves\
  \ and it won\u2019t eat or drink during this time, due to this many believe it to\
  \ be dead until its psychic powers awaken and it starts communicating telepathically."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Blipbug]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Orbeetle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Telepathy
HomeSprite: SRD-dottler-HomeSprite.png
Image: dottler.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sticky Web|Sticky Web]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Supersonic|Supersonic]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Infestation|Infestation]]'
Number: 825
ShuffleToken: SRD-dottler-ShuffleToken.png
Type1: Bug
Type2: Psychic
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dottler-BookSprite.png|wsmall]]
> ![[SRD-dottler-HomeSprite.png]]
> ![[SRD-dottler-BoxSprite.png|htiny]]
> ![[SRD-dottler-ShuffleToken.png|wsmall]]


*Radome Pokemon*
*It grows into its final stage inside a hard shell. It barely moves and it won’t eat or drink during this time, due to this many believe it to be dead until its psychic powers awaken and it starts communicating telepathically.*

**DexID**:: 0825
**Name**:: Dottler
**Type**:: Bug / Psychic
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Blipbug]]  | Level  | Fast    |
| To        | [[SRD-Orbeetle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dottler.md"
flatten moves as T
where file.path = this.file.path
```
