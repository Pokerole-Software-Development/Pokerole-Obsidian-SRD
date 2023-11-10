---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-torracat-BookSprite.png
BoxSprite: SRD-torracat-BoxSprite.png
DexCategory: Fire Cat Pokemon
DexDescription: The bell on its neck glows and chimes when it shots fire through it.
  Although it acts spoiled with its Trainer, it is a capable and relentless brawler,
  it will keep battling until its foes lose their fighting spirits.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Litten]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Incineroar]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Intimidate
HomeSprite: SRD-torracat-HomeSprite.png
Image: torracat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 726
ShuffleToken: SRD-torracat-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-torracat-BookSprite.png|wsmall]]
> ![[SRD-torracat-HomeSprite.png]]
> ![[SRD-torracat-BoxSprite.png|htiny]]
> ![[SRD-torracat-ShuffleToken.png|wsmall]]


*Fire Cat Pokemon*
*The bell on its neck glows and chimes when it shots fire through it. Although it acts spoiled with its Trainer, it is a capable and relentless brawler, it will keep battling until its foes lose their fighting spirits.*

**DexID**:: 0726
**Name**:: Torracat
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Litten]]     | Level  | Medium  |
| To        | [[SRD-Incineroar]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Torracat.md"
flatten moves as T
where file.path = this.file.path
```
