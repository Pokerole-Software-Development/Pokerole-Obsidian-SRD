---
Ability1: Keen Eye
Ability2: Vital Spirit
BookSprite: SRD-rockruff-BookSprite.png
BoxSprite: SRD-rockruff-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: Rockruff are very social and friendly, their keen sense of smell allows
  them to find their trainers easily. However, as they age they become wilder and
  rebellious. Do not let them roam alone at night.
EventAbilities: Own Tempo
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lycanroc (Midday Form)]]'
  Special: Day
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lycanroc (Dusk Form)]]'
  Special: Dawn
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lycanroc (Midnight Form)]]'
  Special: Night
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Steadfast
HomeSprite: SRD-rockruff-HomeSprite.png
Image: rockruff.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Snarl|Snarl]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
Number: 744
ShuffleToken: SRD-rockruff-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 9.2
  Pounds: 20.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rockruff-BookSprite.png|wsmall]]
> ![[SRD-rockruff-HomeSprite.png]]
> ![[SRD-rockruff-BoxSprite.png|htiny]]
> ![[SRD-rockruff-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*Rockruff are very social and friendly, their keen sense of smell allows them to find their trainers easily. However, as they age they become wilder and rebellious. Do not let them roam alone at night.*

**DexID**:: 0744
**Name**:: Rockruff
**Type**:: Rock
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Vital Spirit|Vital Spirit]] ([[SRD-Steadfast|Steadfast]]) <[[SRD-Own Tempo|Own Tempo]]>
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 20.3lbs / 9.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                          | Kind   | Speed   | Special   |
|:----------|:---------------------------------|:-------|:--------|:----------|
| To        | [[SRD-Lycanroc (Midday Form)]]   | Level  | Medium  | Day       |
| To        | [[SRD-Lycanroc (Dusk Form)]]     | Level  | Medium  | Dawn      |
| To        | [[SRD-Lycanroc (Midnight Form)]] | Level  | Medium  | Night     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rockruff.md"
flatten moves as T
where file.path = this.file.path
```
