---
Ability1: Poison Point
Ability2: Poison Touch
BookSprite: SRD-dragalge-BookSprite.png
BoxSprite: SRD-dragalge-BoxSprite.png
DexCategory: Mock Kelp Pokemon
DexDescription: Their poison is strong enough to eat through the hull of a tanker,
  and they spit it indiscriminately at anything that enters their territory. Touching
  them can be fatal if you are not treated within a few hours.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Skrelp]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Adaptability
HomeSprite: SRD-dragalge-HomeSprite.png
Image: dragalge.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Twister|Twister]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 691
ShuffleToken: SRD-dragalge-ShuffleToken.png
Type1: Poison
Type2: Dragon
Weight:
  Kilograms: 81.5
  Pounds: 179.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dragalge-BookSprite.png|wsmall]]
> ![[SRD-dragalge-HomeSprite.png]]
> ![[SRD-dragalge-BoxSprite.png|htiny]]
> ![[SRD-dragalge-ShuffleToken.png|wsmall]]


*Mock Kelp Pokemon*
*Their poison is strong enough to eat through the hull of a tanker, and they spit it indiscriminately at anything that enters their territory. Touching them can be fatal if you are not treated within a few hours.*

**DexID**:: 0691
**Name**:: Dragalge
**Type**:: Poison / Dragon
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Poison Touch|Poison Touch]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 5'9" / 1.8m
**Weight**: 179.7lbs / 81.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Skrelp]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dragalge.md"
flatten moves as T
where file.path = this.file.path
```
