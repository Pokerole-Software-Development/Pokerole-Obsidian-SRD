---
Ability1: Thick Fat
Ability2: ''
BookSprite: SRD-venusaur-mega-form-BookSprite.png
BoxSprite: SRD-venusaur-mega-form-BoxSprite.png
DexCategory: Seed Pokemon
DexDescription: "With the power of the Mega Stone, this Pokemon grows taller and thicker.\
  \ It\u2019s bark and skin are now impervious to the elements.\nIts demeanor becomes\
  \ even more serious and determined."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Venusaurite
  Kind: Mega
  Pokemon: '[[SRD-Venusaur]]'
GenderType: ''
Height:
  Feet: 7.9
  Meters: 2.4
HiddenAbility: ''
HomeSprite: SRD-venusaur-mega-form-HomeSprite.png
Image: venusaur-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Dance|Petal Dance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Frenzy Plant|Frenzy Plant]]'
Number: 3
ShuffleToken: SRD-venusaur-mega-form-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 155.5
  Pounds: 342.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-venusaur-mega-form-BookSprite.png|wsmall]]
> ![[SRD-venusaur-mega-form-HomeSprite.png]]
> ![[SRD-venusaur-mega-form-BoxSprite.png|htiny]]
> ![[SRD-venusaur-mega-form-ShuffleToken.png|wsmall]]


*Seed Pokemon*
*With the power of the Mega Stone, this Pokemon grows taller and thicker. It’s bark and skin are now impervious to the elements.
Its demeanor becomes even more serious and determined.*

**DexID**:: 0003M1
**Name**:: Venusaur (Mega Form)
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Thick Fat|Thick Fat]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 7'9" / 2.4m
**Weight**: 342.8lbs / 155.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Venusaur]] | Mega   | Venusaurite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Venusaur (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
