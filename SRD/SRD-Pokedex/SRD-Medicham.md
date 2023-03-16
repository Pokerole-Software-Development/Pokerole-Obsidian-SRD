---
Ability1: Pure Power
Ability2: ''
BookSprite: SRD-medicham-BookSprite.png
BoxSprite: SRD-medicham-BoxSprite.png
DexCategory: Meditate Pokemon
DexDescription: "They are thought to posses a sixth sense. Some of them can hide their\
  \ presence by lowering their ki. Medichams fight with expert yoga moves, foretelling\
  \ their foe\u2019s attacks and sensing their thoughts."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Meditite]]'
  Speed: Medium
- Evolves: To
  Item: Medichamite
  Kind: Mega
  Pokemon: '[[SRD-Medicham (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Telepathy
HomeSprite: SRD-medicham-HomeSprite.png
Image: medicham.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Acupressure|Acupressure]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
Number: 308
ShuffleToken: SRD-medicham-ShuffleToken.png
Type1: Fighting
Type2: Psychic
Weight:
  Kilograms: 31.5
  Pounds: 69.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-medicham-BookSprite.png|wsmall]]
> ![[SRD-medicham-HomeSprite.png]]
> ![[SRD-medicham-BoxSprite.png|htiny]]
> ![[SRD-medicham-ShuffleToken.png|wsmall]]


*Meditate Pokemon*
*They are thought to posses a sixth sense. Some of them can hide their presence by lowering their ki. Medichams fight with expert yoga moves, foretelling their foe’s attacks and sensing their thoughts.*

**DexID**:: 0308
**Name**:: Medicham
**Type**:: Fighting / Psychic
**Abilities**:: [[SRD-Pure Power|Pure Power]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 69.4lbs / 31.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Meditite]]             | Level  | Medium  |             |
| To        | [[SRD-Medicham (Mega Form)]] | Mega   |         | Medichamite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Medicham.md"
flatten moves as T
where file.path = this.file.path
```
