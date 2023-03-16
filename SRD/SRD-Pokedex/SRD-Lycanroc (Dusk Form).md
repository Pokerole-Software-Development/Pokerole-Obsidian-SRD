---
Ability1: Tough Claws
Ability2: ''
BookSprite: SRD-lycanroc-dusk-form-BookSprite.png
BoxSprite: SRD-lycanroc-dusk-form-BoxSprite.png
DexCategory: Wolf Pokemon
DexDescription: An independent but loyal Rockruff will evolve at dusk. This evolved
  for is very hard to achieve. An intense fighting spirit lies underneath its calm
  exterior. Prone to act on its own.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rockruff]]'
  Special: Dawn
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-lycanroc-dusk-form-HomeSprite.png
Image: lycanroc-dusk-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Accelerock|Accelerock]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
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
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
Number: 745
ShuffleToken: SRD-lycanroc-dusk-form-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lycanroc-dusk-form-BookSprite.png|wsmall]]
> ![[SRD-lycanroc-dusk-form-HomeSprite.png]]
> ![[SRD-lycanroc-dusk-form-BoxSprite.png|htiny]]
> ![[SRD-lycanroc-dusk-form-ShuffleToken.png|wsmall]]


*Wolf Pokemon*
*An independent but loyal Rockruff will evolve at dusk. This evolved for is very hard to achieve. An intense fighting spirit lies underneath its calm exterior. Prone to act on its own.*

**DexID**:: 0745F2
**Name**:: Lycanroc (Dusk Form)
**Type**:: Rock
**Abilities**:: [[SRD-Tough Claws|Tough Claws]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Special   |
|:----------|:-----------------|:-------|:--------|:----------|
| From      | [[SRD-Rockruff]] | Level  | Medium  | Dawn      |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lycanroc (Dusk Form).md"
flatten moves as T
where file.path = this.file.path
```
