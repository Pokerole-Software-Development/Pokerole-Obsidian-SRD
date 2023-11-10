---
Ability1: Stance Change
Ability2: ''
BookSprite: SRD-aegislash-BookSprite.png
BoxSprite: SRD-aegislash-BoxSprite.png
DexCategory: Royal Sword Pokemon
DexDescription: The legend tells of how this Pokemon lead the first King of Kalos
  to victory. A crushing grip can be felt on the arm of the wielder. While in this
  form it can only use Support moves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Doublade]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Aegislash (Blade Form)]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-aegislash-HomeSprite.png
Image: aegislash.png
Legendary: 'No'
Moves:
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-King''s Shield|King''s Shield]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 681
ShuffleToken: SRD-aegislash-ShuffleToken.png
Type1: Steel
Type2: Ghost
Weight:
  Kilograms: 53.0
  Pounds: 116.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aegislash-BookSprite.png|wsmall]]
> ![[SRD-aegislash-HomeSprite.png]]
> ![[SRD-aegislash-BoxSprite.png|htiny]]
> ![[SRD-aegislash-ShuffleToken.png|wsmall]]


*Royal Sword Pokemon*
*The legend tells of how this Pokemon lead the first King of Kalos to victory. A crushing grip can be felt on the arm of the wielder. While in this form it can only use Support moves.*

**DexID**:: 0681
**Name**:: Aegislash
**Type**:: Steel / Ghost
**Abilities**:: [[SRD-Stance Change|Stance Change]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::4)/(MaxInsight::8)     |

**Height**: 5'6" / 1.7m
**Weight**: 116.8lbs / 53.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                        | Kind   | Item       |
|:----------|:-------------------------------|:-------|:-----------|
| From      | [[SRD-Doublade]]               | Stone  | Dusk Stone |
| To        | [[SRD-Aegislash (Blade Form)]] | Form   |            |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aegislash.md"
flatten moves as T
where file.path = this.file.path
```
