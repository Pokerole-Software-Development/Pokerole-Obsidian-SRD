---
Ability1: Poison Point
Ability2: Swarm
BookSprite: SRD-venipede-BookSprite.png
BoxSprite: SRD-venipede-BoxSprite.png
DexCategory: Centipede Pokemon
DexDescription: "Incredibly aggressive for a Pokemon that size. It uses the feelers\
  \ on it\u2019s front and back to locate things around. Its bite injects a potent\
  \ venom, enough to deter the large bird Pokemon that try to prey on it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Whirlipede]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Speed Boost
HomeSprite: SRD-venipede-HomeSprite.png
Image: venipede.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Steamroller|Steamroller]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Pin Missile|Pin Missile]]'
Number: 543
ShuffleToken: SRD-venipede-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 5.3
  Pounds: 11.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-venipede-BookSprite.png|wsmall]]
> ![[SRD-venipede-HomeSprite.png]]
> ![[SRD-venipede-BoxSprite.png|htiny]]
> ![[SRD-venipede-ShuffleToken.png|wsmall]]


*Centipede Pokemon*
*Incredibly aggressive for a Pokemon that size. It uses the feelers on it’s front and back to locate things around. Its bite injects a potent venom, enough to deter the large bird Pokemon that try to prey on it.*

**DexID**:: 0543
**Name**:: Venipede
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Swarm|Swarm]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 11.7lbs / 5.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Whirlipede]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Venipede.md"
flatten moves as T
where file.path = this.file.path
```
