---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-giratina-origin-form-BookSprite.png
BoxSprite: SRD-giratina-origin-form-BoxSprite.png
DexCategory: Plot Device
DexDescription: Plot Device
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Giratina]]'
GenderType: N
Height:
  Feet: 22.6
  Meters: 6.9
HiddenAbility: ''
HomeSprite: SRD-giratina-origin-form-HomeSprite.png
Image: giratina-origin-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Master
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Master
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Master
  - '[[SRD-Shadow Force|Shadow Force]]'
- - Master
  - '[[SRD-Hex|Hex]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Spite|Spite]]'
- - Master
  - '[[SRD-Pain Split|Pain Split]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
Number: 487
ShuffleToken: SRD-giratina-origin-form-ShuffleToken.png
Type1: Ghost
Type2: Dragon
Weight:
  Kilograms: 650.0
  Pounds: 1433.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-giratina-origin-form-BookSprite.png|wsmall]]
> ![[SRD-giratina-origin-form-HomeSprite.png]]
> ![[SRD-giratina-origin-form-BoxSprite.png|htiny]]
> ![[SRD-giratina-origin-form-ShuffleToken.png|wsmall]]


*Plot Device*
*Plot Device*

**DexID**:: 0487F1
**Name**:: Giratina (Origin Form)
**Type**:: Ghost / Dragon
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 22'6" / 6.9m
**Weight**: 1433.0lbs / 650.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Giratina]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Giratina (Origin Form).md"
flatten moves as T
where file.path = this.file.path
```
