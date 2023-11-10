---
Ability1: Poison Touch
Ability2: Gluttony
BookSprite: SRD-muk-alolan-form-BookSprite.png
BoxSprite: SRD-muk-alolan-form-BoxSprite.png
DexCategory: Sludge Pokemon
DexDescription: It is as friendly as it is toxic, be careful for it tries to hug others
  regularly. A good diet does not help reduce its toxicity levels, it only makes it
  cranky and prone to destroy furniture. It releases toxic fumes all the time.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grimer (Alolan Form)]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Power of Alchemy
HomeSprite: SRD-muk-alolan-form-HomeSprite.png
Image: muk-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
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
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Swallow|Swallow]]'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
Number: 89
ShuffleToken: SRD-muk-alolan-form-ShuffleToken.png
Type1: Poison
Type2: Dark
Weight:
  Kilograms: 52.0
  Pounds: 114.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-muk-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-muk-alolan-form-HomeSprite.png]]
> ![[SRD-muk-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-muk-alolan-form-ShuffleToken.png|wsmall]]


*Sludge Pokemon*
*It is as friendly as it is toxic, be careful for it tries to hug others regularly. A good diet does not help reduce its toxicity levels, it only makes it cranky and prone to destroy furniture. It releases toxic fumes all the time.*

**DexID**:: 0089A
**Name**:: Muk (Alolan Form)
**Type**:: Poison / Dark
**Abilities**:: [[SRD-Poison Touch|Poison Touch]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Power of Alchemy|Power of Alchemy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 114.6lbs / 52.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   |
|:----------|:-----------------------------|:-------|:--------|
| From      | [[SRD-Grimer (Alolan Form)]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Muk (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
