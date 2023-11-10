---
Ability1: Inner Focus
Ability2: Ice Body
BookSprite: SRD-snorunt-BookSprite.png
BoxSprite: SRD-snorunt-BoxSprite.png
DexCategory: Snow Hat Pokemon
DexDescription: This friendly Pokemon lives in cold mountains and deserted snowlands.
  It survives by eating snow and ice. They form small groups to protect themselves
  from predators. If you take their hat off, they will get angry.
EventAbilities: ''
Evolutions:
- Evolves: To
  Gender: Male
  Kind: Level
  Pokemon: '[[SRD-Glalie]]'
  Speed: Medium
- Evolves: To
  Gender: Female
  Item: Dawn Stone
  Kind: Stone
  Pokemon: '[[SRD-Froslass]]'
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Moody
HomeSprite: SRD-snorunt-HomeSprite.png
Image: snorunt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Frost Breath|Frost Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 361
ShuffleToken: SRD-snorunt-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 16.8
  Pounds: 37.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-snorunt-BookSprite.png|wsmall]]
> ![[SRD-snorunt-HomeSprite.png]]
> ![[SRD-snorunt-BoxSprite.png|htiny]]
> ![[SRD-snorunt-ShuffleToken.png|wsmall]]


*Snow Hat Pokemon*
*This friendly Pokemon lives in cold mountains and deserted snowlands. It survives by eating snow and ice. They form small groups to protect themselves from predators. If you take their hat off, they will get angry.*

**DexID**:: 0361
**Name**:: Snorunt
**Type**:: Ice
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Moody|Moody]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 37.0lbs / 16.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   | Gender   | Item       |
|:----------|:-----------------|:-------|:--------|:---------|:-----------|
| To        | [[SRD-Glalie]]   | Level  | Medium  | Male     |            |
| To        | [[SRD-Froslass]] | Stone  |         | Female   | Dawn Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Snorunt.md"
flatten moves as T
where file.path = this.file.path
```
