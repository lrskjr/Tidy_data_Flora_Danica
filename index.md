# Tidy data i regneark. Flora Danica

Materialet er målrettet humaniorastuderende og er beregnet til 45 minutter i første blok og 35 minutter i anden blok. Man arbejder kun i Excel.

Materialet kan bidrage til, at man kan lære at se, når en celle rummer flere oplysninger, som bør deles op i flere kolonner, så det bliver lettere at filtrere og sortere data.

## Tidy data

Tidy data er en måde at bygge et datasæt på, så en maskine kan læse det. Det er beskrevet i artiklen Tidy Data, der er skrevet af Hadley Wickham i 2014. 
*“Tidy Data.” Journal of Statistical Software, vol. 59, no. 1, September 2014, pp. 1-23, [https://doi.org/10.18637/jss.v059.i10](https://doi.org/10.18637/jss.v059.i10).* 

Wickham nævner tre regler for en god opbygning af et tidy datasæt:

- én variabel pr. kolonne
- én observation pr. række
- én værdi pr. celle

En variabel er en egenskab, som man kan betragte som en kasse, der ideelt set indeholder værdier af samme type. Det er f.eks. en tekststreng eller et tal. I et Excel-ark er variabelnavnet skrevet i første række og bliver kolonenavnet. Det kan f.eks. være år. Værdierne i kolonnen under år svarer på, hvilket år er knyttet til den obervation, som rækken handler. Det kan f.eks.være, at året er 1761, hvilket er publikationsåret for den Flora Danica tavle, som hele rækken handler om.

Et Excel-ark bliver let brugt forkert, f.eks. ser man ofte, at der er blandet noter ind i et excelark og at særlige observationer omkring værdier er fremhævet med farver. En god artikel med gode råd til at organisere data i regneark er Karl W. Broman og Kara H. Woos artikel *Data Organization in Spreadsheets*, udgivet i The American Statistician, 72(1) i 2018, https://doi.org/10.1080/00031305.2017.1375989.

## Tidsplan

Blok 1. 45 minutter.

- [Introduktion](00-introduktion.md). 8 minutter.
- [Typiske fejl](01-typiske-fejl.md). 15 minutter.
- [Formatér data](02-formater-data.md). 22 minutter.

Blok 2. 35 minutter.

- [Datoer og ophav](03-datoer-og-ophav.md). 12 minutter.
- [Kvalitetskontrol](04-kvalitetskontrol.md). 12 minutter.
- [Eksport af data](05-eksport-af-data.md). 11 minutter.

Øvelsesfilen ligger her: [ovelse_flora_danica.xlsx](data/ovelse_flora_danica.xlsx).

## Sådan arbejder I

Åbn en kopi af øvelsesfilen. Ret ikke i [*Index_FloraDanica.xlsx*](data/Index_FloraDanica.xlsx). Den er kilden (kildefilen) og skal blive, som den er. Når I ændrer noget, så gør det i kopien af øvelsesfilen.

Kildefilen har ét ark, *Exported Record Data*. Det er et dataudtræk fra Det Kgl. Biblioteks [Digitale Samlinger](https://digitalesamlinger.kb.dk/images/billed/2010/okt/billeder/subject5449/da/?notAfter=&notBefore=&search_field=all_fields) og består af 3.240 datarækker og 10 kolonner. Alle værdier er gemt som tekst. Der er 3.060 hovedtavler, *floradanica_0001.tif* til *floradanica_3060.tif*, og 180 supplementer, *floradanica_S0001.tif* til *floradanica_S0180.tif*. Hvert hæfte har 60 tavler. Årstallene ligger mellem 1761 og 1883. Ét år pr. hæfte.

## Øvelsesfilens ark

*Tavler* har 40 datarækker. Kolonnerne er *Record Name*, *Titel*, *År*, *Taxonomisk gruppe* og *Hæfte*. Værdierne er kopieret urørt fra kilden.

*Noter* har ni datarækker. Kolonnerne er *Record Name*, *Titel*, *År*, *Note*, *Ophav* og *Lokalitet*. Hele noten og hele ophavsfeltet er med, også linjeskiftene. Klik i cellen, og læs resten i formellinjen, hvis rækken er for lav. [Eller klik på fanebladet Hjem og Ombryd tekst under Justering](https://support.microsoft.com/da-dk/excel/wrap-text-in-a-cell-in-excel). 

*Opstilling* og *Copyright* er ikke taget med i øvelsesfilen. I kilden er værdierne de samme på alle rækker.

## Valgfri opgave på kildefilen

Tag en kopi af [*Index_FloraDanica.xlsx*](data/Index_FloraDanica.xlsx). I [episode 01](01-typiske-fejl.md) læser I gruppenavn og hæfte ud af stierne på *Tavler*. I [episode 05](05-eksport-af-data.md) kan I gemme en csv af kopien på samme måde og se, om den åbner med 10 kolonner.

## Kilder og licens

Oeder, Georg Christian. *Flora Danica*. 1883. Det Kgl. Bibliotek, LOAR. https://loar.kb.dk/items/71694c8f-f4c5-4f22-ae44-009d5899d775 og https://loar.kb.dk/handle/1902/49102

Broman, Karl W., and Kara H. Woo. “Data Organization in Spreadsheets.” The American Statistician [PHILADELPHIA], vol. 72, no. 1, January 2018, pp. 2–10, https://doi.org/10.1080/00031305.2017.1375989.

Hadley Wickham. “Tidy Data.” Journal of Statistical Software, vol. 59, no. 1, September 2014, pp. 1–23, https://doi.org/10.18637/jss.v059.i10.

Teksten til "Tidy data i regneark. Flora Danica" er inspireret af Library Carpentry lektionen [Tidy data for librarians](https://librarycarpentry.github.io/lc-spreadsheets). Teksten er ikke en kopi af lektionen, men er skrevet, så en workshop om Tidy Data kan blive afviklet med udgangspunkt i filen *Index_FloraDanica.xlsx*.

Public Domain Mark 1.0. http://creativecommons.org/publicdomain/mark/1.0/

Materialet er fri af ophavsret.