---
Ability1: Poison Point
Ability2: Swarm
BookSprite: SRD-whirlipede-BookSprite.png
BoxSprite: SRD-whirlipede-BoxSprite.png
DexCategory: Curlipede Pokemon
DexDescription: It is usually motionless, when it is attacked, it rotates at high
  speed and then crashes into its opponent with its body full of poison spikes. Inside
  it is storing energy for evolving, which normally takes a few months.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Venipede]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Scolipede]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Speed Boost
HomeSprite: SRD-whirlipede-HomeSprite.png
Image: whirlipede.png
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
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Steamroller|Steamroller]]'
- - Ace
  - '[[SRD-Venoshock|Venoshock]]'
- - Ace
  - '[[SRD-Venom Drench|Venom Drench]]'
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
Number: 544
ShuffleToken: SRD-whirlipede-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 58.5
  Pounds: 129.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-whirlipede-BookSprite.png|wsmall]]
> ![[SRD-whirlipede-HomeSprite.png]]
> ![[SRD-whirlipede-BoxSprite.png|htiny]]
> ![[SRD-whirlipede-ShuffleToken.png|wsmall]]


*Curlipede Pokemon*
*It is usually motionless, when it is attacked, it rotates at high speed and then crashes into its opponent with its body full of poison spikes. Inside it is storing energy for evolving, which normally takes a few months.*

**DexID**:: 0544
**Name**:: Whirlipede
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Swarm|Swarm]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 129.0lbs / 58.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Venipede]]  | Level  | Medium  |
| To        | [[SRD-Scolipede]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Whirlipede.md"
flatten moves as T
where file.path = this.file.path
```
