---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-incineroar-BookSprite.png
BoxSprite: SRD-incineroar-BoxSprite.png
DexCategory: Heel Pokemon
DexDescription: It has a bad reputation, some of them have attacked the opposing Trainer
  during battles. They are also prone to disobey their own Trainer, going for a more
  brutal fighting style to shred their foes to pieces.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Torracat]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Intimidate
HomeSprite: SRD-incineroar-HomeSprite.png
Image: incineroar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Amateur
  - '[[SRD-Darkest Lariat|Darkest Lariat]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 727
ShuffleToken: SRD-incineroar-ShuffleToken.png
Type1: Fire
Type2: Dark
Weight:
  Kilograms: 83.0
  Pounds: 183.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-incineroar-BookSprite.png|wsmall]]
> ![[SRD-incineroar-HomeSprite.png]]
> ![[SRD-incineroar-BoxSprite.png|htiny]]
> ![[SRD-incineroar-ShuffleToken.png|wsmall]]


*Heel Pokemon*
*It has a bad reputation, some of them have attacked the opposing Trainer during battles. They are also prone to disobey their own Trainer, going for a more brutal fighting style to shred their foes to pieces.*

**DexID**:: 0727
**Name**:: Incineroar
**Type**:: Fire / Dark
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 183.0lbs / 83.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Torracat]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Incineroar.md"
flatten moves as T
where file.path = this.file.path
```
