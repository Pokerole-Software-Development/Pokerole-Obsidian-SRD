---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-braixen-BookSprite.png
BoxSprite: SRD-braixen-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: Using friction from its tail fur, it sets the twig it carries on fire
  and launches into battle. The flame on the twig is used to send signals and to create
  patters out of the embers. It is said the twig is a magic wand.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Fennekin]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Delphox]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Magician
HomeSprite: SRD-braixen-HomeSprite.png
Image: braixen.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 654
ShuffleToken: SRD-braixen-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 14.5
  Pounds: 32.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-braixen-BookSprite.png|wsmall]]
> ![[SRD-braixen-HomeSprite.png]]
> ![[SRD-braixen-BoxSprite.png|htiny]]
> ![[SRD-braixen-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*Using friction from its tail fur, it sets the twig it carries on fire and launches into battle. The flame on the twig is used to send signals and to create patters out of the embers. It is said the twig is a magic wand.*

**DexID**:: 0654
**Name**:: Braixen
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Magician|Magician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 32.0lbs / 14.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Fennekin]] | Level  | Medium  |
| To        | [[SRD-Delphox]]  | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Braixen.md"
flatten moves as T
where file.path = this.file.path
```
