---
Ability1: Shadow Tag
Ability2: ''
BookSprite: SRD-gengar-mega-form-BookSprite.png
BoxSprite: SRD-gengar-mega-form-BoxSprite.png
DexCategory: Shadow Pokemon
DexDescription: With the power of the Mega Stone Gengar can now teleport through dimensions,
  whatever horrors it witnesses there make it try to curse anything or anyone it perceives
  as prey, even its beloved trainer!
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Gengarite
  Kind: Mega
  Pokemon: '[[SRD-Gengar]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-gengar-mega-form-HomeSprite.png
Image: gengar-mega-form.png
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
ShuffleToken: SRD-gengar-mega-form-ShuffleToken.png
Type1: Ghost
Type2: Poison
Weight:
  Kilograms: 40.5
  Pounds: 89.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gengar-mega-form-BookSprite.png|wsmall]]
> ![[SRD-gengar-mega-form-HomeSprite.png]]
> ![[SRD-gengar-mega-form-BoxSprite.png|htiny]]
> ![[SRD-gengar-mega-form-ShuffleToken.png|wsmall]]


*Shadow Pokemon*
*With the power of the Mega Stone Gengar can now teleport through dimensions, whatever horrors it witnesses there make it try to curse anything or anyone it perceives as prey, even its beloved trainer!*

**DexID**:: 0094M1
**Name**:: Gengar (Mega Form)
**Type**:: Ghost / Poison
**Abilities**:: [[SRD-Shadow Tag|Shadow Tag]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 89.3lbs / 40.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Gengar]] | Mega   | Gengarite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gengar (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
