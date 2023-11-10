---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-pansear-BookSprite.png
BoxSprite: SRD-pansear-BoxSprite.png
DexCategory: High Temp Pokemon
DexDescription: "It lives close to volcanic mountains. It\u2019s very intelligent,\
  \ it roasts berries before eating them and helps lost people. When angered the tuft\
  \ of hair on it\u2019s head and tail can burst into flames."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Simisear]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Blaze
HomeSprite: SRD-pansear-HomeSprite.png
Image: pansear.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
Number: 513
ShuffleToken: SRD-pansear-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pansear-BookSprite.png|wsmall]]
> ![[SRD-pansear-HomeSprite.png]]
> ![[SRD-pansear-BoxSprite.png|htiny]]
> ![[SRD-pansear-ShuffleToken.png|wsmall]]


*High Temp Pokemon*
*It lives close to volcanic mountains. It’s very intelligent, it roasts berries before eating them and helps lost people. When angered the tuft of hair on it’s head and tail can burst into flames.*

**DexID**:: 0513
**Name**:: Pansear
**Type**:: Fire
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Blaze|Blaze]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| To        | [[SRD-Simisear]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pansear.md"
flatten moves as T
where file.path = this.file.path
```
