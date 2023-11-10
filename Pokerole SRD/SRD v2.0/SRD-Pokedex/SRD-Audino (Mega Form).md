---
Ability1: Inner Focus
Ability2: ''
BookSprite: SRD-audino-mega-form-BookSprite.png
BoxSprite: SRD-audino-mega-form-BoxSprite.png
DexCategory: Hearing Pokemon
DexDescription: The power of the Mega Stone increases the purity of this Pokemon,
  revealing its Fairy type. It is so caring and protective of its trainer that it
  can hear its cries for help from miles away. It loves to soothe and care for others.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Audinite
  Kind: Mega
  Pokemon: '[[SRD-Audino]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-audino-mega-form-HomeSprite.png
Image: audino-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Beginner
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Secret Power|Secret Power]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Entrainment|Entrainment]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
Number: 531
ShuffleToken: SRD-audino-mega-form-ShuffleToken.png
Type1: Normal
Type2: Fairy
Weight:
  Kilograms: 32.0
  Pounds: 70.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-audino-mega-form-BookSprite.png|wsmall]]
> ![[SRD-audino-mega-form-HomeSprite.png]]
> ![[SRD-audino-mega-form-BoxSprite.png|htiny]]
> ![[SRD-audino-mega-form-ShuffleToken.png|wsmall]]


*Hearing Pokemon*
*The power of the Mega Stone increases the purity of this Pokemon, revealing its Fairy type. It is so caring and protective of its trainer that it can hear its cries for help from miles away. It loves to soothe and care for others.*

**DexID**:: 0531M1
**Name**:: Audino (Mega Form)
**Type**:: Normal / Fairy
**Abilities**:: [[SRD-Inner Focus|Inner Focus]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 4'9" / 1.5m
**Weight**: 70.5lbs / 32.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Item     |
|:----------|:---------------|:-------|:---------|
| From      | [[SRD-Audino]] | Mega   | Audinite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Audino (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
