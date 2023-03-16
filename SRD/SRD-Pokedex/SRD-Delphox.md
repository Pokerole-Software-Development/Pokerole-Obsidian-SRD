---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-delphox-BookSprite.png
BoxSprite: SRD-delphox-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: It swirls its twig to create amazing flamethrowers. It gazes into
  the flame at the tip of its stick to achieve a focused state and rumor says that
  it can see the future within the glowing ember.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Braixen]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Magician
HomeSprite: SRD-delphox-HomeSprite.png
Image: delphox.png
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
  - '[[SRD-Magic Room|Magic Room]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Mystical Fire|Mystical Fire]]'
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
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Role Play|Role Play]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Pro
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 655
ShuffleToken: SRD-delphox-ShuffleToken.png
Type1: Fire
Type2: Psychic
Weight:
  Kilograms: 39.0
  Pounds: 86.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-delphox-BookSprite.png|wsmall]]
> ![[SRD-delphox-HomeSprite.png]]
> ![[SRD-delphox-BoxSprite.png|htiny]]
> ![[SRD-delphox-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*It swirls its twig to create amazing flamethrowers. It gazes into the flame at the tip of its stick to achieve a focused state and rumor says that it can see the future within the glowing ember.*

**DexID**:: 0655
**Name**:: Delphox
**Type**:: Fire / Psychic
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Magician|Magician]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 86.0lbs / 39.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Braixen]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Delphox.md"
flatten moves as T
where file.path = this.file.path
```
