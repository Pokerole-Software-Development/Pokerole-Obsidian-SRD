---
Ability1: Swift Swim
Ability2: Sniper
BookSprite: SRD-kingdra-BookSprite.png
BoxSprite: SRD-kingdra-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: Kingdra sleeps on the seafloor where it is otherwise devoid of life.
  When a storm arrives, it is said to awaken and wander about in search of prey. They
  are known for creating twisters in the sea.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dragon Scale
  Kind: Trade
  Pokemon: '[[SRD-Seadra]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Damp
HomeSprite: SRD-kingdra-HomeSprite.png
Image: kingdra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble|Bubble]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Yawn|Yawn]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brine|Brine]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Muddy Water|Muddy Water]]'
Number: 230
ShuffleToken: SRD-kingdra-ShuffleToken.png
Type1: Water
Type2: Dragon
Weight:
  Kilograms: 152.0
  Pounds: 335.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kingdra-BookSprite.png|wsmall]]
> ![[SRD-kingdra-HomeSprite.png]]
> ![[SRD-kingdra-BoxSprite.png|htiny]]
> ![[SRD-kingdra-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*Kingdra sleeps on the seafloor where it is otherwise devoid of life. When a storm arrives, it is said to awaken and wander about in search of prey. They are known for creating twisters in the sea.*

**DexID**:: 0230
**Name**:: Kingdra
**Type**:: Water / Dragon
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Sniper|Sniper]] ([[SRD-Damp|Damp]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'9" / 1.8m
**Weight**: 335.1lbs / 152.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item         |
|:----------|:---------------|:-------|:-------------|
| From      | [[SRD-Seadra]] | Trade  | Dragon Scale |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kingdra.md"
flatten moves as T
where file.path = this.file.path
```
