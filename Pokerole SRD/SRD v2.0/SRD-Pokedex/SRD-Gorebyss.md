---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-gorebyss-BookSprite.png
BoxSprite: SRD-gorebyss-BoxSprite.png
DexCategory: South Sea Pokemon
DexDescription: Found in the depths of the southern seas. Their body is built to withstand
  the sea pressure. While it appears to be beautiful and harmless, it is a cruel and
  deceitful creature.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dragon Scale
  Kind: Trade
  Pokemon: '[[SRD-Clamperl]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Hydration
HomeSprite: SRD-gorebyss-HomeSprite.png
Image: gorebyss.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Bind|Bind]]'
- - Pro
  - '[[SRD-Muddy Water|Muddy Water]]'
Number: 368
ShuffleToken: SRD-gorebyss-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 22.6
  Pounds: 49.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gorebyss-BookSprite.png|wsmall]]
> ![[SRD-gorebyss-HomeSprite.png]]
> ![[SRD-gorebyss-BoxSprite.png|htiny]]
> ![[SRD-gorebyss-ShuffleToken.png|wsmall]]


*South Sea Pokemon*
*Found in the depths of the southern seas. Their body is built to withstand the sea pressure. While it appears to be beautiful and harmless, it is a cruel and deceitful creature.*

**DexID**:: 0368
**Name**:: Gorebyss
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 49.8lbs / 22.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item         |
|:----------|:-----------------|:-------|:-------------|
| From      | [[SRD-Clamperl]] | Trade  | Dragon Scale |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gorebyss.md"
flatten moves as T
where file.path = this.file.path
```
