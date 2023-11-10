---
Ability1: Zen Mode
Ability2: ''
BookSprite: SRD-darmanitan-zen-form-BookSprite.png
BoxSprite: SRD-darmanitan-zen-form-BoxSprite.png
DexCategory: Blazing Pokemon
DexDescription: "Apparently this Darmanitan just became a statue after receiving a\
  \ lot of damage. It remained immobile, but as soon as it\u2019s health recovered\
  \ it returned to it\u2019s original state and lost its psychic powers."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Darmanitan]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: ''
HomeSprite: SRD-darmanitan-zen-form-HomeSprite.png
Image: darmanitan-zen-form.png
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
ShuffleToken: SRD-darmanitan-zen-form-ShuffleToken.png
Type1: Fire
Type2: Psychic
Weight:
  Kilograms: 92.9
  Pounds: 204.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darmanitan-zen-form-BookSprite.png|wsmall]]
> ![[SRD-darmanitan-zen-form-HomeSprite.png]]
> ![[SRD-darmanitan-zen-form-BoxSprite.png|htiny]]
> ![[SRD-darmanitan-zen-form-ShuffleToken.png|wsmall]]


*Blazing Pokemon*
*Apparently this Darmanitan just became a statue after receiving a lot of damage. It remained immobile, but as soon as it’s health recovered it returned to it’s original state and lost its psychic powers.*

**DexID**:: 0555F1
**Name**:: Darmanitan (Zen Form)
**Type**:: Fire / Psychic
**Abilities**:: [[SRD-Zen Mode|Zen Mode]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 204.8lbs / 92.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   |
|:----------|:-------------------|:-------|
| From      | [[SRD-Darmanitan]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Darmanitan (Zen Form).md"
flatten moves as T
where file.path = this.file.path
```
