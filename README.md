# Auktoritetsdata

# Länkar
* [KulturNav Ulf Bodin Gemensam samnordisk auktoritets-hantering för kultursektorn](http://media.digikult.se/2014/04/Digikult-2014-KulturNav-Bodin.pdf)
* [Funktionella krav på auktoritetsdata  En konceptuell modell 2008](https://www.ifla.org/files/assets/cataloguing/frad/frad_2009-sv.pdf)
```
Auktoritetsposten brukar också innehålla information om
vilket regelverk som använts för att skapa den kontrollerade sökingången, vilka källor som
konsulterats, vilken katalogiseringsinstans som fastställt den kontrollerade sökingången etc
```
* [Digisam DISKA, resultat av inventering på 24 myndigheter, överblick](http://www.digisam.se/lista-oever-register-fran-diska-projektet/) 2013-08-19
   * [Om inventeringen](http://www.digisam.se/diska-projektet-efter-inventeringen/)
   * Delrapport till VINNOVA 2013-05-30 [(pdf-fil)](http://www.digisam.se/wp-content/uploads/2013/07/Vinnova%20delrapport%20hela%20med%20bilagor%20inlmnad%202013-05-30.pdf)
   * [Prezi](https://prezi.com/qdze6qvqmscr/diska-ett-projekt-pa-digisam-i-samarbete-med-kth/)
* DISKA-seminarium 2014-02-11
   * Digitala semantiska kulturarvsauktoriteter [presenation](https://docs.google.com/presentation/d/1a-f3wBh1lHIbogW8VzkpbIVsE-swVur8ZlMmdkFCgL4)
   * Johanna Berg, Digisam: http://www.slideshare.net/Digisam/johanna-berg-kth-20140211
   * Helena Lundin, Digisam: http://www.slideshare.net/Digisam/diskaprojektet-31432298
   * Matthias Palmér, MetaSolutions: http://www.slideshare.net/MetaSolutionsAB/introduktion-till-lodify
   * Ulf Bodin, Kultur-IT: http://www.digisam.se/images/docs/Bodin_KulturNav_DISKA_20140211_dist.pdf 
   * André Costa, Wikimedia Sverige: http://www.digisam.se/images/docs/Costa_DISKA presentation-2014-02-11.pdf
* Rolf Källman Länsmuseernas samarbetsråd [Ett samordnat digitalt kulturarv](https://www.slideshare.net/Digisam/rolf-kllman-lnsmuseernas-samarbetsrd-24-0kt-2012)

* Phabricator [Task 227554](https://phabricator.wikimedia.org/T227554) "P777 Swedish civil parish code/ATA code need care"

## K-samsök
* [Underlag för utvecklingsplan för K-samsök](http://www.ksamsok.se/wp-content/uploads/2014/09/Rapport-K-sams%C3%B6k-v2.pdf) 15 september, 2014 

```
K-samsöks roll idag, utöver att vara en aggregator, är något vagt definierad.
```
....
```
Det finns ingen triple store, vilket innebär att man får bygga nya tabeller varje gång en ny relation läggs 
till. Vidare lagras alla länkar mellan objekt i K-samsök separat, så att objekten inte känner till dem,
eftersom K-samsök inte äger objekten.
```
....
```
Flera intervjupersoner tar upp problem med datakvalitet och ägandeskap. Dataleveransen
upplevs som spretig, delvis på grund av att det inte finns någon överenskommelse kring
master data (som är ett sätt att se auktoritetslistor) och för att mycket data inte är strukturerad,
vilket gör att man måste matcha i fritext. Detta kopplas till frågan om ägandeskap, och att en
konsekvens av skördningen är att data frikopplas från förvaltaren. Den varierande
datakvaliteten beror också på underliggande datainsamling och museisystem. 
```
....
```
Roll 2: Auktoritetslistor – samordnare och/eller ägare

För att länkade data ska funka fullt ut måste man i någon utsträckning använda samma
auktoritetslistor (gemensamma resurser för exempelvis plats och tid – ett slags master data) –
eller specificera hur olika auktoriteter förhåller sig till varandra. För att auktoritetslistor ska
komma till användning måste de upplevas som relevanta och långsiktiga, för vilket det krävs
samordning och ägarskap. Oavsett ägarskap handlar det inte om att skapa en enda stor
kulturhistorisk ontologi, utan att se till att gemensamma basdata finns på plats samtidigt som
andra uppdelningar av koncept är möjliga. Ett sätt att uppnå långsiktighet är att koppla till
wikidata (där det eventuellt redan finns en del poster som kan användas).
Hur K-samsök agerar i frågan om auktoritetslistor är en avvägning som både har att göra med
ansvar och kostnad, men också att dra fördel av den mångfald länkade data kan erbjuda
samtidigt som man faciliterar en samsyn när sådan är möjlig och till hjälp för
innehållsleverantörer.
```
.....

```
K-samsök kan även ta denna roll utan att vara aggregator, men om arbetet som aggregator ska
bli framgångsrikt måste man aktivt förhålla sig till denna fråga. Här krävs samordning, bl a
innehållsleverantörer, Riksarkivet och Kungliga biblioteket.
```

Kommentar Magnus: Intressant att man reda 2014 peka på Wikidata lite konstigt att inget material hittas efter 2014....
