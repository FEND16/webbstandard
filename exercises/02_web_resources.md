# Web Resources

Varje gång vi besöker en hemsida gör vi det via ett visst standardiserat sätt att hämta de resurser som vår sida består av.

För att få reda på vad som händer när vi besöker en hemsida kan vi använda **Developer Tools** i den webbläsaren vi använder. I developer tools hittar vi en flik som heter **Network**. Denna flik berättar allt om vad som hämtas när vi besöker en specifik hemsida och hur det görs. 

Varje gång vi besöker en hemsida gör vi en request, en förfrågan, till en viss server och ber om att hämta `index.html`. I svaret får vi tillbaka dels `index.html` samt alla andra resurser som din sida behöver ha för att fungera rätt.

**Övningarna är inget som ska lämnas in utan är till för att ge en överblick över hur resurser hämtas via de standardiserade protokollen**

## Övning 1

Besök er egen hemsida som ni använder till HTML/CSS-projektet och öppna *Network Tab* i din webbläsare och ladda om sidan.

* Vilka resurser är det som hämtas?
* Vilka resurser hämtas först och fundera kring varför? De resurser som är högst upp hämtas först men vilka är det?
* Vilka resurser laddas in sist och varför?
* Hur lång tid tar sidan att ladda in? (DOMContentLoaded samt Load) Är det en rimlig inladdningstid relaterat till vad sidan innehåller?
* Hittar ni några resurser som tar lång tid att ladda in? Går det att minska den tiden?


**Använd nätverksfliken och besök två eller tre andra hemsidor med mer innehåll och se vad för innehåll det är som laddas in. Testa en köttig sida som t.ex. aftonbladet eller en statlig sida.**

## Övning 2

För att optimera hur och när innehållet laddas in kan vi inte styra helt över. Dels beror det på hur själva standarden för att skicka och ta emot data beter sig. Det beror också på saker som hur servern är konfigurerad. Om vi har vår sida på GitHub Pages har vi inte full kontroll men man kan ändå se över hur pass bra vår sida presterar.

För att se mer "objektivt" hur vår sida presterar kan man använda verktyg som:
* **[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)**

Här får man en överblick över dels hur, enligt Google, ens sida presterar både på mobil samt desktop. Tänk på att det är opinionated och tipsen från sidan kan tas med en nypa salt.

* Kör er sida i *PageSpeed Insights*
* Se över om någon av punkterna behöver åtgärdas eller om de faktiskt går att åtgärda. Vad kan vi påverka och vad kan vi inte påverka?
* Detta är Googles test över hur en sida fungerar, borde man ställa sig kritisk? Den här sidan är den mest använda, kan man säga att det är det standardiserade sättet att testa hemsidor? Kolla upp om det finns andra "speed test"-sidor där du kan mäta hur bra din sida presterar. Jämför sedan resultaten.


### Länkar

* [Chrome: Network panel](https://developers.google.com/web/tools/chrome-devtools/network-performance/resource-loading)
* [Firefox: Network Monitor](https://developer.mozilla.org/en-US/docs/Tools/Network_Monitor)
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
* [WebPageTest](https://www.webpagetest.org/)