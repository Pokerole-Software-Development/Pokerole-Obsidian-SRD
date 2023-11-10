---
Ability1: Weak Armor
Ability2: ''
BookSprite: SRD-polteageist-BookSprite.png
BoxSprite: SRD-polteageist-BoxSprite.png
DexCategory: Black Tea Pokemon
DexDescription: This species lives in old ceramic teapots. They struggle to find real
  antiques, for most tea sets nowadays are just imitations. Never leave your tea unattended
  or a Poltegeist might come to haunt it.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Cracked Pot
  Kind: Item
  Pokemon: '[[SRD-Sinistea]]'
GenderType: N
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Cursed Body
HomeSprite: SRD-polteageist-HomeSprite.png
Image: polteageist.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Teatime|Teatime]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Strength Sap|Strength Sap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Poltergeist|Poltergeist]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 855
ShuffleToken: SRD-polteageist-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 0.4
  Pounds: 0.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-polteageist-BookSprite.png|wsmall]]
> ![[SRD-polteageist-HomeSprite.png]]
> ![[SRD-polteageist-BoxSprite.png|htiny]]
> ![[SRD-polteageist-ShuffleToken.png|wsmall]]


*Black Tea Pokemon*
*This species lives in old ceramic teapots. They struggle to find real antiques, for most tea sets nowadays are just imitations. Never leave your tea unattended or a Poltegeist might come to haunt it.*

**DexID**:: 0855
**Name**:: Polteageist
**Type**:: Ghost
**Abilities**:: [[SRD-Weak Armor|Weak Armor]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 0'7" / 0.2m
**Weight**: 0.9lbs / 0.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Sinistea]] | Item   | Cracked Pot |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Polteageist.md"
flatten moves as T
where file.path = this.file.path
```
