---
Ability1: Sand Stream
Ability2: ''
BookSprite: SRD-hippopotas-BookSprite.png
BoxSprite: SRD-hippopotas-BoxSprite.png
DexCategory: Hippo Pokemon
DexDescription: It lives in arid places where it joins small groups. It closes its
  nostrils and submerges under the sand to rest. Females have a different coloration,
  usually a darker and duller color.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hippowdon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Sand Force
HomeSprite: SRD-hippopotas-HomeSprite.png
Image: hippopotas.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dig|Dig]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slack Off|Slack Off]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Pulse|Water Pulse]]'
Number: 449
ShuffleToken: SRD-hippopotas-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 49.5
  Pounds: 109.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hippopotas-BookSprite.png|wsmall]]
> ![[SRD-hippopotas-HomeSprite.png]]
> ![[SRD-hippopotas-BoxSprite.png|htiny]]
> ![[SRD-hippopotas-ShuffleToken.png|wsmall]]


*Hippo Pokemon*
*It lives in arid places where it joins small groups. It closes its nostrils and submerges under the sand to rest. Females have a different coloration, usually a darker and duller color.*

**DexID**:: 0449
**Name**:: Hippopotas
**Type**:: Ground
**Abilities**:: [[SRD-Sand Stream|Sand Stream]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 109.1lbs / 49.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Hippowdon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hippopotas.md"
flatten moves as T
where file.path = this.file.path
```
