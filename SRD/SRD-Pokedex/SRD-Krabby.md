---
Ability1: Hyper Cutter
Ability2: Shell Armor
BookSprite: SRD-krabby-BookSprite.png
BoxSprite: SRD-krabby-BoxSprite.png
DexCategory: River Crab Pokemon
DexDescription: A Krabby dig holes in the sand near the sea. They can be seen squabbling
  with each other over food and territory. They usually avoid humans but will fight
  if provoked.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kingler]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Sheer Force
HomeSprite: SRD-krabby-HomeSprite.png
Image: krabby.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - Ace
  - '[[SRD-Brine|Brine]]'
- - Ace
  - '[[SRD-Crabhammer|Crabhammer]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Mimic|Mimic]]'
Number: 98
ShuffleToken: SRD-krabby-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-krabby-BookSprite.png|wsmall]]
> ![[SRD-krabby-HomeSprite.png]]
> ![[SRD-krabby-BoxSprite.png|htiny]]
> ![[SRD-krabby-ShuffleToken.png|wsmall]]


*River Crab Pokemon*
*A Krabby dig holes in the sand near the sea. They can be seen squabbling with each other over food and territory. They usually avoid humans but will fight if provoked.*

**DexID**:: 0098
**Name**:: Krabby
**Type**:: Water
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Kingler]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Krabby.md"
flatten moves as T
where file.path = this.file.path
```
