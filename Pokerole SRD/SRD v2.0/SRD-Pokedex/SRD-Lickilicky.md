---
Ability1: Own Tempo
Ability2: Oblivious
BookSprite: SRD-lickilicky-BookSprite.png
BoxSprite: SRD-lickilicky-BoxSprite.png
DexCategory: Licking Pokemon
DexDescription: It uses its tongue as an stretchable arm. It will wrap prey with it
  and then proceed to eat it. Its saliva causes numbness. Try not to touch its tongue,
  it might try to eat you by reflex.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Lickitung]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Cloud Nine
HomeSprite: SRD-lickilicky-HomeSprite.png
Image: lickilicky.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Wrap|Wrap]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rollout|Rollout]]'
- - Ace
  - '[[SRD-Chip Away|Chip Away]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Power Whip|Power Whip]]'
- - Pro
  - '[[SRD-Wring Out|Wring Out]]'
Number: 463
ShuffleToken: SRD-lickilicky-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 140.0
  Pounds: 308.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lickilicky-BookSprite.png|wsmall]]
> ![[SRD-lickilicky-HomeSprite.png]]
> ![[SRD-lickilicky-BoxSprite.png|htiny]]
> ![[SRD-lickilicky-ShuffleToken.png|wsmall]]


*Licking Pokemon*
*It uses its tongue as an stretchable arm. It will wrap prey with it and then proceed to eat it. Its saliva causes numbness. Try not to touch its tongue, it might try to eat you by reflex.*

**DexID**:: 0463
**Name**:: Lickilicky
**Type**:: Normal
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Cloud Nine|Cloud Nine]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 308.6lbs / 140.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Lickitung]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lickilicky.md"
flatten moves as T
where file.path = this.file.path
```
