---
Ability1: Guts
Ability2: Sheer Force
BaseHP: 4
BoxSprite: SRD-BoxSprite-gurdurr.png
DexID: '0533'
Dexterity: 1
EventAbilities: ''
GenderType: ''
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: Iron Fist
HomeSprite: SRD-HomeSprite-gurdurr.png
Insight: 2
Legendary: 'No'
MaxDexterity: 3
MaxInsight: 4
MaxSpecial: 3
MaxStrength: 6
MaxVitality: 5
Name: Gurdurr
Number: 533
RecommendedRank: Amateur
Special: 1
Sprite: gurdurr.png
Strength: 3
Type1: Fighting
Type2: ''
Unevolved: 'Yes'
Vitality: 2
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-gurdurr.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-gurdurr.png|right]]

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

![[SRD-Gurdurr-Learnset]]