---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-cinderace-BookSprite.png
BoxSprite: SRD-cinderace-BoxSprite.png
DexCategory: Striker Pokemon
DexDescription: They are confident and boastful of their abilities. They take a pebble
  and light it on fire to create a scorching weapon they kick towards their foes.
  They can grow arrogant if they feel cheered on.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Raboot]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Libero
HomeSprite: SRD-cinderace-HomeSprite.png
Image: cinderace.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pyro Ball|Pyro Ball]]'
- - Starter
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ember|Ember]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Headbutt|Headbutt]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Court Change|Court Change]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Pro
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 815
ShuffleToken: SRD-cinderace-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cinderace-BookSprite.png|wsmall]]
> ![[SRD-cinderace-HomeSprite.png]]
> ![[SRD-cinderace-BoxSprite.png|htiny]]
> ![[SRD-cinderace-ShuffleToken.png|wsmall]]


*Striker Pokemon*
*They are confident and boastful of their abilities. They take a pebble and light it on fire to create a scorching weapon they kick towards their foes. They can grow arrogant if they feel cheered on.*

**DexID**:: 0815
**Name**:: Cinderace
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Libero|Libero]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Raboot]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cinderace.md"
flatten moves as T
where file.path = this.file.path
```
