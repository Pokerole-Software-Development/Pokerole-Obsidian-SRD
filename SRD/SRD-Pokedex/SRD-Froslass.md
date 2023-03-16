---
Ability1: Snow Cloak
Ability2: ''
BookSprite: SRD-froslass-BookSprite.png
BoxSprite: SRD-froslass-BoxSprite.png
DexCategory: Snow Land Pokemon
DexDescription: This Pokemon is female only. Legends in snowy regions say that a woman
  who was lost at an icy mountain was reborn as Froslass. It appears during blizzards
  to take lost people away.
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Female
  Item: Dawn Stone
  Kind: Stone
  Pokemon: '[[SRD-Snorunt]]'
GenderType: F
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Cursed Body
HomeSprite: SRD-froslass-HomeSprite.png
Image: froslass.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
Number: 478
ShuffleToken: SRD-froslass-ShuffleToken.png
Type1: Ice
Type2: Ghost
Weight:
  Kilograms: 26.6
  Pounds: 58.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-froslass-BookSprite.png|wsmall]]
> ![[SRD-froslass-HomeSprite.png]]
> ![[SRD-froslass-BoxSprite.png|htiny]]
> ![[SRD-froslass-ShuffleToken.png|wsmall]]


*Snow Land Pokemon*
*This Pokemon is female only. Legends in snowy regions say that a woman who was lost at an icy mountain was reborn as Froslass. It appears during blizzards to take lost people away.*

**DexID**:: 0478
**Name**:: Froslass
**Type**:: Ice / Ghost
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 58.6lbs / 26.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item       | Gender   |
|:----------|:----------------|:-------|:-----------|:---------|
| From      | [[SRD-Snorunt]] | Stone  | Dawn Stone | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Froslass.md"
flatten moves as T
where file.path = this.file.path
```
