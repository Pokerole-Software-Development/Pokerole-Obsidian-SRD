---
Ability1: Cotton Down
Ability2: Regenerator
BookSprite: SRD-eldegoss-BookSprite.png
BoxSprite: SRD-eldegoss-BoxSprite.png
DexCategory: Cotton Bloom Pokemon
DexDescription: The cotton it produces has a glossy finish so clothes made with it
  are insanely expensive. In nature they are calm and selfless Pokemon who allow others
  to take nourishment from the cotton seeds in their head.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gossifleur]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Effect Spore
HomeSprite: SRD-eldegoss-HomeSprite.png
Image: eldegoss.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leafage|Leafage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - Ace
  - '[[SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
Number: 830
ShuffleToken: SRD-eldegoss-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 2.5
  Pounds: 5.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eldegoss-BookSprite.png|wsmall]]
> ![[SRD-eldegoss-HomeSprite.png]]
> ![[SRD-eldegoss-BoxSprite.png|htiny]]
> ![[SRD-eldegoss-ShuffleToken.png|wsmall]]


*Cotton Bloom Pokemon*
*The cotton it produces has a glossy finish so clothes made with it are insanely expensive. In nature they are calm and selfless Pokemon who allow others to take nourishment from the cotton seeds in their head.*

**DexID**:: 0830
**Name**:: Eldegoss
**Type**:: Grass
**Abilities**:: [[SRD-Cotton Down|Cotton Down]] / [[SRD-Regenerator|Regenerator]] ([[SRD-Effect Spore|Effect Spore]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 1'6" / 0.5m
**Weight**: 5.5lbs / 2.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Gossifleur]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Eldegoss.md"
flatten moves as T
where file.path = this.file.path
```
