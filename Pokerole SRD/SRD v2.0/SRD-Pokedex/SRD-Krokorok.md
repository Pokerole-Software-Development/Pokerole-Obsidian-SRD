---
Ability1: Intimidate
Ability2: Moxie
BookSprite: SRD-krokorok-BookSprite.png
BoxSprite: SRD-krokorok-BoxSprite.png
DexCategory: Desert Croc Pokemon
DexDescription: The protective membranes shield their eyes from sandstorms and allow
  them to see in the dark. They can be aggressive and territorial and love to destroy
  things with their fangs.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sandile]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Krookodile]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Anger Point
HomeSprite: SRD-krokorok-HomeSprite.png
Image: krokorok.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Torment|Torment]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Number: 552
ShuffleToken: SRD-krokorok-ShuffleToken.png
Type1: Ground
Type2: Dark
Weight:
  Kilograms: 33.4
  Pounds: 73.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-krokorok-BookSprite.png|wsmall]]
> ![[SRD-krokorok-HomeSprite.png]]
> ![[SRD-krokorok-BoxSprite.png|htiny]]
> ![[SRD-krokorok-ShuffleToken.png|wsmall]]


*Desert Croc Pokemon*
*The protective membranes shield their eyes from sandstorms and allow them to see in the dark. They can be aggressive and territorial and love to destroy things with their fangs.*

**DexID**:: 0552
**Name**:: Krokorok
**Type**:: Ground / Dark
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Moxie|Moxie]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 73.6lbs / 33.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Sandile]]    | Level  | Medium  |
| To        | [[SRD-Krookodile]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Krokorok.md"
flatten moves as T
where file.path = this.file.path
```
