---
Ability1: Pure Power
Ability2: ''
BookSprite: SRD-meditite-BookSprite.png
BoxSprite: SRD-meditite-BoxSprite.png
DexCategory: Meditate Pokemon
DexDescription: Deep in the mountains they train their mind to increase their spiritual
  power, however they lack focus and get distracted easily. As part of their training,
  Meditites barely eat.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Medicham]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Telepathy
HomeSprite: SRD-meditite-HomeSprite.png
Image: meditite.png
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
  - '[[SRD-Foresight|Foresight]]'
- - Pro
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Pro
  - '[[SRD-Power Swap|Power Swap]]'
Number: 307
ShuffleToken: SRD-meditite-ShuffleToken.png
Type1: Fighting
Type2: Psychic
Weight:
  Kilograms: 11.2
  Pounds: 24.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meditite-BookSprite.png|wsmall]]
> ![[SRD-meditite-HomeSprite.png]]
> ![[SRD-meditite-BoxSprite.png|htiny]]
> ![[SRD-meditite-ShuffleToken.png|wsmall]]


*Meditate Pokemon*
*Deep in the mountains they train their mind to increase their spiritual power, however they lack focus and get distracted easily. As part of their training, Meditites barely eat.*

**DexID**:: 0307
**Name**:: Meditite
**Type**:: Fighting / Psychic
**Abilities**:: [[SRD-Pure Power|Pure Power]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 24.7lbs / 11.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Medicham]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meditite.md"
flatten moves as T
where file.path = this.file.path
```
