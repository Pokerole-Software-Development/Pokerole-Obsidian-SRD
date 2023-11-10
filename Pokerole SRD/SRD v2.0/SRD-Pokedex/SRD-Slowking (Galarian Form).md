---
Ability1: Curious Medicine
Ability2: Own Tempo
BookSprite: SRD-slowking-galarian-form-BookSprite.png
BoxSprite: SRD-slowking-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Regenerator
HomeSprite: SRD-slowking-galarian-form-HomeSprite.png
Image: slowking-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Eerie Spell|Eerie Spell]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slack Off|Slack Off]]'
- - Ace
  - '[[SRD-Surf|Surf]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hex|Hex]]'
- - Pro
  - '[[SRD-Expanding Force|Expanding Force]]'
- - Pro
  - '[[SRD-Sludge Wave|Sludge Wave]]'
Number: 199
ShuffleToken: SRD-slowking-galarian-form-ShuffleToken.png
Type1: Poison
Type2: Psychic
Weight:
  Kilograms: 79.5
  Pounds: 175.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowking-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-slowking-galarian-form-HomeSprite.png]]
> ![[SRD-slowking-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-slowking-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0199G
**Name**:: Slowking (Galarian Form)
**Type**:: Poison / Psychic
**Abilities**:: [[SRD-Curious Medicine|Curious Medicine]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'9" / 1.8m
**Weight**: 175.3lbs / 79.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slowking (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
