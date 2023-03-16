---
Ability1: Adaptability
Ability2: ''
BookSprite: SRD-lucario-mega-form-BookSprite.png
BoxSprite: SRD-lucario-mega-form-BoxSprite.png
DexCategory: Aura Pokemon
DexDescription: 'The explosive, pulsing energy of the auras and the Mega Stone have
  awoken its combative instincts. Its fighting style can be summed up in a single
  word: heartless.'
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Lucarionite
  Kind: Mega
  Pokemon: '[[SRD-Lucario]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: ''
HomeSprite: SRD-lucario-mega-form-HomeSprite.png
Image: lucario-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
Number: 448
ShuffleToken: SRD-lucario-mega-form-ShuffleToken.png
Type1: Fighting
Type2: Steel
Weight:
  Kilograms: 57.5
  Pounds: 126.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lucario-mega-form-BookSprite.png|wsmall]]
> ![[SRD-lucario-mega-form-HomeSprite.png]]
> ![[SRD-lucario-mega-form-BoxSprite.png|htiny]]
> ![[SRD-lucario-mega-form-ShuffleToken.png|wsmall]]


*Aura Pokemon*
*The explosive, pulsing energy of the auras and the Mega Stone have awoken its combative instincts. Its fighting style can be summed up in a single word: heartless.*

**DexID**:: 0448M1
**Name**:: Lucario (Mega Form)
**Type**:: Fighting / Steel
**Abilities**:: [[SRD-Adaptability|Adaptability]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 126.8lbs / 57.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Lucario]] | Mega   | Lucarionite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lucario (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
