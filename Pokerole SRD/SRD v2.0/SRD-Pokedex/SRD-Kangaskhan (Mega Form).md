---
Ability1: Parental Bond
Ability2: ''
BookSprite: SRD-kangaskhan-mega-form-BookSprite.png
BoxSprite: SRD-kangaskhan-mega-form-BoxSprite.png
DexCategory: Parent Pokemon
DexDescription: "The mother gives all the power of the Mega Stone to her child. The\
  \ child grows violent and both team up as formidable fighters. But the mother worries\
  \ about her child\u2019s future as she raised it better than that."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Kangaskhanite
  Kind: Mega
  Pokemon: '[[SRD-Kangaskhan]]'
GenderType: F
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: ''
HomeSprite: SRD-kangaskhan-mega-form-HomeSprite.png
Image: kangaskhan-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 115
ShuffleToken: SRD-kangaskhan-mega-form-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 100.0
  Pounds: 220.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kangaskhan-mega-form-BookSprite.png|wsmall]]
> ![[SRD-kangaskhan-mega-form-HomeSprite.png]]
> ![[SRD-kangaskhan-mega-form-BoxSprite.png|htiny]]
> ![[SRD-kangaskhan-mega-form-ShuffleToken.png|wsmall]]


*Parent Pokemon*
*The mother gives all the power of the Mega Stone to her child. The child grows violent and both team up as formidable fighters. But the mother worries about her child’s future as she raised it better than that.*

**DexID**:: 0115M1
**Name**:: Kangaskhan (Mega Form)
**Type**:: Normal
**Abilities**:: [[SRD-Parental Bond|Parental Bond]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 7'2" / 2.2m
**Weight**: 220.5lbs / 100.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Item          |
|:----------|:-------------------|:-------|:--------------|
| From      | [[SRD-Kangaskhan]] | Mega   | Kangaskhanite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kangaskhan (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
