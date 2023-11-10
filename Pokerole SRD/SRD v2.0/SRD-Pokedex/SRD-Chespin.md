---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-chespin-BookSprite.png
BoxSprite: SRD-chespin-BoxSprite.png
DexCategory: Spiky Nut Pokemon
DexDescription: "A small and curious Pokemon. They are rare to find but their nests\
  \ have been found on chestnut trees. Their heads are covered by spikes and if there\u2019\
  s a threat they roll into balls to protect themselves."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Quilladin]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Bulletproof
HomeSprite: SRD-chespin-HomeSprite.png
Image: chespin.png
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
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 650
ShuffleToken: SRD-chespin-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 9.0
  Pounds: 19.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chespin-BookSprite.png|wsmall]]
> ![[SRD-chespin-HomeSprite.png]]
> ![[SRD-chespin-BoxSprite.png|htiny]]
> ![[SRD-chespin-ShuffleToken.png|wsmall]]


*Spiky Nut Pokemon*
*A small and curious Pokemon. They are rare to find but their nests have been found on chestnut trees. Their heads are covered by spikes and if there’s a threat they roll into balls to protect themselves.*

**DexID**:: 0650
**Name**:: Chespin
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 19.8lbs / 9.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Quilladin]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chespin.md"
flatten moves as T
where file.path = this.file.path
```
