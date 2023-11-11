---
Ability1: Insomnia
Ability2: Super Luck
BookSprite: SRD-honchkrow-BookSprite.png
BoxSprite: SRD-honchkrow-BoxSprite.png
DexCategory: Big Boss Pokemon
DexDescription: It lets out a deep cry to summon Murkrows, which fetch food and shiny
  objects to Honchkrow. It is, however, a tyrant to the Murkrow. It only goes out
  at night to carry out evil deeds.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Murkrow]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Moxie
HomeSprite: SRD-honchkrow-HomeSprite.png
Image: honchkrow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wing Attack|Wing Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swagger|Swagger]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quash|Quash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Cutter|Air Cutter]]'
Number: 430
ShuffleToken: SRD-honchkrow-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 27.3
  Pounds: 60.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-honchkrow-BookSprite.png|wsmall]]
> ![[SRD-honchkrow-HomeSprite.png]]
> ![[SRD-honchkrow-BoxSprite.png|htiny]]
> ![[SRD-honchkrow-ShuffleToken.png|wsmall]]


*Big Boss Pokemon*
*It lets out a deep cry to summon Murkrows, which fetch food and shiny objects to Honchkrow. It is, however, a tyrant to the Murkrow. It only goes out at night to carry out evil deeds.*

**DexID**:: 0430
**Name**:: Honchkrow
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Moxie|Moxie]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 60.2lbs / 27.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Murkrow]] | Stone  | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Honchkrow.md"
flatten moves as T
where file.path = this.file.path
```
