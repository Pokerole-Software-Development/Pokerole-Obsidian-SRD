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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Taunt|Taunt]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quash|Quash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Instruct|Instruct]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick Room|Trick Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic Terrain|Psychic Terrain]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extrasensory|Extrasensory]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Oranguru.md"
flatten moves as T
where file.path = this.file.path
```
