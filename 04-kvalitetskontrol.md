# Kvalitetskontrol

Blok 2. 12 minutter.

## Læringsmål

- Bruge sortering, filtrering og betinget formatering til at se fejl efter indtastning.
- Lægge en tilladt liste på en ny kolonne med datavalidering.
- Bruge farver i celleregler til at genfinde en værdi. 

I forrige blok sorterede og filtrerede I for at opdage fejl, der allerede står i filen. Kvalitetskontrol ved indtastning virker den anden vej. Det vil sige, at I begrænser, hvad der kan skrives.

Kildefilen har ingen datavalidering. Det har øvelsesfilen heller ikke, før I selv lægger den på.

De gruppenavne, der faktisk bruges som sidste led, er Karplanter, Svampe, Mosser, Alger, Laver og Slimsvampe.

## Øvelse

Arbejdet foregår på *Tavler*. *Gruppenavn* og *Hæfte nr* står allerede i de to kolonner til højre for *Hæfte*.

Skriv overskriften *Tilladte grupper* i celle J1. Skriv de seks navne under hinanden i J2 til J7, ét navn pr. celle: Karplanter, Svampe, Mosser, Alger, Laver, Slimsvampe.

Skriv overskriften *Gruppe* i celle H1. Markér H2 til H41. Vælg Data, Datavalidering. Under Tillad vælger I Liste. I Kilde markerer I J2:J7. Tryk OK.

Prøv listen på to rækker. På *floradanica_0001.tif* kan I vælge Karplanter. På *floradanica_0472.tif* kan I vælge Laver. Skriv derefter *Lave* i en celle i *Gruppe*. Listen afviser stavemåden, fordi den tilladte værdi er *Laver*.

*floradanica_2517.tif* har både *Alger* og *Lave*. De to navne kan ikke stå i én celle i *Gruppe*, hvis I holder reglen om én værdi pr. celle. Lad rækken være. Det når I ikke i dag.

Markér titlerne fra H2 og ned. Vælg Hjem, Betinget formatering, Fremhæv celleregler, Lig med. Skriv f.eks. Karplanter, og vælg en farve.

Vælg igen Fremhæv celleregler, Tekst, der indeholder. Skriv f.eks. Mosser, og vælg en anden farve.

Lad kolonne J stå uden for sorteringen.

[Klik her, og se kort vejledning om datavalidering](https://support.microsoft.com/en-us/excel/get-started/apply-data-validation-to-cells).

## Forslag til resultat

*Gruppe* har en rulleliste med de seks navne. *Lave* kan ikke indtastes.

På *floradanica_0001.tif* står *Karplanter* i *Gruppe*. Cellen får den røde farve fra reglen Lig med, fordi værdien er præcis *Karplanter*.

[Oversigt](index.md) | [Næste: Eksport af data](05-eksport-af-data.md)
