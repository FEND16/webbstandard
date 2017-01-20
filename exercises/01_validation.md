# Övning - JSON / XML / HTML5

I ditt framtida yrke som javascriptproffs kommer du att få jobba mycket med olika sorters data i olika sorters format. Eftersom en dator tolkar allting på det sättet vi har sagt till den att den ska tolka på blir det viktigt att vi är tydliga i hur vi ger instruktioner till datorn.

Det blir viktigt att vår data är **välformatterad**. Ett objekt måste börja och sluta med `{}` annars vet inte JavaScript var objektet slutar och börjar. Varje egenskap/värde-par måste även vara separerade med `,` så JavaScript vet när en ny egenskap kommer. Det mest vanliga dataformatet inom JavaScript fungerar i princip som ett JavaScript-objekt.

### JSON

JSON står för `JavaScript Object Notation` och som namnet antyder är det utformat för att kunna lätt kunna manipuleras av JavaScript. Ett `JSON`-objekt är i princip ett objekt som följer en striktare standard:

```json
{
    "property": "value",
    "property_2": "value",
    "property3": {
        "nested_property": "nested_value",
        "nested_property2": "nested_value2"
    }
}
```

Som vi ser är det ett JavaScript-objekt med den skillnaden att varje egenskap och varje värde måste vara en sträng. 

### Övning

Denna övning handlar om att skapa olika dokument utifrån olika webbstandarder samtidigt som vi jobbar med validering av koden.

#### 1. Validera `JSON`

Här nedan har du en riktigt rörig `JSON` som du ska strukturera upp med hjälp av validatorn nedanför.

```json
{
    "dateCreated": new Date(),
    "username": "webstandard_boy_91",
    "password": "s3cur3",
    age: 55,
    "gender": "male"
    "admin": true,
    "name": {
        "firstName": "Job",
        "lastName": "JavaScript"
    }
    "sayIt": "function(){return this.name}"
}

```


* [JSON Validator](http://jsonlint.com/)
* [JSON/XML Examples](http://json.org/example.html)

1. Vilka regler måste en `JSON`-fil följa?
2. Vilka värden kan vi lagra i en `JSON`-fil?
3. I vilka scenarion använder vi oss av dessa filer?


#### 2. Skapa en valid XML-fil

Bra att du nu har en valid `JSON`-fil. Nu ska vi konvertera vår `JSON` till `XML`! `XML` används inte i lika stor utsträckning inom JavaScript-världen men chansen att du stöter på `XML` är stor då det är ett av de mest använda sättet för att formattera data. Du har redan stött på något som liknar XML då `HTML` har sitt arv i `XML`

```xml
<xmlexample>
    <property>Value</property>
    <property2>Value2</property2>
    <property3>
        <nested_property>nested_value</nested_property>
        <nested_property2>nested_value</nested_property2>
    </property3>
</xmlexample>

```


1. Du ska nu skapa en XML-fil utifrån din tidigare valida JSON. Använd sedan XML-validator för att se om det funkar som det ska.
2. `json` är ju som gjort för JavaScript, varför vill vi ens använda något annat?" Ja, varför måste vi lära oss om XML? När kan vi stöta på XML?



