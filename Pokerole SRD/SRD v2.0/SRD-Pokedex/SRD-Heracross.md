---
Ability1: Swarm
Ability2: Guts
BookSprite: SRD-heracross-BookSprite.png
BoxSprite: SRD-heracross-BoxSprite.png
DexCategory: Single Horn Pokemon
DexDescription: A docile creature that loves honey. They batter down trees with their
  powerful horn and chase off anyone who gets close to their prized honey. Not many
  Pokemon dare to mess with it in the wild.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Heracronite
  Kind: Mega
  Pokemon: '[[SRD-Heracross (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Moxie
HomeSprite: SRD-heracross-HomeSprite.png
Image: heracross.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Endure|Endure]]'
- - Starter
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Night Slash|Night Slash]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Pro
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 214
ShuffleToken: SRD-heracross-ShuffleToken.png
Type1: Bug
Type2: Fighting
Weight:
  Kilograms: 54.0
  Pounds: 119.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-heracross-BookSprite.png|wsmall]]
> ![[SRD-heracross-HomeSprite.png]]
> ![[SRD-heracross-BoxSprite.png|htiny]]
> ![[SRD-heracross-ShuffleToken.png|wsmall]]


*Single Horn Pokemon*
*A docile creature that loves honey. They batter down trees with their powerful horn and chase off anyone who gets close to their prized honey. Not many Pokemon dare to mess with it in the wild.*

**DexID**:: 0214
**Name**:: Heracross
**Type**:: Bug / Fighting
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Guts|Guts]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 119.0lbs / 54.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Item        |
|:----------|:------------------------------|:-------|:------------|
| To        | [[SRD-Heracross (Mega Form)]] | Mega   | Heracronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Heracross.md"
flatten moves as T
where file.path = this.file.path
```
