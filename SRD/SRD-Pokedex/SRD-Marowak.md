---
Ability1: Rock Head
Ability2: Lightning Rod
BookSprite: SRD-marowak-BookSprite.png
BoxSprite: SRD-marowak-BoxSprite.png
DexCategory: Bone Keeper Pokemon
DexDescription: Its rough past has hardened its heart. Now tenacious and violent,
  this Pokemon will use its Bone club as a weapon against foes. Marowak's den is usually
  full of the bones it has collected.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cubone]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Battle Armor
HomeSprite: SRD-marowak-HomeSprite.png
Image: marowak.png
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
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Bonemerang|Bonemerang]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 105
ShuffleToken: SRD-marowak-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 45.0
  Pounds: 99.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-marowak-BookSprite.png|wsmall]]
> ![[SRD-marowak-HomeSprite.png]]
> ![[SRD-marowak-BoxSprite.png|htiny]]
> ![[SRD-marowak-ShuffleToken.png|wsmall]]


*Bone Keeper Pokemon*
*Its rough past has hardened its heart. Now tenacious and violent, this Pokemon will use its Bone club as a weapon against foes. Marowak's den is usually full of the bones it has collected.*

**DexID**:: 0105
**Name**:: Marowak
**Type**:: Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Battle Armor|Battle Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 99.2lbs / 45.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Cubone]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Marowak.md"
flatten moves as T
where file.path = this.file.path
```
