# GET med Postman

För att få en praktisk inblick i hur `GET`  fungerar ska vi simulera dessa förfrågningar genom att använda verktyget __[Postman](https://www.getpostman.com/)__ som har blivit standard för att testa hur man gör dessa förfrågningar (ibland kallade _anrop_ från engelskans _call_). 

![Postman](https://www.getpostman.com/img/v2/logo-big.svg?ed269600be149e730a7984faca045f78)

Med detta verktyg kan man göra anrop till många olika resurser och hämta information angående resursen. När vi gör en vanlig förfrågan till en hemsida så händer mer än att `html`, `css` samt bilder bara hämtas. Varje förfrågan måste även skickas med metadata för att berätta _hur_ data ska skickas. 

## HTTP Headers & Body

På liknande sätt som en `html` fil har en `<head>`-tagg som innehåller extra information om sidan som inte visas upp på sidan så har varje förfrågan `headers` som berättar vad det är för innehåll. På liknande sätt som `html` har en `<body>` som innehåller innehållet har även förfrågan en `body`. 

### Övning 1: Hämta hemsidor med Postman

* **Besök 5 olika sidor eller resurser på webben med Postman individuellt**

* Se över vilka `headers` som skickas med och använd sedan länkarna nedan för att ta reda på vad de olika `headers` betyder och vilken information som skickas med.

* **Jämför sedan informationen du hittat med en annan i klassen och plocka ut de gemensamma headers som ni hittat. Diskutera de headers som är gemensamma och vad de säger om resursen.**

### Övning 2: Samma källa, olika svar

Börja med att hämta följande två filer med hjälp av Postman, vilka skillnader är det i svaret från postman, vilka headers sätts?

https://fend16.github.io/dist/css/main.css

https://raw.githubusercontent.com/FEND16/fend16.github.io/master/dist/css/main.css

Använd den andra länken som ett stylesheet på en html-sida:
`<link rel="stylesheet" href="https://raw.githubusercontent.com/FEND16/fend16.github.io/master/dist/css/main.css"`

* Vilket svar får du i `console` och vad säger det om resursen och en resurs headers?

### Källor att använda

* [HTTP Headers | TutorialsPoint](https://www.tutorialspoint.com/http/http_header_fields.htm)
* [List of HTTP Headers | Wikipedia](https://en.wikipedia.org/wiki/List_of_HTTP_header_fields)
* [Possible MIME Types | Stack Overflow](http://stackoverflow.com/a/37416922)
* [Mime Types | IANA](http://www.iana.org/assignments/media-types/media-types.xhtml)
