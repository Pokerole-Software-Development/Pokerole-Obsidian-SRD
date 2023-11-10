---
Ability1: Static
Ability2: ''
BookSprite: SRD-pichu-BookSprite.png
BoxSprite: SRD-pichu-BoxSprite.png
DexCategory: Tiny Mouse Pokemon
DexDescription: Its cheek pouches are not fully developed yet. Pichu gets startled
  if its cheeks release electricity jolts. It needs a friendly environment to grow
  happy. It can be quite the rascal, though.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Pikachu]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Lightning Rod
HomeSprite: SRD-pichu-HomeSprite.png
Image: pichu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
Number: 172
ShuffleToken: SRD-pichu-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pichu-BookSprite.png|wsmall]]
> ![[SRD-pichu-HomeSprite.png]]
> ![[SRD-pichu-BoxSprite.png|htiny]]
> ![[SRD-pichu-ShuffleToken.png|wsmall]]


*Tiny Mouse Pokemon*
*Its cheek pouches are not fully developed yet. Pichu gets startled if its cheeks release electricity jolts. It needs a friendly environment to grow happy. It can be quite the rascal, though.*

**DexID**:: 0172
**Name**:: Pichu
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Pikachu]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pichu.md"
flatten moves as T
where file.path = this.file.path
```
