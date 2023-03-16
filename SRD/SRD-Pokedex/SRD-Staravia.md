---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-staravia-BookSprite.png
BoxSprite: SRD-staravia-BoxSprite.png
DexCategory: Starling Pokemon
DexDescription: They lead a huge flock and fight other flocks for territory. If you
  leave it alone, it will start to make a horrible noise. It is a fierce but bad-mannered
  Pokemon. When they are too weak they abandon their flocks.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Starly]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Staraptor]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Reckless
HomeSprite: SRD-staravia-HomeSprite.png
Image: staravia.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 397
ShuffleToken: SRD-staravia-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 15.5
  Pounds: 34.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-staravia-BookSprite.png|wsmall]]
> ![[SRD-staravia-HomeSprite.png]]
> ![[SRD-staravia-BoxSprite.png|htiny]]
> ![[SRD-staravia-ShuffleToken.png|wsmall]]


*Starling Pokemon*
*They lead a huge flock and fight other flocks for territory. If you leave it alone, it will start to make a horrible noise. It is a fierce but bad-mannered Pokemon. When they are too weak they abandon their flocks.*

**DexID**:: 0397
**Name**:: Staravia
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Intimidate|Intimidate]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 34.2lbs / 15.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Starly]]    | Level  | Medium  |
| To        | [[SRD-Staraptor]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Staravia.md"
flatten moves as T
where file.path = this.file.path
```
