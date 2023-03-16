---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-luvdisc-BookSprite.png
BoxSprite: SRD-luvdisc-BoxSprite.png
DexCategory: Rendezvous Pokemon
DexDescription: Luvdisc is a symbol of romance. It lives in shallow seas, swimming
  after couples, bringing them closer and promising eternal love. During their spawning
  season, the waters around them turn pink.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Hydration
HomeSprite: SRD-luvdisc-HomeSprite.png
Image: luvdisc.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Heart Stamp|Heart Stamp]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
Number: 370
ShuffleToken: SRD-luvdisc-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 8.7
  Pounds: 19.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-luvdisc-BookSprite.png|wsmall]]
> ![[SRD-luvdisc-HomeSprite.png]]
> ![[SRD-luvdisc-BoxSprite.png|htiny]]
> ![[SRD-luvdisc-ShuffleToken.png|wsmall]]


*Rendezvous Pokemon*
*Luvdisc is a symbol of romance. It lives in shallow seas, swimming after couples, bringing them closer and promising eternal love. During their spawning season, the waters around them turn pink.*

**DexID**:: 0370
**Name**:: Luvdisc
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 19.2lbs / 8.7kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Luvdisc.md"
flatten moves as T
where file.path = this.file.path
```
