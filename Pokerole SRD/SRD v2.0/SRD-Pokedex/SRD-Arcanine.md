---
Ability1: Intimidate
Ability2: Flash Fire
BookSprite: SRD-arcanine-BookSprite.png
BoxSprite: SRD-arcanine-BoxSprite.png
DexCategory: Legendary Pokemon
DexDescription: "Its proud and regal appearance has made it be revered by people of\
  \ ancient societies. Its magnificent bark conveys a sense of majesty. Anyone in\
  \ front of Arcanine can\u2019t help but stare in awe."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Growlithe]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Justified
HomeSprite: SRD-arcanine-HomeSprite.png
Image: arcanine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roar|Roar]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Fang|Fire Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Burn Up|Burn Up]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extreme Speed|Extreme Speed]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
Number: 59
ShuffleToken: SRD-arcanine-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 155.0
  Pounds: 341.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arcanine-BookSprite.png|wsmall]]
> ![[SRD-arcanine-HomeSprite.png]]
> ![[SRD-arcanine-BoxSprite.png|htiny]]
> ![[SRD-arcanine-ShuffleToken.png|wsmall]]


*Legendary Pokemon*
*Its proud and regal appearance has made it be revered by people of ancient societies. Its magnificent bark conveys a sense of majesty. Anyone in front of Arcanine can’t help but stare in awe.*

**DexID**:: 0059
**Name**:: Arcanine
**Type**:: Fire
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Justified|Justified]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 341.7lbs / 155.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Item       |
|:----------|:------------------|:-------|:-----------|
| From      | [[SRD-Growlithe]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arcanine.md"
flatten moves as T
where file.path = this.file.path
```
