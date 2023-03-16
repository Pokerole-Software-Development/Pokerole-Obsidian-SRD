---
Ability1: Download
Ability2: ''
BookSprite: SRD-genesect-BookSprite.png
BoxSprite: SRD-genesect-BoxSprite.png
DexCategory: No Data
DexDescription: Fossil revival is now possible with our incredible technology. Recently,
  some researchers sparked a controversial debate by altering the original forms of
  the revived Pokemon through artificial means.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-genesect-HomeSprite.png
Image: genesect.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Techno Blast|Techno Blast]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Screech|Screech]]'
- - Master
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Master
  - '[[SRD-Lock-On|Lock-On]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Magnet Bomb|Magnet Bomb]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Master
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Master
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Master
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Master
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Bullet Seed|Bullet Seed]]'
Number: 649
ShuffleToken: SRD-genesect-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 82.5
  Pounds: 181.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-genesect-BookSprite.png|wsmall]]
> ![[SRD-genesect-HomeSprite.png]]
> ![[SRD-genesect-BoxSprite.png|htiny]]
> ![[SRD-genesect-ShuffleToken.png|wsmall]]


*No Data*
*Fossil revival is now possible with our incredible technology. Recently, some researchers sparked a controversial debate by altering the original forms of the revived Pokemon through artificial means.*

**DexID**:: 0649
**Name**:: Genesect
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Download|Download]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 181.9lbs / 82.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Genesect.md"
flatten moves as T
where file.path = this.file.path
```
