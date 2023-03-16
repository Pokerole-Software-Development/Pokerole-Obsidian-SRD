---
Ability1: Swarm
Ability2: Compound Eyes
BookSprite: SRD-blipbug-BookSprite.png
BoxSprite: SRD-blipbug-BoxSprite.png
DexCategory: Larva Pokemon
DexDescription: Often found in gardens, Blipbug has hairs on its body that it uses
  to assess its surroundings. They are very smart and easy to teach but they are not
  very strong and other Pokemon bully them often.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dottler]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Telepathy
HomeSprite: SRD-blipbug-HomeSprite.png
Image: blipbug.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Pro
  - '[[SRD-Supersonic|Supersonic]]'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
Number: 824
ShuffleToken: SRD-blipbug-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blipbug-BookSprite.png|wsmall]]
> ![[SRD-blipbug-HomeSprite.png]]
> ![[SRD-blipbug-BoxSprite.png|htiny]]
> ![[SRD-blipbug-ShuffleToken.png|wsmall]]


*Larva Pokemon*
*Often found in gardens, Blipbug has hairs on its body that it uses to assess its surroundings. They are very smart and easy to teach but they are not very strong and other Pokemon bully them often.*

**DexID**:: 0824
**Name**:: Blipbug
**Type**:: Bug
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Dottler]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Blipbug.md"
flatten moves as T
where file.path = this.file.path
```
