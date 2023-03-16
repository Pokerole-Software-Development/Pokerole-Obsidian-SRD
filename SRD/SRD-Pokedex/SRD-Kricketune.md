---
Ability1: Swarm
Ability2: ''
BookSprite: SRD-kricketune-BookSprite.png
BoxSprite: SRD-kricketune-BoxSprite.png
DexCategory: Cricket Pokemon
DexDescription: It can make all kind of sounds with its antennae, arms and mouth.
  It signals emotions with different tunes but scientists still cannot define what
  they mean. They imitate the songs they hear.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Kricketot]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Technician
HomeSprite: SRD-kricketune-HomeSprite.png
Image: kricketune.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Absorb|Absorb]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Pro
  - '[[SRD-Mud Slap|Mud Slap]]'
Number: 402
ShuffleToken: SRD-kricketune-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 25.5
  Pounds: 56.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kricketune-BookSprite.png|wsmall]]
> ![[SRD-kricketune-HomeSprite.png]]
> ![[SRD-kricketune-BoxSprite.png|htiny]]
> ![[SRD-kricketune-ShuffleToken.png|wsmall]]


*Cricket Pokemon*
*It can make all kind of sounds with its antennae, arms and mouth. It signals emotions with different tunes but scientists still cannot define what they mean. They imitate the songs they hear.*

**DexID**:: 0402
**Name**:: Kricketune
**Type**:: Bug
**Abilities**:: [[SRD-Swarm|Swarm]] ([[SRD-Technician|Technician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 56.2lbs / 25.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Kricketot]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kricketune.md"
flatten moves as T
where file.path = this.file.path
```
