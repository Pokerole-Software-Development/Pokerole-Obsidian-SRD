---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-litten-BookSprite.png
BoxSprite: SRD-litten-BoxSprite.png
DexCategory: Fire Cat Pokemon
DexDescription: It has an aloof personality and likes to be alone. Its fur produces
  flammable oils and its rough tongue lights them every time it grooms itself. Not
  recommended as a pet for they can cause house fires easily.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Torracat]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Intimidate
HomeSprite: SRD-litten-HomeSprite.png
Image: litten.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 725
ShuffleToken: SRD-litten-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 4.3
  Pounds: 9.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-litten-BookSprite.png|wsmall]]
> ![[SRD-litten-HomeSprite.png]]
> ![[SRD-litten-BoxSprite.png|htiny]]
> ![[SRD-litten-ShuffleToken.png|wsmall]]


*Fire Cat Pokemon*
*It has an aloof personality and likes to be alone. Its fur produces flammable oils and its rough tongue lights them every time it grooms itself. Not recommended as a pet for they can cause house fires easily.*

**DexID**:: 0725
**Name**:: Litten
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.5lbs / 4.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Torracat]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Litten.md"
flatten moves as T
where file.path = this.file.path
```
