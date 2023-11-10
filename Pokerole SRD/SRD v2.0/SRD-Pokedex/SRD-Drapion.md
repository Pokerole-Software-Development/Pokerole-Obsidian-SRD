---
Ability1: Battle Armor
Ability2: Sniper
BookSprite: SRD-drapion-BookSprite.png
BoxSprite: SRD-drapion-BoxSprite.png
DexCategory: Ogre Scorp Pokemon
DexDescription: "This Pokemon is very aggressive. It can completely rotate its head\
  \ over its body, because of this, Drapion has no blind spots. Its venom is deadly\
  \ and it won\u2019t hesitate to use it."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Skorupi]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Keen Eye
HomeSprite: SRD-drapion-HomeSprite.png
Image: drapion.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Beginner
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Acupressure|Acupressure]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Poison Tail|Poison Tail]]'
Number: 452
ShuffleToken: SRD-drapion-ShuffleToken.png
Type1: Poison
Type2: Dark
Weight:
  Kilograms: 61.5
  Pounds: 135.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drapion-BookSprite.png|wsmall]]
> ![[SRD-drapion-HomeSprite.png]]
> ![[SRD-drapion-BoxSprite.png|htiny]]
> ![[SRD-drapion-ShuffleToken.png|wsmall]]


*Ogre Scorp Pokemon*
*This Pokemon is very aggressive. It can completely rotate its head over its body, because of this, Drapion has no blind spots. Its venom is deadly and it won’t hesitate to use it.*

**DexID**:: 0452
**Name**:: Drapion
**Type**:: Poison / Dark
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] / [[SRD-Sniper|Sniper]] ([[SRD-Keen Eye|Keen Eye]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 135.6lbs / 61.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Skorupi]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drapion.md"
flatten moves as T
where file.path = this.file.path
```
