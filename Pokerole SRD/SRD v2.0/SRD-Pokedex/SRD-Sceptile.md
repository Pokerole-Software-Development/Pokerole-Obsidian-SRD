---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-sceptile-BookSprite.png
BoxSprite: SRD-sceptile-BoxSprite.png
DexCategory: Forest Pokemon
DexDescription: "They raise trees with love and care and protect the jungles with\
  \ their lives. Their tails can restore a plant\u2019s beauty. Sceptiles power is\
  \ truly unmatched in their habitats. They are very proud, though."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grovyle]]'
  Speed: Medium
- Evolves: To
  Item: Sceptilite
  Kind: Mega
  Pokemon: '[[SRD-Sceptile (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Unburden
HomeSprite: SRD-sceptile-HomeSprite.png
Image: sceptile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Dual Chop|Dual Chop]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 254
ShuffleToken: SRD-sceptile-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 52.2
  Pounds: 115.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sceptile-BookSprite.png|wsmall]]
> ![[SRD-sceptile-HomeSprite.png]]
> ![[SRD-sceptile-BoxSprite.png|htiny]]
> ![[SRD-sceptile-ShuffleToken.png|wsmall]]


*Forest Pokemon*
*They raise trees with love and care and protect the jungles with their lives. Their tails can restore a plant’s beauty. Sceptiles power is truly unmatched in their habitats. They are very proud, though.*

**DexID**:: 0254
**Name**:: Sceptile
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 115.1lbs / 52.2kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item       |
|:----------|:-----------------------------|:-------|:--------|:-----------|
| From      | [[SRD-Grovyle]]              | Level  | Medium  |            |
| To        | [[SRD-Sceptile (Mega Form)]] | Mega   |         | Sceptilite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sceptile.md"
flatten moves as T
where file.path = this.file.path
```
