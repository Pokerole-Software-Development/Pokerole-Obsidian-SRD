---
Ability1: Pickup
Ability2: Cheek Pouch
BookSprite: SRD-diggersby-BookSprite.png
BoxSprite: SRD-diggersby-BoxSprite.png
DexCategory: Digging Pokemon
DexDescription: A powerful excavator, its ears can reduce dense bedrock to rubble.
  After it has finished digging, it just lounges lazily. Some of them have been trained
  to work at construction sites with good results.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bunnelby]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Huge Power
HomeSprite: SRD-diggersby-HomeSprite.png
Image: diggersby.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Facade|Facade]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
Number: 660
ShuffleToken: SRD-diggersby-ShuffleToken.png
Type1: Normal
Type2: Ground
Weight:
  Kilograms: 42.4
  Pounds: 93.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-diggersby-BookSprite.png|wsmall]]
> ![[SRD-diggersby-HomeSprite.png]]
> ![[SRD-diggersby-BoxSprite.png|htiny]]
> ![[SRD-diggersby-ShuffleToken.png|wsmall]]


*Digging Pokemon*
*A powerful excavator, its ears can reduce dense bedrock to rubble. After it has finished digging, it just lounges lazily. Some of them have been trained to work at construction sites with good results.*

**DexID**:: 0660
**Name**:: Diggersby
**Type**:: Normal / Ground
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Cheek Pouch|Cheek Pouch]] ([[SRD-Huge Power|Huge Power]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 93.5lbs / 42.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Bunnelby]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Diggersby.md"
flatten moves as T
where file.path = this.file.path
```
