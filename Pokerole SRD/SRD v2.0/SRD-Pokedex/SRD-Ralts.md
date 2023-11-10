---
Ability1: Synchronize
Ability2: Trace
BookSprite: SRD-ralts-BookSprite.png
BoxSprite: SRD-ralts-BoxSprite.png
DexCategory: Feeling Pokemon
DexDescription: They sense the emotions of people and Pokemon, usually sharing the
  mood of anyone nearby. They show if they feel joy and cheer, but hide if they sense
  hostility. They dislike fighting and negativity.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kirlia]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Telepathy
HomeSprite: SRD-ralts-HomeSprite.png
Image: ralts.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Double Team|Double Team]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Ace
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Mean Look|Mean Look]]'
Number: 280
ShuffleToken: SRD-ralts-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 6.6
  Pounds: 14.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ralts-BookSprite.png|wsmall]]
> ![[SRD-ralts-HomeSprite.png]]
> ![[SRD-ralts-BoxSprite.png|htiny]]
> ![[SRD-ralts-ShuffleToken.png|wsmall]]


*Feeling Pokemon*
*They sense the emotions of people and Pokemon, usually sharing the mood of anyone nearby. They show if they feel joy and cheer, but hide if they sense hostility. They dislike fighting and negativity.*

**DexID**:: 0280
**Name**:: Ralts
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Trace|Trace]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 14.6lbs / 6.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Kirlia]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ralts.md"
flatten moves as T
where file.path = this.file.path
```
