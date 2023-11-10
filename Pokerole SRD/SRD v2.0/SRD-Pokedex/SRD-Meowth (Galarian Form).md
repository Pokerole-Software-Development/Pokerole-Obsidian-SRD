---
Ability1: Pickup
Ability2: Tough Claws
BookSprite: SRD-meowth-galarian-form-BookSprite.png
BoxSprite: SRD-meowth-galarian-form-BoxSprite.png
DexCategory: Scratch Cat Pokemon
DexDescription: The coin on its head has rusted. Meowths were taken into viking ships
  on long travels through the sea, living for so long in such harsh conditions toughened
  it up so much that parts of it have turned to iron.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Perrserker]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Unnerve
HomeSprite: SRD-meowth-galarian-form-HomeSprite.png
Image: meowth-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Beginner
  - '[[SRD-Pay Day|Pay Day]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Steel Beam|Steel Beam]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
Number: 52
ShuffleToken: SRD-meowth-galarian-form-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 7.5
  Pounds: 16.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meowth-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-meowth-galarian-form-HomeSprite.png]]
> ![[SRD-meowth-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-meowth-galarian-form-ShuffleToken.png|wsmall]]


*Scratch Cat Pokemon*
*The coin on its head has rusted. Meowths were taken into viking ships on long travels through the sea, living for so long in such harsh conditions toughened it up so much that parts of it have turned to iron.*

**DexID**:: 0052G
**Name**:: Meowth (Galarian Form)
**Type**:: Steel
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Tough Claws|Tough Claws]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 16.5lbs / 7.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Perrserker]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meowth (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
