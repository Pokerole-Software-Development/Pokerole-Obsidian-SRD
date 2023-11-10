---
Ability1: Run Away
Ability2: Flash Fire
BookSprite: SRD-rapidash-BookSprite.png
BoxSprite: SRD-rapidash-BoxSprite.png
DexCategory: Fire Horse Pokemon
DexDescription: It lives happily on prairies. It loves speed competitions - a herd
  can often be seen running alongside a train. It can regulate the heat of its mane
  as to let its trainer ride it, but only if it trusts him enough.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ponyta]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Flame Body
HomeSprite: SRD-rapidash-HomeSprite.png
Image: rapidash.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Inferno|Inferno]]'
- - Amateur
  - '[[SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
Number: 78
ShuffleToken: SRD-rapidash-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 95.0
  Pounds: 209.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rapidash-BookSprite.png|wsmall]]
> ![[SRD-rapidash-HomeSprite.png]]
> ![[SRD-rapidash-BoxSprite.png|htiny]]
> ![[SRD-rapidash-ShuffleToken.png|wsmall]]


*Fire Horse Pokemon*
*It lives happily on prairies. It loves speed competitions - a herd can often be seen running alongside a train. It can regulate the heat of its mane as to let its trainer ride it, but only if it trusts him enough.*

**DexID**:: 0078
**Name**:: Rapidash
**Type**:: Fire
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 209.4lbs / 95.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Ponyta]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rapidash.md"
flatten moves as T
where file.path = this.file.path
```
