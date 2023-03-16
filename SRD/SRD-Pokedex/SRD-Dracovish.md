---
Ability1: Water Absorb
Ability2: Strong Jaw
BookSprite: SRD-dracovish-BookSprite.png
BoxSprite: SRD-dracovish-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: "The DNA of two apex predators combined. It can run at incredibly\
  \ high speeds and tear almost anything with its sharp teeth. Sadly, this Pokemon\
  \ can only breathe underwater and it\u2019s a lousy swimmer."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: Sand Rush
HomeSprite: SRD-dracovish-HomeSprite.png
Image: dracovish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - Beginner
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Fishious Rend|Fishious Rend]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Whirlpool|Whirlpool]]'
Number: 882
ShuffleToken: SRD-dracovish-ShuffleToken.png
Type1: Water
Type2: Dragon
Weight:
  Kilograms: 215.0
  Pounds: 474.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dracovish-BookSprite.png|wsmall]]
> ![[SRD-dracovish-HomeSprite.png]]
> ![[SRD-dracovish-BoxSprite.png|htiny]]
> ![[SRD-dracovish-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*The DNA of two apex predators combined. It can run at incredibly high speeds and tear almost anything with its sharp teeth. Sadly, this Pokemon can only breathe underwater and it’s a lousy swimmer.*

**DexID**:: 0882
**Name**:: Dracovish
**Type**:: Water / Dragon
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Sand Rush|Sand Rush]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'5" / 2.3m
**Weight**: 474.0lbs / 215.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dracovish.md"
flatten moves as T
where file.path = this.file.path
```
