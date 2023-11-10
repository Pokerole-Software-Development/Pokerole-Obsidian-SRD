---
Ability1: Hydration
Ability2: ''
BookSprite: SRD-phione-BookSprite.png
BoxSprite: SRD-phione-BoxSprite.png
DexCategory: No Data
DexDescription: There have been sightings of small groups of similar Pokemon but its
  existence has never been confirmed. It is said to be the offspring of Manaphy.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-phione-HomeSprite.png
Image: phione.png
Legendary: 'No'
Moves:
- - Master
  - '[[SRD-Bubble|Bubble]]'
- - Master
  - '[[SRD-Water Sport|Water Sport]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Supersonic|Supersonic]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Surf|Surf]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Last Resort|Last Resort]]'
Number: 489
ShuffleToken: SRD-phione-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 3.1
  Pounds: 6.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-phione-BookSprite.png|wsmall]]
> ![[SRD-phione-HomeSprite.png]]
> ![[SRD-phione-BoxSprite.png|htiny]]
> ![[SRD-phione-ShuffleToken.png|wsmall]]


*No Data*
*There have been sightings of small groups of similar Pokemon but its existence has never been confirmed. It is said to be the offspring of Manaphy.*

**DexID**:: 0489
**Name**:: Phione
**Type**:: Water
**Abilities**:: [[SRD-Hydration|Hydration]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 6.8lbs / 3.1kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Phione.md"
flatten moves as T
where file.path = this.file.path
```
