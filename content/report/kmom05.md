---
Title: Kmom05
Description: Kursmoment 5
Template: kmom
---
# Kursmoment 5

Välkommen att läsa min presentation [online][1].

## Undersökningen

Jag fick min undersökning gjord rätt kvickt. Bra det, för nu ligger jag
ordentligt efter. Jag har hoppat friskt mellan kmom04 och kmom05. Några av
de problem som skall lösas finns i bägge momenten. Framför allt att använda
sig av bilder och ett responsivt grid.

Ett urval om tre webbplatser, särskilt när de är valda ur samma kate&shy;gori
kan lätt få fel viktning. Jag har skaffat mig över&shy;blick över tre
myndig&shy;heters hemsidor, det är egentligen allt.

## Cimage

Att använda Cimage är inte helt nytt för mig, men den här gången nådde jag en
bättre förståelse. Det är väldigt praktiskt att cacha upp de bilder man behöver
senare, men att ändå bara ladda upp en enda bild.

Att spara endast lite kvalitet i poten&shy;tiellt stora kvanti&shy;teter kan ge
oanad rationali&shy;sering.

## Responsivitet och användbarhet

Det som mest behövs för en god responsi&shy;vitet är det&shy;samma som behövs
för en god använd&shy;barhet; väl&shy;for&shy;mulerad HTML. Att därefter
app&shy;licera CSS blir så mycket enklare ju bättre kod man har att utgå ifrån.

Att begära bilder
i rätt storlek är mycket fördel&shy;aktigt, både för att spara in på
data&shy;trafik och ladd&shy;tider.

Ett verktyg jag själv använder flitigt är _&amp;shy;_. Det anger var ord får
avstavas när det behövs. När man då ändrar storlek på view-port så ändrar
avstav&shy;ningarna sig också.

Det saknas ett opensource-verktyg på svenska för att auto&shy;matiskt
identi&shy;fiera lämpliga ställen och lägga till _&amp;shy;_. Det kanske
är ett framtida projekt?

## Bildgalleriet
Bilderna jag använder är mina egna. I vanliga fall när jag skapar bilder för
nätet så konver&shy;terar jag dem från raw-formatet till jpg. Jag passar på att
göra bilderna mindre, och att dra ner kvalitén till 85%. Det brukar resultera i
filer omkring 300 kB stora.

För att nu få ett hyggligt övnings&shy;material försökte jag att göra en så rak
export som möjligt. De flesta av mina filer ligger nu mellan 500- och 700 kB.
En är på 1,2 MB. Vissa är omkring 300 kB. Upp&shy;lös&shy;ningen varierar
beroende på vilken kamera jag använt, och de flesta bilder är svart&shy;vita.

Jag skapade en ny splash-page för ett bildgalleri. Jag angav en ny maxbredd;
10&nbsp;000 px för att alltid fylla hela skärmen. I meta-datan lade jag till
klasser för att sedan få en så enkel CSS som möjligt. Filen som styr galleriet
är 26 rader lång. Grid hjälper till rätt mycket.

Missa inte att mitt galleri också fungerar i mitt mörka tema, men då som
mono&shy;kromatiska bilder med grön tint.

### Kort och koncist

__Berätta kort om erfarenheterna med din undersökning av webbplatsers laddningstid och vad du kom fram till.__

I mitt mycket smala urval fann jag att för stora bilder inte var ett problem.
Däremot föreslog [Google Pagespeed][2] att man borde använda Googles nya
bild&shy;format i alla tre fallen. Dock med om&shy;skriv&shy;ningen att man
borde använda "modernare" bild&shy;format.

__Har du några funderingar kring Cimage och dess nytta och features? Vilka bildverktyg använder du själv normalt sett?__

Jag har alltid skapat mina bilder via Adobe Lightroom &ndash; en rätt gammal
utgåva. Där kan man välja att optimera för skärm, och får filer kring 300 kb.
Till&shy;sammans med _width: 100%;_ brukar det bli responsivt med hyggligt lätta
filer.

Cimage verkar vara ett trevligt verktyg. Det roade mig att man var tvungen att
definiera formatet 1:1 själv.

__Vad är din egen allmänna uppfattning kring bilder för webben, nedladdningstider, responsiva bilder och allmänt kring bildbehandling för webben?__

Jag vill gärna ha ett verktyg som löser det åt mig, men jag vill också ha
större kontroll över _hur_ verktyget arbetar. Det krävs en ordentlig
djup&shy;dykning i Cimage för att förstå just det.

Med detta sagt så har jag använt liknande verktyg för Wordpress. Det har då
involverat något slags användargränssnitt. Resultatet har alltid handlat om
att göra bilder mindre, inte att lägga till effekter.

__Vilken är din TIL för detta kmom?__

Markdown kan inte renderas inom html-block. Om man använder html så använder man html full ut. Ända undantaget är inline-element som <code\>.

[1]: http://www.student.bth.se/~olai19/dbwebb-kurser/design/me/portfolio/report/kmom05

[2]: https://developers.google.com/speed/pagespeed/insights/
