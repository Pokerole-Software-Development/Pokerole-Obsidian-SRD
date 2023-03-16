---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-turtwig-BookSprite.png
BoxSprite: SRD-turtwig-BoxSprite.png
DexCategory: Tiny Leaf Pokemon
DexDescription: It makes its home close to lakes, although it is rare to find one.
  The shell on its back is made of hardened soil and should be moist for it to be
  healthy. It uses photosynthesis to get energy.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Grotle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Shell Armor
HomeSprite: SRD-turtwig-HomeSprite.png
Image: turtwig.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 387
ShuffleToken: SRD-turtwig-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 10.2
  Pounds: 22.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-turtwig-BookSprite.png|wsmall]]
> ![[SRD-turtwig-HomeSprite.png]]
> ![[SRD-turtwig-BoxSprite.png|htiny]]
> ![[SRD-turtwig-ShuffleToken.png|wsmall]]


*Tiny Leaf Pokemon*
*It makes its home close to lakes, although it is rare to find one. The shell on its back is made of hardened soil and should be moist for it to be healthy. It uses photosynthesis to get energy.*

**DexID**:: 0387
**Name**:: Turtwig
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 22.5lbs / 10.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Grotle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Turtwig.md"
flatten moves as T
where file.path = this.file.path
```
