---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-huntail-BookSprite.png
BoxSprite: SRD-huntail-BoxSprite.png
DexCategory: Deep Sea Pokemon
DexDescription: It lives at extreme depths of the sea. Their eyes can see perfectly
  in complete darkness. Huntails light up their tail to attract their prey, then swallow
  them whole with a single bite.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dragon Fang
  Kind: Trade
  Pokemon: '[[SRD-Clamperl]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Water Veil
HomeSprite: SRD-huntail-HomeSprite.png
Image: huntail.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Starter
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Pro
  - '[[SRD-Bind|Bind]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
Number: 367
ShuffleToken: SRD-huntail-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 27.0
  Pounds: 59.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-huntail-BookSprite.png|wsmall]]
> ![[SRD-huntail-HomeSprite.png]]
> ![[SRD-huntail-BoxSprite.png|htiny]]
> ![[SRD-huntail-ShuffleToken.png|wsmall]]


*Deep Sea Pokemon*
*It lives at extreme depths of the sea. Their eyes can see perfectly in complete darkness. Huntails light up their tail to attract their prey, then swallow them whole with a single bite.*

**DexID**:: 0367
**Name**:: Huntail
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Water Veil|Water Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 59.5lbs / 27.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Clamperl]] | Trade  | Dragon Fang |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Huntail.md"
flatten moves as T
where file.path = this.file.path
```
