---
Ability1: Run Away
Ability2: Adaptability
BookSprite: SRD-eevee-BookSprite.png
BoxSprite: SRD-eevee-BoxSprite.png
DexCategory: Evolution Pokemon
DexDescription: This Pokemon is extremely rare to find. Eevee has an unstable genetic
  makeup that suddenly mutates to fit its environment. Radiation from various stones
  causes this Pokemon to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Vaporeon]]'
- Evolves: To
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Jolteon]]'
- Evolves: To
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Flareon]]'
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Espeon]]'
  Special: Sunlight
  Stat: Happiness
  Value: 4
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Umbreon]]'
  Special: Moonlight
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Leafeon]]'
- Evolves: To
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Glaceon]]'
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Sylveon]]'
  Stat: Loyalty
  Value: 5
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Anticipation
HomeSprite: SRD-eevee-HomeSprite.png
Image: eevee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Trump Card|Trump Card]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 133
ShuffleToken: SRD-eevee-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eevee-BookSprite.png|wsmall]]
> ![[SRD-eevee-HomeSprite.png]]
> ![[SRD-eevee-BoxSprite.png|htiny]]
> ![[SRD-eevee-ShuffleToken.png|wsmall]]


*Evolution Pokemon*
*This Pokemon is extremely rare to find. Eevee has an unstable genetic makeup that suddenly mutates to fit its environment. Radiation from various stones causes this Pokemon to evolve.*

**DexID**:: 0133
**Name**:: Eevee
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Adaptability|Adaptability]] ([[SRD-Anticipation|Anticipation]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind    | Item          | Stat      | Value   | Special   |
|:----------|:-----------------|:--------|:--------------|:----------|:--------|:----------|
| To        | [[SRD-Vaporeon]] | Stone   | Water Stone   |           |         |           |
| To        | [[SRD-Jolteon]]  | Stone   | Thunder Stone |           |         |           |
| To        | [[SRD-Flareon]]  | Stone   | Fire Stone    |           |         |           |
| To        | [[SRD-Espeon]]   | Special |               | Happiness | 4.0     | Sunlight  |
| To        | [[SRD-Umbreon]]  | Special |               | Happiness | 4.0     | Moonlight |
| To        | [[SRD-Leafeon]]  | Stone   | Leaf Stone    |           |         |           |
| To        | [[SRD-Glaceon]]  | Stone   | Ice Stone     |           |         |           |
| To        | [[SRD-Sylveon]]  | Stat    |               | Loyalty   | 5.0     |           |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Eevee.md"
flatten moves as T
where file.path = this.file.path
```
