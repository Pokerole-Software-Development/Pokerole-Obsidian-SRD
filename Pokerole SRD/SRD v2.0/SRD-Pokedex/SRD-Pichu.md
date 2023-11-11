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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disarming Voice|Disarming Voice]]'
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
