---
Ability1: Cursed Body
Ability2: ''
BookSprite: SRD-gengar-BookSprite.png
BoxSprite: SRD-gengar-BoxSprite.png
DexCategory: Shadow Pokemon
DexDescription: This Pokemon is mischievous but it can be downright evil. It takes
  joy in casting curses upon innocents and eating the life of people and Pokemon.
  It lurks in the shadows and disguises itself as one.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Haunter]]'
- Evolves: To
  Item: Gengarite
  Kind: Mega
  Pokemon: '[[SRD-Gengar (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-gengar-HomeSprite.png
Image: gengar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Spite|Spite]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Mean Look|Mean Look]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Shadow Punch|Shadow Punch]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Nightmare|Nightmare]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 94
ShuffleToken: SRD-gengar-ShuffleToken.png
Type1: Ghost
Type2: Poison
Weight:
  Kilograms: 40.5
  Pounds: 89.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gengar-BookSprite.png|wsmall]]
> ![[SRD-gengar-HomeSprite.png]]
> ![[SRD-gengar-BoxSprite.png|htiny]]
> ![[SRD-gengar-ShuffleToken.png|wsmall]]


*Shadow Pokemon*
*This Pokemon is mischievous but it can be downright evil. It takes joy in casting curses upon innocents and eating the life of people and Pokemon. It lurks in the shadows and disguises itself as one.*

**DexID**:: 0094
**Name**:: Gengar
**Type**:: Ghost / Poison
**Abilities**:: [[SRD-Cursed Body|Cursed Body]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 89.3lbs / 40.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                    | Kind   | Item      |
|:----------|:---------------------------|:-------|:----------|
| From      | [[SRD-Haunter]]            | Trade  |           |
| To        | [[SRD-Gengar (Mega Form)]] | Mega   | Gengarite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gengar.md"
flatten moves as T
where file.path = this.file.path
```
