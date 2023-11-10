---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-buzzwole-BookSprite.png
BoxSprite: SRD-buzzwole-BoxSprite.png
DexCategory: 'Aether Foundation Log #071'
DexDescription: "What we thought were harmless displays of strength were just the\
  \ first warning signs. Today UB-02 destroyed the truck where it was being transported,\
  \ it escaped and hasn\u2019t been located."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 7.9
  Meters: 2.4
HiddenAbility: ''
HomeSprite: SRD-buzzwole-HomeSprite.png
Image: buzzwole.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Master
  - '[[SRD-Harden|Harden]]'
- - Master
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Master
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Leech Life|Leech Life]]'
- - Master
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Lunge|Lunge]]'
- - Master
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
Number: 794
ShuffleToken: SRD-buzzwole-ShuffleToken.png
Type1: Bug
Type2: Fighting
Weight:
  Kilograms: 333.6
  Pounds: 735.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-buzzwole-BookSprite.png|wsmall]]
> ![[SRD-buzzwole-HomeSprite.png]]
> ![[SRD-buzzwole-BoxSprite.png|htiny]]
> ![[SRD-buzzwole-ShuffleToken.png|wsmall]]


*Aether Foundation Log #071*
*What we thought were harmless displays of strength were just the first warning signs. Today UB-02 destroyed the truck where it was being transported, it escaped and hasn’t been located.*

**DexID**:: 0794
**Name**:: Buzzwole
**Type**:: Bug / Fighting
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::4)/(MaxInsight::4)     |

**Height**: 7'9" / 2.4m
**Weight**: 735.5lbs / 333.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Buzzwole.md"
flatten moves as T
where file.path = this.file.path
```
