# Eksport af data

Blok 2. 11 minutter.

## Læringsmål

- Forklare, hvorfor en csv-fil er tekst, og en xlsx-fil ikke er det.
- Gemme arket *Noter* som csv ved siden af øvelsesfilen.

## Hvorfor csv

En csv-fil er en tekstfil, hvor et tegn adskiller kolonnerne. I RFC 4180, https://www.rfc-editor.org/rfc/rfc4180, er tegnet et komma. Excel skriver et semikolon, når filtypen hedder *CSV (semikolonsepareret)*. Fordi det er en tekstfil kan I åbne filen i en teksteditor, f.eks. Notepad++, og stadig læse værdierne.

En xlsx-fil er den projektmappe, Excel gemmer. Den kan ikke læses som almindelige linjer i en teksteditor. Til opbevaring og til at at give videre bliver csv-filer ofte foretrukket, fordi de er lettere at åbne igen om mange år.

UTF-8 er en tegnkodning, der kan gemme æ, ø og å. Den er beskrevet i RFC 3629, https://www.rfc-editor.org/rfc/rfc3629. Nyere Excel har filtypen *CSV UTF-8 (kommasepareret)*. Ældre udgaver af Excel har den ikke. De har filtypen *CSV (semikolonsepareret)*, som gemmer bogstaverne i Windows-1252. Ord som *Multebær* og *Særudgivelser* som har et æ kan ofte skabe problemer og blive læst forkert, hvis en fil er gemt i ét format og senere åbnes i et andet, så det er godt, at have styr på sin tegnkodning, når man gemmer en tekstfil.

## Øvelse

Gå til arket *Noter*. Vælg Filer, Gem som. Vælg den mappe, hvor kopien af øvelsesfilen ligger.

Filtype: CSV (semikolonsepareret) (*.csv). Kald filen *noter.csv*. Gem den ved siden af xlsx-filen. Overskriv ikke *ovelse_flora_danica.xlsx*.

Excel gør opmærksom på, at en csv-fil kun kan rumme det aktive ark. Fortsæt. De andre ark bliver i xlsx-filen, ikke i csv-filen.

Når der er gemt, er det csv-filen, Excel har åben. Luk den uden at gemme den oven i xlsx-filen.

## Forslag til resultat

*noter.csv* ligger i samme mappe som øvelsesfilen. *ovelse_flora_danica.xlsx* er der stadig og har arkene *Tavler* og *Noter*.

[Oversigt](index.md)
