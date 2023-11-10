---
Ability1: Natural Cure
Ability2: ''
BookSprite: SRD-altaria-BookSprite.png
BoxSprite: SRD-altaria-BoxSprite.png
DexCategory: Humming Pokemon
DexDescription: Seen as dancing clouds in the sky, Altarias sing melodies in their
  sweet voices, evoking wonder, beauty and dreams to the listeners. They live far
  away from people and throw colorful fireballs at uninvited guests.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Swablu]]'
  Speed: Slow
- Evolves: To
  Item: Altarianite
  Kind: Mega
  Pokemon: '[[SRD-Altaria (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Cloud Nine
HomeSprite: SRD-altaria-HomeSprite.png
Image: altaria.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Swap|Power Swap]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
Number: 334
ShuffleToken: SRD-altaria-ShuffleToken.png
Type1: Dragon
Type2: Flying
Weight:
  Kilograms: 20.6
  Pounds: 45.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-altaria-BookSprite.png|wsmall]]
> ![[SRD-altaria-HomeSprite.png]]
> ![[SRD-altaria-BoxSprite.png|htiny]]
> ![[SRD-altaria-ShuffleToken.png|wsmall]]


*Humming Pokemon*
*Seen as dancing clouds in the sky, Altarias sing melodies in their sweet voices, evoking wonder, beauty and dreams to the listeners. They live far away from people and throw colorful fireballs at uninvited guests.*

**DexID**:: 0334
**Name**:: Altaria
**Type**:: Dragon / Flying
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] ([[SRD-Cloud Nine|Cloud Nine]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 45.4lbs / 20.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                     | Kind   | Speed   | Item        |
|:----------|:----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Swablu]]              | Level  | Slow    |             |
| To        | [[SRD-Altaria (Mega Form)]] | Mega   |         | Altarianite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Altaria.md"
flatten moves as T
where file.path = this.file.path
```
