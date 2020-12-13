---
Title: Kmom04
Description: Kursmoment 4
Template: kmom
---
# Kursmoment 4

Välkommen att läsa min presentation [online][1].

Rutnätet har funnits så länge som vi skrivit böcker. Även gamla handskrifter
från tiden innan bokpressen höll en strikt visuell form. Det är en uråldrig
form som tilltalar människans förkärlek för symmetri, och som har finslipats
genom hundratals år.

Det faktum att vi fortfarande kämpar för att få den här grundläggande tekniken
att fungera i våra webbläsare är ett tecken på hur tidigt i utvecklingen vi
fortfarande är. Och hur lite vi har prioriterat de här frågorna. Visst talas
det om hur olika det är att läsa text på en skärm kontra att läsa den i tryck,
men det känns ofta som att lösningen har varit att bryta alla regler som vi
samlat på oss genom dessa sekler.

## Grid och flexbox

Jag har ägnat ganska mycket tid åt att läsa om- och experimentera med grid den
här gången. Det finns många bra instruktioner att läsa på nätet och mycket fin
inspiration på många sajter.

Det kan vara svårt, tycker jag, att blanda flexbox med grid, men uppenbarligen
så går det. Nu har jag bara kvar flexbox i min header, redovisningarna styrs
upp med hjälp av ett grid. Min förstasida och min om-sida är ännu så länge
bara några _div_, men jag har planer för dem.

Egentligen förstår jag inte grid mer än jag förstår flex-box, men jag har lättare
att visualisera i form av rutnät &ndash; kanske längtar jag tillbaks till att
designa i tabeller? (Antagligen inte...)

## Uppgiften

Under arbetet med min redovisnings&shy;sida fann jag äntligen något jag länge letat
efter; _grid order_. Jag skulle kunna lägga inne&shy;hålls&shy;förteckningen efter
inne&shy;hållet
i min html (.twig), och ändå presentera den till vänster på skärmen. Alternativa
skärm&shy;läsare som presenterar innehållet i braille eller talsyntes behöver inte
traggla igenom innehållsförteckningen först på varje sida.

Det spökade dock till det med tab-ordningen och buggade ordentligt om man försökte
markera text, så jag övergav projektet. Jag lade innehålls&shy;förteckningen först i
html-dokumentet.

Enligt specen så skall innehållsförteckningen ligga till vänster. I annat fall
hade jag föredragit att ha den till höger. Då hade den helt enkelt fallit ner
under huvudinnehållet när man går ner på mindre skärmar.

Jag behöver däremot inte gömma den helt på en mindre skärm. Jag kan flytta ner
den till slutet av sidan med _grid-order_. Den finns till hands, och användaren
behöver ändå inte scrolla femton centimeter innan själva innehållet.

### Refactoring

Jag har börjat inse att jag kommer att slipa vidare på allting under kursens
gång. Det är ingen mening att ta något längre än specen. Till exempel så har
jag klarat kravet för min _landing-site_, men jag kommer jobba vidare med
typografi och färger framgent.

När jag fick griddet på plats ville jag försöka att ta min typografi ett steg längre.
Jag skapade en _mixin_ som räknar ut rätt radhöjd utifrån font-size för att
närma sig en multipel av "det magiska talet".

För att få det riktigt bra skulle jag vilja lägga till ett horisontellt
grid &ndash; rader för att nivellera radhöjder mellan olika element. Vi hade en
bra modell i förra versionen av den här kursen. Det borde finnas något som
fungerar tillsammans med SASS.

## Skapa och skriva

Ibland ser jag för mycket på den här kursen ur en skribents per&shy;spektiv. Jag glömmer
ibland är att _jag_ skall vara länken mellan den som skapar och publik&shy;ationen på
nätet. _Jag_ skall göra det enkelt att publicera. Alla de betänklig&shy;heter som jag
har är det upp till mig att lösa. Jag ska inte bekymra mig så mycket för innehåll
som jag gör.

Målbilden är att uppdragsgivaren kan använda sin sajt utan att behöva tänka på
allt det som jag tänker på just nu. Sajten skall vara ett verktyg, inte ett
problem.

## Kort och koncist

__Kommentera kort om skrivuppgiften, något som är värt att nämna från arbetet med den?__

Jag valde ett ämne som legat mig nära under min karriär hittills. Hur
marknadsför man klassisk musik på ett bra vis. Det jag upptäckt är att det
används ganska tråkiga färgval för en så kreativ bransch.

__Vilket färgschema valde du till ditt tema och hur valde du att använda färgerna (mer eller mindre eller lika mycket av alla färger)?__

Mitt tema bygger på en gammal monitor. Jag har använt grönt, och bara grönt.
Till och med bilderna gjorde jag monokroma med CSS och färgade sedan gröna.
Hade jag vetat hur man ger bilder sämre upplösning (utan att bearbeta dem i
en dator) så hade jag gjort det.

Det blev lite nördigt.

__Valde du att jobba med accentfärg och isåfall hur?__

__Hur valde du att lösa ditt dark theme? Gjorde du en kopia på ditt vanliga tema? Eller löste du det med imports?__

Jag använde rikligt med imports.

__Vilken är din TIL för detta kmom?__

Jag fortsätter att lära mig saker om grid. grid-template-columns tillsammans med
fr-måttet blir väldigt lättjobbat.

[1]: http://www.student.bth.se/~olai19/dbwebb-kurser/design/me/portfolio/report/kmom03
