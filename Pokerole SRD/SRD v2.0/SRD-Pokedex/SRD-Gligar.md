---
Ability1: Hyper Cutter
Ability2: Sand Veil
BookSprite: SRD-gligar-BookSprite.png
BoxSprite: SRD-gligar-BoxSprite.png
DexCategory: Fly Scorpion Pokemon
DexDescription: "It hangs from cliffs waiting for its prey. It flies straight at the\
  \ target\u2019s face, grapples the victim with its pincers and clawed hind legs,\
  \ lastly, it injects poison with its tail. Gligar can glide without making any noise."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Razor Fang
  Kind: Level
  Pokemon: '[[SRD-Gliscor]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Immunity
HomeSprite: SRD-gligar-HomeSprite.png
Image: gligar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Harden|Harden]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-U-Turn|U-Turn]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Screech|Screech]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sky Uppercut|Sky Uppercut]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Tail|Poison Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint|Feint]]'
Number: 207
ShuffleToken: SRD-gligar-ShuffleToken.png
Type1: Ground
Type2: Flying
Weight:
  Kilograms: 64.8
  Pounds: 142.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gligar-BookSprite.png|wsmall]]
> ![[SRD-gligar-HomeSprite.png]]
> ![[SRD-gligar-BoxSprite.png|htiny]]
> ![[SRD-gligar-ShuffleToken.png|wsmall]]


*Fly Scorpion Pokemon*
*It hangs from cliffs waiting for its prey. It flies straight at the target’s face, grapples the victim with its pincers and clawed hind legs, lastly, it injects poison with its tail. Gligar can glide without making any noise.*

**DexID**:: 0207
**Name**:: Gligar
**Type**:: Ground / Flying
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Sand Veil|Sand Veil]] ([[SRD-Immunity|Immunity]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 142.9lbs / 64.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| To        | [[SRD-Gliscor]] | Level  | Razor Fang |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gligar.md"
flatten moves as T
where file.path = this.file.path
```
