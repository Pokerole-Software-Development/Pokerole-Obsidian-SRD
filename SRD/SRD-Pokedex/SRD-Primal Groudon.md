---
Ability1: Desolate Land
Ability2: ''
BaseHP: 7
BoxSprite: SRD-BoxSprite-groudon-primal.png
DexID: 0383M1
Dexterity: 5
EventAbilities: ''
GenderType: N
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-groudon-primal.png
Insight: 5
Legendary: 'Yes'
MaxDexterity: 5
MaxInsight: 5
MaxSpecial: 8
MaxStrength: 9
MaxVitality: 8
Name: Primal Groudon
Number: 383
RecommendedRank: Master
Special: 8
Sprite: groudon-primal.png
Strength: 9
Type1: Ground
Type2: Fire
Unevolved: 'No'
Vitality: 8
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-groudon-primal.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-groudon-primal.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | `= this.Strength`/`= this.MaxStrength`   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | `= this.Dexterity`/`= this.MaxDexterity` |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | `= this.Vitality`/`= this.MaxVitality`   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | `= this.Special`/`= this.MaxSpecial`     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | `= this.Insight`/`= this.MaxInsight`     |

**Recommended Rank:** `= this.RecommendedRank`
**Good Starting Pokemon?** `= this.GoodStarter`
**Can Evolve?** `= this.Unevolved`

![[SRD-Primal Groudon-Learnset]]