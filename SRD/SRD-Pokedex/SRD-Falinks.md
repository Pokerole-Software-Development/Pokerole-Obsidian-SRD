---
Ability1: Battle Armor
Ability2: ''
BookSprite: SRD-falinks-BookSprite.png
BoxSprite: SRD-falinks-BoxSprite.png
DexCategory: Formation Pokemon
DexDescription: "It is formed by six of them, five are troopers, and one is the brass.\
  \ The brass\u2019s orders are absolute to the others, they work as a perfect team\
  \ and can rearrange their formation to better suit them in battle."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Defiant
HomeSprite: SRD-falinks-HomeSprite.png
Image: falinks.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-First Impression|First Impression]]'
- - Amateur
  - '[[SRD-No Retreat|No Retreat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Poison Jab|Poison Jab]]'
Number: 870
ShuffleToken: SRD-falinks-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 62.0
  Pounds: 136.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-falinks-BookSprite.png|wsmall]]
> ![[SRD-falinks-HomeSprite.png]]
> ![[SRD-falinks-BoxSprite.png|htiny]]
> ![[SRD-falinks-ShuffleToken.png|wsmall]]


*Formation Pokemon*
*It is formed by six of them, five are troopers, and one is the brass. The brass’s orders are absolute to the others, they work as a perfect team and can rearrange their formation to better suit them in battle.*

**DexID**:: 0870
**Name**:: Falinks
**Type**:: Fighting
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 9'8" / 3.0m
**Weight**: 136.7lbs / 62.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Falinks.md"
flatten moves as T
where file.path = this.file.path
```
