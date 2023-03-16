---
Ability1: Sheer Force
Ability2: ''
BookSprite: SRD-darmanitan-BookSprite.png
BoxSprite: SRD-darmanitan-BoxSprite.png
DexCategory: Blazing Pokemon
DexDescription: This Pokemon is shrouded in mystery as old writings and mural paintings
  describe it as being blue and using psychic powers, but years of study have not
  seen those traits on this Pokemon that relies on brute force.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Darumaka]]'
  Speed: Medium
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Darmanitan (Zen Form)]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Zen Mode
HomeSprite: SRD-darmanitan-HomeSprite.png
Image: darmanitan.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Incinerate|Incinerate]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Fire Fang|Fire Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Facade|Facade]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Belly Drum|Belly Drum]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
Number: 555
ShuffleToken: SRD-darmanitan-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 92.9
  Pounds: 204.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darmanitan-BookSprite.png|wsmall]]
> ![[SRD-darmanitan-HomeSprite.png]]
> ![[SRD-darmanitan-BoxSprite.png|htiny]]
> ![[SRD-darmanitan-ShuffleToken.png|wsmall]]


*Blazing Pokemon*
*This Pokemon is shrouded in mystery as old writings and mural paintings describe it as being blue and using psychic powers, but years of study have not seen those traits on this Pokemon that relies on brute force.*

**DexID**:: 0555
**Name**:: Darmanitan
**Type**:: Fire
**Abilities**:: [[SRD-Sheer Force|Sheer Force]] ([[SRD-Zen Mode|Zen Mode]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 204.8lbs / 92.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| From      | [[SRD-Darumaka]]              | Level  | Medium  |
| To        | [[SRD-Darmanitan (Zen Form)]] | Form   |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Darmanitan.md"
flatten moves as T
where file.path = this.file.path
```
