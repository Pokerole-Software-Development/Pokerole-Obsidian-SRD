---
Ability1: Skill Link
Ability2: ''
BookSprite: SRD-heracross-mega-form-BookSprite.png
BoxSprite: SRD-heracross-mega-form-BoxSprite.png
DexCategory: Single Horn Pokemon
DexDescription: With the power of the Mega Stone its muscles and exoskeleton grow
  in size and strength but after going back to normal its exoskeleton reduces size
  but its muscles do not and that causes it to feel sore.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Heracronite
  Kind: Mega
  Pokemon: '[[SRD-Heracross]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-heracross-mega-form-HomeSprite.png
Image: heracross-mega-form.png
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
ShuffleToken: SRD-heracross-mega-form-ShuffleToken.png
Type1: Bug
Type2: Fighting
Weight:
  Kilograms: 62.5
  Pounds: 137.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-heracross-mega-form-BookSprite.png|wsmall]]
> ![[SRD-heracross-mega-form-HomeSprite.png]]
> ![[SRD-heracross-mega-form-BoxSprite.png|htiny]]
> ![[SRD-heracross-mega-form-ShuffleToken.png|wsmall]]


*Single Horn Pokemon*
*With the power of the Mega Stone its muscles and exoskeleton grow in size and strength but after going back to normal its exoskeleton reduces size but its muscles do not and that causes it to feel sore.*

**DexID**:: 0214M1
**Name**:: Heracross (Mega Form)
**Type**:: Bug / Fighting
**Abilities**:: [[SRD-Skill Link|Skill Link]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 137.8lbs / 62.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Item        |
|:----------|:------------------|:-------|:------------|
| From      | [[SRD-Heracross]] | Mega   | Heracronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Heracross (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
