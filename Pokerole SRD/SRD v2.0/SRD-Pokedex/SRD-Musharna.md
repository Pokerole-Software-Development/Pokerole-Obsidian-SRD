---
Ability1: Forewarn
Ability2: Synchronize
BookSprite: SRD-musharna-BookSprite.png
BoxSprite: SRD-musharna-BoxSprite.png
DexCategory: Drowsing Pokemon
DexDescription: It communicates with the mist on its forehead, it can create shapes
  and images from dreams it has eaten. It is said that this Pokemon is a link between
  this world and a another one made entirely of dreams.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Munna]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Telepathy
HomeSprite: SRD-musharna-HomeSprite.png
Image: musharna.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic Terrain|Psychic Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Healing Wish|Healing Wish]]'
Number: 518
ShuffleToken: SRD-musharna-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 60.5
  Pounds: 133.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-musharna-BookSprite.png|wsmall]]
> ![[SRD-musharna-HomeSprite.png]]
> ![[SRD-musharna-BoxSprite.png|htiny]]
> ![[SRD-musharna-ShuffleToken.png|wsmall]]


*Drowsing Pokemon*
*It communicates with the mist on its forehead, it can create shapes and images from dreams it has eaten. It is said that this Pokemon is a link between this world and a another one made entirely of dreams.*

**DexID**:: 0518
**Name**:: Musharna
**Type**:: Psychic
**Abilities**:: [[SRD-Forewarn|Forewarn]] / [[SRD-Synchronize|Synchronize]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 133.4lbs / 60.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item       |
|:----------|:--------------|:-------|:-----------|
| From      | [[SRD-Munna]] | Stone  | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Musharna.md"
flatten moves as T
where file.path = this.file.path
```
