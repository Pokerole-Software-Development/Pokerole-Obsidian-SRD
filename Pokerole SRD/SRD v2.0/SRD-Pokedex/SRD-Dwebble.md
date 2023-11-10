---
Ability1: Sturdy
Ability2: Shell Armor
BookSprite: SRD-dwebble-BookSprite.png
BoxSprite: SRD-dwebble-BoxSprite.png
DexCategory: Rock Inn Pokemon
DexDescription: Their saliva is corrosive and it uses it to slowly cut pieces of rock.
  The rock becomes a shelter until it grows too large for it. If the rock breaks,
  it stays anxious and agitated until it finds a replacement.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Crustle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Weak Armor
HomeSprite: SRD-dwebble-HomeSprite.png
Image: dwebble.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Starter
  - '[[SRD-Rock Blast|Rock Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Rock Wrecker|Rock Wrecker]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Number: 557
ShuffleToken: SRD-dwebble-ShuffleToken.png
Type1: Bug
Type2: Rock
Weight:
  Kilograms: 14.5
  Pounds: 32.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dwebble-BookSprite.png|wsmall]]
> ![[SRD-dwebble-HomeSprite.png]]
> ![[SRD-dwebble-BoxSprite.png|htiny]]
> ![[SRD-dwebble-ShuffleToken.png|wsmall]]


*Rock Inn Pokemon*
*Their saliva is corrosive and it uses it to slowly cut pieces of rock. The rock becomes a shelter until it grows too large for it. If the rock breaks, it stays anxious and agitated until it finds a replacement.*

**DexID**:: 0557
**Name**:: Dwebble
**Type**:: Bug / Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 32.0lbs / 14.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Crustle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dwebble.md"
flatten moves as T
where file.path = this.file.path
```
