---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-talonflame-BookSprite.png
BoxSprite: SRD-talonflame-BoxSprite.png
DexCategory: Scorching Pokemon
DexDescription: They soar over desert canyons. If they spot prey they launch down
  at full speed to deliver a finishing blow. They are excellent hunters, with every
  wing flap they take, it leaves a trail of fire dust behind.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Fletchinder]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Gale Wings
HomeSprite: SRD-talonflame-HomeSprite.png
Image: talonflame.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Ember|Ember]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 663
ShuffleToken: SRD-talonflame-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 24.5
  Pounds: 54.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-talonflame-BookSprite.png|wsmall]]
> ![[SRD-talonflame-HomeSprite.png]]
> ![[SRD-talonflame-BoxSprite.png|htiny]]
> ![[SRD-talonflame-ShuffleToken.png|wsmall]]


*Scorching Pokemon*
*They soar over desert canyons. If they spot prey they launch down at full speed to deliver a finishing blow. They are excellent hunters, with every wing flap they take, it leaves a trail of fire dust behind.*

**DexID**:: 0663
**Name**:: Talonflame
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Gale Wings|Gale Wings]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 54.0lbs / 24.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| From      | [[SRD-Fletchinder]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Talonflame.md"
flatten moves as T
where file.path = this.file.path
```
