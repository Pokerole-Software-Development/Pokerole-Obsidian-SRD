```dataview
TABLE 
MegaBaseForm.Strength+
MegaBaseForm.Dexterity+
MegaBaseForm.Vitality+
MegaBaseForm.Special+
MegaBaseForm.Insight AS Bases,
Strength+Dexterity+Vitality+Special+Insight AS Mega_Bases,
MegaBaseForm.MaxStrength+
MegaBaseForm.MaxDexterity+
MegaBaseForm.MaxVitality+
MegaBaseForm.MaxSpecial+
MegaBaseForm.MaxVitality AS Mega_Maxes,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS Mega_Maxes
from #PokeroleSRD/Pokedex 
where MegaBaseForm
```