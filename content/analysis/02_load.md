---
Title: load
Description: load
Template: analysis
---

==========

Webbplatsernas Laddningstider
-----------------------
Tre webbplatser ska jämföras beroende på hur snabbt de laddas och hur dessa sidor skulle kunna förbättra sin allmänna hastighet och användbarhet.

Urval
-----------------------
 Jag har valt att undersöka tre olika webbutiker som specialisera i att sälja merch åt olika band och franchiseavtal.  Dem specifika sidorna är EMP.com, Impericon.com och merchbar.com. Varför jag valde juste dessa sidor är för att dem är alla tre väldigt framgångsrika inom branschen men de är väldigt olika oavsett om dem säljer samma sak. 

Metod
-----------------------
Jag kommer till att använda”PageSpeed” för att utföra denna undersökning. PageSpeed ger väldigt utförlig statistik på olika laddningstider på hemsidor. Google Chrome DevTools är ett annat vertyg jag kommer att använda för att kolla vad som laddas och hur stora sidans filer är.

Resultat
-----------------------
<div class = "table">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTzpE5m9OPVEqD7rsz0awTcbGfKuU7SNxx4HeIPpHctgWTYpZVE_RnqW6E6PjoTtUM7Ku1Q-eK6nvhU/pubhtml?widget=true&amp;headers=false" class ="gsheet"></iframe>
</div>

<h3>EMP</h3>
Enligt Page Speed skulle EMP kunna förbättras genom att ta bort oanvänd CSS / JavaScript och ändra gamla filformat på bilder till modernare alternativ, till exempel ändra PNG och JPG till WebP och AVIF. EMP har redan bra resultat med snabba laddningstider på desktop men skulle kunna förbättra sina resultat på mobilen.

![emp](%assets_url%/img/emp.png)

<h3>Impericon</h3>
Impericon har ganska bra resultat på datorn men har väldigt mycket lägre resultat på mobiltelefoner. För att förbättras behöver impericon enligt Page Speed bli av med oanvänt javascript / CSS, ändra förminska storlek på bilder, förminska server responstid och använda text compression. Oanvänd Javascript och bildstorlek verkar vara största problemet och håller tillbaka sidan med över 3 sekunder.

![Impericon](%assets_url%/img/impericon.png)

<h3>Merchbar</h3>
Merchbar har mycket samma problem som de andra sidorna som oanvänd javascript/css, ändra filformat till modernare alternativ, förminska server responstid och ändra storlek på bilder. Några andra problem är att ladda bilder som inte visas senare och förminska javascript exekverings tid. Merchbar är den långsammaste av dem tre sidorna både på mobilen och datorn med väldigt låga resultat, därför behövs det att någonting görs åt detta.

![merchbar](%assets_url%/img/merchbar.png)

Analys
-----------------------
Många av problemen är sådant som alla tre har gemensamt som oanvänd kod, bildstorlekar/ format och lite annat som server responstid. Eftersom mitt urval av hemsidor är webbutiker finns det många bilder som behöver laddas in. Ett sätt att lösa detta är att inte har för många bilder på startsidan och sedan ge användaren ett alternativ på hur många produkter ska laddas in på samma sida.
<p> </p>
EMP vinner i alla tre test förutom i kontaktsidan vart Merchbar vinner för engångskull. EMP har över lag bäst resultat sedan Impericon och sist Merchbar. Alla tre hemsidor laddar ganska långsamt på mobilen i jämförelse med datorvarianterna.
<p> </p> 
För mig personligen ligger de absoluta en sida borde tar för att laddas är runt 10 sekunder men det hade varit idealt om en sida ladda på 3–5 sekunder. Om det tar mer än 10 sekunder brukar jag börja leta efter andra alternativ om inte jag redan är familjär med sidan. Så att en sida laddas snabbt är viktigt angående första intryck. Sidorna jag har valt klarar kriterierna på datorn men knappast på mobilen. Det är viktigt att sidor funkar bra på mobilen för det är vanligare med mobiler nu för tiden. 
<p> </p> 
Den enda sidan som riktigt klara detta är EMP på datorn men jag tycker alla sidor känns relativt snabba i tanke på hur mycket en webbutik brukar har att ladda in. 

