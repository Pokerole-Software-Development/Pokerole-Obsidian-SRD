---
Ability1: Compound Eyes
Ability2: Tinted Lens
BookSprite: SRD-venonat-BookSprite.png
BoxSprite: SRD-venonat-BoxSprite.png
DexCategory: Insect Pokemon
DexDescription: It lives in the holes of trees in dense forests and jungles. Its large
  eyes never fail to spot even minuscule prey. Sometimes Venonat uses its powers to
  confuse travelers and make them lose their way.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Venomoth]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Run Away
HomeSprite: SRD-venonat-HomeSprite.png
Image: venonat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 48
ShuffleToken: SRD-venonat-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-venonat-BookSprite.png|wsmall]]
> ![[SRD-venonat-HomeSprite.png]]
> ![[SRD-venonat-BoxSprite.png|htiny]]
> ![[SRD-venonat-ShuffleToken.png|wsmall]]


*Insect Pokemon*
*It lives in the holes of trees in dense forests and jungles. Its large eyes never fail to spot even minuscule prey. Sometimes Venonat uses its powers to confuse travelers and make them lose their way.*

**DexID**:: 0048
**Name**:: Venonat
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Compound Eyes|Compound Eyes]] / [[SRD-Tinted Lens|Tinted Lens]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Venomoth]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Venonat.md"
flatten moves as T
where file.path = this.file.path
```
