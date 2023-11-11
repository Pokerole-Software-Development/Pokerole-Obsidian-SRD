---
Ability1: Gorilla Tactics
Ability2: Zen Mode
BookSprite: SRD-darmanitan-galarian-form-BookSprite.png
BoxSprite: SRD-darmanitan-galarian-form-BoxSprite.png
DexCategory: Zen Charm Pokemon
DexDescription: The Galarian form of Darmanitan. They walk into towns during the blizzards
  to steal food. Darmanitans seem mean, but they are gentle and shy.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Darumaka (Galarian Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Darmanitan (Galarian Zen Form)]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-darmanitan-galarian-form-HomeSprite.png
Image: darmanitan-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Work Up|Work Up]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thrash|Thrash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icicle Crash|Icicle Crash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thief|Thief]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Freeze Dry|Freeze Dry]]'
Number: 555
ShuffleToken: SRD-darmanitan-galarian-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darmanitan-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-darmanitan-galarian-form-HomeSprite.png]]
> ![[SRD-darmanitan-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-darmanitan-galarian-form-ShuffleToken.png|wsmall]]


*Zen Charm Pokemon*
*The Galarian form of Darmanitan. They walk into towns during the blizzards to steal food. Darmanitans seem mean, but they are gentle and shy.*

**DexID**:: 0555G
**Name**:: Darmanitan (Galarian Form)
**Type**:: Ice
**Abilities**:: [[SRD-Gorilla Tactics|Gorilla Tactics]] / [[SRD-Zen Mode|Zen Mode]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                                | Kind   | Item      |
|:----------|:---------------------------------------|:-------|:----------|
| From      | [[SRD-Darumaka (Galarian Form)]]       | Stone  | Ice Stone |
| To        | [[SRD-Darmanitan (Galarian Zen Form)]] | Form   |           |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Darmanitan (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
