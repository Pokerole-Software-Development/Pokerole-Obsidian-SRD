---
Ability1: Cute Charm
Ability2: Magic Guard
BookSprite: SRD-clefairy-BookSprite.png
BoxSprite: SRD-clefairy-BoxSprite.png
DexCategory: Fairy Pokemon
DexDescription: Very rare to find. Clefairies are said to come from the moon. They
  are drawn to the light of this celestial body and come out of hiding at night to
  dance and play in the moonlight.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Cleffa]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Clefable]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Friend Guard
HomeSprite: SRD-clefairy-HomeSprite.png
Image: clefairy.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metronome|Metronome]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[SRD-Spotlight|Spotlight]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Moonlight|Moonlight]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Gravity|Gravity]]'
- - Ace
  - '[[SRD-Meteor Mash|Meteor Mash]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
Number: 35
ShuffleToken: SRD-clefairy-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 7.5
  Pounds: 16.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clefairy-BookSprite.png|wsmall]]
> ![[SRD-clefairy-HomeSprite.png]]
> ![[SRD-clefairy-BoxSprite.png|htiny]]
> ![[SRD-clefairy-ShuffleToken.png|wsmall]]


*Fairy Pokemon*
*Very rare to find. Clefairies are said to come from the moon. They are drawn to the light of this celestial body and come out of hiding at night to dance and play in the moonlight.*

**DexID**:: 0035
**Name**:: Clefairy
**Type**:: Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 16.5lbs / 7.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Stat      | Value   | Item       |
|:----------|:-----------------|:-------|:----------|:--------|:-----------|
| From      | [[SRD-Cleffa]]   | Stat   | Happiness | 4.0     |            |
| To        | [[SRD-Clefable]] | Stone  |           |         | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Clefairy.md"
flatten moves as T
where file.path = this.file.path
```
