---
Ability1: Adaptability
Ability2: ''
BookSprite: SRD-beedrill-mega-form-BookSprite.png
BoxSprite: SRD-beedrill-mega-form-BoxSprite.png
DexCategory: Poison Bee Pokemon
DexDescription: With the power of the Mega Stone all of its limbs are now powerful
  stingers. Their attack can be really vicious stinging and piercing its foe repeatedly
  until the finishing blow with the sting on its rear.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Beedrillite
  Kind: Mega
  Pokemon: '[[SRD-Beedrill]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-beedrill-mega-form-HomeSprite.png
Image: beedrill-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Twineedle|Twineedle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Ace
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
Number: 15
ShuffleToken: SRD-beedrill-mega-form-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 40.5
  Pounds: 89.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beedrill-mega-form-BookSprite.png|wsmall]]
> ![[SRD-beedrill-mega-form-HomeSprite.png]]
> ![[SRD-beedrill-mega-form-BoxSprite.png|htiny]]
> ![[SRD-beedrill-mega-form-ShuffleToken.png|wsmall]]


*Poison Bee Pokemon*
*With the power of the Mega Stone all of its limbs are now powerful stingers. Their attack can be really vicious stinging and piercing its foe repeatedly until the finishing blow with the sting on its rear.*

**DexID**:: 0015M1
**Name**:: Beedrill (Mega Form)
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Adaptability|Adaptability]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 89.3lbs / 40.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Beedrill]] | Mega   | Beedrillite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Beedrill (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
