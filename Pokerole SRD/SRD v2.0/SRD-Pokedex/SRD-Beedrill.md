---
Ability1: Swarm
Ability2: ''
BookSprite: SRD-beedrill-BookSprite.png
BoxSprite: SRD-beedrill-BoxSprite.png
DexCategory: Poison Bee Pokemon
DexDescription: Beedrill are extremely territorial. For safety reasons, no one should
  ever approach their nest. If disturbed, they will attack in swarm. It has three
  stings. The one on its tail secretes a powerful poison.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Kakuna]]'
  Speed: Fast
- Evolves: To
  Item: Beedrillite
  Kind: Mega
  Pokemon: '[[SRD-Beedrill (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sniper
HomeSprite: SRD-beedrill-HomeSprite.png
Image: beedrill.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Twineedle|Twineedle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
Number: 15
ShuffleToken: SRD-beedrill-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 29.5
  Pounds: 65.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beedrill-BookSprite.png|wsmall]]
> ![[SRD-beedrill-HomeSprite.png]]
> ![[SRD-beedrill-BoxSprite.png|htiny]]
> ![[SRD-beedrill-ShuffleToken.png|wsmall]]


*Poison Bee Pokemon*
*Beedrill are extremely territorial. For safety reasons, no one should ever approach their nest. If disturbed, they will attack in swarm. It has three stings. The one on its tail secretes a powerful poison.*

**DexID**:: 0015
**Name**:: Beedrill
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Swarm|Swarm]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 65.0lbs / 29.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Kakuna]]               | Level  | Fast    |             |
| To        | [[SRD-Beedrill (Mega Form)]] | Mega   |         | Beedrillite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Beedrill.md"
flatten moves as T
where file.path = this.file.path
```
