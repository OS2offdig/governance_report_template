# GUIDE til Governance Report

> Dette er OS2s checkliste der skal benyttes til at belyse niveauet af et OS2 produkt. Er du projektleder, koordinator eller på anden måde ansvarlig for et OS2 produkt? Så lav en kopi af denne fil og navngiv den efter produktet. F.eks. __OS2produkt_governance_report.md__ Derefter udfylder du checklisten og publisere den til det relevante repository på Github.
>
> Du udfylder checklisten ved at anvende en af de følgende markeringer, under  🔽 kolonnen:
>
> ✅ - Kriteriet er opfyldt
>
> ❌ - Kriteriet er IKKE opfyldt
> 
> ➖ - Kriteriet er ikke relevant for dette produkt
> 
> ❓ - Der er tvivl om hvordan dette kriterie evalueres
>
> Hvis feltet efterlades tomt, betragtes evalueringen som ikke færdiggjort.
>
> Har du spørgsmål? [Kontakt OS2s sekretariat](https://os2.eu/kontakt), vi er her for at hjælpe.
>
> Information om OS2s produktniveauer og baggrunden herfor kan der [læses mere om her](https://governance.os2.eu).

# INDSÆT NAVNET PÅ PRODUKTET

Denne checkliste belyser efterlevelsen af OS2s niveaukrav for produktet.

## RELEVANS

| 🔽  | #   | Krav                                          | Beskrivelse / Dokumentation | Produktniveau | Retningslinjer                                                                                                        |
| --- | --- | --------------------------------------------- | ----------------------------| --------------| ----------------------------------------------------------------------------------------------------------------------|
|     | R1  | Løsningen skaber lokal værdi                  |                             | sandkasse     | Beskriv den konkrete værdi løsningen skaber i organisationen. F.eks. økonomisk, organisatorisk eller brugerrelateret. |
|     | R2  | Løsningen er accepteret af lokal linjeledelse |                             | 2             | Beskriv eller henvis til en formel accept fra ledelse hos initiativtagerne til løsningen.                             |
|     | R3  | Løsningen har fælles offentligt potentiale    |                             | 2             | Redegør for hvordan løsningen kan bruges på tværs af kommuner og/eller offentlige myndigheder.                        |
|     | R4  | Ophæng til nationale strategier er til stede  |                             | 3             | Henvis til relevante strategier og forklar hvordan løsningen understøtter disse.                                      |


## FORMKRAV

| 🔽  | #   | Krav                                          | Beskrivelse / Dokumentation | Produktniveau | Retningslinjer                                                                                                        |
| --- | --- | --------------------------------------------- | ----------------------------| --------------| ----------------------------------------------------------------------------------------------------------------------|
|     | F1  | Alt kildekode til projektet udvikles synligt og aktivt i et repositorie og versionskontrolsystem, anvist af OS2 |      | sandkasse | Upload al kildekode i et offentligt OS2 GitHub repository med aktiv versionshistorik. |
|     | F2  | Open Source licenskriterier overholdes                                                                          |      | sandkasse | Angiv hvilken OSI-godkendt licens projektet bruger. OS2 standard er MPL 2.0 |
|     | F3  | Udbudsregler og alm. lovformlighed er overholdt                                                                 |      | sandkasse | Bekræft at udbudspligt er overholdt eller redegør for undtagelse. Vedlæg evt. beslutningsnotat.|
|     | F4  | Der er tænkt på sikkerheden i løsningen                                                                         |      | sandkasse | Beskriv hvordan sikkerhed er indtænkt i design, kode og drift – f.eks. kryptering, adgangsstyring. |
|     | F5  | Løsningens formål og værdi er beskrevet                                                                         |      | sandkasse | Henvis til dokumentation (f.eks. README) hvor formål og målgruppe fremgår.    |
|     | F6  | Kildekoden er overdraget og er placeret under OS2's github                                                      |      | 1         | Bekræft og link til den officielle OS2 GitHub repository.                     |
|     | F7  | Alt dokumentation til projektet udarbejdes med og overholder OS2s standardskabelon for dokumentation.           |      | 1         | Brug OS2’s standard template til dokumentation. [Documentation template for OS2 projects](http://github.com/OS2offdig/os2-docs-template) |
|     | F10 | OS2's kommunikationskanaler anvendes (OS2.eu)                                                                   |      | 1         | Bekræft og link til omtale på f.eks. os2.eu, nyhedsbrev eller andet. |
|     | F11 | Der anvendes offentlig issue-tracking anvist af OS2, hvor der tydeligt henvises til specifikke kodeændringer    |      | 1         | Henvis til f.eks. GitHub Issues, hvor opgaver er koblet til pull-requests/commits. |
|     | F12 | Der er kun en version af core koden                                                                             |      | 2         | Bekræft at der kun findes én ‘main’ version og at den er aktivt vedligeholdt. |
|     | F13 | Der er udarbejdet præsentationsmateriale af løsningen                                                           |      | 2         | Link til f.eks. slides, brochurer eller andet introduktionsmateriale. |
|     | F14 | Der er udarbejdet kommunikationsmateriale til strategisk niveau                                                 |      | 2         | F.eks. businesscase, one-pager til direktionsniveau og præsentation til udvalg. |
|     | F15 | Best practice for implementering i organisationen dokumenteres                                                  |      | 2         | Angiv implementeringsvejledning, erfaringsopsamling eller cases.                                  |
|     | F16 | Teknisk dokumentation indeholder best practice for kodestandarder i forhold til de anvendte teknologier         |      | 2         | Beskriv Hvilke kodestandarder projektet følger. Evt. med links til eksterne guides og supplerende retningslinjer. |
|     | F17 | Drifts og vedligeholdelses setup er beskrevet                                                                   |      | 2         | Redegør for driftspartner(e), ansvar og finansiering. Hvem drifter, hvem vedligeholder og hvem koordinere. Beskriv også Hvordan kører løsningen? (on-prem, cloud, container, SaaS). Hvilke komponenter indgår? (fx databaser, API’er, microservices). Hvilke værktøjer bruges til monitorering, deployment og backup. |
|     | F18 | Rammearkitekturen og standarder er fulgt og afvigelser er forklaret                                             |      | 2         | Beskriv om/hvordan løsningen følger fællesoffentlig rammearkitektur – eller forklar hvorfor ikke. |
|     | F19 | Løsningen er leveret i et containerformat f.eks. docker (anbefaling)                                            |      | 2         | Angiv om løsningen tilbydes i en containeriseret version som definerer hvordan applikationen bygges og køres. |
|     | F20 | Uddannelsesmateriale er udarbejdet (anbefaling)                                                                 |      | 2         | Henvis til manual, brugervejledning eller andet brugerrelateret materiale. |
|     | F21 | Politisk kommunikation er udarbejdet (Lokal + Omverden)                                                         |      | 3         | Angiv indhold der kan bruges i politiske fora – f.eks. beslutningsoplæg eller pressemeddelelse. |
|     | F22 | Procesplan + procesansvar for driftsimplementering er udarbejdet                                                |      | 3         | Tilføj en implementeringsplan med ‘hvem gør hvad hvornår’. |

## STRATEGISK SAMMENHÆNG

| 🔽  | #   | Krav                                                                                             | Beskrivelse / Dokumentation | Produktniveau | Retningslinjer                                                          |
| --- | --- | ------------------------------------------------------------------------------------------------ | ---------- | ------ | ---------------------------------------------------------------------------------- |
|     | S1  | Produktet har en kobling til OS2's strategi                                                      | Hvordan?   | 1      | Beskriv hvordan produktet understøtter fx digitalisering, deling eller fællesskab. |
|     | S2  | Løsningen understøtter innovation og open source                                                 | Hvordan?   | 1      | Angiv hvordan open source-værdier og nyskabelse er tænkt ind.                      |
|     | S3  | Produktets (forventlige) kobling til OS2's mission, vision og strategi er beskrevet              | Hvor?      | 2      | Link til dokument hvor dette er uddybet.                                           |
|     | S4  | Der er udarbejdet en vision og strategi for produktet                                            | Hvor?      | 2      | Link til dokument med produktvision og strategiske mål.                            |
|     | S5  | Produktets kobling til og overensstemmelse med OS2's vision og strategi er tilstede og beskrevet | Hvordan?   | 3      | Forklar hvordan løsningen passer ind i OS2’s overordnede formål og værdisæt.       |

## GOVERNANCE

| 🔽  | #   | Krav                                                                               | Beskrivelse / Dokumentation       | Produktniveau | Retningslinjer                                           |
| --- | --- | ---------------------------------------------------------------------------------- | ------------------------------------------------- | ------------- | --------------------------------------------------------------------- |
|     | G1  | Produktet er oprettet i OS2's porteføljestyring                       | Indsæt link                                       | 1             | Produktet er oprettet på OS2s hjemmeside og indgår i årshjul. Dette koordineres med sekretariatet i OS2.                            |
|     | G2  | Der koordineres løbende med OS2-sekretariatet                                      |                                                   | 1             | Bekræft, evt. med årshjul/datoer/mails for koordinering.                      |
|     | G3  | Der er udpeget en projektleder/tovholder                                           | Hvem? evt. link til beskrivelse af ansvar/opgaver | 1             | Navngiv og link evt. til beskrivelse af rolle og opgaver.             |
|     | G4  | Bestyrelsen er orienteret                                                          | fx link til referat                               | 1             | Link til mødereferat eller beslutning.                                |
|     | G5  | Bestyrelsen har godkendt produktet                                                 | fx link til referat                               | 2             | Vedlæg dokumentation for godkendelse.                                 |
|     | G6  | Der er nedsat en styregruppe                                                       | Link til kommissorium                             | 2             | Link til eller beskrivelse af styregruppen.                           |
|     | G7  | Der er nedsat en koordinationsgruppe (anbefaling)                                  | Link til kommissorium                             | 2             | Link eller beskrivelse af koordinationsgruppen.                       |
|     | G8  | En projektmodel anvendes og er dokumenteret (anbefaling)                           | Hvor?                                             | 2             | Link til brugt projektmodel eller metode.                             |
|     | G9  | Review af kode foretages af tredjepart (anbefaling)                                |                                                   | 2             | Angiv hvilken ekstern part har udført review og hvad der blev fundet. |
|     | G10 | Der er udarbejdet en tilslutningserklæring til sikring af økonomi (anbefaling)     | Hvor?                                             | 2             | Vedlæg eller henvis til dokument for tilslutning og økonomi.          |
|     | G11 | Bestyrelsen har godkendt styregruppen                                              | fx link til referat                               | 3             | Link til beslutning eller protokol.                                   |
|     | G12 | Bestyrelsen er repræsenteret i styregruppen                                        | fx link til referat                               | 3             | Angiv hvilket medlem deltager på vegne af bestyrelsen.                |
|     | G13 | Der foreligger en aftale der sikrer økonomi til koordinering og videreudvikling    | Link til aftale                                   | 3             | Indsæt eller beskriv finansieringsaftalen.                            |
|     | G14 | Der er etableret et fagligt fællesskab bag løsningen hvor erfaringer kan udveksles | Henvisning til en faggruppe eller et forum        | 3             | Henvis til fx brugerforum, teamsgruppe eller fysisk netværk.          |
