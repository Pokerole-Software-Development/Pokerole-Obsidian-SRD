---
Ability1: Justified
Ability2: ''
BookSprite: SRD-keldeo-resolute-form-BookSprite.png
BoxSprite: SRD-keldeo-resolute-form-BoxSprite.png
DexCategory: No Data
DexDescription: The old fairy tale ends with the youngest Pokemon rising above evil
  and injustice due to its resolute and determined desire for justice. The mentorship
  of the other Pokemon bearing fruits.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Keldeo]]'
GenderType: N
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-keldeo-resolute-form-HomeSprite.png
Image: keldeo-resolute-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Retaliate|Retaliate]]'
- - Master
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Work Up|Work Up]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Surf|Surf]]'
- - Master
  - '[[SRD-Waterfall|Waterfall]]'
- - Master
  - '[[SRD-Follow Me|Follow Me]]'
- - Master
  - '[[SRD-Noble Roar|Noble Roar]]'
Number: 647
ShuffleToken: SRD-keldeo-resolute-form-ShuffleToken.png
Type1: Water
Type2: Fighting
Weight:
  Kilograms: 48.5
  Pounds: 106.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-keldeo-resolute-form-BookSprite.png|wsmall]]
> ![[SRD-keldeo-resolute-form-HomeSprite.png]]
> ![[SRD-keldeo-resolute-form-BoxSprite.png|htiny]]
> ![[SRD-keldeo-resolute-form-ShuffleToken.png|wsmall]]


*No Data*
*The old fairy tale ends with the youngest Pokemon rising above evil and injustice due to its resolute and determined desire for justice. The mentorship of the other Pokemon bearing fruits.*

**DexID**:: 0647F1
**Name**:: Keldeo (Resolute Form)
**Type**:: Water / Fighting
**Abilities**:: [[SRD-Justified|Justified]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 106.9lbs / 48.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Keldeo]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Keldeo (Resolute Form).md"
flatten moves as T
where file.path = this.file.path
```
