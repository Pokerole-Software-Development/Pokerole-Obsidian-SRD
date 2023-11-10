---
Ability1: Rattled
Ability2: Static
BookSprite: SRD-toxel-BookSprite.png
BoxSprite: SRD-toxel-BoxSprite.png
DexCategory: Baby Pokemon
DexDescription: Toxel secrete poison through their skin, the closer they are to evolving,
  the brighter their skin color becomes. They need a lot of nurturing but are bad
  tempered and ill mannered so not many take the task.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Toxtricity (Amped Form)]]'
  Special: Extrovert
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Toxtricity (Low Key Form)]]'
  Special: Introvert
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Klutz
HomeSprite: SRD-toxel-HomeSprite.png
Image: toxel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Starter
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Encore|Encore]]'
- - Pro
  - '[[SRD-Rest|Rest]]'
- - Pro
  - '[[SRD-Round|Round]]'
Number: 848
ShuffleToken: SRD-toxel-ShuffleToken.png
Type1: Electric
Type2: Poison
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-toxel-BookSprite.png|wsmall]]
> ![[SRD-toxel-HomeSprite.png]]
> ![[SRD-toxel-BoxSprite.png|htiny]]
> ![[SRD-toxel-ShuffleToken.png|wsmall]]


*Baby Pokemon*
*Toxel secrete poison through their skin, the closer they are to evolving, the brighter their skin color becomes. They need a lot of nurturing but are bad tempered and ill mannered so not many take the task.*

**DexID**:: 0848
**Name**:: Toxel
**Type**:: Electric / Poison
**Abilities**:: [[SRD-Rattled|Rattled]] / [[SRD-Static|Static]] ([[SRD-Klutz|Klutz]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                           | Kind   | Speed   | Special   |
|:----------|:----------------------------------|:-------|:--------|:----------|
| To        | [[SRD-Toxtricity (Amped Form)]]   | Level  | Slow    | Extrovert |
| To        | [[SRD-Toxtricity (Low Key Form)]] | Level  | Slow    | Introvert |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Toxel.md"
flatten moves as T
where file.path = this.file.path
```
