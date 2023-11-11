---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-ho-oh-BookSprite.png
BoxSprite: SRD-ho-oh-BoxSprite.png
DexCategory: No Data
DexDescription: "Ho-oh inhabited the Bell Tower, where Pokemon were said to rest.\
  \ Ho-oh\u2019s Myth talks about a creature that brought eternal rest for those whose\
  \ time was right, and also gave back life if death was premature."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 12.5
  Meters: 3.8
HiddenAbility: Regenerator
HomeSprite: SRD-ho-oh-HomeSprite.png
Image: ho-oh.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sacred Fire|Sacred Fire]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Punishment|Punishment]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recover|Recover]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Weather Ball|Weather Ball]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash|Flash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defog|Defog]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Strength|Strength]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fly|Fly]]'
Number: 250
ShuffleToken: SRD-ho-oh-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 199.0
  Pounds: 438.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ho-oh-BookSprite.png|wsmall]]
> ![[SRD-ho-oh-HomeSprite.png]]
> ![[SRD-ho-oh-BoxSprite.png|htiny]]
> ![[SRD-ho-oh-ShuffleToken.png|wsmall]]


*No Data*
*Ho-oh inhabited the Bell Tower, where Pokemon were said to rest. Ho-oh’s Myth talks about a creature that brought eternal rest for those whose time was right, and also gave back life if death was premature.*

**DexID**:: 0250
**Name**:: Ho-oh
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 12'5" / 3.8m
**Weight**: 438.7lbs / 199.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ho-oh.md"
flatten moves as T
where file.path = this.file.path
```
