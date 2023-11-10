---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-latios-mega-form-BookSprite.png
BoxSprite: SRD-latios-mega-form-BoxSprite.png
DexCategory: No Data
DexDescription: Latios is very in sync with human logic, it can communicate using
  telepathy. With the power of the Mega Stone all of its capabilities are enhanced
  although its personality becomes more caring than usual.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Latiasite
  Kind: Mega
  Pokemon: '[[SRD-Latios]]'
GenderType: M
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: ''
HomeSprite: SRD-latios-mega-form-HomeSprite.png
Image: latios-mega-form.png
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
  - '[[SRD-Heal Block|Heal Block]]'
- - Pro
  - '[[SRD-Protect|Protect]]'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[SRD-Luster Purge|Luster Purge]]'
- - Pro
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
- - Pro
  - '[[SRD-Camouflage|Camouflage]]'
- - Pro
  - '[[SRD-Transform|Transform]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
Number: 381
ShuffleToken: SRD-latios-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Psychic
Weight:
  Kilograms: 70.0
  Pounds: 154.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-latios-mega-form-BookSprite.png|wsmall]]
> ![[SRD-latios-mega-form-HomeSprite.png]]
> ![[SRD-latios-mega-form-BoxSprite.png|htiny]]
> ![[SRD-latios-mega-form-ShuffleToken.png|wsmall]]


*No Data*
*Latios is very in sync with human logic, it can communicate using telepathy. With the power of the Mega Stone all of its capabilities are enhanced although its personality becomes more caring than usual.*

**DexID**:: 0381M1
**Name**:: Latios (Mega Form)
**Type**:: Dragon / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 7'5" / 2.3m
**Weight**: 154.3lbs / 70.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Latios]] | Mega   | Latiasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Latios (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
