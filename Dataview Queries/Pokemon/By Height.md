```dataview
TABLE
Height["Feet"]
from #PokeroleSRD/Pokedex 
WHERE contains(Type, "Flying")
SORT Height["Feet"] ASC
```
embed(link(HomeSprite)) AS Image