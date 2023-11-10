---
Ability1: Thick Fat
Ability2: Hydration
BookSprite: SRD-seel-BookSprite.png
BoxSprite: SRD-seel-BoxSprite.png
DexCategory: Sea Lion Pokemon
DexDescription: A Pokemon that lives on icebergs. It swims in the sea using the point
  on its head to break up the ice. It sleeps a lot during the day, being most active
  at dawn when the temperature starts to cool.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dewgong]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Ice Body
HomeSprite: SRD-seel-HomeSprite.png
Image: seel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Lick|Lick]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 86
ShuffleToken: SRD-seel-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 90.0
  Pounds: 198.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-seel-BookSprite.png|wsmall]]
> ![[SRD-seel-HomeSprite.png]]
> ![[SRD-seel-BoxSprite.png|htiny]]
> ![[SRD-seel-ShuffleToken.png|wsmall]]


*Sea Lion Pokemon*
*A Pokemon that lives on icebergs. It swims in the sea using the point on its head to break up the ice. It sleeps a lot during the day, being most active at dawn when the temperature starts to cool.*

**DexID**:: 0086
**Name**:: Seel
**Type**:: Water
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Hydration|Hydration]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 198.4lbs / 90.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Dewgong]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Seel.md"
flatten moves as T
where file.path = this.file.path
```
