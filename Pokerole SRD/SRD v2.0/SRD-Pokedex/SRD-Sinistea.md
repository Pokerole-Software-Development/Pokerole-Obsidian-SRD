---
Ability1: Weak Armor
Ability2: ''
BookSprite: SRD-sinistea-BookSprite.png
BoxSprite: SRD-sinistea-BoxSprite.png
DexCategory: Black Tea Pokemon
DexDescription: This Pokemon is said to have been born when a lonely spirit possessed
  a cold, leftover cup of tea. It absorbs the life-force of those who drink it but
  it tastes so bad that it gets spat out immediately.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Cracked Pot
  Kind: Item
  Pokemon: '[[SRD-Polteageist]]'
GenderType: ''
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: Cursed Body
HomeSprite: SRD-sinistea-HomeSprite.png
Image: sinistea.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 854
ShuffleToken: SRD-sinistea-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 0.2
  Pounds: 0.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sinistea-BookSprite.png|wsmall]]
> ![[SRD-sinistea-HomeSprite.png]]
> ![[SRD-sinistea-BoxSprite.png|htiny]]
> ![[SRD-sinistea-ShuffleToken.png|wsmall]]


*Black Tea Pokemon*
*This Pokemon is said to have been born when a lonely spirit possessed a cold, leftover cup of tea. It absorbs the life-force of those who drink it but it tastes so bad that it gets spat out immediately.*

**DexID**:: 0854
**Name**:: Sinistea
**Type**:: Ghost
**Abilities**:: [[SRD-Weak Armor|Weak Armor]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'3" / 0.1m
**Weight**: 0.4lbs / 0.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon             | Kind   | Item        |
|:----------|:--------------------|:-------|:------------|
| To        | [[SRD-Polteageist]] | Item   | Cracked Pot |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sinistea.md"
flatten moves as T
where file.path = this.file.path
```
