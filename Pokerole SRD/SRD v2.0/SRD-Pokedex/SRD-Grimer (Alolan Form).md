---
Ability1: Poison Touch
Ability2: Gluttony
BookSprite: SRD-grimer-alolan-form-BookSprite.png
BoxSprite: SRD-grimer-alolan-form-BoxSprite.png
DexCategory: Sludge Pokemon
DexDescription: Grimer were brought into Alola to eat garbage on the region. It seemed
  like a counterintuitive measure but ended up solving the problem. But now Grimer
  are incredibly noxious, much more toxic than usual.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Muk (Alolan Form)]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Power of Alchemy
HomeSprite: SRD-grimer-alolan-form-HomeSprite.png
Image: grimer-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Assurance|Assurance]]'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
Number: 88
ShuffleToken: SRD-grimer-alolan-form-ShuffleToken.png
Type1: Poison
Type2: Dark
Weight:
  Kilograms: 42.0
  Pounds: 92.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grimer-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-grimer-alolan-form-HomeSprite.png]]
> ![[SRD-grimer-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-grimer-alolan-form-ShuffleToken.png|wsmall]]


*Sludge Pokemon*
*Grimer were brought into Alola to eat garbage on the region. It seemed like a counterintuitive measure but ended up solving the problem. But now Grimer are incredibly noxious, much more toxic than usual.*

**DexID**:: 0088A
**Name**:: Grimer (Alolan Form)
**Type**:: Poison / Dark
**Abilities**:: [[SRD-Poison Touch|Poison Touch]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Power of Alchemy|Power of Alchemy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 92.6lbs / 42.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                   | Kind   | Speed   |
|:----------|:--------------------------|:-------|:--------|
| To        | [[SRD-Muk (Alolan Form)]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Grimer (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
