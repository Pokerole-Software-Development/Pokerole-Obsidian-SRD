---
Ability1: Intimidate
Ability2: Quick Feet
BookSprite: SRD-mightyena-BookSprite.png
BoxSprite: SRD-mightyena-BoxSprite.png
DexCategory: Bite Pokemon
DexDescription: They attack savagely, travel in packs and hunt in groups. They will
  only obey trainers that show superior skills, which they recognize as the alpha
  leader. They are extremely obedient once they find a master.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Poochyena]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Moxie
HomeSprite: SRD-mightyena-HomeSprite.png
Image: mightyena.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Howl|Howl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Thief|Thief]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Embargo|Embargo]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Snarl|Snarl]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Poison Fang|Poison Fang]]'
Number: 262
ShuffleToken: SRD-mightyena-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 37.0
  Pounds: 81.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mightyena-BookSprite.png|wsmall]]
> ![[SRD-mightyena-HomeSprite.png]]
> ![[SRD-mightyena-BoxSprite.png|htiny]]
> ![[SRD-mightyena-ShuffleToken.png|wsmall]]


*Bite Pokemon*
*They attack savagely, travel in packs and hunt in groups. They will only obey trainers that show superior skills, which they recognize as the alpha leader. They are extremely obedient once they find a master.*

**DexID**:: 0262
**Name**:: Mightyena
**Type**:: Dark
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Quick Feet|Quick Feet]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 81.6lbs / 37.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Poochyena]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mightyena.md"
flatten moves as T
where file.path = this.file.path
```
