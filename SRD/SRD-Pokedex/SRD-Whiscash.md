---
Ability1: Oblivious
Ability2: Anticipation
BookSprite: SRD-whiscash-BookSprite.png
BoxSprite: SRD-whiscash-BoxSprite.png
DexCategory: Whiskers Pokemon
DexDescription: Dangerous and territorial, they claim entire ponds as their homes
  and will crush whoever dares to dive in with earthquakes. They eat anything alive
  in their pond or swamp. They have learned to foretell real tremors.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Barboach]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Hydration
HomeSprite: SRD-whiscash-HomeSprite.png
Image: whiscash.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Starter
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Belch|Belch]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Snore|Snore]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Spark|Spark]]'
Number: 340
ShuffleToken: SRD-whiscash-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 23.6
  Pounds: 52.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-whiscash-BookSprite.png|wsmall]]
> ![[SRD-whiscash-HomeSprite.png]]
> ![[SRD-whiscash-BoxSprite.png|htiny]]
> ![[SRD-whiscash-ShuffleToken.png|wsmall]]


*Whiskers Pokemon*
*Dangerous and territorial, they claim entire ponds as their homes and will crush whoever dares to dive in with earthquakes. They eat anything alive in their pond or swamp. They have learned to foretell real tremors.*

**DexID**:: 0340
**Name**:: Whiscash
**Type**:: Water / Ground
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Anticipation|Anticipation]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 52.0lbs / 23.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Barboach]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Whiscash.md"
flatten moves as T
where file.path = this.file.path
```
