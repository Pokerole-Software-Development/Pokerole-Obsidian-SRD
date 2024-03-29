---
Ability1: Insomnia
Ability2: Forewarn
BookSprite: SRD-drowzee-BookSprite.png
BoxSprite: SRD-drowzee-BoxSprite.png
DexCategory: Hypnosis Pokemon
DexDescription: It eats the dreams of a sleeping person or Pokemon and shows fondness
  to the dreams of young children. Once the victim is deep in slumber it will extract
  and eat the dream through the nose.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hypno]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Inner Focus
HomeSprite: SRD-drowzee-HomeSprite.png
Image: drowzee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pound|Pound]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disable|Disable]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Gas|Poison Gas]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Meditate|Meditate]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synchronoise|Synchronoise]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psyshock|Psyshock]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Role Play|Role Play]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Substitute|Substitute]]'
Number: 96
ShuffleToken: SRD-drowzee-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 32.4
  Pounds: 71.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drowzee-BookSprite.png|wsmall]]
> ![[SRD-drowzee-HomeSprite.png]]
> ![[SRD-drowzee-BoxSprite.png|htiny]]
> ![[SRD-drowzee-ShuffleToken.png|wsmall]]


*Hypnosis Pokemon*
*It eats the dreams of a sleeping person or Pokemon and shows fondness to the dreams of young children. Once the victim is deep in slumber it will extract and eat the dream through the nose.*

**DexID**:: 0096
**Name**:: Drowzee
**Type**:: Psychic
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Forewarn|Forewarn]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 71.4lbs / 32.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| To        | [[SRD-Hypno]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drowzee.md"
flatten moves as T
where file.path = this.file.path
```
