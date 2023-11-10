---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-salamence-BookSprite.png
BoxSprite: SRD-salamence-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: "After a lifetime of struggling for a dream, it finally grew its wings.\
  \ Salamence, however, is extremely dangerous, it scorches entire fields and mountains.\
  \ It\u2019s easily angered and completely uncontrollable."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shelgon]]'
  Speed: Slow
- Evolves: To
  Item: Salamencite
  Kind: Mega
  Pokemon: '[[SRD-Salamence (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Moxie
HomeSprite: SRD-salamence-HomeSprite.png
Image: salamence.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Fly|Fly]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 373
ShuffleToken: SRD-salamence-ShuffleToken.png
Type1: Dragon
Type2: Flying
Weight:
  Kilograms: 102.6
  Pounds: 226.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-salamence-BookSprite.png|wsmall]]
> ![[SRD-salamence-HomeSprite.png]]
> ![[SRD-salamence-BoxSprite.png|htiny]]
> ![[SRD-salamence-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*After a lifetime of struggling for a dream, it finally grew its wings. Salamence, however, is extremely dangerous, it scorches entire fields and mountains. It’s easily angered and completely uncontrollable.*

**DexID**:: 0373
**Name**:: Salamence
**Type**:: Dragon / Flying
**Abilities**:: [[SRD-Intimidate|Intimidate]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 226.2lbs / 102.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                       | Kind   | Speed   | Item        |
|:----------|:------------------------------|:-------|:--------|:------------|
| From      | [[SRD-Shelgon]]               | Level  | Slow    |             |
| To        | [[SRD-Salamence (Mega Form)]] | Mega   |         | Salamencite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Salamence.md"
flatten moves as T
where file.path = this.file.path
```
