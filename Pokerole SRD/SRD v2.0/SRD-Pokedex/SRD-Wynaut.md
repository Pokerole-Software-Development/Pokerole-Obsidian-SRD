---
Ability1: Shadow Tag
Ability2: ''
BookSprite: SRD-wynaut-BookSprite.png
BoxSprite: SRD-wynaut-BoxSprite.png
DexCategory: Bright Pokemon
DexDescription: Its face always appears to be happy, but Wynaut can be deceitful.
  You can only discern its true emotions through its tail. They live together in caves
  and bump into each other to gain strength.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Wobbuffet]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Telepathy
HomeSprite: SRD-wynaut-HomeSprite.png
Image: wynaut.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Encore|Encore]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Counter|Counter]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Destiny Bond|Destiny Bond]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Coat|Mirror Coat]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
Number: 360
ShuffleToken: SRD-wynaut-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 14.0
  Pounds: 30.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wynaut-BookSprite.png|wsmall]]
> ![[SRD-wynaut-HomeSprite.png]]
> ![[SRD-wynaut-BoxSprite.png|htiny]]
> ![[SRD-wynaut-ShuffleToken.png|wsmall]]


*Bright Pokemon*
*Its face always appears to be happy, but Wynaut can be deceitful. You can only discern its true emotions through its tail. They live together in caves and bump into each other to gain strength.*

**DexID**:: 0360
**Name**:: Wynaut
**Type**:: Psychic
**Abilities**:: [[SRD-Shadow Tag|Shadow Tag]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 30.9lbs / 14.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Wobbuffet]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wynaut.md"
flatten moves as T
where file.path = this.file.path
```
