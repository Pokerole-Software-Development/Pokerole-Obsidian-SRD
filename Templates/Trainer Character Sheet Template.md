---
StrengthPoints: 0
DexterityPoints: 0
VitalityPoints: 0
SpecialPoints: 0
InsightPoints: 0
Tough: 0
Cool: 0
Beauty: 0
Cute: 0
Clever: 0
---

# Trainer Name

**Age**:
**Concept**: 
**HP**: `= 4 + this.VitalityPoints`
**Will**:: `= 1 + this.InsightPoints + 2`
**Initiative**:: `= 1+this.DexterityPoints+this.Alert`
**Rank**:: 
**Nature**::
**Gender**: 


|           |                                                                                                                                                                            |                                                                               |        |                                                     |                     |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------ | --------------------------------------------------- | ------------------- |
| Strength  | `= padleft("",1,"⬤")+padleft("",this.StrengthPoints,"⦿")+padright("",5 - (1+this.StrengthPoints),"⭘")`      | `= 1+this.StrengthPoints`/`= 5`    | Tough  | `= padright(padright("⬤",this.Tough+1,"⦿"),5,"⭘")`  | `= this.Tough+1`/5  |
| Dexterity | `= padleft("",1,"⬤")+padleft("",this.DexterityPoints,"⦿")+padright("",5 - (1+this.DexterityPoints),"⭘")` | `= 1+this.DexterityPoints`/`= 5` | Cool   | `=padright(padright("⬤",this.Cool+1,"⦿"),5,"⭘")`    | `= this.Cool+1`/5   |
| Vitality  | `= padleft("",1,"⬤")+padleft("",this.VitalityPoints,"⦿")+padright("",5 - (1+this.VitalityPoints),"⭘")`      | `= 1+this.VitalityPoints`/`= 5`    | Beauty | `= padright(padright("⬤",this.Beauty+1,"⦿"),5,"⭘")` | `= this.Beauty+1`/5 |
| Special   | `= padleft("",0,"⬤")+padleft("",this.SpecialPoints,"⦿")+padright("",5 - (this.SpecialPoints),"⭘")`           | `= this.SpecialPoints`/`= 5`       | Cute   | `=padright( padright("⬤",this.Cute+1,"⦿"),5,"⭘")`   | `= this.Cute+1`/5   |
| Insight   | `= padleft("",1,"⬤")+padleft("",this.InsightPoints,"⦿")+padright("",5 - (1+this.InsightPoints),"⭘")`           | `= 1+this.InsightPoints`/`= 5`       | Clever | `= padright(padright("⬤",this.Clever+1,"⦿"),5,"⭘")` | `= this.Clever+1`/5 |


| Fight         | Survival       | Social           | Knowledge      |
| ------------- | -------------- | ---------------- | -------------- |
| [Brawl:: 0]   | [Alert:: 0]    | [Empathy:: 0]    | [Crafts:: 0]   |
| [Evasion:: 0] | [Athletic:: 0] | [Etiquette:: 0]  | [Lore:: 0]     |
| [Throw:: 0]   | [Nature:: 0]   | [Intimidate:: 0] | [Medicine:: 0] |
| [Weapons:: 0] | [Stealth:: 0]  | [Perform:: 0]    | [Science:: 0]  |

## Party 

- 

---