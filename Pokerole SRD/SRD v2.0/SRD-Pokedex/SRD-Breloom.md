---
Ability1: Effect Spore
Ability2: Poison Heal
BookSprite: SRD-breloom-BookSprite.png
BoxSprite: SRD-breloom-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: Their flexible arms and quick footwork can put good fighters to shame.
  The seeds on their tail and the cap on their head release poison spores. They love
  humid and hot climates.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shroomish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Technician
HomeSprite: SRD-breloom-HomeSprite.png
Image: breloom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 286
ShuffleToken: SRD-breloom-ShuffleToken.png
Type1: Grass
Type2: Fighting
Weight:
  Kilograms: 39.2
  Pounds: 86.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-breloom-BookSprite.png|wsmall]]
> ![[SRD-breloom-HomeSprite.png]]
> ![[SRD-breloom-BoxSprite.png|htiny]]
> ![[SRD-breloom-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*Their flexible arms and quick footwork can put good fighters to shame. The seeds on their tail and the cap on their head release poison spores. They love humid and hot climates.*

**DexID**:: 0286
**Name**:: Breloom
**Type**:: Grass / Fighting
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] / [[SRD-Poison Heal|Poison Heal]] ([[SRD-Technician|Technician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 86.4lbs / 39.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Shroomish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Breloom.md"
flatten moves as T
where file.path = this.file.path
```
