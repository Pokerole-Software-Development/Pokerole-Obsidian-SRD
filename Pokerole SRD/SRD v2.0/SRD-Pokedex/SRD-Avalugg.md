---
Ability1: Own Tempo
Ability2: Ice Body
BookSprite: SRD-avalugg-BookSprite.png
BoxSprite: SRD-avalugg-BoxSprite.png
DexCategory: Iceberg Pokemon
DexDescription: They carry their Bergmite offspring on their backs. Its Ice body is
  hard as steel and its cumbersome frame crushes anything that stands in its way.
  They are capable of swimming but they move very slowly.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bergmite]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Sturdy
HomeSprite: SRD-avalugg-HomeSprite.png
Image: avalugg.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Sharpen|Sharpen]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Skull Bash|Skull Bash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
Number: 713
ShuffleToken: SRD-avalugg-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 505.0
  Pounds: 1113.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-avalugg-BookSprite.png|wsmall]]
> ![[SRD-avalugg-HomeSprite.png]]
> ![[SRD-avalugg-BoxSprite.png|htiny]]
> ![[SRD-avalugg-ShuffleToken.png|wsmall]]


*Iceberg Pokemon*
*They carry their Bergmite offspring on their backs. Its Ice body is hard as steel and its cumbersome frame crushes anything that stands in its way. They are capable of swimming but they move very slowly.*

**DexID**:: 0713
**Name**:: Avalugg
**Type**:: Ice
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::9)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 6'6" / 2.0m
**Weight**: 1113.3lbs / 505.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Bergmite]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Avalugg.md"
flatten moves as T
where file.path = this.file.path
```
