---
Ability1: Inner Focus
Ability2: Ice Body
BookSprite: SRD-glalie-BookSprite.png
BoxSprite: SRD-glalie-BoxSprite.png
DexCategory: Face Pokemon
DexDescription: Its body is so hard it was thought to be made of rock. They can be
  aggressive if provoked. When they hunt, they freeze their prey solid before eating
  it. They can live in warm places without trouble.
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Male
  Kind: Level
  Pokemon: '[[SRD-Snorunt]]'
  Speed: Medium
- Evolves: To
  Item: Glalitite
  Kind: Mega
  Pokemon: '[[SRD-Glalie (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Moody
HomeSprite: SRD-glalie-HomeSprite.png
Image: glalie.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Frost Breath|Frost Breath]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
Number: 362
ShuffleToken: SRD-glalie-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 256.5
  Pounds: 565.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-glalie-BookSprite.png|wsmall]]
> ![[SRD-glalie-HomeSprite.png]]
> ![[SRD-glalie-BoxSprite.png|htiny]]
> ![[SRD-glalie-ShuffleToken.png|wsmall]]


*Face Pokemon*
*Its body is so hard it was thought to be made of rock. They can be aggressive if provoked. When they hunt, they freeze their prey solid before eating it. They can live in warm places without trouble.*

**DexID**:: 0362
**Name**:: Glalie
**Type**:: Ice
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Moody|Moody]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 565.5lbs / 256.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                    | Kind   | Speed   | Gender   | Item      |
|:----------|:---------------------------|:-------|:--------|:---------|:----------|
| From      | [[SRD-Snorunt]]            | Level  | Medium  | Male     |           |
| To        | [[SRD-Glalie (Mega Form)]] | Mega   |         |          | Glalitite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Glalie.md"
flatten moves as T
where file.path = this.file.path
```
