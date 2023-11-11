---
Ability1: Serene Grace
Ability2: ''
BookSprite: SRD-meloetta-pirouette-form-BookSprite.png
BoxSprite: SRD-meloetta-pirouette-form-BoxSprite.png
DexCategory: No Data
DexDescription: There are old songs about a beautiful Pokemon that inspired the hearts
  of artists through its graceful dance and singing.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Meloetta]]'
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-meloetta-pirouette-form-HomeSprite.png
Image: meloetta-pirouette-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Round|Round]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sing|Sing]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teeter Dance|Teeter Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acrobatics|Acrobatics]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Echoed Voice|Echoed Voice]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-U-Turn|U-Turn]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Role Play|Role Play]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Perish Song|Perish Song]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Entrainment|Entrainment]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Revelation Dance|Revelation Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rapid Spin|Rapid Spin]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Captivate|Captivate]]'
Number: 648
ShuffleToken: SRD-meloetta-pirouette-form-ShuffleToken.png
Type1: Normal
Type2: Fighting
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meloetta-pirouette-form-BookSprite.png|wsmall]]
> ![[SRD-meloetta-pirouette-form-HomeSprite.png]]
> ![[SRD-meloetta-pirouette-form-BoxSprite.png|htiny]]
> ![[SRD-meloetta-pirouette-form-ShuffleToken.png|wsmall]]


*No Data*
*There are old songs about a beautiful Pokemon that inspired the hearts of artists through its graceful dance and singing.*

**DexID**:: 0648F1
**Name**:: Meloetta (Pirouette Form)
**Type**:: Normal / Fighting
**Abilities**:: [[SRD-Serene Grace|Serene Grace]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Meloetta]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meloetta (Pirouette Form).md"
flatten moves as T
where file.path = this.file.path
```
