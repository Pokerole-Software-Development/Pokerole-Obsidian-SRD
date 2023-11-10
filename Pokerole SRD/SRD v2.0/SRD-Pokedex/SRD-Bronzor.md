---
Ability1: Levitate
Ability2: Heatproof
BookSprite: SRD-bronzor-BookSprite.png
BoxSprite: SRD-bronzor-BoxSprite.png
DexCategory: Bronze Pokemon
DexDescription: They are found in ancient tombs and temples. Objects shaped like Bronzor
  have been found within the vaults. Bronzors reflect images like mirrors, people
  say that this reflection shows the future.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Bronzong]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Heavy Metal
HomeSprite: SRD-bronzor-HomeSprite.png
Image: bronzor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Imprison|Imprison]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 436
ShuffleToken: SRD-bronzor-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 60.5
  Pounds: 133.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bronzor-BookSprite.png|wsmall]]
> ![[SRD-bronzor-HomeSprite.png]]
> ![[SRD-bronzor-BoxSprite.png|htiny]]
> ![[SRD-bronzor-ShuffleToken.png|wsmall]]


*Bronze Pokemon*
*They are found in ancient tombs and temples. Objects shaped like Bronzor have been found within the vaults. Bronzors reflect images like mirrors, people say that this reflection shows the future.*

**DexID**:: 0436
**Name**:: Bronzor
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]] / [[SRD-Heatproof|Heatproof]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 133.4lbs / 60.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Bronzong]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bronzor.md"
flatten moves as T
where file.path = this.file.path
```
