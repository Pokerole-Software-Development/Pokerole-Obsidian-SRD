---
Ability1: Insomnia
Ability2: Keen Eye
BookSprite: SRD-hoothoot-BookSprite.png
BoxSprite: SRD-hoothoot-BoxSprite.png
DexCategory: Owl Pokemon
DexDescription: "A nocturnal Pokemon found in dark forests. It has an internal organ\
  \ that senses the earth\u2019s rotation. By using this special organ a Hoothoot\
  \ begins hooting at precisely the same time every day."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Noctowl]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Tinted Lens
HomeSprite: SRD-hoothoot-HomeSprite.png
Image: hoothoot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Moonblast|Moonblast]]'
- - Amateur
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Roost|Roost]]'
- - Ace
  - '[[SRD-Dream Eater|Dream Eater]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Shade|Night Shade]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
Number: 163
ShuffleToken: SRD-hoothoot-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 21.2
  Pounds: 46.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hoothoot-BookSprite.png|wsmall]]
> ![[SRD-hoothoot-HomeSprite.png]]
> ![[SRD-hoothoot-BoxSprite.png|htiny]]
> ![[SRD-hoothoot-ShuffleToken.png|wsmall]]


*Owl Pokemon*
*A nocturnal Pokemon found in dark forests. It has an internal organ that senses the earth’s rotation. By using this special organ a Hoothoot begins hooting at precisely the same time every day.*

**DexID**:: 0163
**Name**:: Hoothoot
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Keen Eye|Keen Eye]] ([[SRD-Tinted Lens|Tinted Lens]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 46.7lbs / 21.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Noctowl]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hoothoot.md"
flatten moves as T
where file.path = this.file.path
```
