---
Title: Load
Description: This is our color page.
Template: analysis
---

# Load


Rapport: Utvärdering av Webbplatsers Laddningstid och Användbarhet (v2)
Webbplatser som analyserats
Jag har valt att analysera tre populära webbplatser: YouTube, Zalando och Amazon. Urvalet är baserat på deras omfattande användning och relevans för en global användarbas. Dessa webbplatser representerar olika typer av digitala plattformar: en videostreamingtjänst (YouTube), en e-handelsplattform (Zalando) och en gigantisk marknadsplats (Amazon). Jag valde dessa för att få en bredare förståelse för hur laddningstider och användbarhet kan variera mellan olika typer av webbplatser.


https://www.zalando.se/

https://m.youtube.com/

https://www.amazon.se/


Verktyg och metod
För att mäta laddningstider och analysera användbarheten på dessa webbplatser, använde jag följande verktyg:

Google PageSpeed Insights:

Jag mätte både mobil- och desktopversionerna av webbplatsernas sidor.
För varje webbplats valde jag tre representativa sidor att mäta.
Google Chrome DevTools:

Jag använde fliken "Network" för att mäta laddningstider, antal resurser och sidans totala storlek.
För varje sida utförde jag tre mätningar och tog medelvärdet för att få en rättvis bedömning.
Mätning och Data
För att samla mätvärden, utförde jag följande:

Google PageSpeed Insights:

Mätte varje sida på både mobil och desktop och dokumenterade de betyg som gavs.
DevTools Network:

Mätningar gjordes på tre olika sidor per webbplats.
Jag dokumenterade laddningstiden, antalet resurser som laddades och sidans totala storlek.
Data sammanställdes i ett Google Kalkylark för att hålla reda på mätvärdena och lätt kunna jämföra mellan webbplatserna.

Google Kalkylark med mätdata

Här är hur de olika webbplatserna presterade:

YouTube
Snapshot:

Desktop: YouTube homepage
Mobil: YouTube homepage
Mätningar:

Desktop: PageSpeed Insight = 88/100 (Desktop), 55/100 (Mobile).
Laddningstid: 2.7s (snitt), Antal resurser: 300, Totalt storlek: 6.8 MB.
Mätningar (3 gånger): 2.8s, 2.6s, 2.7s.
Förbättringsområden:

YouTube kan optimera videor för snabbare laddning, samt minska antalet externa skript och bilder på startsidan.
Zalando
Snapshot:

Desktop: Zalando homepage
Mobil: Zalando homepage
Mätningar:

Desktop: PageSpeed Insight = 72/100 (Desktop), 60/100 (Mobile).
Laddningstid: 1.2s (snitt), Antal resurser: 150, Totalt storlek: 3.2 MB.
Mätningar (3 gånger): 1.2s, 1.1s, 1.3s.
Förbättringsområden:

Zalando har ett stort antal externa resurser och bilder som kan optimeras för att minska laddningstiden. Det kan också vara fördelaktigt att använda lazy-loading för bilder.
Amazon
Snapshot:

Desktop: Amazon homepage
Mobil: Amazon homepage
Mätningar:

Desktop: PageSpeed Insight = 76/100 (Desktop), 50/100 (Mobile).
Laddningstid: 1.5s (snitt), Antal resurser: 200, Totalt storlek: 4.5 MB.
Mätningar (3 gånger): 1.5s, 1.6s, 1.4s.

https://docs.google.com/spreadsheets/d/1-tlxxHY9Xrg5XOhm5S_6yxuVo7A89OroCA9_70VE0W4/edit?usp=sharing


Förbättringsområden:

Amazon skulle kunna använda bättre cache-strategier och minska mängden skript på hemsidan för att förbättra hastigheten, särskilt på mobilversionen.
Sammanfattning av resultat
Efter att ha analyserat alla tre webbplatser har jag noterat några gemensamma mönster och möjliga förbättringsområden:

Optimering av bilder och media: En stor mängd av de laddningstider som observerades beror på tunga bilder och videor. Optimera dessa till lägre upplösning och använd moderna bildformat som WebP för att minska laddningstider.

Minskning av externa resurser: Alla tre webbplatser har många externa resurser, såsom skript och tredjeparts widgets. Dessa resurser kan blockera sidladdningen och fördröja användarupplevelsen.

Lazy-loading: För alla tre sidor skulle lazy-loading för bilder och videor vara ett effektivt sätt att minska sidans initiala laddningstid.

Cache-strategier: För Amazon och Zalando är det viktigt att implementera mer effektiva cache-strategier för att förbättra laddningstiden vid återbesök.

Rangordning av Webbplatser
Här är den sammanfattade rankingen baserat på de mätvärden jag samlade in:

YouTube: Bäst prestanda, särskilt på desktopversionen. Trots några optimeringsmöjligheter är laddningstiden snabb.
Amazon: Hyfsad laddningstid och prestanda, men kan förbättras, särskilt på mobilversionen.
Zalando: Har det längsta laddningstiden och största resursanvändningen, vilket gör den långsam jämfört med de andra.
Gräns för "Snabb" Webbplats
Jag definierar en webbplats som "snabb" om den laddar inom 3 sekunder på både mobil och desktop. Baserat på mina mätningar har YouTube den bästa laddningstiden och klarar denna gräns utan problem. Amazon och Zalando behöver förbättra sina laddningstider för att anses vara optimalt snabba.

Slutsats
De webbplatser som testats presterar generellt bra men har flera områden för förbättring, särskilt när det gäller optimering av media, minimering av externa skript och optimering av cachning. YouTube är den webbplats som presterar bäst, medan Zalando skulle behöva större förbättringar för att minska laddningstiden.

Gruppmedlemmar
Denna analys utfördes av:

Safa Moti
