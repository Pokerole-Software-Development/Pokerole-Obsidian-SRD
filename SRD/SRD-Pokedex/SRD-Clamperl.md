---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-clamperl-BookSprite.png
BoxSprite: SRD-clamperl-BoxSprite.png
DexCategory: Bivalve Pokemon
DexDescription: It is protected by a sturdy shell which is used to catch its prey.
  Clamperl will produce a magnificent pearl once in a lifetime. That pearl is said
  to increase psychic powers and will sell for a lot of money.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Dragon Fang
  Kind: Trade
  Pokemon: '[[SRD-Huntail]]'
- Evolves: To
  Item: Dragon Scale
  Kind: Trade
  Pokemon: '[[SRD-Gorebyss]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Rattled
HomeSprite: SRD-clamperl-HomeSprite.png
Image: clamperl.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Clamp|Clamp]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
Number: 366
ShuffleToken: SRD-clamperl-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 52.5
  Pounds: 115.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clamperl-BookSprite.png|wsmall]]
> ![[SRD-clamperl-HomeSprite.png]]
> ![[SRD-clamperl-BoxSprite.png|htiny]]
> ![[SRD-clamperl-ShuffleToken.png|wsmall]]


*Bivalve Pokemon*
*It is protected by a sturdy shell which is used to catch its prey. Clamperl will produce a magnificent pearl once in a lifetime. That pearl is said to increase psychic powers and will sell for a lot of money.*

**DexID**:: 0366
**Name**:: Clamperl
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 115.7lbs / 52.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item         |
|:----------|:-----------------|:-------|:-------------|
| To        | [[SRD-Huntail]]  | Trade  | Dragon Fang  |
| To        | [[SRD-Gorebyss]] | Trade  | Dragon Scale |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Clamperl.md"
flatten moves as T
where file.path = this.file.path
```
