---
Ability1: Cute Charm
Ability2: Magic Guard
BookSprite: SRD-clefable-BookSprite.png
BoxSprite: SRD-clefable-BoxSprite.png
DexCategory: Fairy Pokemon
DexDescription: There are not many records about it in the wild. They are timid but
  playful. Clefable uses its wings to skip lightly as if it was flying. Its bouncy
  step lets it walk on water. On quiet, moonlit nights, it strolls near lakes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Clefairy]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Unaware
HomeSprite: SRD-clefable-HomeSprite.png
Image: clefable.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Spotlight|Spotlight]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Moonblast|Moonblast]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Ace
  - '[[SRD-Metronome|Metronome]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
Number: 36
ShuffleToken: SRD-clefable-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clefable-BookSprite.png|wsmall]]
> ![[SRD-clefable-HomeSprite.png]]
> ![[SRD-clefable-BoxSprite.png|htiny]]
> ![[SRD-clefable-ShuffleToken.png|wsmall]]


*Fairy Pokemon*
*There are not many records about it in the wild. They are timid but playful. Clefable uses its wings to skip lightly as if it was flying. Its bouncy step lets it walk on water. On quiet, moonlit nights, it strolls near lakes.*

**DexID**:: 0036
**Name**:: Clefable
**Type**:: Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Unaware|Unaware]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| From      | [[SRD-Clefairy]] | Stone  | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Clefable.md"
flatten moves as T
where file.path = this.file.path
```
