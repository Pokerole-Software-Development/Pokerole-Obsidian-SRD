---
Ability1: Guts
Ability2: Inner Focus
BookSprite: SRD-throh-BookSprite.png
BoxSprite: SRD-throh-BoxSprite.png
DexCategory: Judo Pokemon
DexDescription: When they encounter foes bigger than themselves, they try to throw
  them away. In the wild they always travel in packs of five and make their clothes
  and belts out of plants and vines.
EventAbilities: ''
Evolutions: []
GenderType: M
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Mold Breaker
HomeSprite: SRD-throh-HomeSprite.png
Image: throh.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bind|Bind]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mat Block|Mat Block]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Storm Throw|Storm Throw]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Ace
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Number: 538
ShuffleToken: SRD-throh-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 55.5
  Pounds: 122.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-throh-BookSprite.png|wsmall]]
> ![[SRD-throh-HomeSprite.png]]
> ![[SRD-throh-BoxSprite.png|htiny]]
> ![[SRD-throh-ShuffleToken.png|wsmall]]


*Judo Pokemon*
*When they encounter foes bigger than themselves, they try to throw them away. In the wild they always travel in packs of five and make their clothes and belts out of plants and vines.*

**DexID**:: 0538
**Name**:: Throh
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 122.4lbs / 55.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Throh.md"
flatten moves as T
where file.path = this.file.path
```
