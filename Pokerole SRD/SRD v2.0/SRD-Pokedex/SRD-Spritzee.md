---
Ability1: Healer
Ability2: ''
BookSprite: SRD-spritzee-BookSprite.png
BoxSprite: SRD-spritzee-BoxSprite.png
DexCategory: Perfume Pokemon
DexDescription: In the past, rather than using a perfume, royal ladies had a Spritzee
  that would waft a fragrance they liked. They are popular today for this same reason.
  They are said to attract the opposite gender to you.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Sachet
  Kind: Trade
  Pokemon: '[[SRD-Aromatisse]]'
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Aroma Veil
HomeSprite: SRD-spritzee-HomeSprite.png
Image: spritzee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Starter
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Moonblast|Moonblast]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Disable|Disable]]'
- - Pro
  - '[[SRD-Covet|Covet]]'
Number: 682
ShuffleToken: SRD-spritzee-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spritzee-BookSprite.png|wsmall]]
> ![[SRD-spritzee-HomeSprite.png]]
> ![[SRD-spritzee-BoxSprite.png|htiny]]
> ![[SRD-spritzee-ShuffleToken.png|wsmall]]


*Perfume Pokemon*
*In the past, rather than using a perfume, royal ladies had a Spritzee that would waft a fragrance they liked. They are popular today for this same reason. They are said to attract the opposite gender to you.*

**DexID**:: 0682
**Name**:: Spritzee
**Type**:: Fairy
**Abilities**:: [[SRD-Healer|Healer]] ([[SRD-Aroma Veil|Aroma Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Item   |
|:----------|:-------------------|:-------|:-------|
| To        | [[SRD-Aromatisse]] | Trade  | Sachet |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Spritzee.md"
flatten moves as T
where file.path = this.file.path
```
