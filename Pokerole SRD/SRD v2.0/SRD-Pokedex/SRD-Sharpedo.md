---
Ability1: Rough Skin
Ability2: ''
BookSprite: SRD-sharpedo-BookSprite.png
BoxSprite: SRD-sharpedo-BoxSprite.png
DexCategory: Brutal Pokemon
DexDescription: "Known as the \u201CBully of the Sea\u201D, widely feared for its\
  \ cruelty, malice and gangster attitude. They hurt Pokemon for fun and sink boats\
  \ for sport. Sharpedos are among the fastest swimmers."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Carvanha]]'
  Speed: Medium
- Evolves: To
  Item: Sharpedonite
  Kind: Mega
  Pokemon: '[[SRD-Sharpedo (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Speed Boost
HomeSprite: SRD-sharpedo-HomeSprite.png
Image: sharpedo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Skull Bash|Skull Bash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
Number: 319
ShuffleToken: SRD-sharpedo-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 88.8
  Pounds: 195.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sharpedo-BookSprite.png|wsmall]]
> ![[SRD-sharpedo-HomeSprite.png]]
> ![[SRD-sharpedo-BoxSprite.png|htiny]]
> ![[SRD-sharpedo-ShuffleToken.png|wsmall]]


*Brutal Pokemon*
*Known as the “Bully of the Sea”, widely feared for its cruelty, malice and gangster attitude. They hurt Pokemon for fun and sink boats for sport. Sharpedos are among the fastest swimmers.*

**DexID**:: 0319
**Name**:: Sharpedo
**Type**:: Water / Dark
**Abilities**:: [[SRD-Rough Skin|Rough Skin]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 5'9" / 1.8m
**Weight**: 195.8lbs / 88.8kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item         |
|:----------|:-----------------------------|:-------|:--------|:-------------|
| From      | [[SRD-Carvanha]]             | Level  | Medium  |              |
| To        | [[SRD-Sharpedo (Mega Form)]] | Mega   |         | Sharpedonite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sharpedo.md"
flatten moves as T
where file.path = this.file.path
```
