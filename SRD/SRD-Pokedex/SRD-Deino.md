---
Ability1: Hustle
Ability2: ''
BookSprite: SRD-deino-BookSprite.png
BoxSprite: SRD-deino-BoxSprite.png
DexCategory: Irate Pokemon
DexDescription: This Pokemon is blind, It bites all it finds to be aware of its surroundings.
  It constantly bumps into things and attacks anything close to it. Their bodies are
  covered in wounds and they are very aggressive.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Zweilous]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-deino-HomeSprite.png
Image: deino.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
Number: 633
ShuffleToken: SRD-deino-ShuffleToken.png
Type1: Dark
Type2: Dragon
Weight:
  Kilograms: 17.3
  Pounds: 38.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deino-BookSprite.png|wsmall]]
> ![[SRD-deino-HomeSprite.png]]
> ![[SRD-deino-BoxSprite.png|htiny]]
> ![[SRD-deino-ShuffleToken.png|wsmall]]


*Irate Pokemon*
*This Pokemon is blind, It bites all it finds to be aware of its surroundings. It constantly bumps into things and attacks anything close to it. Their bodies are covered in wounds and they are very aggressive.*

**DexID**:: 0633
**Name**:: Deino
**Type**:: Dark / Dragon
**Abilities**:: [[SRD-Hustle|Hustle]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 38.1lbs / 17.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Zweilous]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Deino.md"
flatten moves as T
where file.path = this.file.path
```
