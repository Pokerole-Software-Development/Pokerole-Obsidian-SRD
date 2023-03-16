---
Ability1: Early Bird
Ability2: Flash Fire
BookSprite: SRD-houndour-BookSprite.png
BoxSprite: SRD-houndour-BoxSprite.png
DexCategory: Dark Pokemon
DexDescription: They hunt in coordinated packs to corner their prey. They howl at
  dawn to announce that this is their territory and bark to communicate tactics. Their
  teamwork is very efficient and they rarely welcome strangers.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Houndoom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Unnerve
HomeSprite: SRD-houndour-HomeSprite.png
Image: houndour.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Reversal|Reversal]]'
- - Pro
  - '[[SRD-Feint|Feint]]'
Number: 228
ShuffleToken: SRD-houndour-ShuffleToken.png
Type1: Dark
Type2: Fire
Weight:
  Kilograms: 10.8
  Pounds: 23.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-houndour-BookSprite.png|wsmall]]
> ![[SRD-houndour-HomeSprite.png]]
> ![[SRD-houndour-BoxSprite.png|htiny]]
> ![[SRD-houndour-ShuffleToken.png|wsmall]]


*Dark Pokemon*
*They hunt in coordinated packs to corner their prey. They howl at dawn to announce that this is their territory and bark to communicate tactics. Their teamwork is very efficient and they rarely welcome strangers.*

**DexID**:: 0228
**Name**:: Houndour
**Type**:: Dark / Fire
**Abilities**:: [[SRD-Early Bird|Early Bird]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 23.8lbs / 10.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Houndoom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Houndour.md"
flatten moves as T
where file.path = this.file.path
```
