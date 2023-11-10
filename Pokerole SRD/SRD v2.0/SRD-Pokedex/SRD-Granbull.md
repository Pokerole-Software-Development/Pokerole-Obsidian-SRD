---
Ability1: Intimidate
Ability2: Quick Feet
BookSprite: SRD-granbull-BookSprite.png
BoxSprite: SRD-granbull-BoxSprite.png
DexCategory: Fairy Pokemon
DexDescription: Granbull is usually a timid creature that is easily spooked. Its fangs
  are extremely powerful and scary so no one dares to mess with it or its loved ones.
  It will use its giant fangs to attack if it needs to.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Snubbull]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Rattled
HomeSprite: SRD-granbull-HomeSprite.png
Image: granbull.png
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
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
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
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
Number: 210
ShuffleToken: SRD-granbull-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 48.7
  Pounds: 107.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-granbull-BookSprite.png|wsmall]]
> ![[SRD-granbull-HomeSprite.png]]
> ![[SRD-granbull-BoxSprite.png|htiny]]
> ![[SRD-granbull-ShuffleToken.png|wsmall]]


*Fairy Pokemon*
*Granbull is usually a timid creature that is easily spooked. Its fangs are extremely powerful and scary so no one dares to mess with it or its loved ones. It will use its giant fangs to attack if it needs to.*

**DexID**:: 0210
**Name**:: Granbull
**Type**:: Fairy
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Quick Feet|Quick Feet]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 107.4lbs / 48.7kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Snubbull]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Granbull.md"
flatten moves as T
where file.path = this.file.path
```
