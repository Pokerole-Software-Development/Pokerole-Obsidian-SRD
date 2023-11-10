---
Ability1: Sturdy
Ability2: ''
BookSprite: SRD-cosmoem-BookSprite.png
BoxSprite: SRD-cosmoem-BoxSprite.png
DexCategory: No Data
DexDescription: The creature observed through the telescope changed shapes and remained
  motionless for the rest of the investigation. A strange energy was gathering on
  its core.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cosmog]]'
  Speed: Unknown
- Evolves: To
  Game: Sword
  Kind: Level
  Pokemon: '[[SRD-Solgaleo]]'
- Evolves: To
  Game: Shield
  Kind: Level
  Pokemon: '[[SRD-Lunala]]'
GenderType: N
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: ''
HomeSprite: SRD-cosmoem-HomeSprite.png
Image: cosmoem.png
Legendary: 'Yes'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
Number: 790
ShuffleToken: SRD-cosmoem-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 999.9
  Pounds: 2204.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cosmoem-BookSprite.png|wsmall]]
> ![[SRD-cosmoem-HomeSprite.png]]
> ![[SRD-cosmoem-BoxSprite.png|htiny]]
> ![[SRD-cosmoem-ShuffleToken.png|wsmall]]


*No Data*
*The creature observed through the telescope changed shapes and remained motionless for the rest of the investigation. A strange energy was gathering on its core.*

**DexID**:: 0790
**Name**:: Cosmoem
**Type**:: Psychic
**Abilities**:: [[SRD-Sturdy|Sturdy]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 0'3" / 0.1m
**Weight**: 2204.4lbs / 999.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Game   |
|:----------|:-----------------|:-------|:--------|:-------|
| From      | [[SRD-Cosmog]]   | Level  | Unknown |        |
| To        | [[SRD-Solgaleo]] | Level  |         | Sword  |
| To        | [[SRD-Lunala]]   | Level  |         | Shield |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cosmoem.md"
flatten moves as T
where file.path = this.file.path
```
