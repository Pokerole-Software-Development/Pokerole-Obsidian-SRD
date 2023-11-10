---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-latias-BookSprite.png
BoxSprite: SRD-latias-BoxSprite.png
DexCategory: No Data
DexDescription: The legend tells about two Pokemon that could take human shapes, use
  psychic powers and become invisible. They were raised by an old couple as their
  own children. The little girl had a red dress.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Latiasite
  Kind: Mega
  Pokemon: '[[SRD-Latias (Mega Form)]]'
GenderType: F
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-latias-HomeSprite.png
Image: latias.png
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
ShuffleToken: SRD-latias-ShuffleToken.png
Type1: Dragon
Type2: Psychic
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-latias-BookSprite.png|wsmall]]
> ![[SRD-latias-HomeSprite.png]]
> ![[SRD-latias-BoxSprite.png|htiny]]
> ![[SRD-latias-ShuffleToken.png|wsmall]]


*No Data*
*The legend tells about two Pokemon that could take human shapes, use psychic powers and become invisible. They were raised by an old couple as their own children. The little girl had a red dress.*

**DexID**:: 0380
**Name**:: Latias
**Type**:: Dragon / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 4'6" / 1.4m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                    | Kind   | Item      |
|:----------|:---------------------------|:-------|:----------|
| To        | [[SRD-Latias (Mega Form)]] | Mega   | Latiasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Latias.md"
flatten moves as T
where file.path = this.file.path
```
