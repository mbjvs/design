---
---
En färganalys av tre webbplatser
=========================

Webbplatsbyggande är mycket mer än kod och sidelement. Arbetet innehåller också ställningstaganden kring design och ett försök att förmedla någon typ av *känsla*.  Med en start i detta påstående syftar denna rapport till att åstadkomma två saker, att kartlägga och analysera de färgval som gjorts i byggandet av ett antal webbplatser. Analysen kommer främst grunda sig i de teorier som författarna Beaird och George presenterar i boken *The Principles of Beautiful Web Design*.


1. Urval
-----------------------
De webbplatser som kommer granskas valdes ut på ett förhållandevis godtyckligt sätt - nämligen de tre webbplatser som en av författarens webbläsare presenterade som de mest frekvent besökta under den senaste månaden. De tre webbplatserna är

* **Dagens Nyheter, dn.se** - en av sveriges största dagstidningar.
* **Kritiker.se** - en webbsida som aggregerar recensioner från svenska medier, likt den amerikanska motsvarigheten metacritic.com.
* **php.net** - PHP-manualen.

Den godtyckliga urvalsmetoden till trots är det en intressant samling webbplatser med olika syften och troligtvis helt olika förhållningssätt till färg och typsnitt.


2. Metod
-----------------------

I uppstartsfasen av skrivandet testades ett par olika metoder för att hitta de färger och typografiska val som gjorts i byggandet av webbsidorna. "Granska element" i Safari visade sig vara lite trubbigt och omständligt och det visade sig vara lättare sagt än gjort att leta reda på alla färger. Sedan testades en hel rad olika webbtjänster innan valet föll på verktyget *Stylify Me* som på ett enkelt och överskådligt sätt visar vilka färger och typsnitt en webbsidas CSS innehåller [1].

I resultatet visar verktyget färger som används av sidelement och typsnitt separat, men jag har i resultatpresentationen valt att sammanställa de mest använda färgerna samlat.



3. Resultat
-----------------------

#### 3.1 DN.se  
![dn.se](image/dnse.jpg?w=821 "dn.se")  

<table style="border-spacing: 3px; border-collapse: separate">
<tr>
Färger som används:
<td style="height: 37px; width: 37px; background-color: #fff">
<td style="height: 37px; width: 37px; background-color: #222222">
<td style="height: 37px; width: 37px; background-color: #da000d">
<td style="height: 37px; width: 37px; background-color: #dddddd">
<td style="height: 37px; width: 37px; background-color: #ffeabe">
<td style="height: 37px; width: 37px; background-color: #f2f2f2">
</tr>
</table>
Denna webbplatsen använder sig av ett färgschema som är svårt att placera i någon av de teorier som Beaird och George presenterar. Det är en vit sida med två huvudsakliga accentfärger - svart och röd. Kanske något i stil med "Analo-adjust" - ett monkromt tema med en stark röd kontrastfärg [2]

Alla rubriker har serifer och är av typsnittet *PublicoBanner*. Även brödtexten har serifer och typsnittet är *Georgia*. Valet av tyspnitt med serifer är antagligen gjort för att signalera att det är ett seriöst innehåll på en seriös sida [3]. Intressant är att "annonsrubrikerna" saknar serifer.

Webbplatsen är antagligen framtagen för att se ut som en klassisk dagstidning med svart text på vit grund, ett trovärdigt och inte så, färgmässigt, plottrig design. Den röda färgen är med för att visa på fokus på webbplatsen.

#### 3.2 kritiker.se
![kritiker.se](image/kritikerse.jpg?w=821 "Kritiker.se")

<table style="border-spacing: 3px; border-collapse: separate">
<tr>
Färger som används:
<td style="height: 37px; width: 37px; background-color: #bd1550">
<td style="height: 37px; width: 37px; background-color: #f8ca00">
<td style="height: 37px; width: 37px; background-color: #717b2f">
<td style="height: 37px; width: 37px; background-color: #E97F02">
<td style="height: 37px; width: 37px; background-color: #490a3d">
<td style="height: 37px; width: 37px; background-color: #ffffff">



</tr>
</table>
Denna webbplatsen använder sig av ett kvadratiskt färgschema. Det är helt klart "vågade" färger som används och där varje färg har sitt eget tema på webbplatsen. Värt att notera att accentfärgerna för varje tema figurerar mer frekent och i större sidelement när en klickat sig vidare på webbplatsen.

De större rubrikerna, h1 och h2 saknar serifer och har typsnittet *Raleway* och den mindre rubriken, h3 samt brödtexten har serifer och har typsnittet *Merriweather*.

Syftet med typsnitt och färg i detta fallet är antaligen en vilja att visa att sidan har ett populärkulturellt- och underhållningstungt innehåll med lekfulla färger och tydliga skillnader mellan olika teman.

#### 3.3 php.net
![php.net](image/phpnet.jpg?w=821 "php.net")

<table style="border-spacing: 3px; border-collapse: separate">
<tr>
Färger som används:
<td style="height: 37px; width: 37px; background-color: #8892bf">
<td style="height: 37px; width: 37px; background-color: #333333">
<td style="height: 37px; width: 37px; background-color: #c0c0c0">
<td style="height: 37px; width: 37px; background-color: #e2e4ef">
<td style="height: 37px; width: 37px; background-color: #336699">
<td style="height: 37px; width: 37px; background-color: #ffffff">
</tr>
</table>
php.net använder sig av ett monokromatiskt färgschema där den blågrå tonen genomsyrar i princip alla sidelement och typsnitt. Alla rubriker och brödtexten är utan serifer och är av typsnittet *Frutiger*.

I och med att sidan i princip inte innehåller några bilder eller "negative spaces"  syftar webbsidan antagligen till att kommunicera att det är en faktatungt och relativt mastigt innehåll [4]. Att sidan inte använder sig av serifer visar också på ett mer "modernt" innehåll [5].



4. Analys
-----------------------
De tre webbplatser som undersöktes i denna rapport är av tre helt olika typer, en nyhetssida, en populärkulturell sida och en faktatung "manual". Efter att ha läst igenom Beaird och Georges bok tillsammans med de kompletterande artiklarna och sedan givit sig på att gissa på utformningen av dessa webbsidor hade en antagligen inte varit alldeles långt ifrån verkligheten. Webbsidorna ger prov på de vanligaste teorierna kring vad typsnitt och färger kan kommunicera, med allt från serifval till hur pass sobert färgschemat är.


5. Referenser
-----------------------
[1]: Stylify me, www.stylifyme.com  [2019-12-04]  
[2]: s. 140 - The Principles of Beautiful Web Design, Jason Beaird & James George, Sitepoint 2014  
[3]: s. 79 - The Principles of Beautiful Web Design, Jason Beaird & James George, Sitepoint 2014  
[4]: The Characteristics of Minimalism in Web Design, Kate Moran, https://www.nngroup.com/articles/characteristics-minimalism/ [2019-12-05]  
[5]: s. 142 - The Principles of Beautiful Web Design, Jason Beaird & James George, Sitepoint 2014  
