---
Ability1: Ripen
Ability2: Gluttony
BookSprite: SRD-flapple-BookSprite.png
BoxSprite: SRD-flapple-BoxSprite.png
DexCategory: Apple Wing Pokemon
DexDescription: It grew inside a sour apple, and thus developed an acid that can cause
  chemical burns. It uses the discarded apple skin to fly or disguise itself as a
  rancid apple. They are loners as not many like how it looks or smells.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Tart Apple
  Kind: Item
  Pokemon: '[[SRD-Applin]]'
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Hustle
HomeSprite: SRD-flapple-HomeSprite.png
Image: flapple.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wing Attack|Wing Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recycle|Recycle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grav Apple|Grav Apple]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fly|Fly]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
Number: 841
ShuffleToken: SRD-flapple-ShuffleToken.png
Type1: Grass
Type2: Dragon
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-flapple-BookSprite.png|wsmall]]
> ![[SRD-flapple-HomeSprite.png]]
> ![[SRD-flapple-BoxSprite.png|htiny]]
> ![[SRD-flapple-ShuffleToken.png|wsmall]]


*Apple Wing Pokemon*
*It grew inside a sour apple, and thus developed an acid that can cause chemical burns. It uses the discarded apple skin to fly or disguise itself as a rancid apple. They are loners as not many like how it looks or smells.*

**DexID**:: 0841
**Name**:: Flapple
**Type**:: Grass / Dragon
**Abilities**:: [[SRD-Ripen|Ripen]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item       |
|:----------|:---------------|:-------|:-----------|
| From      | [[SRD-Applin]] | Item   | Tart Apple |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Flapple.md"
flatten moves as T
where file.path = this.file.path
```
