---
Ability1: Quick Draw
Ability2: Own Tempo
BookSprite: SRD-slowbro-galarian-form-BookSprite.png
BoxSprite: SRD-slowbro-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Regenerator
HomeSprite: SRD-slowbro-galarian-form-HomeSprite.png
Image: slowbro-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Shell Side Arm|Shell Side Arm]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Surf|Surf]]'
- - Ace
  - '[[SRD-Slack Off|Slack Off]]'
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
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Pro
  - '[[SRD-Expanding Force|Expanding Force]]'
- - Pro
  - '[[SRD-Venoshock|Venoshock]]'
Number: 80
ShuffleToken: SRD-slowbro-galarian-form-ShuffleToken.png
Type1: Poison
Type2: Psychic
Weight:
  Kilograms: 70.5
  Pounds: 155.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowbro-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-slowbro-galarian-form-HomeSprite.png]]
> ![[SRD-slowbro-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-slowbro-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0080G
**Name**:: Slowbro (Galarian Form)
**Type**:: Poison / Psychic
**Abilities**:: [[SRD-Quick Draw|Quick Draw]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 155.4lbs / 70.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slowbro (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
