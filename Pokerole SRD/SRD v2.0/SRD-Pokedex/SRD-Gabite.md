---
Ability1: Sand Veil
Ability2: ''
BookSprite: SRD-gabite-BookSprite.png
BoxSprite: SRD-gabite-BoxSprite.png
DexCategory: Cave Pokemon
DexDescription: It hoards a small treasure of sparkly things back in its cave. It
  will react aggressively towards any potential thief. It is also an excellent hunter,
  capable of running, swimming and gliding extremely fast.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gible]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Garchomp]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Rough Skin
HomeSprite: SRD-gabite-HomeSprite.png
Image: gabite.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sandstorm|Sandstorm]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dig|Dig]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
Number: 444
ShuffleToken: SRD-gabite-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 56.0
  Pounds: 123.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gabite-BookSprite.png|wsmall]]
> ![[SRD-gabite-HomeSprite.png]]
> ![[SRD-gabite-BoxSprite.png|htiny]]
> ![[SRD-gabite-ShuffleToken.png|wsmall]]


*Cave Pokemon*
*It hoards a small treasure of sparkly things back in its cave. It will react aggressively towards any potential thief. It is also an excellent hunter, capable of running, swimming and gliding extremely fast.*

**DexID**:: 0444
**Name**:: Gabite
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] ([[SRD-Rough Skin|Rough Skin]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 123.5lbs / 56.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Gible]]    | Level  | Slow    |
| To        | [[SRD-Garchomp]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gabite.md"
flatten moves as T
where file.path = this.file.path
```
