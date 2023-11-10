---
Ability1: Corrosion
Ability2: ''
BookSprite: SRD-salandit-BookSprite.png
BoxSprite: SRD-salandit-BoxSprite.png
DexCategory: Toxic Lizard Pokemon
DexDescription: The markings at the end of its tail emit flames and a toxic gas, be
  careful as this gas smells sweet and specially appealing for the males of any species.
  Only female Salandit are known to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Salazzle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Oblivious
HomeSprite: SRD-salandit-HomeSprite.png
Image: salandit.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
Number: 757
ShuffleToken: SRD-salandit-ShuffleToken.png
Type1: Poison
Type2: Fire
Weight:
  Kilograms: 4.8
  Pounds: 10.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-salandit-BookSprite.png|wsmall]]
> ![[SRD-salandit-HomeSprite.png]]
> ![[SRD-salandit-BoxSprite.png|htiny]]
> ![[SRD-salandit-ShuffleToken.png|wsmall]]


*Toxic Lizard Pokemon*
*The markings at the end of its tail emit flames and a toxic gas, be careful as this gas smells sweet and specially appealing for the males of any species. Only female Salandit are known to evolve.*

**DexID**:: 0757
**Name**:: Salandit
**Type**:: Poison / Fire
**Abilities**:: [[SRD-Corrosion|Corrosion]] ([[SRD-Oblivious|Oblivious]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 10.6lbs / 4.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   | Gender   |
|:----------|:-----------------|:-------|:--------|:---------|
| To        | [[SRD-Salazzle]] | Level  | Medium  | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Salandit.md"
flatten moves as T
where file.path = this.file.path
```
