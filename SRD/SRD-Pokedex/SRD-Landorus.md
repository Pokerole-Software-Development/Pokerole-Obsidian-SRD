---
Ability1: Sand Force
Ability2: ''
BookSprite: SRD-landorus-BookSprite.png
BoxSprite: SRD-landorus-BoxSprite.png
DexCategory: No Data
DexDescription: Earthquakes and landslides raze Unova with frequency, but the places
  who suffer them are left with a plentiful harvest that year. Feared by some, revered
  by others who claim to have seen it.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Landorus (Therian Form)]]'
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Sheer Force
HomeSprite: SRD-landorus-HomeSprite.png
Image: landorus.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Block|Block]]'
- - Master
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Master
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[SRD-Earthquake|Earthquake]]'
- - Master
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[SRD-Fissure|Fissure]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Rototiller|Rototiller]]'
- - Master
  - '[[SRD-Dig|Dig]]'
Number: 645
ShuffleToken: SRD-landorus-ShuffleToken.png
Type1: Ground
Type2: Flying
Weight:
  Kilograms: 68.0
  Pounds: 149.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-landorus-BookSprite.png|wsmall]]
> ![[SRD-landorus-HomeSprite.png]]
> ![[SRD-landorus-BoxSprite.png|htiny]]
> ![[SRD-landorus-ShuffleToken.png|wsmall]]


*No Data*
*Earthquakes and landslides raze Unova with frequency, but the places who suffer them are left with a plentiful harvest that year. Feared by some, revered by others who claim to have seen it.*

**DexID**:: 0645
**Name**:: Landorus
**Type**:: Ground / Flying
**Abilities**:: [[SRD-Sand Force|Sand Force]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 149.9lbs / 68.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                         | Kind   |
|:----------|:--------------------------------|:-------|
| To        | [[SRD-Landorus (Therian Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Landorus.md"
flatten moves as T
where file.path = this.file.path
```
