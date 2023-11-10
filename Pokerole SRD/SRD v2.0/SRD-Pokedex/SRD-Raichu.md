---
Ability1: Static
Ability2: ''
BookSprite: SRD-raichu-BookSprite.png
BoxSprite: SRD-raichu-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: When electricity builds on its body, it starts to emit a faint glow
  and it becomes more aggressive than it normally is. They live in forests but are
  rare to find in the wild.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Pikachu]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Lightning Rod
HomeSprite: SRD-raichu-HomeSprite.png
Image: raichu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Volt Tackle|Volt Tackle]]'
Number: 26
ShuffleToken: SRD-raichu-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-raichu-BookSprite.png|wsmall]]
> ![[SRD-raichu-HomeSprite.png]]
> ![[SRD-raichu-BoxSprite.png|htiny]]
> ![[SRD-raichu-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*When electricity builds on its body, it starts to emit a faint glow and it becomes more aggressive than it normally is. They live in forests but are rare to find in the wild.*

**DexID**:: 0026
**Name**:: Raichu
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item          |
|:----------|:----------------|:-------|:--------------|
| From      | [[SRD-Pikachu]] | Stone  | Thunder Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Raichu.md"
flatten moves as T
where file.path = this.file.path
```
