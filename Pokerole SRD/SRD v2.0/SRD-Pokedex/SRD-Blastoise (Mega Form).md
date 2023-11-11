---
Ability1: Mega Launcher
Ability2: ''
BookSprite: SRD-blastoise-mega-form-BookSprite.png
BoxSprite: SRD-blastoise-mega-form-BoxSprite.png
DexCategory: Shellfish Pokemon
DexDescription: With the power of the Mega Stone the canon on its back can shoot exploding
  water projectiles that can pierce through concrete. Its body is incredibly hard
  and its hind legs root themselves to prevent recoil.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Blastoisinite
  Kind: Mega
  Pokemon: '[[SRD-Blastoise]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-blastoise-mega-form-HomeSprite.png
Image: blastoise-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble|Bubble]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Skull Bash|Skull Bash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zap Cannon|Zap Cannon]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Cannon|Hydro Cannon]]'
Number: 9
ShuffleToken: SRD-blastoise-mega-form-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 101.1
  Pounds: 222.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blastoise-mega-form-BookSprite.png|wsmall]]
> ![[SRD-blastoise-mega-form-HomeSprite.png]]
> ![[SRD-blastoise-mega-form-BoxSprite.png|htiny]]
> ![[SRD-blastoise-mega-form-ShuffleToken.png|wsmall]]


*Shellfish Pokemon*
*With the power of the Mega Stone the canon on its back can shoot exploding water projectiles that can pierce through concrete. Its body is incredibly hard and its hind legs root themselves to prevent recoil.*

**DexID**:: 0009M1
**Name**:: Blastoise (Mega Form)
**Type**:: Water
**Abilities**:: [[SRD-Mega Launcher|Mega Launcher]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 222.9lbs / 101.1kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   | Item          |
|:----------|:------------------|:-------|:--------------|
| From      | [[SRD-Blastoise]] | Mega   | Blastoisinite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Blastoise (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
