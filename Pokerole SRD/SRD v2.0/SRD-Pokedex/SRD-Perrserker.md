---
Ability1: Battle Armor
Ability2: Tough Claws
BookSprite: SRD-perrserker-BookSprite.png
BoxSprite: SRD-perrserker-BoxSprite.png
DexCategory: Viking Pokemon
DexDescription: What appears to be an iron helmet is actually hardened hair. Unlike
  other Meowth evolutions, Perrserker does not want riches and luxury, it enjoys battles,
  the outdoors and traveling though the sea.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Meowth (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Steely Spirit
HomeSprite: SRD-perrserker-HomeSprite.png
Image: perrserker.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pay Day|Pay Day]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[SRD-Throat Chop|Throat Chop]]'
Number: 863
ShuffleToken: SRD-perrserker-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-perrserker-BookSprite.png|wsmall]]
> ![[SRD-perrserker-HomeSprite.png]]
> ![[SRD-perrserker-BoxSprite.png|htiny]]
> ![[SRD-perrserker-ShuffleToken.png|wsmall]]


*Viking Pokemon*
*What appears to be an iron helmet is actually hardened hair. Unlike other Meowth evolutions, Perrserker does not want riches and luxury, it enjoys battles, the outdoors and traveling though the sea.*

**DexID**:: 0863
**Name**:: Perrserker
**Type**:: Steel
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] / [[SRD-Tough Claws|Tough Claws]] ([[SRD-Steely Spirit|Steely Spirit]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                        | Kind   | Speed   |
|:----------|:-------------------------------|:-------|:--------|
| From      | [[SRD-Meowth (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Perrserker.md"
flatten moves as T
where file.path = this.file.path
```
