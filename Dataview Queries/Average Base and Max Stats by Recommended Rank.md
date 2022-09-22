```dataview
Table without id 
recommended-rank
,round(sum(rows.Strength)/length(rows.Strength),2) as Strength
,round(sum(rows.Dexterity)/length(rows.Dexterity),2) as Dexterity
,round(sum(rows.Vitality)/length(rows.Vitality),2) as Vitality 
,round(sum(rows.Special)/length(rows.Special),2) as Special
,round(sum(rows.Insight)/length(rows.Insight),2) as Insight
From #PokeroleSRD/Pokedex 
Group by recommended-rank sort round(sum(rows.Dexterity)/length(rows.Dexterity),2) Asc
```

```dataview
Table without id 
recommended-rank
,round(sum(rows.MaxStrength)/length(rows.MaxStrength),2) as MaxStrength
,round(sum(rows.MaxDexterity)/length(rows.MaxDexterity),2) as MaxDexterity
,round(sum(rows.MaxVitality)/length(rows.MaxVitality),2) as MaxVitality 
,round(sum(rows.MaxSpecial)/length(rows.MaxSpecial),2) as MaxSpecial
,round(sum(rows.MaxInsight)/length(rows.MaxInsight),2) as MaxInsight
From #PokeroleSRD/Pokedex 
Group by recommended-rank sort round(sum(rows.MaxDexterity)/length(rows.MaxDexterity),2) Asc
```