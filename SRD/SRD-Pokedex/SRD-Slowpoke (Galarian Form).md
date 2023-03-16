---
Ability1: Gluttony
Ability2: Own Tempo
BookSprite: SRD-slowpoke-galarian-form-BookSprite.png
BoxSprite: SRD-slowpoke-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Regenerator
HomeSprite: SRD-slowpoke-galarian-form-HomeSprite.png
Image: slowpoke-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Surf|Surf]]'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Expanding Force|Expanding Force]]'
- - Pro
  - '[[SRD-Belch|Belch]]'
Number: 79
ShuffleToken: SRD-slowpoke-galarian-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 36.0
  Pounds: 79.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowpoke-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-slowpoke-galarian-form-HomeSprite.png]]
> ![[SRD-slowpoke-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-slowpoke-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0079G
**Name**:: Slowpoke (Galarian Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Gluttony|Gluttony]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'9" / 1.2m
**Weight**: 79.4lbs / 36.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Slowpoke (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
