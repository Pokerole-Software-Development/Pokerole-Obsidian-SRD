---
Ability1: Sand Veil
Ability2: ''
BookSprite: SRD-garchomp-BookSprite.png
BoxSprite: SRD-garchomp-BoxSprite.png
DexCategory: Mach Pokemon
DexDescription: Garchomps are scarce in the wild and very dangerous. It folds its
  arms and uses its fins to fly extremely fast at low heights. Territorial and aggressive
  it will not rest until it catches any daring trespasser.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gabite]]'
  Speed: Slow
- Evolves: To
  Item: Garchompite
  Kind: Mega
  Pokemon: '[[SRD-Garchomp (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Rough Skin
HomeSprite: SRD-garchomp-HomeSprite.png
Image: garchomp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 445
ShuffleToken: SRD-garchomp-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 95.0
  Pounds: 209.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-garchomp-BookSprite.png|wsmall]]
> ![[SRD-garchomp-HomeSprite.png]]
> ![[SRD-garchomp-BoxSprite.png|htiny]]
> ![[SRD-garchomp-ShuffleToken.png|wsmall]]


*Mach Pokemon*
*Garchomps are scarce in the wild and very dangerous. It folds its arms and uses its fins to fly extremely fast at low heights. Territorial and aggressive it will not rest until it catches any daring trespasser.*

**DexID**:: 0445
**Name**:: Garchomp
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] ([[SRD-Rough Skin|Rough Skin]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 209.4lbs / 95.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Gabite]]               | Level  | Slow    |             |
| To        | [[SRD-Garchomp (Mega Form)]] | Mega   |         | Garchompite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Garchomp.md"
flatten moves as T
where file.path = this.file.path
```
