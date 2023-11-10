---
Ability1: Ice Body
Ability2: Snow Cloak
BookSprite: SRD-vanillite-BookSprite.png
BoxSprite: SRD-vanillite-BoxSprite.png
DexCategory: Fresh Snow Pokemon
DexDescription: This Pokemon were born from icicles that bathed in the energy of the
  morning sun. It uses snow to cover its head and protect it from melting. They are
  playful and love to make snow fall around them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vanillish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Weak Armor
HomeSprite: SRD-vanillite-HomeSprite.png
Image: vanillite.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 582
ShuffleToken: SRD-vanillite-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 5.7
  Pounds: 12.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vanillite-BookSprite.png|wsmall]]
> ![[SRD-vanillite-HomeSprite.png]]
> ![[SRD-vanillite-BoxSprite.png|htiny]]
> ![[SRD-vanillite-ShuffleToken.png|wsmall]]


*Fresh Snow Pokemon*
*This Pokemon were born from icicles that bathed in the energy of the morning sun. It uses snow to cover its head and protect it from melting. They are playful and love to make snow fall around them.*

**DexID**:: 0582
**Name**:: Vanillite
**Type**:: Ice
**Abilities**:: [[SRD-Ice Body|Ice Body]] / [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.6lbs / 5.7kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Vanillish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vanillite.md"
flatten moves as T
where file.path = this.file.path
```
