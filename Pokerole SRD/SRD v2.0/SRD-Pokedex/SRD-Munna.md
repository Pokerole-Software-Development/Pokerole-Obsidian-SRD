---
Ability1: Forewarn
Ability2: Synchronize
BookSprite: SRD-munna-BookSprite.png
BoxSprite: SRD-munna-BoxSprite.png
DexCategory: Dream Eater Pokemon
DexDescription: It lurks close to towns and eats the dreams of people and Pokemon.
  When it eats a pleasant dream, it expels pink-colored mist. If you forgot what you
  dreamed, a Munna must have eaten your dream.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Musharna]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Telepathy
HomeSprite: SRD-munna-HomeSprite.png
Image: munna.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Psywave|Psywave]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Nightmare|Nightmare]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Healing Wish|Healing Wish]]'
Number: 517
ShuffleToken: SRD-munna-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 23.3
  Pounds: 51.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-munna-BookSprite.png|wsmall]]
> ![[SRD-munna-HomeSprite.png]]
> ![[SRD-munna-BoxSprite.png|htiny]]
> ![[SRD-munna-ShuffleToken.png|wsmall]]


*Dream Eater Pokemon*
*It lurks close to towns and eats the dreams of people and Pokemon. When it eats a pleasant dream, it expels pink-colored mist. If you forgot what you dreamed, a Munna must have eaten your dream.*

**DexID**:: 0517
**Name**:: Munna
**Type**:: Psychic
**Abilities**:: [[SRD-Forewarn|Forewarn]] / [[SRD-Synchronize|Synchronize]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 51.4lbs / 23.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| To        | [[SRD-Musharna]] | Stone  | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Munna.md"
flatten moves as T
where file.path = this.file.path
```
