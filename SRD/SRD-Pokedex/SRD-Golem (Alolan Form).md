---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-golem-alolan-form-BookSprite.png
BoxSprite: SRD-golem-alolan-form-BoxSprite.png
DexCategory: Megaton Pokemon
DexDescription: "The Alolan variant of Golem does not roll around like its counterpart,\
  \ instead it loads rocks into the charger on its head and shoots them around, if\
  \ the rocks miss, the electric shockwave doesn\u2019t."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Graveler (Alolan Form)]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Galvanize
HomeSprite: SRD-golem-alolan-form-HomeSprite.png
Image: golem-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Wild Charge|Wild Charge]]'
Number: 76
ShuffleToken: SRD-golem-alolan-form-ShuffleToken.png
Type1: Rock
Type2: Electric
Weight:
  Kilograms: 316.0
  Pounds: 696.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golem-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-golem-alolan-form-HomeSprite.png]]
> ![[SRD-golem-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-golem-alolan-form-ShuffleToken.png|wsmall]]


*Megaton Pokemon*
*The Alolan variant of Golem does not roll around like its counterpart, instead it loads rocks into the charger on its head and shoots them around, if the rocks miss, the electric shockwave doesn’t.*

**DexID**:: 0076A
**Name**:: Golem (Alolan Form)
**Type**:: Rock / Electric
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Galvanize|Galvanize]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 696.7lbs / 316.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                        | Kind   |
|:----------|:-------------------------------|:-------|
| From      | [[SRD-Graveler (Alolan Form)]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Golem (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
