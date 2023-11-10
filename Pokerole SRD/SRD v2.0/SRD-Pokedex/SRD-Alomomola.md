---
Ability1: Healer
Ability2: Hydration
BookSprite: SRD-alomomola-BookSprite.png
BoxSprite: SRD-alomomola-BoxSprite.png
DexCategory: Caring Pokemon
DexDescription: Floating in the open sea is how they live. When they find a wounded
  Pokemon, they embrace it and use their special membrane to heal their wounds. A
  caring, noble and selfless Pokemon.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Regenerator
HomeSprite: SRD-alomomola-HomeSprite.png
Image: alomomola.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 594
ShuffleToken: SRD-alomomola-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 31.6
  Pounds: 69.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-alomomola-BookSprite.png|wsmall]]
> ![[SRD-alomomola-HomeSprite.png]]
> ![[SRD-alomomola-BoxSprite.png|htiny]]
> ![[SRD-alomomola-ShuffleToken.png|wsmall]]


*Caring Pokemon*
*Floating in the open sea is how they live. When they find a wounded Pokemon, they embrace it and use their special membrane to heal their wounds. A caring, noble and selfless Pokemon.*

**DexID**:: 0594
**Name**:: Alomomola
**Type**:: Water
**Abilities**:: [[SRD-Healer|Healer]] / [[SRD-Hydration|Hydration]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 69.7lbs / 31.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Alomomola.md"
flatten moves as T
where file.path = this.file.path
```
