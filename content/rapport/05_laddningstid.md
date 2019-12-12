---
---
En analys av tre webbplatsers laddningstider
=========================


1. Urval
-----------------------
Liksom i föregående kmom ska det göras ett urval av webbplatser. Något som konsterades i färganalysrapporten var urvalet något godtyckligt då det helt enkelt var de mest besökta sidorna den senaste månaden. Även denna gång kommer samma webbsidor användas för att bibehålla någon typ av stringens i rapportförfattandet. Således är de webbsidor denna rapport baseras på följande:

* **Dagens Nyheter, dn.se** - en av sveriges största dagstidningar.
* **Kritiker.se** - en webbsida som aggregerar recensioner från svenska medier, likt den amerikanska motsvarigheten metacritic.com.
* **php.net** - PHP-manualen.


2. Metod
-----------------------
För att samla in data till uppgiften används Googles PageSpeed Insights samt devtools i webbläsaren Google Chrome. För att vara säker på att resultatet baseras på replikerbar data rensas all webbplatsdata innan mätningen påbörjas och mellan varje mätning görs en hård refresh - CMD+SHIFT+R.

Datorn som används är en Apple MacBook Pro från 2015 och uppkopplingen är en internetdelad sådan från en iPhone med 3 "bars" 4G-nät.

All rådata har sammanställts i en Excelfil du kan ladda ner: [här!](files/kmom05.xlsx)


3. Resultat
-----------------------

#### 3.1 DN.se  
![dn.se](image/dnse2.jpg?w=821 "dn.se")  

I verktyget PageSpeed Insights får Dagens Nyheter betyget 80 för desktop och 67 för mobila enheter. Mätningarna i Google Chrome devtools visar på en laddningstid som i snitt ligger på 2,15 sekunder. I snitt laddas 46 resurser och storleken är i snitt 1,9mb.

Något som skulle göra DN.se snabbare är hanteringen av bilder där både rätt storlek på bilderna och en prioritetsordning för när de ska laddas skulle spara en hel del tid.

#### 3.2 kritiker.se
![kritiker.se](image/kritikerse2.jpg?w=821 "Kritiker.se")

I verktyget PageSpeed Insights får Kritiker.se betyget 53 för desktop och 27 för mobila enheter. Mätningarna i Google Chrome devtools visar på en laddningstid som i snitt ligger på 11,4 sekunder. I snitt laddas 131 resurser och storleken är i snitt 4,8mb.

Det största problemet med denna webbsida är helt enkelt mängden data och resurser som används och att det bör komma till någon typ av prioordning för data som ska läsas in - typ tunga CSS-filer med beroenden.


#### 3.3 php.net
![php.net](image/phpnet2.jpg?w=821 "php.net")

I verktyget PageSpeed Insights får php-manualen betyget 92 för desktop och 44 för mobila enheter. Mätningarna i Google Chrome devtools visar på en laddningstid som i snitt ligger på 2,16 sekunder. I snitt laddas 32 resurser och storleken är i snitt 1,35mb.

#### 3.4 Vinnare?
"Vinnare" av mätningen blir utan tvekan DN.se som ser ut att vara bäst optimerad för både desktop och mobila enheter. Tvåan blir php-manualen och på klar sista plats hamnar kritiker.se som har en hel del förbättningspotential, inte minst när det kommer till mängden resurser och storleken på dem. Resultatet är kanske inte helt överraskande då DN.se antagligen har bra mycket mer resurser än kritiker.se som antagligen är en enmansoperation eller liknande. Samtidigt är också kritiker.se mer krävande i sin natur än vad php-manualen är - ett mättat grafiskt innehåll med olika medier kontra textbaserat kodsyntax i princip.

4. Analys
-----------------------
Trots att de tre webbsidorna skiljer sig åt i syfte, innehåll och upplägg finns det några förbättringsförslag som återkommer och det är framförallt att ta bort resurser som blockerar renderingen av webbsidan och att skjuta upp inläsning av bilder som inte visas på skärmen. I och med att både DN.se och Kritiker.se använder sig av många resurser och en hel del data så skulle någon typ av prioriteringsordning hjälpa båda webbplatser.

För att klargöra om laddningstiderna är långsamma eller snabba behövs en mer tillförlitlig nollmätning med tillhörande teoretisk grund. Men givet den tunna empirin denna rapport är baserad på skulle DN och php.net kunna bedömas vara snabbladdande och kritiker.se förhållandevis långsam. Längre än 2 sekunder ska en inte behöva vänta på att en sida laddas givet att det är ett vanligt text+bild-innehåll.

5. Övrigt
-----------------------
Författare: von Sydow, Magnus
