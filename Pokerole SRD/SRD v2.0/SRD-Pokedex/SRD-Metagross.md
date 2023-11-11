---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-metagross-BookSprite.png
BoxSprite: SRD-metagross-BoxSprite.png
DexCategory: Iron Leg Pokemon
DexDescription: It has four powerful brains that allow it to react at the speed of
  a super computer. It pins its prey under its massive body, then eats it using the
  large mouth on its stomach. A powerful and ruthless Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Metang]]'
  Speed: Slow
- Evolves: To
  Item: Metagrossite
  Kind: Mega
  Pokemon: '[[SRD-Metagross (Mega Form)]]'
GenderType: N
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Light Metal
HomeSprite: SRD-metagross-HomeSprite.png
Image: metagross.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Meteor Mash|Meteor Mash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Block|Block]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Telekinesis|Telekinesis]]'
Number: 376
ShuffleToken: SRD-metagross-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 550.0
  Pounds: 1212.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-metagross-BookSprite.png|wsmall]]
> ![[SRD-metagross-HomeSprite.png]]
> ![[SRD-metagross-BoxSprite.png|htiny]]
> ![[SRD-metagross-ShuffleToken.png|wsmall]]


*Iron Leg Pokemon*
*It has four powerful brains that allow it to react at the speed of a super computer. It pins its prey under its massive body, then eats it using the large mouth on its stomach. A powerful and ruthless Pokemon.*

**DexID**:: 0376
**Name**:: Metagross
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Light Metal|Light Metal]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 1212.5lbs / 550.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                       | Kind   | Speed   | Item         |
|:----------|:------------------------------|:-------|:--------|:-------------|
| From      | [[SRD-Metang]]                | Level  | Slow    |              |
| To        | [[SRD-Metagross (Mega Form)]] | Mega   |         | Metagrossite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Metagross.md"
flatten moves as T
where file.path = this.file.path
```
