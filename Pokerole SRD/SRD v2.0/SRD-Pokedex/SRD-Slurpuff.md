---
Ability1: Sweet Veil
Ability2: ''
BookSprite: SRD-slurpuff-BookSprite.png
BoxSprite: SRD-slurpuff-BoxSprite.png
DexCategory: Meringue Pokemon
DexDescription: This Pokemon lives in human cities and towns. It has an extremely
  keen sense of smell. It puts its sensitive nose to use by helping bakers and chefs
  to find the most delicious ingredients.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Whipped Dream
  Kind: Trade
  Pokemon: '[[SRD-Swirlix]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Unburden
HomeSprite: SRD-slurpuff-HomeSprite.png
Image: slurpuff.png
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
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Copycat|Copycat]]'
Number: 685
ShuffleToken: SRD-slurpuff-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slurpuff-BookSprite.png|wsmall]]
> ![[SRD-slurpuff-HomeSprite.png]]
> ![[SRD-slurpuff-BoxSprite.png|htiny]]
> ![[SRD-slurpuff-ShuffleToken.png|wsmall]]


*Meringue Pokemon*
*This Pokemon lives in human cities and towns. It has an extremely keen sense of smell. It puts its sensitive nose to use by helping bakers and chefs to find the most delicious ingredients.*

**DexID**:: 0685
**Name**:: Slurpuff
**Type**:: Fairy
**Abilities**:: [[SRD-Sweet Veil|Sweet Veil]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item          |
|:----------|:----------------|:-------|:--------------|
| From      | [[SRD-Swirlix]] | Trade  | Whipped Dream |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slurpuff.md"
flatten moves as T
where file.path = this.file.path
```
