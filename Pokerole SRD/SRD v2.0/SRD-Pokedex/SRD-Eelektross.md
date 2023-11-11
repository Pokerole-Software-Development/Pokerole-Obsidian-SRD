---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-eelektross-BookSprite.png
BoxSprite: SRD-eelektross-BoxSprite.png
DexCategory: EleFish Pokemon
DexDescription: They crawl out of the water and attack anyone on shore by sucking
  them into their mouths, shocking them, and dragging them back into the ocean. They
  are aggressive and unpredictable, be very careful
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Eelektrik]]'
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: ''
HomeSprite: SRD-eelektross-HomeSprite.png
Image: eelektross.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crush Claw|Crush Claw]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ion Deluge|Ion Deluge]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Coil|Coil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Punch|Fire Punch]]'
Number: 604
ShuffleToken: SRD-eelektross-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 80.5
  Pounds: 177.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eelektross-BookSprite.png|wsmall]]
> ![[SRD-eelektross-HomeSprite.png]]
> ![[SRD-eelektross-BoxSprite.png|htiny]]
> ![[SRD-eelektross-ShuffleToken.png|wsmall]]


*EleFish Pokemon*
*They crawl out of the water and attack anyone on shore by sucking them into their mouths, shocking them, and dragging them back into the ocean. They are aggressive and unpredictable, be very careful*

**DexID**:: 0604
**Name**:: Eelektross
**Type**:: Electric
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 177.5lbs / 80.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Item          |
|:----------|:------------------|:-------|:--------------|
| From      | [[SRD-Eelektrik]] | Stone  | Thunder Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Eelektross.md"
flatten moves as T
where file.path = this.file.path
```
