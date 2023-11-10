---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-vibrava-BookSprite.png
BoxSprite: SRD-vibrava-BoxSprite.png
DexCategory: Vibration Pokemon
DexDescription: "This Pokemon\u2019s vibrations can cause severe headaches or even\
  \ fainting. If their prey faints, they proceed to melt them with acid. Vibrava's\
  \ wings are still growing, making it a clumsy flier with low endurance."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Trapinch]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Flygon]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: ''
HomeSprite: SRD-vibrava-HomeSprite.png
Image: vibrava.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Toxic|Toxic]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
Number: 329
ShuffleToken: SRD-vibrava-ShuffleToken.png
Type1: Ground
Type2: Dragon
Weight:
  Kilograms: 15.3
  Pounds: 33.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vibrava-BookSprite.png|wsmall]]
> ![[SRD-vibrava-HomeSprite.png]]
> ![[SRD-vibrava-BoxSprite.png|htiny]]
> ![[SRD-vibrava-ShuffleToken.png|wsmall]]


*Vibration Pokemon*
*This Pokemon’s vibrations can cause severe headaches or even fainting. If their prey faints, they proceed to melt them with acid. Vibrava's wings are still growing, making it a clumsy flier with low endurance.*

**DexID**:: 0329
**Name**:: Vibrava
**Type**:: Ground / Dragon
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 33.7lbs / 15.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Trapinch]] | Level  | Medium  |
| To        | [[SRD-Flygon]]   | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vibrava.md"
flatten moves as T
where file.path = this.file.path
```
