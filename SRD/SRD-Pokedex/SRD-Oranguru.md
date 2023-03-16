---
Ability1: Inner Focus
Ability2: Telepathy
BookSprite: SRD-oranguru-BookSprite.png
BoxSprite: SRD-oranguru-BoxSprite.png
DexCategory: Sage Pokemon
DexDescription: These solitary Pokemon live deep in the forests where it provides
  food and herbal medicine to those in need. It is incredibly smart even learning
  how to use pokeballs, for that reason it dislikes being ordered around.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Symbiosis
HomeSprite: SRD-oranguru-HomeSprite.png
Image: oranguru.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Quash|Quash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Instruct|Instruct]]'
- - Amateur
  - '[[SRD-Foul Play|Foul Play]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Trick Room|Trick Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Number: 765
ShuffleToken: SRD-oranguru-ShuffleToken.png
Type1: Normal
Type2: Psychic
Weight:
  Kilograms: 76.0
  Pounds: 167.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-oranguru-BookSprite.png|wsmall]]
> ![[SRD-oranguru-HomeSprite.png]]
> ![[SRD-oranguru-BoxSprite.png|htiny]]
> ![[SRD-oranguru-ShuffleToken.png|wsmall]]


*Sage Pokemon*
*These solitary Pokemon live deep in the forests where it provides food and herbal medicine to those in need. It is incredibly smart even learning how to use pokeballs, for that reason it dislikes being ordered around.*

**DexID**:: 0765
**Name**:: Oranguru
**Type**:: Normal / Psychic
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Telepathy|Telepathy]] ([[SRD-Symbiosis|Symbiosis]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 167.6lbs / 76.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Oranguru.md"
flatten moves as T
where file.path = this.file.path
```
