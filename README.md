# California Housing

**Introduktion**
Du arbetar som dataanalytiker på ett konsultbolag som hjälper kommuner och fastighetsaktörer att fatta datadrivna beslut. Ni har fått tillgång till ett dataset som beskriver områden i Kalifornien (geografi, hushåll, inkomst m.m.).
Ledningen vill använda ML som beslutsstöd. Det betyder att de inte bara vill ha “en modell”, utan ett underlag som:
- går att köra om (reproducerbart),
- visar hur du utvärderat på ett rimligt sätt,
- och förklarar varför du valt vissa metoder.
Du ska därför leverera:
- en körbar ML-lösning (kod)
- och en kort, tydlig rapport (beslutsunderlag)

**Kolumner (förklaring):**
* longitude: longitud (geografisk position öst/väst)
* latitude: latitud (geografisk position nord/syd)
* housing_median_age: medianålder på bostäder i området
* total_rooms: totalt antal rum i området (summerat över hushåll)
* total_bedrooms: totalt antal sovrum i området (summerat över hushåll)
* population: total befolkning i området
* households: antal hushåll i området
* median_income: medianinkomst i området (skalat mått i datasetet)
* ocean_proximity: kategorisk variabel som beskriver närhet till hav (t.ex. INLAND/NEAR OCEAN)
* median_house_value: medianvärde på bostäder i området (detta är target i spår A)

**Bakgrundshistoria**
En kund vill kunna göra grova värderingar av bostadsområden för att kunna planera investeringar och resurser. De vill kunna uppskatta bostadsvärdet baserat på områdets egenskaper.

**Uppdrag**
Bygg en modell som förutsäger median_house_value.

**Syfte**
Att kunna göra en rimlig värdeprognos och samtidigt förstå vilka faktorer som verkar hänga ihop med högre/lägre värde.

## Reproducerbarhet
1. Kört Restart & Run All 
2. Sätte en slump-seed i början
3. Lagt till en requirements.txt genom att köra: "python -m pip freeze > requirements.txt" i terminalen
**Python version**
`Python 3.13.7`
4. Lagt in  .venv i .gitignore så att den inte råkar pushas upp på github