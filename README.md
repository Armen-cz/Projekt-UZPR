# Projekt-UZPR
Repositář pro semestrální projekt z UZPR 2025 pro skupinu E: Analýza areálu výskytu vlků v ČR

Členové skupiny:
* Adam Králič
* Barbora Matějková
  
Použitá data:
* ArcČR500 (obce, okresy, polygon ČR, digitální model reliéfu)
* ZABAGED (turistické trasy, velkoplošná chráněná území)
* https://aopkcr.maps.arcgis.com/home/item.html?id=4eecf840fc854327a53b75afb3462ae3 (výskyt vlků, škody způsobené vlkem, úhyn vlků)

Spuštění: 

Pro tuto práci je jako výpočetní skript použit jupyter notebook, který slouží jak pro výpočet, tak pro prezentaci výsledků. Veškeré podklady jsou uloženy ve společné složce. Analýza obsahuje zobrazení výskytu vlků a způsobených škod na různých vrstvách z ArcČR500 a ZABAGED. Momentálně obsahuje spoustu nefunkčních buněk, které jsou okomentářováním deaktivovány.

Potřebné Python moduly:
* geopandas==1.0.1
* matplotlib==3.9.2
* numpy==2.3.5
* rasterio==1.4.3
* rasterstats==0.20.0
* shapely==2.0.6




