---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-kakuna-BookSprite.png
BoxSprite: SRD-kakuna-BoxSprite.png
DexCategory: Cocoon Pokemon
DexDescription: It remains virtually immobile while it clings to a tree. On the inside,
  it is preparing for evolution by rising the temperature of its shell. Beware of
  Beedrills that may roam close to it.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Weedle]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Beedrill]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-kakuna-HomeSprite.png
Image: kakuna.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Electroweb|Electroweb]]'
Number: 14
ShuffleToken: SRD-kakuna-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 10.0
  Pounds: 22.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kakuna-BookSprite.png|wsmall]]
> ![[SRD-kakuna-HomeSprite.png]]
> ![[SRD-kakuna-BoxSprite.png|htiny]]
> ![[SRD-kakuna-ShuffleToken.png|wsmall]]


*Cocoon Pokemon*
*It remains virtually immobile while it clings to a tree. On the inside, it is preparing for evolution by rising the temperature of its shell. Beware of Beedrills that may roam close to it.*

**DexID**:: 0014
**Name**:: Kakuna
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Shed Skin|Shed Skin]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 22.0lbs / 10.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Weedle]]   | Level  | Fast    |
| To        | [[SRD-Beedrill]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kakuna.md"
flatten moves as T
where file.path = this.file.path
```
