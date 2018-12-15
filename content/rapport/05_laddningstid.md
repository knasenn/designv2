---
---
05_laddningstid
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/redovisning/04_laddtid.md`.



######Välj ut 3 webbplatser som skall analyseras, berätta hur du gjorde urvalet.

Jag ville välja tre sidor som har snarlika uteseenden och syften. Det vart tre banker.

1. Nordea
2. Swedbank
3. Handelsbanken




######Beskriv vilka verktyg du använde och hur du utförde arbetet för att samla in dina mätvärden. Det blir en kort beskrivning av din metod.

1. snapshot
2. google pageloader
3. Firefox developer


######Skapa ett excelark, till exempel Google Kalkylark, för att spara dina mätningar i. För allt du nu skall mäta, dokumentera det i excelarket. Länka till ditt excelark så man ser rådatan.
[Excell](https://docs.google.com/spreadsheets/d/1lWzbCLdjlHbbiIp8zE233SY62BWCw0xtgAeR89YzYl0/edit#gid=0)


###För varje webbplats, gör följande:
######Ta en snapshot (bild) på webbplatsen.

#####Nordea
![nordea](http://www.student.bth.se/~aiur18/dbwebb-kurser/design/me/redovisa/htdocs/img/nordea.png)

#####Swedbank
![sw](http://www.student.bth.se/~aiur18/dbwebb-kurser/design/me/redovisa/htdocs/img/swedbank.png)

#####Handelsbanken
![hb](http://www.student.bth.se/~aiur18/dbwebb-kurser/design/me/redovisa/htdocs/img/handelsbanken.png)



######Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.
1. [Nordea sida 1](https://www.nordea.se/)
2. [Nordea sida 2](https://www.nordea.se/privat/kundservice/)
3. [Nordea sida 3](https://www.nordea.se/foretag/)
1. [Swedbank sida 1](https://www.swedbank.se/)
2. [Swedbank sida 2](https://www.swedbank.se/om-oss/kontakta-oss.html)
3. [Swedbank sida 3](https://www.swedbank.se/foretag.html)
1. [Handelsbanken sida 1](https://www.handelsbanken.se/sv/)
2. [Handelsbanken sida 2](https://www.handelsbanken.se/sv/kontakta-oss)
3. [Handelsbankensida 3](https://www.handelsbanken.se/sv/foretag)


######För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.

![NORDEA](https://www.nordea.se/)
Mobil testet: 72, Desktop testet: 100, Speed: 2.32s, Resources: 41, 1.52 MB


![SWEDBANK](https://www.swedbank.se)
Mobil testet: 7, Desktop testet: 96, Speed: 1.37s, Resources: 48, 2,4 MB

![HANDELSBANKEN](https://www.handelsbanken.se)
Mobil testet: 85, Desktop testet: 100, Speed: 2.71 s, Resources: 33, 3.83 MB



######Diskutera och skriv en mening om hur webbplatsen kan förbättra sig. Sammanfatta ditt resultat i en analys och skriv om vilka de vanligaste förbättringsåtgärderna verkar vara för ditt urval av webbplatser.
#####NORDEA
Nordea var var snabb på både dator och mobil men enligt Googles speed test så fanns några förbättringar att göra. Exempelvis "refer unused CSS" vilket innebär att man skulle radera oanvända regler i stylesheeten. Andra enkla förbättringsmöjligheter som  var att tex minifiera(minify) CSSen och ändra bildernas till bättre(bl.a. bättre kompresion) format.

#####SWEDBANK
Swedbank fick bra på desktop men uselt på mobil. Enligt Googles speed test så fanns många förbättringar att göra. Exempelvis. Aktivera textkomprimering DVS att Textresurser bör skickas komprimerade (gzip, deflate eller brotli) så att färre byte skickas via nätverket. Även här fanns CSS som inte användes.

#####Handelsbanken
Handelsbanken var var snabb på både dator och mobil men enligt Googles speed test så fanns några förbättringar att göra. Samma som nordeas sida så kunde bilderna bytas ut till ett "modernare" bildformat.

#####Rangordna dina webbplatser baserat på deras mätvärden och utse en vinnare i testet och kommentera resultatet.
Handelsbanken fick högre "betyg" än både nordea och swebank trots att laddtiden faktiskt var något sämra. Jag antar att värdet är baserat på storleken av sidan då den var sörs av alla tre.
Så för att utse en vinnare bör man kika på om båda sidorna förmedlar "samma" information eller om man faktiskt får mera av handelsbanken.

#####Bestäm en gräns för absolut laddningstid som du själv uppfattar som snabb eller långsam webbplats. Skriv en mening om hur ditt urval av webbplatser klarar ditt gränsvärde och hur du upplever webbplatsernas snabbhet, rent generellt, i ditt urval.
Jag tycker alla alla tre hemsidor är väldigt sanbba. Om jag laddar om handelsbankens sida utan att använda cashat data så tar det någon sekund tills allt är helt alddat. Men personligt tycker jag även detta är blixtsnabb laddning. Men om man får önska så kanske man vill få till att sidan laddar snabbare än 5sekunder?

#####I slutet av rapporten skriver du ett eget stycke med namnen på dina gruppmedlemmar.
Rapport av: Witold Urbas
