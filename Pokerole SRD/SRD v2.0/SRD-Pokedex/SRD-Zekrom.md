---
Ability1: Teravolt
Ability2: ''
BookSprite: SRD-zekrom-BookSprite.png
BoxSprite: SRD-zekrom-BoxSprite.png
DexCategory: No Data
DexDescription: An old rock tablet full of ancient symbols tells the story of two
  brothers. One of them wanted a world of ideals built with the energy of the young.
  The rest of the stone is broken as if struck by lightning.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 9.5
  Meters: 2.9
HiddenAbility: ''
HomeSprite: SRD-zekrom-HomeSprite.png
Image: zekrom.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Fang|Thunder Fang]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Imprison|Imprison]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunderbolt|Thunderbolt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fusion Bolt|Fusion Bolt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder|Thunder]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bolt Strike|Bolt Strike]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Topsy-Turvy|Topsy-Turvy]]'
Number: 644
ShuffleToken: SRD-zekrom-ShuffleToken.png
Type1: Dragon
Type2: Electric
Weight:
  Kilograms: 345.0
  Pounds: 760.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zekrom-BookSprite.png|wsmall]]
> ![[SRD-zekrom-HomeSprite.png]]
> ![[SRD-zekrom-BoxSprite.png|htiny]]
> ![[SRD-zekrom-ShuffleToken.png|wsmall]]


*No Data*
*An old rock tablet full of ancient symbols tells the story of two brothers. One of them wanted a world of ideals built with the energy of the young. The rest of the stone is broken as if struck by lightning.*

**DexID**:: 0644
**Name**:: Zekrom
**Type**:: Dragon / Electric
**Abilities**:: [[SRD-Teravolt|Teravolt]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 9'5" / 2.9m
**Weight**: 760.6lbs / 345.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zekrom.md"
flatten moves as T
where file.path = this.file.path
```
