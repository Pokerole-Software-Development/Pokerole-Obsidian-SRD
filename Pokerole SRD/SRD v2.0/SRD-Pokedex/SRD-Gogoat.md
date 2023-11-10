---
Ability1: Sap Sipper
Ability2: ''
BookSprite: SRD-gogoat-BookSprite.png
BoxSprite: SRD-gogoat-BoxSprite.png
DexCategory: Mount Pokemon
DexDescription: In the wild, they inhabit mountain regions with the leader of the
  herd decided by a battle of clashing horns. People rely on Gogoat to get them through
  harsh terrains as it always knows where you want to go.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Skiddo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Grass Pelt
HomeSprite: SRD-gogoat-HomeSprite.png
Image: gogoat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Milk Drink|Milk Drink]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 673
ShuffleToken: SRD-gogoat-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 91.0
  Pounds: 200.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gogoat-BookSprite.png|wsmall]]
> ![[SRD-gogoat-HomeSprite.png]]
> ![[SRD-gogoat-BoxSprite.png|htiny]]
> ![[SRD-gogoat-ShuffleToken.png|wsmall]]


*Mount Pokemon*
*In the wild, they inhabit mountain regions with the leader of the herd decided by a battle of clashing horns. People rely on Gogoat to get them through harsh terrains as it always knows where you want to go.*

**DexID**:: 0673
**Name**:: Gogoat
**Type**:: Grass
**Abilities**:: [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Grass Pelt|Grass Pelt]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 200.6lbs / 91.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Skiddo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gogoat.md"
flatten moves as T
where file.path = this.file.path
```
