---
Ability1: Dark Aura
Ability2: ''
BookSprite: SRD-yveltal-BookSprite.png
BoxSprite: SRD-yveltal-BoxSprite.png
DexCategory: No Data
DexDescription: A Kalos legend tells about the eternal struggle between life and death.
  The main tale is about a King full of grief and hate who built a doomsday machine
  to kill everyone in the world.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 19.0
  Meters: 5.8
HiddenAbility: ''
HomeSprite: SRD-yveltal-HomeSprite.png
Image: yveltal.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Master
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Snarl|Snarl]]'
- - Master
  - '[[SRD-Oblivion Wing|Oblivion Wing]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Foul Play|Foul Play]]'
- - Master
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Master
  - '[[SRD-Focus Blast|Focus Blast]]'
- - Master
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Number: 717
ShuffleToken: SRD-yveltal-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 203.0
  Pounds: 447.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yveltal-BookSprite.png|wsmall]]
> ![[SRD-yveltal-HomeSprite.png]]
> ![[SRD-yveltal-BoxSprite.png|htiny]]
> ![[SRD-yveltal-ShuffleToken.png|wsmall]]


*No Data*
*A Kalos legend tells about the eternal struggle between life and death. The main tale is about a King full of grief and hate who built a doomsday machine to kill everyone in the world.*

**DexID**:: 0717
**Name**:: Yveltal
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Dark Aura|Dark Aura]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 19'0" / 5.8m
**Weight**: 447.5lbs / 203.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Yveltal.md"
flatten moves as T
where file.path = this.file.path
```
