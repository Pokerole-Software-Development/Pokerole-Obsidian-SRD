---
Ability1: Poison Point
Ability2: Swift Swim
BookSprite: SRD-qwilfish-BookSprite.png
BoxSprite: SRD-qwilfish-BoxSprite.png
DexCategory: Balloon Pokemon
DexDescription: It swallows water to inflate its body to appear bigger than its foes.
  Qwilfish must swallow 2 gallons of water to be able to shoot its stings. The poison
  produced by Qwilfish is known to cause fainting.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Intimidate
HomeSprite: SRD-qwilfish-HomeSprite.png
Image: qwilfish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - Starter
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Starter
  - '[[SRD-Spikes|Spikes]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Minimize|Minimize]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Amateur
  - '[[SRD-Bubble|Bubble]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
Number: 211
ShuffleToken: SRD-qwilfish-ShuffleToken.png
Type1: Water
Type2: Poison
Weight:
  Kilograms: 3.9
  Pounds: 8.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-qwilfish-BookSprite.png|wsmall]]
> ![[SRD-qwilfish-HomeSprite.png]]
> ![[SRD-qwilfish-BoxSprite.png|htiny]]
> ![[SRD-qwilfish-ShuffleToken.png|wsmall]]


*Balloon Pokemon*
*It swallows water to inflate its body to appear bigger than its foes. Qwilfish must swallow 2 gallons of water to be able to shoot its stings. The poison produced by Qwilfish is known to cause fainting.*

**DexID**:: 0211
**Name**:: Qwilfish
**Type**:: Water / Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Swift Swim|Swift Swim]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 8.6lbs / 3.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Qwilfish.md"
flatten moves as T
where file.path = this.file.path
```
