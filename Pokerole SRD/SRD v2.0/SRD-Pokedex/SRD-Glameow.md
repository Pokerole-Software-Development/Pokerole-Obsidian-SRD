---
Ability1: Limber
Ability2: Own Tempo
BookSprite: SRD-glameow-BookSprite.png
BoxSprite: SRD-glameow-BoxSprite.png
DexCategory: Catty Pokemon
DexDescription: "It is plentiful in urban areas, as it is a popular pet. It has a\
  \ very fickle nature, purring in happiness one second, then hooking its claws into\
  \ its trainer\u2019s nose. It loves to be admired and pampered."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Purugly]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Keen Eye
HomeSprite: SRD-glameow-HomeSprite.png
Image: glameow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assist|Assist]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Hone Claws|Hone Claws]]'
Number: 431
ShuffleToken: SRD-glameow-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 3.9
  Pounds: 8.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-glameow-BookSprite.png|wsmall]]
> ![[SRD-glameow-HomeSprite.png]]
> ![[SRD-glameow-BoxSprite.png|htiny]]
> ![[SRD-glameow-ShuffleToken.png|wsmall]]


*Catty Pokemon*
*It is plentiful in urban areas, as it is a popular pet. It has a very fickle nature, purring in happiness one second, then hooking its claws into its trainer’s nose. It loves to be admired and pampered.*

**DexID**:: 0431
**Name**:: Glameow
**Type**:: Normal
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Keen Eye|Keen Eye]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 8.6lbs / 3.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Purugly]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Glameow.md"
flatten moves as T
where file.path = this.file.path
```
