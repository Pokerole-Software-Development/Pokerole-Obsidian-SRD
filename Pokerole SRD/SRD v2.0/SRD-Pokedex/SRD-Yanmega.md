---
Ability1: Speed Boost
Ability2: Compound Eyes
BookSprite: SRD-yanmega-BookSprite.png
BoxSprite: SRD-yanmega-BoxSprite.png
DexCategory: Ogre Darner Pokemon
DexDescription: It goes back to its prehistoric roots. It is a lot more violent than
  its pre-evolved form. Its jaw power is incredible and it is adept at biting apart
  foes while flying by at high speed. This Pokemon can be brutal
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Yanma]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Frisk
HomeSprite: SRD-yanmega-HomeSprite.png
Image: yanmega.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Team|Double Team]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sonic Boom|Sonic Boom]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Detect|Detect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Uproar|Uproar]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Screech|Screech]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-U-Turn|U-Turn]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reversal|Reversal]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
Number: 469
ShuffleToken: SRD-yanmega-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 51.5
  Pounds: 113.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yanmega-BookSprite.png|wsmall]]
> ![[SRD-yanmega-HomeSprite.png]]
> ![[SRD-yanmega-BoxSprite.png|htiny]]
> ![[SRD-yanmega-ShuffleToken.png|wsmall]]


*Ogre Darner Pokemon*
*It goes back to its prehistoric roots. It is a lot more violent than its pre-evolved form. Its jaw power is incredible and it is adept at biting apart foes while flying by at high speed. This Pokemon can be brutal*

**DexID**:: 0469
**Name**:: Yanmega
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Speed Boost|Speed Boost]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Frisk|Frisk]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'2" / 1.9m
**Weight**: 113.5lbs / 51.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Yanma]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Yanmega.md"
flatten moves as T
where file.path = this.file.path
```
