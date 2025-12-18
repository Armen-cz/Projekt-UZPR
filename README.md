# Projekt-UZPR

Repositář pro semestrální projekt z UZPR 2025 pro skupinu E: **Analýza areálu výskytu vlků v ČR**



**Členové skupiny:**

* Adam Králič
* Barbora Matějková



**Použitá data:**

* ArcČR500 (obce, okresy, polygon ČR, digitální model reliéfu)
* ZABAGED (turistické trasy, velkoplošná chráněná území)
* https://aopkcr.maps.arcgis.com/home/item.html?id=4eecf840fc854327a53b75afb3462ae3 (výskyt vlků, škody způsobené vlkem, úhyn vlků)
* Corine Land Cover



**Spuštění:**

Pro tuto práci je jako výpočetní skript použit jupyter notebook, který slouží jak pro výpočet, tak pro prezentaci výsledků. Veškeré podklady jsou uloženy ve společné složce. Analýza obsahuje zobrazení výskytu vlků a způsobených škod na různých vrstvách z ArcČR500 a ZABAGED.



**Analýzy:**

* porovnání areálu výskytu – s údaji o obyvatelstvu (kolik lidí se nachází v jejich blízkosti), využití krajiny (v jaké krajině jsou nejčastější), jak moc koreluje jejich výskyt s chráněnými oblastmi nebo jaká je průměrná výška jejich výskytu
* zobrazení dat bodových vrstev – typy poškozené zvěře, trendy v letech
* statistické analýzy
* průnik bodových a polygonových vrstev – bodové údaje vůči sídelním jednotkám



Potřebné Python moduly viz **requirements.txt**

