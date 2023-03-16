---
Ability1: Thick Fat
Ability2: Ice Body
BookSprite: SRD-spheal-BookSprite.png
BoxSprite: SRD-spheal-BoxSprite.png
DexCategory: Clap Pokemon
DexDescription: They live in big herds with their families. They are bad swimmers
  but good floaters. To move on land, they roll like balls instead of walking. When
  they are happy, they clap and squeal, so they can be really noisy.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sealeo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Oblivious
HomeSprite: SRD-spheal-HomeSprite.png
Image: spheal.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Snore|Snore]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dive|Dive]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 363
ShuffleToken: SRD-spheal-ShuffleToken.png
Type1: Ice
Type2: Water
Weight:
  Kilograms: 39.5
  Pounds: 87.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spheal-BookSprite.png|wsmall]]
> ![[SRD-spheal-HomeSprite.png]]
> ![[SRD-spheal-BoxSprite.png|htiny]]
> ![[SRD-spheal-ShuffleToken.png|wsmall]]


*Clap Pokemon*
*They live in big herds with their families. They are bad swimmers but good floaters. To move on land, they roll like balls instead of walking. When they are happy, they clap and squeal, so they can be really noisy.*

**DexID**:: 0363
**Name**:: Spheal
**Type**:: Ice / Water
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Oblivious|Oblivious]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 87.1lbs / 39.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Sealeo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Spheal.md"
flatten moves as T
where file.path = this.file.path
```
