---
Ability1: Sap Sipper
Ability2: Hydration
BookSprite: SRD-goodra-BookSprite.png
BoxSprite: SRD-goodra-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: Definitely the friendliest of all Dragons. This Pokemon will hug its
  beloved Trainer, leaving them covered in sticky slime. In areas with heavy rainfall
  during the year, one or two may make an appearance.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sliggoo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Gooey
HomeSprite: SRD-goodra-HomeSprite.png
Image: goodra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Power Whip|Power Whip]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 706
ShuffleToken: SRD-goodra-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 150.5
  Pounds: 331.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-goodra-BookSprite.png|wsmall]]
> ![[SRD-goodra-HomeSprite.png]]
> ![[SRD-goodra-BoxSprite.png|htiny]]
> ![[SRD-goodra-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*Definitely the friendliest of all Dragons. This Pokemon will hug its beloved Trainer, leaving them covered in sticky slime. In areas with heavy rainfall during the year, one or two may make an appearance.*

**DexID**:: 0706
**Name**:: Goodra
**Type**:: Dragon
**Abilities**:: [[SRD-Sap Sipper|Sap Sipper]] / [[SRD-Hydration|Hydration]] ([[SRD-Gooey|Gooey]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 6'6" / 2.0m
**Weight**: 331.8lbs / 150.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Sliggoo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Goodra.md"
flatten moves as T
where file.path = this.file.path
```
