---
Ability1: Soundproof
Ability2: ''
BookSprite: SRD-exploud-BookSprite.png
BoxSprite: SRD-exploud-BoxSprite.png
DexCategory: Loud Noise Pokemon
DexDescription: It is said that some tremors are caused by the roars of this Pokemon.
  They communicate with soft noises, raising their voice only in battle. They can
  emit many different kinds of sounds.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Loudred]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Scrappy
HomeSprite: SRD-exploud-HomeSprite.png
Image: exploud.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Pro
  - '[[SRD-Whirlpool|Whirlpool]]'
Number: 295
ShuffleToken: SRD-exploud-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 84.0
  Pounds: 185.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-exploud-BookSprite.png|wsmall]]
> ![[SRD-exploud-HomeSprite.png]]
> ![[SRD-exploud-BoxSprite.png|htiny]]
> ![[SRD-exploud-ShuffleToken.png|wsmall]]


*Loud Noise Pokemon*
*It is said that some tremors are caused by the roars of this Pokemon. They communicate with soft noises, raising their voice only in battle. They can emit many different kinds of sounds.*

**DexID**:: 0295
**Name**:: Exploud
**Type**:: Normal
**Abilities**:: [[SRD-Soundproof|Soundproof]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 185.2lbs / 84.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Loudred]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Exploud.md"
flatten moves as T
where file.path = this.file.path
```
