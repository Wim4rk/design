---
Title: Kmom04
Description: Kursmoment 4
Template: kmom
---
# Kursmoment 4

Välkommen att läsa min presentation [online][1].

Det här är det sista av de kursmoment som jag redan påbörjat vid ett tidigare
kurstillfälle. Nu börjar det bli på riktigt igen.

Jag hade fördelen att kunna bedriva min studie av orkestrars webbsidor under en
lite längre tid. Det har ju varit ett egendomligt år för all scenkonst, så det
har varit intressant att följa med. Egentligen tror jag att pandemin har
bidragit till att de inrapporterade sidorna stagnerat en smula.

## Mondrian

Jag har länge velat bygga det här temat. Jag utgick från en målning av
[Piet Mondrian][2]. Originalet kan beskådas [här][3].

Det första jag gjorde var att skapa en ny förstasida. En splash-page. Till att
börja med försökte jag använda markdown. Det gick alldeles utmärkt, förutom att
det enda jag placerade där var html. När jag skulle loopa igenom alla sidorna
för att skapa en meny, så lyckades jag inte med det. Kanske är det rent av
omöjligt att skriva pico-logik i en markdown-fil?

Så jag skrev hela sidan i html, direkt i twig-filen, undantaget innehållet i den
röda rutan.

## Dark theme

Mitt tema bygger på en gammal monitor. Jag har använt grönt, och bara grönt.
Till och med bilderna gjorde jag monokroma med CSS och färgade sedan gröna.
Hade jag vetat hur man ger bilder sämre upplösning (utan att bearbeta dem i
en dator) så hade jag gjort det.

Jag är väldigt nöjd med hur jag lurar ögat att det rör sig om en monitor. Jag
har inte bara använt grön text på en svart bakgrund, jag har lagt till en
_radial gradient_ som illustrerar ljusläckage, och jag har lagt ett nät över
som ger ränder på ett genuint sätt.

Det blev lite nördigt.

### Refactoring

Jag sitter fortfarande och skriver om min kod från tidigare kursmoment. Jag
kommer att göra det åtminstone tills jag är klar med den här kursen.

Det är inte så att jag har svårt att få arbetet ur händerna, men allteftersom
jag utvecklar sidor så behöver jag, så att säga, skriva rent tidigare stilar.
Eljest skulle jag snart ha ett lapptäcke av kod där ingen längre skulle kunna
följa sömmarna.

## Kort och koncist

__Kommentera kort om skrivuppgiften, något som är värt att nämna från arbetet med den?__

Jag valde ett ämne som legat mig nära under min karriär hittills. Hur
marknadsför man klassisk musik på ett bra vis? Det jag upptäckt är att det
används ganska tråkiga färgval för en så kreativ bransch.

__Vilket färgschema valde du till ditt tema och hur valde du att använda 
färgerna (mer eller mindre eller lika mycket av alla färger)?__

__Valde du att jobba med accentfärg och i så fall hur?__



__Hur valde du att lösa ditt dark theme? Gjorde du en kopia på ditt vanliga tema? Eller löste du det med imports?__

Jag använde rikligt med imports. Och... Naturligtvis så skrev jag om alla mina
moduler igen. Fast det blir ju bättre och bättre för varje gång.

__Vilken är din TIL för detta kmom?__

Fraktioner, <samp>fr</samp>, är ett lysande verktyg tillsammans med grid och flex.

[1]: http://www.student.bth.se/~olai19/dbwebb-kurser/design/me/portfolio/report/kmom04
[2]: https://en.wikipedia.org/wiki/Piet_Mondrian
[3]: https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Piet_Mondriaan%2C_1930_-_Mondrian_Composition_II_in_Red%2C_Blue%2C_and_Yellow.jpg/800px-Piet_Mondriaan%2C_1930_-_Mondrian_Composition_II_in_Red%2C_Blue%2C_and_Yellow.jpg