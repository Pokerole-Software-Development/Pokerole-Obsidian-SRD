---
Ability1: Thick Fat
Ability2: Own Tempo
BookSprite: SRD-purugly-BookSprite.png
BoxSprite: SRD-purugly-BoxSprite.png
DexCategory: Tiger Cat Pokemon
DexDescription: It becomes wilder and aggressive after evolving. It is known to claim
  other Pokemon nests as its own. It will make itself appear bigger and glare with
  piercing eyes to achieve dominance over someone.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Glameow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Defiant
HomeSprite: SRD-purugly-HomeSprite.png
Image: purugly.png
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
- - Amateur
  - '[[SRD-Assist|Assist]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Attract|Attract]]'
- - Ace
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Pro
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
Number: 432
ShuffleToken: SRD-purugly-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 43.8
  Pounds: 96.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-purugly-BookSprite.png|wsmall]]
> ![[SRD-purugly-HomeSprite.png]]
> ![[SRD-purugly-BoxSprite.png|htiny]]
> ![[SRD-purugly-ShuffleToken.png|wsmall]]


*Tiger Cat Pokemon*
*It becomes wilder and aggressive after evolving. It is known to claim other Pokemon nests as its own. It will make itself appear bigger and glare with piercing eyes to achieve dominance over someone.*

**DexID**:: 0432
**Name**:: Purugly
**Type**:: Normal
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 96.6lbs / 43.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Glameow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Purugly.md"
flatten moves as T
where file.path = this.file.path
```
