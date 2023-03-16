---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-mudkip-BookSprite.png
BoxSprite: SRD-mudkip-BoxSprite.png
DexCategory: Mud Fish Pokemon
DexDescription: "The fin on its head is a radar to sense movement underwater. They\
  \ bury themselves under the mud at the water\u2019s edge and at the bottom of rivers.\
  \ They never back away even if their foe is bigger."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Marshtomp]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Damp
HomeSprite: SRD-mudkip-HomeSprite.png
Image: mudkip.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 258
ShuffleToken: SRD-mudkip-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 7.6
  Pounds: 16.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mudkip-BookSprite.png|wsmall]]
> ![[SRD-mudkip-HomeSprite.png]]
> ![[SRD-mudkip-BoxSprite.png|htiny]]
> ![[SRD-mudkip-ShuffleToken.png|wsmall]]


*Mud Fish Pokemon*
*The fin on its head is a radar to sense movement underwater. They bury themselves under the mud at the water’s edge and at the bottom of rivers. They never back away even if their foe is bigger.*

**DexID**:: 0258
**Name**:: Mudkip
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Damp|Damp]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 16.8lbs / 7.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Marshtomp]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mudkip.md"
flatten moves as T
where file.path = this.file.path
```
