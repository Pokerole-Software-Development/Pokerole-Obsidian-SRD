---
Ability1: RKS System
Ability2: ''
BookSprite: SRD-silvally-BookSprite.png
BoxSprite: SRD-silvally-BoxSprite.png
DexCategory: Synthetic Pokemon
DexDescription: 'Pokedex has no data. It was seen in the company of a boy. It appears
  to be a perfected or evolved form of Type: Null. The boy gave it some strange disks
  that allowed it to change its type.'
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Type: Null]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: ''
HomeSprite: SRD-silvally-HomeSprite.png
Image: silvally.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Multi-Attack|Multi-Attack]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Razor Wind|Razor Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Pro
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[SRD-Parting Shot|Parting Shot]]'
Number: 773
ShuffleToken: SRD-silvally-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 100.5
  Pounds: 221.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-silvally-BookSprite.png|wsmall]]
> ![[SRD-silvally-HomeSprite.png]]
> ![[SRD-silvally-BoxSprite.png|htiny]]
> ![[SRD-silvally-ShuffleToken.png|wsmall]]


*Synthetic Pokemon*
*Pokedex has no data. It was seen in the company of a boy. It appears to be a perfected or evolved form of Type: Null. The boy gave it some strange disks that allowed it to change its type.*

**DexID**:: 0773
**Name**:: Silvally
**Type**:: Normal
**Abilities**:: [[SRD-RKS System|RKS System]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 7'5" / 2.3m
**Weight**: 221.6lbs / 100.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Type: Null]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Silvally.md"
flatten moves as T
where file.path = this.file.path
```
