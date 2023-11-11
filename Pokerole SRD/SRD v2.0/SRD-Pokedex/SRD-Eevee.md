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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Refresh|Refresh]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Covet|Covet]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trump Card|Trump Card]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tickle|Tickle]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Tears|Fake Tears]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Eevee.md"
flatten moves as T
where file.path = this.file.path
```
