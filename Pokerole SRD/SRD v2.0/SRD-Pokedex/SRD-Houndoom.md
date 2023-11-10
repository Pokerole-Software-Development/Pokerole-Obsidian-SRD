---
Ability1: Early Bird
Ability2: Flash Fire
BookSprite: SRD-houndoom-BookSprite.png
BoxSprite: SRD-houndoom-BoxSprite.png
DexCategory: Dark Pokemon
DexDescription: It is said the pain from its flames never goes away. Long ago, their
  howl was thought to be the call of the grim reaper. Pokemon and people who hear
  it, will always shiver in fear. They are pack leaders, not followers
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Houndour]]'
  Speed: Medium
- Evolves: To
  Item: Houndoominite
  Kind: Mega
  Pokemon: '[[SRD-Houndoom (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Unnerve
HomeSprite: SRD-houndoom-HomeSprite.png
Image: houndoom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 229
ShuffleToken: SRD-houndoom-ShuffleToken.png
Type1: Dark
Type2: Fire
Weight:
  Kilograms: 35.0
  Pounds: 77.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-houndoom-BookSprite.png|wsmall]]
> ![[SRD-houndoom-HomeSprite.png]]
> ![[SRD-houndoom-BoxSprite.png|htiny]]
> ![[SRD-houndoom-ShuffleToken.png|wsmall]]


*Dark Pokemon*
*It is said the pain from its flames never goes away. Long ago, their howl was thought to be the call of the grim reaper. Pokemon and people who hear it, will always shiver in fear. They are pack leaders, not followers*

**DexID**:: 0229
**Name**:: Houndoom
**Type**:: Dark / Fire
**Abilities**:: [[SRD-Early Bird|Early Bird]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 77.2lbs / 35.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   | Item          |
|:----------|:-----------------------------|:-------|:--------|:--------------|
| From      | [[SRD-Houndour]]             | Level  | Medium  |               |
| To        | [[SRD-Houndoom (Mega Form)]] | Mega   |         | Houndoominite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Houndoom.md"
flatten moves as T
where file.path = this.file.path
```
