---
Ability1: Inner Focus
Ability2: ''
BookSprite: SRD-gallade-mega-form-BookSprite.png
BoxSprite: SRD-gallade-mega-form-BoxSprite.png
DexCategory: Blade Pokemon
DexDescription: With the power of the Mega Stone it senses the emotions of others
  in a large radius and will go help anyone in need. It will only attack if it needs
  to defend someone or something. It is protective and brave.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Galladite
  Kind: Mega
  Pokemon: '[[SRD-Gallade]]'
GenderType: M
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-gallade-mega-form-HomeSprite.png
Image: gallade-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - Beginner
  - '[[SRD-Quick Guard|Quick Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 475
ShuffleToken: SRD-gallade-mega-form-ShuffleToken.png
Type1: Psychic
Type2: Fighting
Weight:
  Kilograms: 56.4
  Pounds: 124.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gallade-mega-form-BookSprite.png|wsmall]]
> ![[SRD-gallade-mega-form-HomeSprite.png]]
> ![[SRD-gallade-mega-form-BoxSprite.png|htiny]]
> ![[SRD-gallade-mega-form-ShuffleToken.png|wsmall]]


*Blade Pokemon*
*With the power of the Mega Stone it senses the emotions of others in a large radius and will go help anyone in need. It will only attack if it needs to defend someone or something. It is protective and brave.*

**DexID**:: 0475M1
**Name**:: Gallade (Mega Form)
**Type**:: Psychic / Fighting
**Abilities**:: [[SRD-Inner Focus|Inner Focus]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 124.3lbs / 56.4kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Gallade]] | Mega   | Galladite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gallade (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
