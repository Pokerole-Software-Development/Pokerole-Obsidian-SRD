---
Ability1: Rivalry
Ability2: Unnerve
BookSprite: SRD-pyroar-BookSprite.png
BoxSprite: SRD-pyroar-BoxSprite.png
DexCategory: Royal Pokemon
DexDescription: The male with the largest fire mane is the leader of the pride. The
  females have a long mane strip. Whenever they roar they also let out a fiery breath.
  Not many Pokemon dare to mess with them.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Litleo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Moxie
HomeSprite: SRD-pyroar-HomeSprite.png
Image: pyroar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Incinerate|Incinerate]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
Number: 668
ShuffleToken: SRD-pyroar-ShuffleToken.png
Type1: Fire
Type2: Normal
Weight:
  Kilograms: 81.5
  Pounds: 179.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pyroar-BookSprite.png|wsmall]]
> ![[SRD-pyroar-HomeSprite.png]]
> ![[SRD-pyroar-BoxSprite.png|htiny]]
> ![[SRD-pyroar-ShuffleToken.png|wsmall]]


*Royal Pokemon*
*The male with the largest fire mane is the leader of the pride. The females have a long mane strip. Whenever they roar they also let out a fiery breath. Not many Pokemon dare to mess with them.*

**DexID**:: 0668
**Name**:: Pyroar
**Type**:: Fire / Normal
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 179.7lbs / 81.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Litleo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pyroar.md"
flatten moves as T
where file.path = this.file.path
```
