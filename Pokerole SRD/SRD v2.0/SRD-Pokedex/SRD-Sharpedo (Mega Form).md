---
Ability1: Strong Jaw
Ability2: ''
BookSprite: SRD-sharpedo-mega-form-BookSprite.png
BoxSprite: SRD-sharpedo-mega-form-BoxSprite.png
DexCategory: Brutal Pokemon
DexDescription: As soon as it feels the power of the Mega Stone surge through its
  body, its mind goes blank with fury and violence. Its sharp spikes and teeth regrow
  sharper if it loses them. The yellow marks on its body are scars
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sharpedonite
  Kind: Mega
  Pokemon: '[[SRD-Sharpedo]]'
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-sharpedo-mega-form-HomeSprite.png
Image: sharpedo-mega-form.png
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
ShuffleToken: SRD-sharpedo-mega-form-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 130.3
  Pounds: 287.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sharpedo-mega-form-BookSprite.png|wsmall]]
> ![[SRD-sharpedo-mega-form-HomeSprite.png]]
> ![[SRD-sharpedo-mega-form-BoxSprite.png|htiny]]
> ![[SRD-sharpedo-mega-form-ShuffleToken.png|wsmall]]


*Brutal Pokemon*
*As soon as it feels the power of the Mega Stone surge through its body, its mind goes blank with fury and violence. Its sharp spikes and teeth regrow sharper if it loses them. The yellow marks on its body are scars*

**DexID**:: 0319M1
**Name**:: Sharpedo (Mega Form)
**Type**:: Water / Dark
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'2" / 2.5m
**Weight**: 287.3lbs / 130.3kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item         |
|:----------|:-----------------|:-------|:-------------|
| From      | [[SRD-Sharpedo]] | Mega   | Sharpedonite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sharpedo (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
