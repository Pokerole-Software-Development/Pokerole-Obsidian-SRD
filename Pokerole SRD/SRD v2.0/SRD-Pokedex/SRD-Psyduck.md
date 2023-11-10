---
Ability1: Damp
Ability2: Cloud Nine
BookSprite: SRD-psyduck-BookSprite.png
BoxSprite: SRD-psyduck-BoxSprite.png
DexCategory: Duck Pokemon
DexDescription: "It lives near lakes and ponds but it\u2019s not very good at swimming.\
  \ It is always tormented by headaches that worsen when it uses psychic powers. Psyducks\
  \ seem unaware of their own power."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Golduck]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Swift Swim
HomeSprite: SRD-psyduck-HomeSprite.png
Image: psyduck.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Wonder Room|Wonder Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
Number: 54
ShuffleToken: SRD-psyduck-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 19.6
  Pounds: 43.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-psyduck-BookSprite.png|wsmall]]
> ![[SRD-psyduck-HomeSprite.png]]
> ![[SRD-psyduck-BoxSprite.png|htiny]]
> ![[SRD-psyduck-ShuffleToken.png|wsmall]]


*Duck Pokemon*
*It lives near lakes and ponds but it’s not very good at swimming. It is always tormented by headaches that worsen when it uses psychic powers. Psyducks seem unaware of their own power.*

**DexID**:: 0054
**Name**:: Psyduck
**Type**:: Water
**Abilities**:: [[SRD-Damp|Damp]] / [[SRD-Cloud Nine|Cloud Nine]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 43.2lbs / 19.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Golduck]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Psyduck.md"
flatten moves as T
where file.path = this.file.path
```
