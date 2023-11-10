---
Ability1: Swift Swim
Ability2: Sniper
BookSprite: SRD-horsea-BookSprite.png
BoxSprite: SRD-horsea-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: It makes its nest in the shade of corals in shallow parts of the sea.
  If it senses danger, it spits a murky ink and flees. It has been seen shooting down
  flying bugs to eat them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Seadra]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Damp
HomeSprite: SRD-horsea-HomeSprite.png
Image: horsea.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Twister|Twister]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Octazooka|Octazooka]]'
Number: 116
ShuffleToken: SRD-horsea-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-horsea-BookSprite.png|wsmall]]
> ![[SRD-horsea-HomeSprite.png]]
> ![[SRD-horsea-BoxSprite.png|htiny]]
> ![[SRD-horsea-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*It makes its nest in the shade of corals in shallow parts of the sea. If it senses danger, it spits a murky ink and flees. It has been seen shooting down flying bugs to eat them.*

**DexID**:: 0116
**Name**:: Horsea
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Sniper|Sniper]] ([[SRD-Damp|Damp]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Seadra]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Horsea.md"
flatten moves as T
where file.path = this.file.path
```
