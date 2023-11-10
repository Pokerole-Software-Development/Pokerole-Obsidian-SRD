---
Ability1: Pickup
Ability2: Gluttony
BookSprite: SRD-zigzagoon-galarian-form-BookSprite.png
BoxSprite: SRD-zigzagoon-galarian-form-BoxSprite.png
DexCategory: Tiny Racoon Pokemon
DexDescription: Zigzagoons raised in Galar grow to be punks. If they see another Pokemon,
  they will purposely run into them to start a fight. The only way to calm them down
  is with a lot of loud noise.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Linoone (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Quick Feet
HomeSprite: SRD-zigzagoon-galarian-form-HomeSprite.png
Image: zigzagoon-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
Number: 263
ShuffleToken: SRD-zigzagoon-galarian-form-ShuffleToken.png
Type1: Dark
Type2: Normal
Weight:
  Kilograms: 17.5
  Pounds: 38.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zigzagoon-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-zigzagoon-galarian-form-HomeSprite.png]]
> ![[SRD-zigzagoon-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-zigzagoon-galarian-form-ShuffleToken.png|wsmall]]


*Tiny Racoon Pokemon*
*Zigzagoons raised in Galar grow to be punks. If they see another Pokemon, they will purposely run into them to start a fight. The only way to calm them down is with a lot of loud noise.*

**DexID**:: 0263G
**Name**:: Zigzagoon (Galarian Form)
**Type**:: Dark / Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 38.6lbs / 17.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   | Speed   |
|:----------|:--------------------------------|:-------|:--------|
| To        | [[SRD-Linoone (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zigzagoon (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
