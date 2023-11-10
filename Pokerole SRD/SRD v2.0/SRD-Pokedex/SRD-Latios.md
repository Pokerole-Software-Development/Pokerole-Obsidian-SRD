---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-latios-BookSprite.png
BoxSprite: SRD-latios-BoxSprite.png
DexCategory: No Data
DexDescription: The legend tells about two Pokemon that could take human shapes, use
  psychic powers and become invisible. They were raised by an old couple as their
  own children. The boy was the oldest and wore a blue shirt.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Latiasite
  Kind: Mega
  Pokemon: '[[SRD-Latios (Mega Form)]]'
GenderType: M
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-latios-HomeSprite.png
Image: latios.png
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
ShuffleToken: SRD-latios-ShuffleToken.png
Type1: Dragon
Type2: Psychic
Weight:
  Kilograms: 60.0
  Pounds: 132.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-latios-BookSprite.png|wsmall]]
> ![[SRD-latios-HomeSprite.png]]
> ![[SRD-latios-BoxSprite.png|htiny]]
> ![[SRD-latios-ShuffleToken.png|wsmall]]


*No Data*
*The legend tells about two Pokemon that could take human shapes, use psychic powers and become invisible. They were raised by an old couple as their own children. The boy was the oldest and wore a blue shirt.*

**DexID**:: 0381
**Name**:: Latios
**Type**:: Dragon / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 132.3lbs / 60.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                    | Kind   | Item      |
|:----------|:---------------------------|:-------|:----------|
| To        | [[SRD-Latios (Mega Form)]] | Mega   | Latiasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Latios.md"
flatten moves as T
where file.path = this.file.path
```
