---
Ability1: Frisk
Ability2: ''
BookSprite: SRD-exeggutor-alolan-form-BookSprite.png
BoxSprite: SRD-exeggutor-alolan-form-BoxSprite.png
DexCategory: Coconut Pokemon
DexDescription: "Alola is the native region for this Pokemon, only in there it can\
  \ evolve into this form. With this size, its Psychic abilities are rarely needed\
  \ and its trainer\u2019s order\u2019s rarely heard. They enjoy the sun in the beach.."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Exeggcute]]'
  Region: Alola
GenderType: ''
Height:
  Feet: 35.8
  Meters: 10.9
HiddenAbility: Harvest
HomeSprite: SRD-exeggutor-alolan-form-HomeSprite.png
Image: exeggutor-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Barrage|Barrage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Egg Bomb|Egg Bomb]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Hammer|Dragon Hammer]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Tail|Dragon Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
Number: 103
ShuffleToken: SRD-exeggutor-alolan-form-ShuffleToken.png
Type1: Grass
Type2: Dragon
Weight:
  Kilograms: 415.6
  Pounds: 916.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-exeggutor-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-exeggutor-alolan-form-HomeSprite.png]]
> ![[SRD-exeggutor-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-exeggutor-alolan-form-ShuffleToken.png|wsmall]]


*Coconut Pokemon*
*Alola is the native region for this Pokemon, only in there it can evolve into this form. With this size, its Psychic abilities are rarely needed and its trainer’s order’s rarely heard. They enjoy the sun in the beach..*

**DexID**:: 0103A
**Name**:: Exeggutor (Alolan Form)
**Type**:: Grass / Dragon
**Abilities**:: [[SRD-Frisk|Frisk]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 35'8" / 10.9m
**Weight**: 916.2lbs / 415.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Item       | Region   |
|:----------|:------------------|:-------|:-----------|:---------|
| From      | [[SRD-Exeggcute]] | Stone  | Leaf Stone | Alola    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Exeggutor (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
