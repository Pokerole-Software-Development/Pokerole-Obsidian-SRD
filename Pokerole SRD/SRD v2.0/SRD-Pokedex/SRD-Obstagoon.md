---
Ability1: Prankster
Ability2: Frisk
BookSprite: SRD-obstagoon-BookSprite.png
BoxSprite: SRD-obstagoon-BoxSprite.png
DexCategory: Blocking Pokemon
DexDescription: Its voice has a very loud volume and it is a noisy and rude Pokemon.
  Obstagoon has a tendency to take on a threatening posture and shout at anyone that
  is in front of it. They rarely take things seriously.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Linoone (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Pickpocket
HomeSprite: SRD-obstagoon-HomeSprite.png
Image: obstagoon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Obstruct|Obstruct]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Hyper Voice|Hyper Voice]]'
Number: 862
ShuffleToken: SRD-obstagoon-ShuffleToken.png
Type1: Dark
Type2: Normal
Weight:
  Kilograms: 46.0
  Pounds: 101.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-obstagoon-BookSprite.png|wsmall]]
> ![[SRD-obstagoon-HomeSprite.png]]
> ![[SRD-obstagoon-BoxSprite.png|htiny]]
> ![[SRD-obstagoon-ShuffleToken.png|wsmall]]


*Blocking Pokemon*
*Its voice has a very loud volume and it is a noisy and rude Pokemon. Obstagoon has a tendency to take on a threatening posture and shout at anyone that is in front of it. They rarely take things seriously.*

**DexID**:: 0862
**Name**:: Obstagoon
**Type**:: Dark / Normal
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Frisk|Frisk]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 101.4lbs / 46.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                         | Kind   | Speed   |
|:----------|:--------------------------------|:-------|:--------|
| From      | [[SRD-Linoone (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Obstagoon.md"
flatten moves as T
where file.path = this.file.path
```
