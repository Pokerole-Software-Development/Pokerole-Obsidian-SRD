---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-latias-mega-form-BookSprite.png
BoxSprite: SRD-latias-mega-form-BoxSprite.png
DexCategory: No Data
DexDescription: Latias is very in sync with human emotions, it can communicate using
  telepathy. With the power of the Mega Stone all of its capabilities are enhanced
  although its personality becomes more distant than usual.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Latiasite
  Kind: Mega
  Pokemon: '[[SRD-Latias]]'
GenderType: F
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-latias-mega-form-HomeSprite.png
Image: latias-mega-form.png
Legendary: 'Yes'
Moves:
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Starter
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psywave|Psywave]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Water Sport|Water Sport]]'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[SRD-Mist Ball|Mist Ball]]'
- - Pro
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Reflect Type|Reflect Type]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Pro
  - '[[SRD-Camouflage|Camouflage]]'
- - Pro
  - '[[SRD-Transform|Transform]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
Number: 380
ShuffleToken: SRD-latias-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Psychic
Weight:
  Kilograms: 52.0
  Pounds: 114.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-latias-mega-form-BookSprite.png|wsmall]]
> ![[SRD-latias-mega-form-HomeSprite.png]]
> ![[SRD-latias-mega-form-BoxSprite.png|htiny]]
> ![[SRD-latias-mega-form-ShuffleToken.png|wsmall]]


*No Data*
*Latias is very in sync with human emotions, it can communicate using telepathy. With the power of the Mega Stone all of its capabilities are enhanced although its personality becomes more distant than usual.*

**DexID**:: 0380M1
**Name**:: Latias (Mega Form)
**Type**:: Dragon / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::8)/(MaxInsight::8)     |

**Height**: 5'9" / 1.8m
**Weight**: 114.6lbs / 52.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Latias]] | Mega   | Latiasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Latias (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
