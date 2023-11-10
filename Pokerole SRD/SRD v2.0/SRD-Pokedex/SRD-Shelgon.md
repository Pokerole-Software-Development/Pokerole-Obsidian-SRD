---
Ability1: Rock Head
Ability2: ''
BookSprite: SRD-shelgon-BookSprite.png
BoxSprite: SRD-shelgon-BoxSprite.png
DexCategory: Endurance Pokemon
DexDescription: The body is covered in a powerful armor that resembles bones. It hides
  in caves awaiting evolution, enduring hunger and harm while its cells prepare for
  its final transformation.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bagon]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Salamence]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Overcoat
HomeSprite: SRD-shelgon-HomeSprite.png
Image: shelgon.png
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
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 372
ShuffleToken: SRD-shelgon-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 110.5
  Pounds: 243.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shelgon-BookSprite.png|wsmall]]
> ![[SRD-shelgon-HomeSprite.png]]
> ![[SRD-shelgon-BoxSprite.png|htiny]]
> ![[SRD-shelgon-ShuffleToken.png|wsmall]]


*Endurance Pokemon*
*The body is covered in a powerful armor that resembles bones. It hides in caves awaiting evolution, enduring hunger and harm while its cells prepare for its final transformation.*

**DexID**:: 0372
**Name**:: Shelgon
**Type**:: Dragon
**Abilities**:: [[SRD-Rock Head|Rock Head]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 243.6lbs / 110.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Bagon]]     | Level  | Slow    |
| To        | [[SRD-Salamence]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shelgon.md"
flatten moves as T
where file.path = this.file.path
```
