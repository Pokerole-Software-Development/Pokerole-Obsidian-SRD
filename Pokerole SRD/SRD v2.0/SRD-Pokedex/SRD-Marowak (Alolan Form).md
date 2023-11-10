---
Ability1: Cursed Body
Ability2: Lightning Rod
BookSprite: SRD-marowak-alolan-form-BookSprite.png
BoxSprite: SRD-marowak-alolan-form-BoxSprite.png
DexCategory: Bone Keeper Pokemon
DexDescription: "Alola has many predators for an orphaned Cubone, so its mother\u2019\
  s spirit lingered close to protect her baby. This otherworldly influence made Marowak\
  \ fiercer and changed its type completely."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cubone]]'
  Region: Alola
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Rock Head
HomeSprite: SRD-marowak-alolan-form-HomeSprite.png
Image: marowak-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bone Club|Bone Club]]'
- - Beginner
  - '[[SRD-Hex|Hex]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Bonemerang|Bonemerang]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Bone|Shadow Bone]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - Ace
  - '[[SRD-Bone Rush|Bone Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Pro
  - '[[SRD-Flame Charge|Flame Charge]]'
Number: 105
ShuffleToken: SRD-marowak-alolan-form-ShuffleToken.png
Type1: Fire
Type2: Ghost
Weight:
  Kilograms: 34.0
  Pounds: 75.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-marowak-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-marowak-alolan-form-HomeSprite.png]]
> ![[SRD-marowak-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-marowak-alolan-form-ShuffleToken.png|wsmall]]


*Bone Keeper Pokemon*
*Alola has many predators for an orphaned Cubone, so its mother’s spirit lingered close to protect her baby. This otherworldly influence made Marowak fiercer and changed its type completely.*

**DexID**:: 0105A
**Name**:: Marowak (Alolan Form)
**Type**:: Fire / Ghost
**Abilities**:: [[SRD-Cursed Body|Cursed Body]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Rock Head|Rock Head]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 75.0lbs / 34.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   | Region   |
|:----------|:---------------|:-------|:--------|:---------|
| From      | [[SRD-Cubone]] | Level  | Slow    | Alola    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Marowak (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
