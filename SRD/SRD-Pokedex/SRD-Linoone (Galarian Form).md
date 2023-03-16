---
Ability1: Pickup
Ability2: Gluttony
BookSprite: SRD-linoone-galarian-form-BookSprite.png
BoxSprite: SRD-linoone-galarian-form-BoxSprite.png
DexCategory: Rush Pokemon
DexDescription: It uses its long tongue to taunt its opponents. Once the foe is enraged,
  this Pokemon hurls itself at it, tackling them forcefully. They are bad-mannered
  and enjoy to thrash things about.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Zigzagoon (Galarian Form)]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Obstagoon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Quick Feet
HomeSprite: SRD-linoone-galarian-form-HomeSprite.png
Image: linoone-galarian-form.png
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
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Payback|Payback]]'
- - Pro
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Pro
  - '[[SRD-Shadow Claw|Shadow Claw]]'
Number: 264
ShuffleToken: SRD-linoone-galarian-form-ShuffleToken.png
Type1: Dark
Type2: Normal
Weight:
  Kilograms: 32.5
  Pounds: 71.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-linoone-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-linoone-galarian-form-HomeSprite.png]]
> ![[SRD-linoone-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-linoone-galarian-form-ShuffleToken.png|wsmall]]


*Rush Pokemon*
*It uses its long tongue to taunt its opponents. Once the foe is enraged, this Pokemon hurls itself at it, tackling them forcefully. They are bad-mannered and enjoy to thrash things about.*

**DexID**:: 0264G
**Name**:: Linoone (Galarian Form)
**Type**:: Dark / Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 71.7lbs / 32.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                           | Kind   | Speed   |
|:----------|:----------------------------------|:-------|:--------|
| From      | [[SRD-Zigzagoon (Galarian Form)]] | Level  | Medium  |
| To        | [[SRD-Obstagoon]]                 | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Linoone (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
