---
Ability1: Fluffy
Ability2: Klutz
BookSprite: SRD-stufful-BookSprite.png
BoxSprite: SRD-stufful-BoxSprite.png
DexCategory: Flailing Pokemon
DexDescription: Despite its adorable appearance it is a dangerous Pokemon. If anyone
  but its mother or Trainer touches it, it will respond by angrily flailing its arms
  around. They are popular pets but owners always regret.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Bewear]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Cute Charm
HomeSprite: SRD-stufful-HomeSprite.png
Image: stufful.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 759
ShuffleToken: SRD-stufful-ShuffleToken.png
Type1: Normal
Type2: Fighting
Weight:
  Kilograms: 6.8
  Pounds: 15.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stufful-BookSprite.png|wsmall]]
> ![[SRD-stufful-HomeSprite.png]]
> ![[SRD-stufful-BoxSprite.png|htiny]]
> ![[SRD-stufful-ShuffleToken.png|wsmall]]


*Flailing Pokemon*
*Despite its adorable appearance it is a dangerous Pokemon. If anyone but its mother or Trainer touches it, it will respond by angrily flailing its arms around. They are popular pets but owners always regret.*

**DexID**:: 0759
**Name**:: Stufful
**Type**:: Normal / Fighting
**Abilities**:: [[SRD-Fluffy|Fluffy]] / [[SRD-Klutz|Klutz]] ([[SRD-Cute Charm|Cute Charm]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 15.0lbs / 6.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Bewear]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stufful.md"
flatten moves as T
where file.path = this.file.path
```
