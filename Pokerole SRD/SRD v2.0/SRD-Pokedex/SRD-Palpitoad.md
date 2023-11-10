---
Ability1: Swift Swim
Ability2: Hydration
BookSprite: SRD-palpitoad-BookSprite.png
BoxSprite: SRD-palpitoad-BoxSprite.png
DexCategory: Vibration Pokemon
DexDescription: It lives both in water and land. It uses its long, sticky tongue to
  capture prey. When they vibrate the bumps on their heads, they can make waves in
  the water and even earthquake-like vibrations on land.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tympole]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Seismitoad]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Water Absorb
HomeSprite: SRD-palpitoad-HomeSprite.png
Image: palpitoad.png
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
Number: 536
ShuffleToken: SRD-palpitoad-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 17.0
  Pounds: 37.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-palpitoad-BookSprite.png|wsmall]]
> ![[SRD-palpitoad-HomeSprite.png]]
> ![[SRD-palpitoad-BoxSprite.png|htiny]]
> ![[SRD-palpitoad-ShuffleToken.png|wsmall]]


*Vibration Pokemon*
*It lives both in water and land. It uses its long, sticky tongue to capture prey. When they vibrate the bumps on their heads, they can make waves in the water and even earthquake-like vibrations on land.*

**DexID**:: 0536
**Name**:: Palpitoad
**Type**:: Water / Ground
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Hydration|Hydration]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 37.5lbs / 17.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Tympole]]    | Level  | Medium  |
| To        | [[SRD-Seismitoad]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Palpitoad.md"
flatten moves as T
where file.path = this.file.path
```
