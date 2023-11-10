---
Ability1: Own Tempo
Ability2: Oblivious
BookSprite: SRD-lickitung-BookSprite.png
BoxSprite: SRD-lickitung-BoxSprite.png
DexCategory: Licking Pokemon
DexDescription: "Its tongue is twice as long as its body and it is used for everything,\
  \ from capturing prey to feeling it\u2019s surroundings and cleaning itself. It\
  \ really dislikes sour and bitter flavors."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lickilicky]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Cloud Nine
HomeSprite: SRD-lickitung-HomeSprite.png
Image: lickitung.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Lick|Lick]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wrap|Wrap]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Refresh|Refresh]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Power Whip|Power Whip]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Number: 108
ShuffleToken: SRD-lickitung-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 65.5
  Pounds: 144.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lickitung-BookSprite.png|wsmall]]
> ![[SRD-lickitung-HomeSprite.png]]
> ![[SRD-lickitung-BoxSprite.png|htiny]]
> ![[SRD-lickitung-ShuffleToken.png|wsmall]]


*Licking Pokemon*
*Its tongue is twice as long as its body and it is used for everything, from capturing prey to feeling it’s surroundings and cleaning itself. It really dislikes sour and bitter flavors.*

**DexID**:: 0108
**Name**:: Lickitung
**Type**:: Normal
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Cloud Nine|Cloud Nine]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 144.4lbs / 65.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Lickilicky]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lickitung.md"
flatten moves as T
where file.path = this.file.path
```
