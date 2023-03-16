---
Ability1: Swift Swim
Ability2: Hydration
BookSprite: SRD-tympole-BookSprite.png
BoxSprite: SRD-tympole-BoxSprite.png
DexCategory: Tadpole Pokemon
DexDescription: They appear in great numbers on marshes and ponds after a heavy rainfall.
  They warn others of danger and predators by vibrating their cheeks to create a high-pitched
  sound.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Palpitoad]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Water Absorb
HomeSprite: SRD-tympole-HomeSprite.png
Image: tympole.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Round|Round]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 535
ShuffleToken: SRD-tympole-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 4.5
  Pounds: 9.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tympole-BookSprite.png|wsmall]]
> ![[SRD-tympole-HomeSprite.png]]
> ![[SRD-tympole-BoxSprite.png|htiny]]
> ![[SRD-tympole-ShuffleToken.png|wsmall]]


*Tadpole Pokemon*
*They appear in great numbers on marshes and ponds after a heavy rainfall. They warn others of danger and predators by vibrating their cheeks to create a high-pitched sound.*

**DexID**:: 0535
**Name**:: Tympole
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Hydration|Hydration]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 9.9lbs / 4.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Palpitoad]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tympole.md"
flatten moves as T
where file.path = this.file.path
```
