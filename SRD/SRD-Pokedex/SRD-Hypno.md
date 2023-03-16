---
Ability1: Insomnia
Ability2: Forewarn
BookSprite: SRD-hypno-BookSprite.png
BoxSprite: SRD-hypno-BoxSprite.png
DexCategory: Hypnosis Pokemon
DexDescription: Old children stories tell of an Hypno who takes away naughty kids
  and feasts on their dreams until they are old men. They have an urge to eat the
  dreams of others since they cannot sleep themselves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Drowzee]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Inner Focus
HomeSprite: SRD-hypno-HomeSprite.png
Image: hypno.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nightmare|Nightmare]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Psyshock|Psyshock]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Metronome|Metronome]]'
Number: 97
ShuffleToken: SRD-hypno-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 75.6
  Pounds: 166.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hypno-BookSprite.png|wsmall]]
> ![[SRD-hypno-HomeSprite.png]]
> ![[SRD-hypno-BoxSprite.png|htiny]]
> ![[SRD-hypno-ShuffleToken.png|wsmall]]


*Hypnosis Pokemon*
*Old children stories tell of an Hypno who takes away naughty kids and feasts on their dreams until they are old men. They have an urge to eat the dreams of others since they cannot sleep themselves.*

**DexID**:: 0097
**Name**:: Hypno
**Type**:: Psychic
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Forewarn|Forewarn]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 166.7lbs / 75.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Drowzee]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hypno.md"
flatten moves as T
where file.path = this.file.path
```
