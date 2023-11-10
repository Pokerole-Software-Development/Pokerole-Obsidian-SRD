---
Ability1: Healer
Ability2: ''
BookSprite: SRD-aromatisse-BookSprite.png
BoxSprite: SRD-aromatisse-BoxSprite.png
DexCategory: Fragance Pokemon
DexDescription: Its scent is so overpowering that makes it difficult to simply be
  in close proximity to it. It emits scents that its foes dislike in order to gain
  an edge in battle. They can also produce pleasant and healing aromas.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sachet
  Kind: Trade
  Pokemon: '[[SRD-Spritzee]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Aroma Veil
HomeSprite: SRD-aromatisse-HomeSprite.png
Image: aromatisse.png
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
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
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
- - Ace
  - '[[SRD-Reflect|Reflect]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Disable|Disable]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 683
ShuffleToken: SRD-aromatisse-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 15.5
  Pounds: 34.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aromatisse-BookSprite.png|wsmall]]
> ![[SRD-aromatisse-HomeSprite.png]]
> ![[SRD-aromatisse-BoxSprite.png|htiny]]
> ![[SRD-aromatisse-ShuffleToken.png|wsmall]]


*Fragance Pokemon*
*Its scent is so overpowering that makes it difficult to simply be in close proximity to it. It emits scents that its foes dislike in order to gain an edge in battle. They can also produce pleasant and healing aromas.*

**DexID**:: 0683
**Name**:: Aromatisse
**Type**:: Fairy
**Abilities**:: [[SRD-Healer|Healer]] ([[SRD-Aroma Veil|Aroma Veil]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 34.2lbs / 15.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item   |
|:----------|:-----------------|:-------|:-------|
| From      | [[SRD-Spritzee]] | Trade  | Sachet |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aromatisse.md"
flatten moves as T
where file.path = this.file.path
```
