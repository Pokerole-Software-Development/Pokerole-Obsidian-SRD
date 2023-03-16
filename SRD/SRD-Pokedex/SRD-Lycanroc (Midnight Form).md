---
Ability1: Keen Eye
Ability2: Vital Spirit
BookSprite: SRD-lycanroc-midnight-form-BookSprite.png
BoxSprite: SRD-lycanroc-midnight-form-BoxSprite.png
DexCategory: Wolf Pokemon
DexDescription: A poorly-behaved Rockruff will evolve at midnight. This Pokemon is
  savage and has no regard for its own safety. It taunts and provokes foes a lot stronger
  just to get its own blood boiling.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rockruff]]'
  Special: Night
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: No Guard
HomeSprite: SRD-lycanroc-midnight-form-HomeSprite.png
Image: lycanroc-midnight-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Pro
  - '[[SRD-Bulk Up|Bulk Up]]'
Number: 745
ShuffleToken: SRD-lycanroc-midnight-form-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lycanroc-midnight-form-BookSprite.png|wsmall]]
> ![[SRD-lycanroc-midnight-form-HomeSprite.png]]
> ![[SRD-lycanroc-midnight-form-BoxSprite.png|htiny]]
> ![[SRD-lycanroc-midnight-form-ShuffleToken.png|wsmall]]


*Wolf Pokemon*
*A poorly-behaved Rockruff will evolve at midnight. This Pokemon is savage and has no regard for its own safety. It taunts and provokes foes a lot stronger just to get its own blood boiling.*

**DexID**:: 0745F1
**Name**:: Lycanroc (Midnight Form)
**Type**:: Rock
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Vital Spirit|Vital Spirit]] ([[SRD-No Guard|No Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Special   |
|:----------|:-----------------|:-------|:--------|:----------|
| From      | [[SRD-Rockruff]] | Level  | Medium  | Night     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lycanroc (Midnight Form).md"
flatten moves as T
where file.path = this.file.path
```
