---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-articuno-BookSprite.png
BoxSprite: SRD-articuno-BoxSprite.png
DexCategory: No Data
DexDescription: Rumor has it that one appeared during a blizzard in front of two lost
  hikers who followed its glistening trail until they found the main road. Others
  say its silhouette can be seen during raging snow storms.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Snow Cloak
HomeSprite: SRD-articuno-HomeSprite.png
Image: articuno.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Master
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Hail|Hail]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Number: 144
ShuffleToken: SRD-articuno-ShuffleToken.png
Type1: Ice
Type2: Flying
Weight:
  Kilograms: 55.4
  Pounds: 122.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-articuno-BookSprite.png|wsmall]]
> ![[SRD-articuno-HomeSprite.png]]
> ![[SRD-articuno-BoxSprite.png|htiny]]
> ![[SRD-articuno-ShuffleToken.png|wsmall]]


*No Data*
*Rumor has it that one appeared during a blizzard in front of two lost hikers who followed its glistening trail until they found the main road. Others say its silhouette can be seen during raging snow storms.*

**DexID**:: 0144
**Name**:: Articuno
**Type**:: Ice / Flying
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Snow Cloak|Snow Cloak]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 5'6" / 1.7m
**Weight**: 122.1lbs / 55.4kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Articuno.md"
flatten moves as T
where file.path = this.file.path
```
