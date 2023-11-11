---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-giratina-BookSprite.png
BoxSprite: SRD-giratina-BoxSprite.png
DexCategory: Plot Device
DexDescription: Plot Device
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Giratina (Origin Form)]]'
GenderType: N
Height:
  Feet: 14.8
  Meters: 4.5
HiddenAbility: Telepathy
HomeSprite: SRD-giratina-HomeSprite.png
Image: giratina.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Sneak|Shadow Sneak]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Destiny Bond|Destiny Bond]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earth Power|Earth Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Claw|Shadow Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Force|Shadow Force]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hex|Hex]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spite|Spite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pain Split|Pain Split]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gravity|Gravity]]'
Number: 487
ShuffleToken: SRD-giratina-ShuffleToken.png
Type1: Ghost
Type2: Dragon
Weight:
  Kilograms: 750.0
  Pounds: 1653.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-giratina-BookSprite.png|wsmall]]
> ![[SRD-giratina-HomeSprite.png]]
> ![[SRD-giratina-BoxSprite.png|htiny]]
> ![[SRD-giratina-ShuffleToken.png|wsmall]]


*Plot Device*
*Plot Device*

**DexID**:: 0487
**Name**:: Giratina
**Type**:: Ghost / Dragon
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 14'8" / 4.5m
**Weight**: 1653.5lbs / 750.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                        | Kind   |
|:----------|:-------------------------------|:-------|
| To        | [[SRD-Giratina (Origin Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Giratina.md"
flatten moves as T
where file.path = this.file.path
```
