---
Ability1: Steadfast
Ability2: Inner Focus
BookSprite: SRD-lucario-BookSprite.png
BoxSprite: SRD-lucario-BoxSprite.png
DexCategory: Aura Pokemon
DexDescription: This Pokemon is completely loyal to its trainer. It has the ability
  to not only see the auras but also to transform them into energy. It is also capable
  of understanding human speech.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Riolu]]'
  Stat: Loyalty
  Value: 5
- Evolves: To
  Item: Lucarionite
  Kind: Mega
  Pokemon: '[[SRD-Lucario (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Justified
HomeSprite: SRD-lucario-HomeSprite.png
Image: lucario.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
Number: 448
ShuffleToken: SRD-lucario-ShuffleToken.png
Type1: Fighting
Type2: Steel
Weight:
  Kilograms: 54.0
  Pounds: 119.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lucario-BookSprite.png|wsmall]]
> ![[SRD-lucario-HomeSprite.png]]
> ![[SRD-lucario-BoxSprite.png|htiny]]
> ![[SRD-lucario-ShuffleToken.png|wsmall]]


*Aura Pokemon*
*This Pokemon is completely loyal to its trainer. It has the ability to not only see the auras but also to transform them into energy. It is also capable of understanding human speech.*

**DexID**:: 0448
**Name**:: Lucario
**Type**:: Fighting / Steel
**Abilities**:: [[SRD-Steadfast|Steadfast]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Justified|Justified]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 119.0lbs / 54.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                     | Kind   | Stat    | Value   | Item        |
|:----------|:----------------------------|:-------|:--------|:--------|:------------|
| From      | [[SRD-Riolu]]               | Stat   | Loyalty | 5.0     |             |
| To        | [[SRD-Lucario (Mega Form)]] | Mega   |         |         | Lucarionite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lucario.md"
flatten moves as T
where file.path = this.file.path
```
