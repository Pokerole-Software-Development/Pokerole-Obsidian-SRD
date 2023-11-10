---
Ability1: Lightning Rod
Ability2: ''
BookSprite: SRD-sceptile-mega-form-BookSprite.png
BoxSprite: SRD-sceptile-mega-form-BoxSprite.png
DexCategory: Forest Pokemon
DexDescription: With the power of the Mega Stone, it allows itself to grow more feral
  in order to gain draconian powers. Its movements are swifter than ever and when
  it attacks it seems like the jungle has come to life.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sceptilite
  Kind: Mega
  Pokemon: '[[SRD-Sceptile]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-sceptile-mega-form-HomeSprite.png
Image: sceptile-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Dual Chop|Dual Chop]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 254
ShuffleToken: SRD-sceptile-mega-form-ShuffleToken.png
Type1: Grass
Type2: Dragon
Weight:
  Kilograms: 55.2
  Pounds: 121.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sceptile-mega-form-BookSprite.png|wsmall]]
> ![[SRD-sceptile-mega-form-HomeSprite.png]]
> ![[SRD-sceptile-mega-form-BoxSprite.png|htiny]]
> ![[SRD-sceptile-mega-form-ShuffleToken.png|wsmall]]


*Forest Pokemon*
*With the power of the Mega Stone, it allows itself to grow more feral in order to gain draconian powers. Its movements are swifter than ever and when it attacks it seems like the jungle has come to life.*

**DexID**:: 0254M1
**Name**:: Sceptile (Mega Form)
**Type**:: Grass / Dragon
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 121.7lbs / 55.2kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| From      | [[SRD-Sceptile]] | Mega   | Sceptilite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sceptile (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
