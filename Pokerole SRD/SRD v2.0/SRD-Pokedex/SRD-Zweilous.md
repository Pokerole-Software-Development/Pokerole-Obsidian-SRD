---
Ability1: Hustle
Ability2: ''
BookSprite: SRD-zweilous-BookSprite.png
BoxSprite: SRD-zweilous-BoxSprite.png
DexCategory: Hostile Pokemon
DexDescription: The two heads do not get along with each other as they compete for
  food. For this reason , Zweilous usually eats more than it should. Touching it carelessly
  can get you attacked by one or both heads.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Deino]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hydreigon]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-zweilous-HomeSprite.png
Image: zweilous.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Double Hit|Double Hit]]'
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
Number: 634
ShuffleToken: SRD-zweilous-ShuffleToken.png
Type1: Dark
Type2: Dragon
Weight:
  Kilograms: 50.0
  Pounds: 110.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zweilous-BookSprite.png|wsmall]]
> ![[SRD-zweilous-HomeSprite.png]]
> ![[SRD-zweilous-BoxSprite.png|htiny]]
> ![[SRD-zweilous-ShuffleToken.png|wsmall]]


*Hostile Pokemon*
*The two heads do not get along with each other as they compete for food. For this reason , Zweilous usually eats more than it should. Touching it carelessly can get you attacked by one or both heads.*

**DexID**:: 0634
**Name**:: Zweilous
**Type**:: Dark / Dragon
**Abilities**:: [[SRD-Hustle|Hustle]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 110.2lbs / 50.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Deino]]     | Level  | Slow    |
| To        | [[SRD-Hydreigon]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zweilous.md"
flatten moves as T
where file.path = this.file.path
```
