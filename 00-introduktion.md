# Introduktion

Blok 1. 8 minutter.

## Læringsmål

- Skelne mellem et datasæt, et menneske kan læse og et datasæt, som en maskine kan bruge.
- Kende forskel på tidy og messy data.

## Åbn filen

Åbn en kopi af [ovelse_flora_danica.xlsx](data/ovelse_flora_danica.xlsx). Originalen *Index_FloraDanica.xlsx* lader I ligge.

En datatabel kan være sat op, så et menneske kan læse den ned over siden. En maskine læser række for række og celle for celle. Den gætter ikke på, at et linjeskift betyder en ny person, eller at en skråstreg betyder et nyt navn. Forskellen på det et menneske læser, og det en maskine læser, er det som Wickham (2014) kalder tidy data. De tre regler kommer I til i [Formatér data](02-formater-data.md).

## Flere værdier i samme celle

På *Noter* ligger *Ophav* og *Lokalitet*. Sammenlign to rækker.

Det er et eksempel på messy data. *Ophav* rummer seks botanikere i samme celle. Hver linje har navn, levetid og ordet botaniker. *Lokalitet* rummer Danmark og Norge, adskilt af et linjeskift. *Ophav* er ikke kunstneren på den enkelte tavle, og *Lokalitet* er ikke plantens findested. Det tager I op i [Datoer og ophav](03-datoer-og-ophav.md).

I kildefilen er *Opstilling* altid *Fol. Top. Bot. Danmark*, og *Copyright* er altid *Materialet er fri af ophavsret*. De to kolonner er udeladt her, fordi værdien er den samme på alle rækker.

[Oversigt](index.md) | [Næste: Typiske fejl](01-typiske-fejl.md)