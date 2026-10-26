# Eksport af data

Blok 2. 11 minutter.

## Læringsmål

- Forklare, hvorfor en csv-fil er tekst, og en xlsx-fil ikke er det.
- Gemme arket *Noter* som csv ved siden af øvelsesfilen.
- Se semikolon og linjeskift, når csv-filen åbnes i en teksteditor.

## Hvorfor csv

En csv-fil er en tekstfil, hvor et tegn adskiller kolonnerne. I RFC 4180, https://www.rfc-editor.org/rfc/rfc4180, er tegnet et komma. Excel på en dansk computer skriver et semikolon, når filtypen hedder *CSV (semikolonsepareret)*. I kan åbne filen i en teksteditor og stadig læse værdierne.

En xlsx-fil er den projektmappe, Excel gemmer. Den kan ikke læses som almindelige linjer i Notesblok. Til opbevaring og til at give filen videre er tekst ofte lettere at åbne igen om mange år. Kildefilen *Index_FloraDanica.xlsx* bliver liggende som xlsx. Csv-filen er en kopi af ét ark, ikke en erstatning.

UTF-8 er en tegnkodning, der kan gemme æ, ø og å. Den er beskrevet i RFC 3629, https://www.rfc-editor.org/rfc/rfc3629. Nyere Excel har filtypen *CSV UTF-8 (kommasepareret)*. Ældre udgaver af Excel har den ikke. De har filtypen *CSV (semikolonsepareret)*, som gemmer bogstaverne i Windows-1252. *Multebær* og *Særudgivelser* bliver i filen. De kan blive læst forkert, hvis filen senere åbnes som UTF-8.

## Øvelse

Gå til arket *Noter*. Vælg Filer, Gem som. Vælg den mappe, hvor kopien af øvelsesfilen ligger.

Filtype: CSV (semikolonsepareret) (*.csv). Kald filen *noter.csv*. Gem den ved siden af xlsx-filen. Overskriv ikke *ovelse_flora_danica.xlsx*.

Excel gør opmærksom på, at en csv-fil kun kan rumme det aktive ark. Fortsæt. De andre ark bliver i xlsx-filen, ikke i csv-filen.

Når der er gemt, er det csv-filen, Excel har åben. Luk den uden at gemme den oven i xlsx-filen. Åbn *noter.csv* i Notesblok. Åbn bagefter *ovelse_flora_danica.xlsx* igen, hvis I skal videre på de andre ark.

Find et semikolon, og find et sted, hvor en linje knækker midt i et felt.

## Forslag til resultat

*noter.csv* ligger i samme mappe som øvelsesfilen. *ovelse_flora_danica.xlsx* er der stadig og har arkene *Tavler* og *Noter*.

[Oversigt](index.md)
