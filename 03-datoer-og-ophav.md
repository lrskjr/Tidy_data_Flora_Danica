# Datoer og ophav

Blok 2. 12 minutter.

## Læringsmål

- Se, at *År* er tekst, og at værdien er hæftets år.
- Se, at *Ophav* er ens, fordi udgiverne er samlet i ét felt.
- Bruge et fødselsår til at udelukke en person som udgiver af tavlen fra 1761.
- Tage én botaniker ud af *Ophav* og lægge navn, fødselsdato og dødsdato i tre celler.
- Vide, at en dato før 1900 ikke kan gemmes som Excel-dato.

## År i Excel-arket

På *Tavler* er *År* for *floradanica_0001.tif* værdien *1761*. Hvert hæfte har ét år. I kildefilen er det tidligste år 1761, og det seneste er 1883.

Værdien er gemt som tekst. I kan se at værdien er tekst, hvis I markerer cellen.

## Hvad Excel gør med en dato

I *Ophav* står den første person sådan:

Hornemann, Jens Wilken (6.3.1770-30.7.1841) botaniker

Det er navn, datointerval og en rolle som botaniker. Formen 6.3.1770 er dag.måned.år, altså 6. marts 1770. 30.7.1841 er 30. juli 1841. De fem andre personer har samme form. Alle har levet 1900, og datointervalerne er skrevet med punktum.

Excel behandler en dato ved at gemme den som et serienummer. Serienummeret er et heltal, der tæller dage efter 1. januar 1900. Da datooplysningerne om "vores" ophavspersoner er før 1900, mangler der et serienummer under teksten *30.7.1841*, og formatet har på den måde ikke noget at ændre.

Hornemanns datoer kan blive stående som tekst, fordi de er før 1900, eller de kan deles i år, måned og dag som almindelige tal.

Broman og Woo anbefaler i Data Organisation in Spreadsheets, at år, måned og dag får hver sin kolonne, fordi på den måde kan værdien ikke skifte udseende, når filen åbnes et andet sted. Anbefalingen er værd at overveje, når I i Excel arbejder med datoer efter 1900.

## Ophav blander tre ting

*Ophav* er ens på alle rækker. På *floradanica_0001.tif* og *floradanica_2491.tif* står de samme seks personer: Hornemann, Lange, Liebmann, Müller, Oeder og Vahl. Hver linje har navn, datainterval, som er levetid, samt ordet botaniker.

Kildefilen stammer fra et dataudtræk fra Det Kgl. Biblioteks [Digitale Samlinger](https://digitalesamlinger.kb.dk/images/billed/2010/okt/billeder/subject5449/da/?notAfter=&notBefore=&search_field=all_fields). Oplysningerne er migreret fra en ældre hjemmeside, som er nedlagt. En del af siden ligger på Internet Archive: [Flora Danica Udgiverne](https://web.archive.org/web/20070715000908/http://www2.kb.dk/udstillinger/floradanica/floradanica/editorer/oversigt.html). Der kan vi læse, at Oeder har udgivet tavle 1-60, og Liebmann har udgivet tavle 2461-2520.

I migrationen er udgiverne samlet i feltet *Ophav*, og feltet er gentaget på hver billedfil. Relationen mellem hæfte og udgiver er på den måde forsvundet i migrationen.

Tavlenummeret står i *Record Name*. *floradanica_0001.tif* er tavle 1. Fra oplysningerne i Internet Archive ved vi dog, at Oeder har udgivet tavle 1-60, så selvom *Ophav* ikke nævner det, kan vi rekonstruere udgiveren ud fra tavlenummeret og data fra Internet Archive.

## Øvelse

*Hvad Excel gør med en dato*

Indtast f.eks. 1970-06-03 i en celle i en tom kolonne. I vil se, at tallet bliver højrestillet, og at formatet automatisk ændres til Dato, fordi Excel genkender værdien som en dato. Ændrer I formatet til Tal, vil I se, at værdien ændrer sig til 25722, som er serienummeret. 

*Ophav blander tre ting*

På *Noter*: sammenlign *Ophav* på *floradanica_0001.tif* og *floradanica_2491.tif*. De seks personer er de samme. Feltet nævner ikke, hvem der har udgivet tavlen.

Læs tavlenummeret i *Record Name*. *floradanica_0001.tif* er tavle 1. *floradanica_2491.tif* er tavle 2491.

På Noter: rekonstruer udgiveren i den første tomme celle til højre for Lokalitet, på rækken for floradanica_0001.tif og på rækken for floradanica_2491.tif. Brug [Flora Danica Udgiverne](https://web.archive.org/web/20070715000908/http://www2.kb.dk/udstillinger/floradanica/floradanica/editorer/oversigt.html). Oeder har udgivet tavle 1-60. Liebmann har udgivet tavle 2461-2520. Lad Ophav blive stående. Den nye celle er udgiveren, som I finder ved at sammenholde tavlenummeret med oplysningerne fra Internet Archive.

Tag én person ud af *Ophav* på *floradanica_0001.tif*. Læg navn, fødselsdato og dødsdato i tre celler ved siden af tabellen eller på et nyt ark. Én person, ikke alle seks. Lad datoerne blive tekst. Ordet botaniker er rollen og skal ikke ind i navnet.

## Forslag til resultat

Serienummeret for 1970-06-03 er 25722. Det er 3. juni 1970.

*floradanica_0001.tif* er tavle 1. Udgiveren er Oeder, fordi han har udgivet tavle 1-60. *floradanica_2491.tif* er tavle 2491. Udgiveren er Liebmann, fordi han har udgivet tavle 2461-2520. *Ophav* er den samme celle på begge rækker.

Forslaget tager den første person i cellen.

- Hornemann, Jens Wilken. Fødselsdato 6.3.1770. Dødsdato 30.7.1841.
- Lange, Johan Martin Christian. 20.3.1818 og 3.4.1898.
- Liebmann, Frederik Michael. 10.10.1813 og 29.10.1856.
- Müller, Otto Frederik. 2.3.1730 og 26.12.1784.
- Oeder, Georg Christian. 3.2.1728 og 28.1.1791.
- Vahl, Martin. 7.10.1749 og 24.12.1804.

Tre celler er nok til øvelsen. Følger I Broman og Woos anbefalinger hele vejen for Hornemann, bliver 6.3.1770 til fødselsår 1770, fødselsmåned 3 og fødselsdag 6, stadig som tal, ikke som Excel-dato.

[Oversigt](index.md) | [Næste: Kvalitetskontrol](04-kvalitetskontrol.md)
