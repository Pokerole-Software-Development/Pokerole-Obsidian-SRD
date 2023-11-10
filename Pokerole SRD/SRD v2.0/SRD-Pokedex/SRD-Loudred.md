---
Ability1: Soundproof
Ability2: ''
BookSprite: SRD-loudred-BookSprite.png
BoxSprite: SRD-loudred-BoxSprite.png
DexCategory: Big Voice Pokemon
DexDescription: Their ears work as loudspeakers capable of breaking glass or even
  blowing apart a wooden house. When it finishes shouting, even they are deafened
  for a while. They have noisy competitions in their packs.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Whismur]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Exploud]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Scrappy
HomeSprite: SRD-loudred-HomeSprite.png
Image: loudred.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Howl|Howl]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 294
ShuffleToken: SRD-loudred-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 40.5
  Pounds: 89.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-loudred-BookSprite.png|wsmall]]
> ![[SRD-loudred-HomeSprite.png]]
> ![[SRD-loudred-BoxSprite.png|htiny]]
> ![[SRD-loudred-ShuffleToken.png|wsmall]]


*Big Voice Pokemon*
*Their ears work as loudspeakers capable of breaking glass or even blowing apart a wooden house. When it finishes shouting, even they are deafened for a while. They have noisy competitions in their packs.*

**DexID**:: 0294
**Name**:: Loudred
**Type**:: Normal
**Abilities**:: [[SRD-Soundproof|Soundproof]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 89.3lbs / 40.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Whismur]] | Level  | Medium  |
| To        | [[SRD-Exploud]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Loudred.md"
flatten moves as T
where file.path = this.file.path
```
