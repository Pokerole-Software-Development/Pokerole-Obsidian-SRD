---
Ability1: Insomnia
Ability2: Keen Eye
BookSprite: SRD-noctowl-BookSprite.png
BoxSprite: SRD-noctowl-BoxSprite.png
DexCategory: Owl Pokemon
DexDescription: It can hunt in full darkness without fail. All Noctowls owe their
  success to their superior vision - that allows them to see in minimal light, and
  to their agile and silent wings. They are very intelligent and critic Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Hoothoot]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Tinted Lens
HomeSprite: SRD-noctowl-HomeSprite.png
Image: noctowl.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psycho Shift|Psycho Shift]]'
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
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
  - '[[SRD-Agility|Agility]]'
Number: 164
ShuffleToken: SRD-noctowl-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 40.8
  Pounds: 89.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-noctowl-BookSprite.png|wsmall]]
> ![[SRD-noctowl-HomeSprite.png]]
> ![[SRD-noctowl-BoxSprite.png|htiny]]
> ![[SRD-noctowl-ShuffleToken.png|wsmall]]


*Owl Pokemon*
*It can hunt in full darkness without fail. All Noctowls owe their success to their superior vision - that allows them to see in minimal light, and to their agile and silent wings. They are very intelligent and critic Pokemon.*

**DexID**:: 0164
**Name**:: Noctowl
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Keen Eye|Keen Eye]] ([[SRD-Tinted Lens|Tinted Lens]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 89.9lbs / 40.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Hoothoot]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Noctowl.md"
flatten moves as T
where file.path = this.file.path
```
