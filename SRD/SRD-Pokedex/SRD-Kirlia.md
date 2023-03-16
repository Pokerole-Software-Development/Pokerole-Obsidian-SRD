---
Ability1: Synchronize
Ability2: Trace
BookSprite: SRD-kirlia-BookSprite.png
BoxSprite: SRD-kirlia-BoxSprite.png
DexCategory: Emotion Pokemon
DexDescription: When they use their powers, their surroundings are distorted with
  mirages and illusory sceneries from the future and the past. Kirlias like to dance
  and dislike to be bossed around.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ralts]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gardevoir]]'
  Speed: Medium
- Evolves: To
  Gender: Male
  Item: Dawn Stone
  Kind: Special
  Pokemon: '[[SRD-Gallade]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Telepathy
HomeSprite: SRD-kirlia-HomeSprite.png
Image: kirlia.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Double Team|Double Team]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
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
  - '[[SRD-Mean Look|Mean Look]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Magic Room|Magic Room]]'
Number: 281
ShuffleToken: SRD-kirlia-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 20.2
  Pounds: 44.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kirlia-BookSprite.png|wsmall]]
> ![[SRD-kirlia-HomeSprite.png]]
> ![[SRD-kirlia-BoxSprite.png|htiny]]
> ![[SRD-kirlia-ShuffleToken.png|wsmall]]


*Emotion Pokemon*
*When they use their powers, their surroundings are distorted with mirages and illusory sceneries from the future and the past. Kirlias like to dance and dislike to be bossed around.*

**DexID**:: 0281
**Name**:: Kirlia
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Trace|Trace]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 44.5lbs / 20.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind    | Speed   | Item       | Gender   |
|:----------|:------------------|:--------|:--------|:-----------|:---------|
| From      | [[SRD-Ralts]]     | Level   | Medium  |            |          |
| To        | [[SRD-Gardevoir]] | Level   | Medium  |            |          |
| To        | [[SRD-Gallade]]   | Special |         | Dawn Stone | Male     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kirlia.md"
flatten moves as T
where file.path = this.file.path
```
