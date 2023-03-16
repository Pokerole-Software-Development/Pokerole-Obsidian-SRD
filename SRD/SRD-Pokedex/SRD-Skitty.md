---
Ability1: Cute Charm
Ability2: Normalize
BookSprite: SRD-skitty-BookSprite.png
BoxSprite: SRD-skitty-BoxSprite.png
DexCategory: Kitten Pokemon
DexDescription: "They are fascinated by moving objects, even chasing their own tail\
  \ without hesitation. They are cute by nature, and popular pets, but it\u2019s hard\
  \ to earn their trust in the wild. They are quite affectionate."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Delcatty]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Wonder Skin
HomeSprite: SRD-skitty-HomeSprite.png
Image: skitty.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - Beginner
  - '[[SRD-Attract|Attract]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Assist|Assist]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Heal Bell|Heal Bell]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 300
ShuffleToken: SRD-skitty-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skitty-BookSprite.png|wsmall]]
> ![[SRD-skitty-HomeSprite.png]]
> ![[SRD-skitty-BoxSprite.png|htiny]]
> ![[SRD-skitty-ShuffleToken.png|wsmall]]


*Kitten Pokemon*
*They are fascinated by moving objects, even chasing their own tail without hesitation. They are cute by nature, and popular pets, but it’s hard to earn their trust in the wild. They are quite affectionate.*

**DexID**:: 0300
**Name**:: Skitty
**Type**:: Normal
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Normalize|Normalize]] ([[SRD-Wonder Skin|Wonder Skin]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| To        | [[SRD-Delcatty]] | Stone  | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Skitty.md"
flatten moves as T
where file.path = this.file.path
```
