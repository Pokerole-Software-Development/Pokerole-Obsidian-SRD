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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Block|Block]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mud Shot|Mud Shot]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Tomb|Rock Tomb]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Imprison|Imprison]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Punishment|Punishment]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earth Power|Earth Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fissure|Fissure]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rototiller|Rototiller]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dig|Dig]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Landorus.md"
flatten moves as T
where file.path = this.file.path
```
