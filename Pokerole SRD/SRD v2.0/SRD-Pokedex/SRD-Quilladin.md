---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-quilladin-BookSprite.png
BoxSprite: SRD-quilladin-BoxSprite.png
DexCategory: Spiny Armor Pokemon
DexDescription: It strengthens its lower body by running into sturdy things. It is
  a kind Pokemon that relies on its sturdy shell and sharp quills to deflect any foe
  trying to attack it. They never start a fight.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Chespin]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Chesnaught]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Bulletproof
HomeSprite: SRD-quilladin-HomeSprite.png
Image: quilladin.png
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
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Needle Arm|Needle Arm]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 651
ShuffleToken: SRD-quilladin-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 29.0
  Pounds: 63.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-quilladin-BookSprite.png|wsmall]]
> ![[SRD-quilladin-HomeSprite.png]]
> ![[SRD-quilladin-BoxSprite.png|htiny]]
> ![[SRD-quilladin-ShuffleToken.png|wsmall]]


*Spiny Armor Pokemon*
*It strengthens its lower body by running into sturdy things. It is a kind Pokemon that relies on its sturdy shell and sharp quills to deflect any foe trying to attack it. They never start a fight.*

**DexID**:: 0651
**Name**:: Quilladin
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 63.9lbs / 29.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Chespin]]    | Level  | Medium  |
| To        | [[SRD-Chesnaught]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Quilladin.md"
flatten moves as T
where file.path = this.file.path
```
