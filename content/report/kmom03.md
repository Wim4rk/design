---
Title: Kmom03
Description: Kursmoment 3
---
# Kursmoment 3

Det hade varit mycket enklare att börja om med en ny sida ändå. Jag skulle
gärna vilja ha samma grid-system rakt igenom.

## Grid

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

Jag har under några år kännt att det är enklare att jobba mer påtagligt. Det är
inte svårt att skapa en design med en penna. Så länge steget är så långt mellan
pennan och webben så kommer vi att få läsa och skapa enligt teknikens
begränsningar.

### Brödtext

Som typsnitt för min brödtext har jag därför valt [Merriweather][1] av Sorkin
Type. Det är en ett seriftypsnitt som är framtaget för att vara trevligt att
läsa på webben. Jag väljer _alltid_ typsnitt till brödtexten först. Det jag
mest av allt är ute efter är läsbarheten.

### Rubriker

Rubriker i tryck använder ofta sans-serifer, men på nätet verkar det vara helt
tvärt om. Jag kan inte förstå varför det blivit på det viset. Att det kan vara
besvärligt att läsa serifer i brödtext kan jag acceptera, men varför man tvunget
skall använda serifer i rubriken är ett mysterium.

Här valde jag verkligen att utmana mig. [Roboto Slab][2], av Christian
Robertsson är en serif-font som används flitigt till rubriker, bland andra av
Wordpress.

Därmed har jag valt serifer både till rubriker och brödtext. Och jag vet inte
om det är god typografi, men det är ett medvetet val.

## Kort och koncist

__Vad tycker du om SASS än så länge?__

Sass är smidigt än så länge. Nu när vi har börjat använda Font Awesome så har
de kompilerade css-filerna börjat att växa till sig rejält. Från under hundra rader
till gott och väl över 5000. Det känns inte rätt för mig, det är mycket kod där
som jag inte använder. Jag kanske inte behöver skriva den, men jag behöver lagra,
och -- inte minst -- servera den till användaren.

__Är du bekant med Node, npm eller npm scripts (t.ex. npm run lint) sedan tidigare? Vad anser du om det?__

Jag har använt det i andra kurser, och i privata projekt. Det är ett smidigt sätt
att installera de verktyg som behövs i en särskild utveckling, men antagligen inte
i alla. Här kompilerar vi SASS, på andra håll kompilerar jag LESS.

Package.json är lättläst

__Hur kändes det att kompilera SASS till CSS, var det något du reflekterade över?__

Nej, det var ganska rättframt. Jag använder _make_ i privata projekt, bland annat
när jag kompilerar C-kod för att koda mikrochipp.

__Kommentera ditt tema, hur kan man beskriva dess design och hade du några planer på “design” när du byggde ditt tema?__

Jag anar lite hur den här kursen kommer att fortskrida. Inom kort kommer vi att
börja jobba med _grid_. Jag väljer att hålla allt så enkelt som möjligt, så att
jag inte behöver ändra så mycket när vi når dit.

__Valde du att dela upp din kod? Vilka uppdelningar valde du att göra?__

Jag valde att dela upp min kod, men jag har inte följt rekommendationerna. Just
nu gör jag skillnad på layout, typografi, nav-meny och variabler för färger m.m.
Det blir genast uppenbart att jag behöver städa igenom mina filer framgent, och
då skall jag följa boken lite närmare.

__Vilken är din TIL för detta kmom?__

Design-kursen kommer att ta mer tid än vad jag hittills satt av.
