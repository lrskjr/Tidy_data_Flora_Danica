# Formatér data

Blok 1. 22 minutter.

## Læringsmål

I afsnittene *Én variabel pr. kolonne*, *Én observation pr. række* og *Én værdi pr. celle*:

- Bruge Wickhams tre regler på felter i øvelsesfilen.
- Kig på begge ark. Både på *Tavler* og på *Noter*.
- Se, når én celle rummer flere værdier.

I afsnittet *Øvelse*:

- Omskrive én tavle, så hver figur får sin egen række.
- Lægge latinsk navn, dansk navn og familie i hver sin kolonne.

Reglerne er Wickhams (2014): én variabel pr. kolonne, én observation pr. række, én værdi pr. celle. En variabel er en egenskab. En observation er den enhed, rækken handler om.

## Én variabel pr. kolonne

*Note* på *floradanica_0001.tif* blander hæfte, tabelnummer, figur, latinsk navn, dansk slægtsnavn og familie i samme celle. På *floradanica_0008.tif* er titlen *Pyrola uniflora L.*, mens notens latinske navn er *Moneses uniflora (L.) A.Gray*. Samme note har også dansk artsepitet, familienavn og en synonymliste. Noterne har altså ikke de samme linjer fra tavle til tavle.

*Ophav* blander navn, rolle og levetid, og det gør det seks gange i samme celle.

*Taxonomisk gruppe* er en sti med kolon. På *floradanica_0001.tif* begynder den *Digitale Samlinger: Digitale Samlinger:* og ender på *Karplanter*. På *floradanica_0472.tif* begynder den *Digitale Samlinger: Billeder:* og ender på *Laver*. Flere led ligger i én celle. Nogle rækker har også to grupper sat sammen med +.

*Record Name* er én oplysning: filnavnet. Den kolonne kan I beholde, så en ny række stadig peger på billedet.

## Én observation pr. række

Kildefilen har én række pr. billedfil. *floradanica_0472.tif* har fire figurer i noten. Hvis observationen er figuren, skal hver figur have sin egen række, og *Record Name* gentages, så billedfilen stadig kan findes.

## Én værdi pr. celle

Titlen på *floradanica_0472.tif* er:

*Lichen ventosus L. / L. ventosus var.? Oed. / L. leprosus etc. Oed. / L. ericetorum Oed.*

Det er fire navne i én celle. *floradanica_0018.tif* har også skråstreg i titlen. I kildefilen har 625 titler en skråstreg. I øvelsen tager I kun tavlen floradanica_0472.tif. Grund til at der er fire navne i cellen er, at der på den tavle, som det handler om, er fire forskellige planter. Se billedet nedenfor.

:::{figure} images/floradanica_0472_1803x2778.jpg
:width: 320px
:alt: Flora Danica, tavle CCCCLXXII, fire figurer

Flora Danica, tavle 472. Fire figurer på samme tavle.
:::


## Øvelse

Lav et nyt ark i kopien af øvelsesfilen. Kald det Figurer. Ret ikke i arkene Tavler og Noter. Benyt kun floradanica_0472.tif.

Skriv kolonnenavnene i første række på Figurer:

- *Record Name*
- *Figur*
- *Navn i titel*
- *Latinsk navn*
- *Dansk navn*
- *Familie*
- *Lange nomenklator*

Lav fire rækker under overskriften, én pr. figur. Kopiér værdierne. Skriv dem ikke om.

Kopiér Record Name fra Tavler. Det er floradanica_0472.tif på alle fire rækker. Skriv 1, 2, 3 og 4 iunder Figur.

Kopiér titlen fra Tavler. Del den ved hver skråstreg, og læg ét navn i *Navn i titel* på hver række. Behold rækkefølgen fra cellen. Noten siger ikke, hvilket navn der hører til hvilken figur. I vælger en rækkefølge og holder den.

Kopiér fra kolonnen Note på arket Noter. Under hver figur står Latinsk navn: efterfulgt af en bindestreg. Kopiér bindestregen over i Latinsk navn. Det navn, I kan læse, står ved Lange nomenklator. Kopiér den linje over i Lange nomenklator, ét navn pr. række. Bemærk at et af navnene ender med ??.

*Latinsk navn*, *Dansk navn* og *Familie* skal optræde som kolonner, også hvor noten ikke har en værdi, fordi en tom celle er et resultat, der viser, at oplysningen mangler. I Broman, Karl W., and Kara H. Woo. “Data Organization in Spreadsheets” findes et afsnit om for og imod tomme celler i en datatabel, som er værd at orientere sig i, fordi der eksisterer ikke enighed om, hvordan man skal forholde sig til manglende data. 

År må gerne med som en ekstra kolonne. Kopiér 1769 fra Tavler over på alle fire rækker.

## Forslag til resultat

Fire rækker. *Record Name* er *floradanica_0472.tif* på dem alle.

Figur 1. *Navn i titel:* Lichen ventosus L. *Lange nomenklator:* Haematomma coccineum &#91;alfa&#93;, ochroleucum Th&#46;Fr.

Figur 2. *Navn i titel:* L. ventosus var.? Oed. *Lange nomenklator:* Galoplaca ferruginea &#91;beta&#93;, festiva Th&#46;Fr.

Figur 3. *Navn i titel:* L. leprosus etc. Oed. *Lange nomenklator:* Lecidea lapicida (Ach.) Fr.??

Figur 4. *Navn i titel:* L. ericetorum Oed. *Lange nomenklator:* Icmadophila aeruginosa Trev. (Lecidea icmadophila Ach.).

[Oversigt](index.md) | [Næste: Datoer og ophav](03-datoer-og-ophav.md)
