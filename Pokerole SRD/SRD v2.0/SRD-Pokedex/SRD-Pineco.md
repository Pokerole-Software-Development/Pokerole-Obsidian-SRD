---
Ability1: Sturdy
Ability2: ''
BookSprite: SRD-pineco-BookSprite.png
BoxSprite: SRD-pineco-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: Pineco looks just like a regular pine cone. It adds layers of tree
  bark as a shield from harm. It waits for bugs to eat while hanging from branches.
  If anyone shakes its tree, it falls down and explodes. Be very careful.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Forretress]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Overcoat
HomeSprite: SRD-pineco-HomeSprite.png
Image: pineco.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Self Destruct|Self Destruct]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bide|Bide]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spikes|Spikes]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Payback|Payback]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Explosion|Explosion]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Secret Power|Secret Power]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pin Missile|Pin Missile]]'
Number: 204
ShuffleToken: SRD-pineco-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 7.2
  Pounds: 15.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pineco-BookSprite.png|wsmall]]
> ![[SRD-pineco-HomeSprite.png]]
> ![[SRD-pineco-BoxSprite.png|htiny]]
> ![[SRD-pineco-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*Pineco looks just like a regular pine cone. It adds layers of tree bark as a shield from harm. It waits for bugs to eat while hanging from branches. If anyone shakes its tree, it falls down and explodes. Be very careful.*

**DexID**:: 0204
**Name**:: Pineco
**Type**:: Bug
**Abilities**:: [[SRD-Sturdy|Sturdy]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 15.9lbs / 7.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Forretress]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pineco.md"
flatten moves as T
where file.path = this.file.path
```
