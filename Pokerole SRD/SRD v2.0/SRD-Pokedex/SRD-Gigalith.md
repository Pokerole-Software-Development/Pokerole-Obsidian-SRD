---
Ability1: Sturdy
Ability2: Sand Stream
BookSprite: SRD-gigalith-BookSprite.png
BoxSprite: SRD-gigalith-BoxSprite.png
DexCategory: Compressed Pokemon
DexDescription: "It is a serious Pokemon that doesn\u2019t interact with others too\
  \ much. It uses the sharp crystals in it\u2019s body to recharge using the sun\u2019\
  s energy. If angered it can bury it\u2019s foe under giant rock slides or explode\
  \ at will."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Boldore]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Sand Force
HomeSprite: SRD-gigalith-HomeSprite.png
Image: gigalith.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 526
ShuffleToken: SRD-gigalith-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 260.0
  Pounds: 573.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gigalith-BookSprite.png|wsmall]]
> ![[SRD-gigalith-HomeSprite.png]]
> ![[SRD-gigalith-BoxSprite.png|htiny]]
> ![[SRD-gigalith-ShuffleToken.png|wsmall]]


*Compressed Pokemon*
*It is a serious Pokemon that doesn’t interact with others too much. It uses the sharp crystals in it’s body to recharge using the sun’s energy. If angered it can bury it’s foe under giant rock slides or explode at will.*

**DexID**:: 0526
**Name**:: Gigalith
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Sand Stream|Sand Stream]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 573.2lbs / 260.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   |
|:----------|:----------------|:-------|
| From      | [[SRD-Boldore]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gigalith.md"
flatten moves as T
where file.path = this.file.path
```
