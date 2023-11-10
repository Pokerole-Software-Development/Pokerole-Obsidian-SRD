---
Ability1: Vital Spirit
Ability2: Sand Rush
BookSprite: SRD-lillipup-BookSprite.png
BoxSprite: SRD-lillipup-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: "Good with children and old people, this gentle Pokemon is a favorite\
  \ to keep as pet. It is very brave and smart and will protect it\u2019s trainer\
  \ against any threat. It uses the hair on its head to feel its surroundings."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Herdier]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Scrappy
HomeSprite: SRD-lillipup-HomeSprite.png
Image: lillipup.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lick|Lick]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 506
ShuffleToken: SRD-lillipup-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 4.1
  Pounds: 9.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lillipup-BookSprite.png|wsmall]]
> ![[SRD-lillipup-HomeSprite.png]]
> ![[SRD-lillipup-BoxSprite.png|htiny]]
> ![[SRD-lillipup-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*Good with children and old people, this gentle Pokemon is a favorite to keep as pet. It is very brave and smart and will protect it’s trainer against any threat. It uses the hair on its head to feel its surroundings.*

**DexID**:: 0506
**Name**:: Lillipup
**Type**:: Normal
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]] / [[SRD-Sand Rush|Sand Rush]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.0lbs / 4.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Herdier]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lillipup.md"
flatten moves as T
where file.path = this.file.path
```
