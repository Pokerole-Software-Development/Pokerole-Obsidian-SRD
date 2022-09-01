---
Ability1: Primordial Sea
Ability2: ''
BaseHP: 10
BoxSprite: SRD-BoxSprite-kyogre-primal.png
DexID: 0382M1
Dexterity: 5
EventAbilities: ''
GenderType: N
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-kyogre-primal.png
Insight: 8
Legendary: 'Yes'
MaxDexterity: 5
MaxInsight: 8
MaxSpecial: 9
MaxStrength: 8
MaxVitality: 5
Name: Primal Kyogre
Number: 382
RecommendedRank: Master
Special: 9
Sprite: kyogre-primal.png
Strength: 8
Type1: Water
Type2: ''
Unevolved: 'No'
Vitality: 5
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-kyogre-primal.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-kyogre-primal.png|right]]

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

![[SRD-Primal Kyogre-Learnset]]