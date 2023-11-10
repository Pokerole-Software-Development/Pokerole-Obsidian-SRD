---
Ability1: Sweet Veil
Ability2: ''
BookSprite: SRD-swirlix-BookSprite.png
BoxSprite: SRD-swirlix-BoxSprite.png
DexCategory: Cotton Candy Pokemon
DexDescription: Because it eats nothing but sweet fruit, honey and sugars, its fur
  is as sticky and sweet as cotton candy. To entangle its opponents in battle, it
  extrudes white and sticky threads but the foes end up eating them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Whipped Dream
  Kind: Trade
  Pokemon: '[[SRD-Slurpuff]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Unburden
HomeSprite: SRD-swirlix-HomeSprite.png
Image: swirlix.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Amateur
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Copycat|Copycat]]'
Number: 684
ShuffleToken: SRD-swirlix-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 3.5
  Pounds: 7.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swirlix-BookSprite.png|wsmall]]
> ![[SRD-swirlix-HomeSprite.png]]
> ![[SRD-swirlix-BoxSprite.png|htiny]]
> ![[SRD-swirlix-ShuffleToken.png|wsmall]]


*Cotton Candy Pokemon*
*Because it eats nothing but sweet fruit, honey and sugars, its fur is as sticky and sweet as cotton candy. To entangle its opponents in battle, it extrudes white and sticky threads but the foes end up eating them.*

**DexID**:: 0684
**Name**:: Swirlix
**Type**:: Fairy
**Abilities**:: [[SRD-Sweet Veil|Sweet Veil]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 7.7lbs / 3.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item          |
|:----------|:-----------------|:-------|:--------------|
| To        | [[SRD-Slurpuff]] | Trade  | Whipped Dream |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Swirlix.md"
flatten moves as T
where file.path = this.file.path
```
