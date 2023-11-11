---
Ability1: Synchronize
Ability2: ''
BookSprite: SRD-espeon-BookSprite.png
BoxSprite: SRD-espeon-BoxSprite.png
DexCategory: Sun Pokemon
DexDescription: Espeon is extremely loyal to the trainer it considers worthy. It is
  said to have developed precognitive powers to protect its trainer from harm. The
  orb on its forehead glows whenever it uses psychic energy.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Eevee]]'
  Special: Sunlight
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Magic Bounce
HomeSprite: SRD-espeon-HomeSprite.png
Image: espeon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Morning Sun|Morning Sun]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Swap|Power Swap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stored Power|Stored Power]]'
Number: 196
ShuffleToken: SRD-espeon-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 26.5
  Pounds: 58.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-espeon-BookSprite.png|wsmall]]
> ![[SRD-espeon-HomeSprite.png]]
> ![[SRD-espeon-BoxSprite.png|htiny]]
> ![[SRD-espeon-ShuffleToken.png|wsmall]]


*Sun Pokemon*
*Espeon is extremely loyal to the trainer it considers worthy. It is said to have developed precognitive powers to protect its trainer from harm. The orb on its forehead glows whenever it uses psychic energy.*

**DexID**:: 0196
**Name**:: Espeon
**Type**:: Psychic
**Abilities**:: [[SRD-Synchronize|Synchronize]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 58.4lbs / 26.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind    | Stat      |   Value | Special   |
|:----------|:--------------|:--------|:----------|--------:|:----------|
| From      | [[SRD-Eevee]] | Special | Happiness |       4 | Sunlight  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Espeon.md"
flatten moves as T
where file.path = this.file.path
```
