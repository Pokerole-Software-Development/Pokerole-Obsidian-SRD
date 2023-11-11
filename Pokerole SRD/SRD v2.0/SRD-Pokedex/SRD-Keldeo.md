---
Ability1: Justified
Ability2: ''
BookSprite: SRD-keldeo-BookSprite.png
BoxSprite: SRD-keldeo-BoxSprite.png
DexCategory: No Data
DexDescription: Age-old fairy tales of Unova tell the story of four Pokemon that brought
  the land to a golden age. The young of the group was brave and naive. It could gallop
  on the water surface leaving a rainbow behind.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Keldeo (Resolute Form)]]'
GenderType: N
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-keldeo-HomeSprite.png
Image: keldeo.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Jet|Aqua Jet]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Kick|Double Kick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Retaliate|Retaliate]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Work Up|Work Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Surf|Surf]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Waterfall|Waterfall]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Follow Me|Follow Me]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Noble Roar|Noble Roar]]'
Number: 647
ShuffleToken: SRD-keldeo-ShuffleToken.png
Type1: Water
Type2: Fighting
Weight:
  Kilograms: 48.5
  Pounds: 106.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-keldeo-BookSprite.png|wsmall]]
> ![[SRD-keldeo-HomeSprite.png]]
> ![[SRD-keldeo-BoxSprite.png|htiny]]
> ![[SRD-keldeo-ShuffleToken.png|wsmall]]


*No Data*
*Age-old fairy tales of Unova tell the story of four Pokemon that brought the land to a golden age. The young of the group was brave and naive. It could gallop on the water surface leaving a rainbow behind.*

**DexID**:: 0647
**Name**:: Keldeo
**Type**:: Water / Fighting
**Abilities**:: [[SRD-Justified|Justified]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 106.9lbs / 48.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                        | Kind   |
|:----------|:-------------------------------|:-------|
| To        | [[SRD-Keldeo (Resolute Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Keldeo.md"
flatten moves as T
where file.path = this.file.path
```
