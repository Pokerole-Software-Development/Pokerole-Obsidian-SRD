---
Ability1: Hyper Cutter
Ability2: Intimidate
BookSprite: SRD-mawile-BookSprite.png
BoxSprite: SRD-mawile-BoxSprite.png
DexCategory: Deceiver Pokemon
DexDescription: They appear to be cute and docile, luring their prey and lowering
  their guards, then, Mawile chomps the prey with huge steel jaws. They are very rare,
  though. Only a few have been seen in Hoenn's Victory Road.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Mawilite
  Kind: Mega
  Pokemon: '[[SRD-Mawile (Mega Form)]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Sheer Force
HomeSprite: SRD-mawile-HomeSprite.png
Image: mawile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Snatch|Snatch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Spit Up|Spit Up]]'
- - Ace
  - '[[SRD-Swallow|Swallow]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
Number: 303
ShuffleToken: SRD-mawile-ShuffleToken.png
Type1: Steel
Type2: Fairy
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mawile-BookSprite.png|wsmall]]
> ![[SRD-mawile-HomeSprite.png]]
> ![[SRD-mawile-BoxSprite.png|htiny]]
> ![[SRD-mawile-ShuffleToken.png|wsmall]]


*Deceiver Pokemon*
*They appear to be cute and docile, luring their prey and lowering their guards, then, Mawile chomps the prey with huge steel jaws. They are very rare, though. Only a few have been seen in Hoenn's Victory Road.*

**DexID**:: 0303
**Name**:: Mawile
**Type**:: Steel / Fairy
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Intimidate|Intimidate]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                    | Kind   | Item     |
|:----------|:---------------------------|:-------|:---------|
| To        | [[SRD-Mawile (Mega Form)]] | Mega   | Mawilite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mawile.md"
flatten moves as T
where file.path = this.file.path
```
