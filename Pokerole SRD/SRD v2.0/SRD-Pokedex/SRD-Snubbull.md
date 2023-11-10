---
Ability1: Intimidate
Ability2: Run Away
BookSprite: SRD-snubbull-BookSprite.png
BoxSprite: SRD-snubbull-BoxSprite.png
DexCategory: Fairy Pokemon
DexDescription: It may look frightening but it is a loving and caring creature, active
  and playful. Snubbulls are easily scared. When threatened by bigger foes they run
  away or make scary faces, that makes them sad though.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Granbull]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Rattled
HomeSprite: SRD-snubbull-HomeSprite.png
Image: snubbull.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Lick|Lick]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Roar|Roar]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Present|Present]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 209
ShuffleToken: SRD-snubbull-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 7.8
  Pounds: 17.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-snubbull-BookSprite.png|wsmall]]
> ![[SRD-snubbull-HomeSprite.png]]
> ![[SRD-snubbull-BoxSprite.png|htiny]]
> ![[SRD-snubbull-ShuffleToken.png|wsmall]]


*Fairy Pokemon*
*It may look frightening but it is a loving and caring creature, active and playful. Snubbulls are easily scared. When threatened by bigger foes they run away or make scary faces, that makes them sad though.*

**DexID**:: 0209
**Name**:: Snubbull
**Type**:: Fairy
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Run Away|Run Away]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 17.2lbs / 7.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Granbull]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Snubbull.md"
flatten moves as T
where file.path = this.file.path
```
