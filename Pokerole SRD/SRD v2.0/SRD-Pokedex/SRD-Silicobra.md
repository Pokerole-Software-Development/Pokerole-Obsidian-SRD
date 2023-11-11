---
Ability1: Sand Spit
Ability2: Shed Skin
BookSprite: SRD-silicobra-BookSprite.png
BoxSprite: SRD-silicobra-BoxSprite.png
DexCategory: Sand Snake Pokemon
DexDescription: Silicobra can appear to be very aggressive but they just want to be
  left alone. They spew sand from their nostrils and while the foe is blinded, they
  burrow back into the ground to hide.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sandaconda]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Sand Veil
HomeSprite: SRD-silicobra-HomeSprite.png
Image: silicobra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Minimize|Minimize]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slam|Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Glare|Glare]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dig|Dig]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Coil|Coil]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Tomb|Sand Tomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mud Slap|Mud Slap]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Tail|Poison Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
Number: 843
ShuffleToken: SRD-silicobra-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 7.6
  Pounds: 16.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-silicobra-BookSprite.png|wsmall]]
> ![[SRD-silicobra-HomeSprite.png]]
> ![[SRD-silicobra-BoxSprite.png|htiny]]
> ![[SRD-silicobra-ShuffleToken.png|wsmall]]


*Sand Snake Pokemon*
*Silicobra can appear to be very aggressive but they just want to be left alone. They spew sand from their nostrils and while the foe is blinded, they burrow back into the ground to hide.*

**DexID**:: 0843
**Name**:: Silicobra
**Type**:: Ground
**Abilities**:: [[SRD-Sand Spit|Sand Spit]] / [[SRD-Shed Skin|Shed Skin]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 7'2" / 2.2m
**Weight**: 16.8lbs / 7.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Sandaconda]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Silicobra.md"
flatten moves as T
where file.path = this.file.path
```
