---
Ability1: Tough Claws
Ability2: ''
BookSprite: SRD-metagross-mega-form-BookSprite.png
BoxSprite: SRD-metagross-mega-form-BoxSprite.png
DexCategory: Iron Leg Pokemon
DexDescription: The power of the Mega Stone made its four minds combine. It is now
  a merciless machine-like beast. If it calculates its chances to win are diminishing
  it will clutch itself into its foe and self-destruct.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Metagrossite
  Kind: Mega
  Pokemon: '[[SRD-Metagross]]'
GenderType: N
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-metagross-mega-form-HomeSprite.png
Image: metagross-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Meteor Mash|Meteor Mash]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
Number: 376
ShuffleToken: SRD-metagross-mega-form-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 942.9
  Pounds: 2078.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-metagross-mega-form-BookSprite.png|wsmall]]
> ![[SRD-metagross-mega-form-HomeSprite.png]]
> ![[SRD-metagross-mega-form-BoxSprite.png|htiny]]
> ![[SRD-metagross-mega-form-ShuffleToken.png|wsmall]]


*Iron Leg Pokemon*
*The power of the Mega Stone made its four minds combine. It is now a merciless machine-like beast. If it calculates its chances to win are diminishing it will clutch itself into its foe and self-destruct.*

**DexID**:: 0376M1
**Name**:: Metagross (Mega Form)
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Tough Claws|Tough Claws]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 8'2" / 2.5m
**Weight**: 2078.7lbs / 942.9kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon           | Kind   | Item         |
|:----------|:------------------|:-------|:-------------|
| From      | [[SRD-Metagross]] | Mega   | Metagrossite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Metagross (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
