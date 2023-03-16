---
Ability1: Sand Stream
Ability2: ''
BookSprite: SRD-tyranitar-mega-form-BookSprite.png
BoxSprite: SRD-tyranitar-mega-form-BoxSprite.png
DexCategory: Armor Pokemon
DexDescription: "The power of the Mega Stone is so overwhelming it splits its back\
  \ open. It becomes overwhelmed by its ferocious instincts and it\u2019s unclear\
  \ if it can even hear its Trainer through the pain and rage."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Tyranitarite
  Kind: Mega
  Pokemon: '[[SRD-Tyranitar]]'
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-tyranitar-mega-form-HomeSprite.png
Image: tyranitar-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 248
ShuffleToken: SRD-tyranitar-mega-form-ShuffleToken.png
Type1: Rock
Type2: Dark
Weight:
  Kilograms: 255.0
  Pounds: 562.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tyranitar-mega-form-BookSprite.png|wsmall]]
> ![[SRD-tyranitar-mega-form-HomeSprite.png]]
> ![[SRD-tyranitar-mega-form-BoxSprite.png|htiny]]
> ![[SRD-tyranitar-mega-form-ShuffleToken.png|wsmall]]


*Armor Pokemon*
*The power of the Mega Stone is so overwhelming it splits its back open. It becomes overwhelmed by its ferocious instincts and it’s unclear if it can even hear its Trainer through the pain and rage.*

**DexID**:: 0248M1
**Name**:: Tyranitar (Mega Form)
**Type**:: Rock / Dark
**Abilities**:: [[SRD-Sand Stream|Sand Stream]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 8'2" / 2.5m
**Weight**: 562.2lbs / 255.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon           | Kind   | Item         |
|:----------|:------------------|:-------|:-------------|
| From      | [[SRD-Tyranitar]] | Mega   | Tyranitarite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tyranitar (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
