---
Ability1: Serene Grace
Ability2: ''
BookSprite: SRD-meloetta-BookSprite.png
BoxSprite: SRD-meloetta-BoxSprite.png
DexCategory: No Data
DexDescription: There are old songs about a beautiful Pokemon that inspired the hearts
  of artists through its graceful dance and singing.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Meloetta (Pirouette Form)]]'
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-meloetta-HomeSprite.png
Image: meloetta.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Boomburst|Boomburst]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disarming Voice|Disarming Voice]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Relic Song|Relic Song]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Captivate|Captivate]]'
Number: 648
ShuffleToken: SRD-meloetta-ShuffleToken.png
Type1: Normal
Type2: Psychic
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meloetta-BookSprite.png|wsmall]]
> ![[SRD-meloetta-HomeSprite.png]]
> ![[SRD-meloetta-BoxSprite.png|htiny]]
> ![[SRD-meloetta-ShuffleToken.png|wsmall]]


*No Data*
*There are old songs about a beautiful Pokemon that inspired the hearts of artists through its graceful dance and singing.*

**DexID**:: 0648
**Name**:: Meloetta
**Type**:: Normal / Psychic
**Abilities**:: [[SRD-Serene Grace|Serene Grace]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 2'0" / 0.6m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                           | Kind   |
|:----------|:----------------------------------|:-------|
| To        | [[SRD-Meloetta (Pirouette Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meloetta.md"
flatten moves as T
where file.path = this.file.path
```
