---
Ability1: Run Away
Ability2: Pastel Veil
BookSprite: SRD-ponyta-galarian-form-BookSprite.png
BoxSprite: SRD-ponyta-galarian-form-BoxSprite.png
DexCategory: Unique Horn Pokemonn
DexDescription: "The old magical forests of Galar made Ponytas adopt a mystic nature.\
  \ Their miraculous horn can heal most wounds and sense the purity in your heart,\
  \ if you hold evil, you\u2019ll never see this Pokemon in the wild."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Rapidash (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Anticipation
HomeSprite: SRD-ponyta-galarian-form-HomeSprite.png
Image: ponyta-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Protect|Protect]]'
Number: 77
ShuffleToken: SRD-ponyta-galarian-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 24.0
  Pounds: 52.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ponyta-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-ponyta-galarian-form-HomeSprite.png]]
> ![[SRD-ponyta-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-ponyta-galarian-form-ShuffleToken.png|wsmall]]


*Unique Horn Pokemonn*
*The old magical forests of Galar made Ponytas adopt a mystic nature. Their miraculous horn can heal most wounds and sense the purity in your heart, if you hold evil, you’ll never see this Pokemon in the wild.*

**DexID**:: 0077G
**Name**:: Ponyta (Galarian Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Pastel Veil|Pastel Veil]] ([[SRD-Anticipation|Anticipation]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 52.9lbs / 24.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                          | Kind   | Speed   |
|:----------|:---------------------------------|:-------|:--------|
| To        | [[SRD-Rapidash (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ponyta (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
