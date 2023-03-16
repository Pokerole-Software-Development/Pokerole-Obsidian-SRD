---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-hydreigon-BookSprite.png
BoxSprite: SRD-hydreigon-BoxSprite.png
DexCategory: Brutal Pokemon
DexDescription: This brutal Pokemon flies in the sky. Anything that moves seems like
  a foe to it, triggering its aggression. The heads on its arms do not have brains.
  They use all three heads to consume and destroy everything.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Zweilous]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-hydreigon-HomeSprite.png
Image: hydreigon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Starter
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
Number: 635
ShuffleToken: SRD-hydreigon-ShuffleToken.png
Type1: Dark
Type2: Dragon
Weight:
  Kilograms: 160.0
  Pounds: 352.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hydreigon-BookSprite.png|wsmall]]
> ![[SRD-hydreigon-HomeSprite.png]]
> ![[SRD-hydreigon-BoxSprite.png|htiny]]
> ![[SRD-hydreigon-ShuffleToken.png|wsmall]]


*Brutal Pokemon*
*This brutal Pokemon flies in the sky. Anything that moves seems like a foe to it, triggering its aggression. The heads on its arms do not have brains. They use all three heads to consume and destroy everything.*

**DexID**:: 0635
**Name**:: Hydreigon
**Type**:: Dark / Dragon
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'9" / 1.8m
**Weight**: 352.7lbs / 160.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Zweilous]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hydreigon.md"
flatten moves as T
where file.path = this.file.path
```
