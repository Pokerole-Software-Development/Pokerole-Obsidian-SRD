---
Ability1: Poison Point
Ability2: Swarm
BookSprite: SRD-scolipede-BookSprite.png
BoxSprite: SRD-scolipede-BoxSprite.png
DexCategory: Megapede Pokemon
DexDescription: Highly aggressive, it uses the claws on its neck to immobilize its
  prey and then inject them with poison to finish them off. Be very careful around
  this Pokemon as it will chase you relentlessly until it gets you.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Whirlipede]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: Speed Boost
HomeSprite: SRD-scolipede-HomeSprite.png
Image: scolipede.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Tail|Poison Tail]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Steamroller|Steamroller]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Venom Drench|Venom Drench]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
Number: 545
ShuffleToken: SRD-scolipede-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 200.5
  Pounds: 442.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scolipede-BookSprite.png|wsmall]]
> ![[SRD-scolipede-HomeSprite.png]]
> ![[SRD-scolipede-BoxSprite.png|htiny]]
> ![[SRD-scolipede-ShuffleToken.png|wsmall]]


*Megapede Pokemon*
*Highly aggressive, it uses the claws on its neck to immobilize its prey and then inject them with poison to finish them off. Be very careful around this Pokemon as it will chase you relentlessly until it gets you.*

**DexID**:: 0545
**Name**:: Scolipede
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Swarm|Swarm]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'2" / 2.5m
**Weight**: 442.0lbs / 200.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Whirlipede]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Scolipede.md"
flatten moves as T
where file.path = this.file.path
```
