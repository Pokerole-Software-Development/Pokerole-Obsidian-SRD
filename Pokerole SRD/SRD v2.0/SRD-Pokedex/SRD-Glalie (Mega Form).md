---
Ability1: Refrigerate
Ability2: ''
BookSprite: SRD-glalie-mega-form-BookSprite.png
BoxSprite: SRD-glalie-mega-form-BoxSprite.png
DexCategory: Face Pokemon
DexDescription: The power of the Mega Stone bent its jaw at an unnatural angle, this
  helps it spew enormous blizzards but leaves it unable to eat any prey it catches.
  This makes it angry and will weaken it if it stays in this form.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Glalitite
  Kind: Mega
  Pokemon: '[[SRD-Glalie]]'
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Moody
HomeSprite: SRD-glalie-mega-form-HomeSprite.png
Image: glalie-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Team|Double Team]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Frost Breath|Frost Breath]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hail|Hail]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
Number: 362
ShuffleToken: SRD-glalie-mega-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 350.2
  Pounds: 772.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-glalie-mega-form-BookSprite.png|wsmall]]
> ![[SRD-glalie-mega-form-HomeSprite.png]]
> ![[SRD-glalie-mega-form-BoxSprite.png|htiny]]
> ![[SRD-glalie-mega-form-ShuffleToken.png|wsmall]]


*Face Pokemon*
*The power of the Mega Stone bent its jaw at an unnatural angle, this helps it spew enormous blizzards but leaves it unable to eat any prey it catches. This makes it angry and will weaken it if it stays in this form.*

**DexID**:: 0362M1
**Name**:: Glalie (Mega Form)
**Type**:: Ice
**Abilities**:: [[SRD-Refrigerate|Refrigerate]] ([[SRD-Moody|Moody]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 772.1lbs / 350.2kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Glalie]] | Mega   | Glalitite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Glalie (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
