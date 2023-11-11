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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ally Switch|Ally Switch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
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
