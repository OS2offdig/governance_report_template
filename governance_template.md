# INDSÆT NAVNET PÅ PRODUKTET

Dette er OS2's governance checkliste der skal benyttes til at belyse niveauet af et OS2 produkt. Er du projektleder, koordinator eller på anden måde ansvarlig for et OS2 produkt? Så lav en kopi af denne fil og navngiv den efter produktet. Derefter udfylder du checklisten, sender den til OS2-sekretariatet eller uploader den til det relevante repository på Github.

Du udfylder checklisten ved at anvende en af de følgende markeringer, under  🔽 kolonnen:

✅ - Kriteriet er opfyldt

❌ - Kriteriet er IKKE opfyldt

➖ - Kriteriet er ikke relevant for dette produkt

❓ - Der er tvivl om hvordan dette kriterie evalueres

Hvis feltet efterlades tomt, betragtes evalueringen som ikke færdiggjort.

> Har du spørgsmål? [Kontakt OS2&#39;s sekretariat](https://os2.eu/kontakt), vi er her for at hjælpe.

> Information om OS2's produktniveauer og baggrunden herfor kan der [læses mere om her](https://governance.os2.eu).

## RELEVANS

| 🔽 | #  | Krav                                                     | Henvisning                | Niveau    |
| -- | -- | -------------------------------------------------------- | ------------------------- | --------- |
|    | R1 | Løsningen skaber lokal værdi                           | Hvordan?                  | sandkasse |
|    | R2 | Løsningen er accepteret af lokal linjeledelse           | fx tilslutningserklæring | 2         |
|    | R3 | Løsningen har fælles offentligt potentiale | Hvordan?                  | 2         |
|    | R4 | Ophæng til nationale strategier er til stede            | Hvordan/hvilke?           | 3         |

## FORMKRAV

|  | #   | Krav                                                                                                                                            | Henvisning                                                          | Niveau    |
| - | --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | --------- |
|  | F1  | Alt kildekode til projektet udvikles synligt og aktivt i et repositorie og versionskontrolsystem, anvist af Os2                                 | Indsæt link                                                        | sandkasse |
|  | F2  | Open Source licenskriterier overholdes                                                                                                          | Indsæt vedtaget licens                                             | sandkasse |
|  | F3  | Udbudsregler og alm. lovformlighed er overholdt                                                                                                 | Kan udfyldes                                                        | sandkasse |
|  | F4  | Der er tænkt på sikkerheden i løsningen                                                                                                      | Hvordan?                                                            | sandkasse |
|  | F5  | Løsningens formål og værdi er beskrevet                                                                                                      | Hvor?                                                               | sandkasse |
|  | F6  | Kildekoden er overdraget og er placeret under OS2's github                                                                                      | Indsæt link                                                        | 1         |
|  | F7  | Alt dokumentation til projektet udarbejdes med og overholder OS2s standardskabelon for dokumentation.                                                                                                       | [Documentation template for OS2 projects](http://github.com/OS2offdig/os2-docs-template)                                    
|  | F10 | OS2's kommunikationskanaler anvendes (OS2.eu)                                                                                                   | Indsæt link(s)                                                     | 1         |
|  | F11 | Der anvendes offentlig issue-tracking anvist af OS2, hvor der tydeligt henvises til specifikke kodeændringer                                   | Indsæt link(s)                                                     | 1         |
|  | F12 | Der er kun en version af core koden (Master)                                                                                                    |                                                                     | 2         |
|  | F13 | Der er udarbejdet præsentationsmateriale af løsningen                                                                                         | Hvor?                                                               | 2         |
|  | F14 | Der er udarbejdet kommunikationsmateriale til strategisk niveau                                                                                 | Hvor?                                                               | 2         |
|  | F15 | Best practice for implementering i organisationen dokumenteres                                                                                  | Hvor?                                                               | 2         |
|  | F16 | Teknisk dokumentation indeholder best practice for kodestandarder i forhold til de anvendte teknologier                                         | Hvor?                                                               | 2         |
|  | F17 | Drifts og vedligeholdelses setup er beskrevet                                                                                                   | Hvem drifter løsningen? er der sat økonomi af til vedligholdelse? | 2         |
|  | F18 | Rammearkitekturen og standarder er fulgt og afvigelser er forklaret                                                                             |                                                                     | 2         |
|  | F19 | _Løsningen er leveret i et containerformat fx docker (anbefaling)_                                                                           |                                                                     | 2         |
|  | F20 | _Uddanelses materiale er udarbejdet (anbefaling)_                                                                                             | Hvor?                                                               | 2         |
|  | F21 | Politisk kommunikation er udarbejdet (Lokal + Omverden)                                                                                         | Hvor?                                                               | 3         |
|  | F22 | Procesplan + procesansvar for driftsimplementering er udarbejdet ([eksempel](https://os2mo.readthedocs.io/en/development/operation/cookbook.html)) | Hvor?                                                               | 3         |

## STRATEGISK SAMMENHÆNG

|  | #  | Krav                                                                                                                          | Henvisning | Niveau |
| - | -- | ----------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ |
|  | S1 | Produktet har en kobling til [OS2&#39;s strategi](https://www.os2.eu/os2s-vision-og-mission)                                         | Hvordan?   | 1      |
|  | S2 | Løsningen understøtter innovation og open source                                                                            | Hvordan?   | 1      |
|  | S3 | Produktets (forventlige) kobling til [OS2&#39;s mission, vision og strategi](https://www.os2.eu/os2s-vision-og-mission) er beskrevet | Hvor?      | 2      |
|  | S4 | Der er udarbejdet en vision og strategi for produktet                                                                         | Hvor?      | 2      |
|  | S5 | Produktets kobling til og overensstemmelse med OS2's vision og strategi er tilstede og beskrevet                              | Hvordan?   | 3      |

## GOVERNANCE

|  | #   | Krav                                                                                 | Henvisning                                        | Niveau |
| - | --- | ------------------------------------------------------------------------------------ | ------------------------------------------------- | ------ |
|  | G1  | Produktet er oprettet i OS2's porteføljestyring (Hjemmeside)                        | Indsæt link                                      | 1      |
|  | G2  | Der koordineres løbende med OS2-sekretariatet                                       |                                                   | 1      |
|  | G3  | Der er udpeget en projektleder/tovholder                                             | Hvem? evt. link til beskrivelse af ansvar/opgaver | 1      |
|  | G4  | Bestyrelsen er orienteret                                                            | fx link til referat                               | 1      |
|  | G5  | Bestyrelsen har godkendt produktet                                                   | fx link til referat                               | 2      |
|  | G6  | Der er nedsat en styregruppe                                                         | Link til kommissorium                             | 2      |
|  | G7  | _Der er nedsat en koordinationsgruppe (anbefaling)_                                | Link til kommissorium                             | 2      |
|  | G8  | _En projektmodel anvendes og er dokumenteret (anbefaling)_                         | Hvor?                                             | 2      |
|  | G9  | _Review af kode foretages af tredjepart (anbefaling)_                              |                                                   | 2      |
|  | G10 | _Der er udarbejdet en tilslutningserklæring til sikring af økonomi (anbefaling)_ | Hvor?                                             | 2      |
|  | G11 | Bestyrelsen har godkendt styregruppen                                                | fx link til referat                               | 3      |
|  | G12 | Bestyrelsen er repræsenteret i styregruppen                                         | fx link til referat                               | 3      |
|  | G13 | Der foreligger en aftale der sikre økonomi til koordinerg og videreudvikling        | Link til aftale                                   | 3      |
|  | G14 | Der er etableret et fagligt fælleskab bag løsningen hvor erfaringer kan udveksles  | Henvisning til en faggruppe eller et forum        | 3      |
