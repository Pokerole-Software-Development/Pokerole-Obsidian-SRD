---
Ability1: Volt Absorb
Ability2: Hustle
BookSprite: SRD-dracozolt-BookSprite.png
BoxSprite: SRD-dracozolt-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: A mix-up of DNA during the revival process resulted in this. Its lower
  body was an incredibly Strong Pokemon that probably preyed on the little one from
  the upper body. Sometimes i1l t will try to run from itself.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Sand Rush
HomeSprite: SRD-dracozolt-HomeSprite.png
Image: dracozolt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pluck|Pluck]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slam|Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bolt Beak|Bolt Beak]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Breaking Swipe|Breaking Swipe]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
Number: 880
ShuffleToken: SRD-dracozolt-ShuffleToken.png
Type1: Electric
Type2: Dragon
Weight:
  Kilograms: 190.0
  Pounds: 418.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dracozolt-BookSprite.png|wsmall]]
> ![[SRD-dracozolt-HomeSprite.png]]
> ![[SRD-dracozolt-BoxSprite.png|htiny]]
> ![[SRD-dracozolt-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*A mix-up of DNA during the revival process resulted in this. Its lower body was an incredibly Strong Pokemon that probably preyed on the little one from the upper body. Sometimes i1l t will try to run from itself.*

**DexID**:: 0880
**Name**:: Dracozolt
**Type**:: Electric / Dragon
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]] / [[SRD-Hustle|Hustle]] ([[SRD-Sand Rush|Sand Rush]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 418.9lbs / 190.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dracozolt.md"
flatten moves as T
where file.path = this.file.path
```
