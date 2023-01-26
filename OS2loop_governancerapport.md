# OS2loop - Governancerapport 

Dette dokument giver indsigt i hvordan produktet OS2loop lever op til kravene i OS2's governance-model.

OS2loop har en målsætning om at efterleve: **Niveau 2.** 

> Har du spørgsmål? [Kontakt OS2's sekretariat](https://os2.eu/kontakt), vi er her for at hjælpe.

> Information om OS2's produktniveauer og baggrunden herfor kan der [læses mere om her](https://os2.eu/side/governance).

## RELEVANS

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| [x]  | R1 | Løsingen skaber lokal værdi | Henvisning til hjemmeside: [https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop) | 0 |
| [x] | R2 | Løsningen skaber potentiel værdi for andre | Henvisning hjemmeside:[https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop)| 1 |
| [x] | R3 | Løsningen er accepteret af lokal linjeledelse | Løsningen anvendes i dag som forretningskritisk værktøj i Aarhus kommune, og er ved at blive implementeret i Ballerup Kommune.Se mere om anvendelse i case-video fra Aarhus kommune [her](https://os2.eu/produkt/os2loop)| 2 |
| [x] | R4 | Løsningen har tværkommunalt potentiale | Loop anvendes i dag til at understøtte videndeling på en række OS2-produkter bl.a. OS2kitos og OS2iot, og sikrer at brugerne altid har en nem adgang til at finde viden og kan søge hjælp, hvis den viden ikke allerede findes i løsningen. OS2loop har et oplagt tværkommunalt potentiale, ved at kunne understøtte videndeling på tværs.| 2 |
| [] | R5 | Ophæng til nationale strategier er til stede. | Ikke relevant pt. | 3 |

## FORMKRAV

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| [x] | F1 | Kildekoden deles | https://github.com/os2loop | 0 |
| [x] | F2 | Open Source licenskriterier overholdes | Overholder [GNU General Public License v2.0](https://github.com/os2loop/os2loop/blob/main/LICENSE.txt) | 0 |
| [x] | F3 | Udbudsregler og alm. lovformidling er overholdt. | Ikke aktuel | 0 |
| [x] | F4 | Der er tænkt på sikkerheden i løsningen. | Drupal og tilhørende contrib-moduler er løbende blevet sikkerhedsopdateret under udviklingsfasen og dette vil fortsætte efter idriftsættelsen. Se evt. [eksempel på dette](https://github.com/os2loop/os2loop/commit/e548458ee00c064670f9cb82a8b3685256bc9993) eller tjek projektets composer-log fil. | 0 |
| [x] | F5 | Løsningens formål og værdi er beskrevet | Se mere her [https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop)| 0 |
| [x] | F6 | Kildekoden er placeret på OS2´s github | https://github.com/os2loop | 1 |
| [] | F7 | Driftskrav til løsningen er dokumenteret | Er ikke dokumenteret. | 1 |
| [x] | F8 | Løsningen er dokumenteret på teknisk niveau | [Se dokumentation](https://github.com/os2loop/os2loop/blob/main/README.md) | 1 |
| [x] | F9 | Teknisk implementering af løsningen er dokumenteret | [Se dokumentation](https://github.com/os2loop/os2loop/blob/main/README.md#installation)| 1 |
| [x] | F10 | OS2´s kommunikationskanaler anvendes (0S2.eu) | OS2loop har en produktside på OS2.eu [https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop)| 1 |
| [x] | F11 | OS2´s værktøjer benyttes (Jira) | [OS2loops Jira](https://os2web.atlassian.net/jira/software/c/projects/LOOP/boards/26) | 1 |
| [x] | F12 | Der er kun en version af core koden (Master) | Der er kun en version af core koden: https://github.com/os2loop/os2loop | 2 |
| [x] | F13 | Der er udarbejdet kommunikationsmateriale til strategisk niveau | Henvisning til kommende artikel ifbm lancering. Derudover [https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop) Link til power point præsentation. | 2 |
| [x] | F14 | Der er udarbejdet præsentationsmateriale | Præsentationsvideo med tutorial. [https://os2.eu/produkt/os2loop](https://os2.eu/produkt/os2loop) | 2 |
| [x] | F15 | Best practice for implementering | Se "Anbefalinger til organisatorisk implementering" samt Hyppige spørgsmål og svar ifbm. implementering | 2 |
| [x] | F16 | Teknisk dokumentation indeholder best practice for kodestandarder | [Se dokumentation](https://github.com/os2loop/os2loop/blob/main/README.md#coding-standards) | 2 |
| [] | F17 | Drifts og vedligeholdelses setup er beskrevet. | Er ikke beskrevet.| 2 |
| [] | F18 | Rammearkitekturen og standarder er fulgt og /eller afvigelser er forklaret. | Nej, dette har vi ikke forholdt os til – andet end at det ikke har været relevant for os at anvende evt. komponenter fra rammearkitekturen. | 2 |
| [x] | F19 | Løsningen er leveret i et containerformat fx docker. | Projektet er udviklet i et Docker-compose-miljø. Projektet har desuden dannet grundlag for et reelt [Docker-miljø](https://github.com/os2loop/os2loop/pkgs/container/os2loop), der anvendes af Ballerup Kommune. | 2 |
| [x] | F20 | Uddannelsesmateriale er udarbejdet | Se materiale på os2.eu. | 2 |
| [] | F21 | Politisk kommunikation er udarbejdet (lokal+omverden). | Ikke relevant pt. | 3 |
| [] | F22 | Procesplan og procesansvar for driftsimplementering er udarbejdet. | Ikke relevant pt. | 3 |

## STRATEGISK SAMMENHÆNG

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| [x] | S1 | Produktet har en kobling til OS2´s strategi | Loop kobler sig til OS2´s mission ved at være en relevant digital løsning, der styrker opgaveløsningen ved at gøre det nemt og hurtigt for medarbejderne at drage nytte af og dele viden spredt over hele organisationen. Med den opgraderede version af Loop er bl.a. kvaliteten af løsningen styrket, nye funktionaliteter tilføjet og det modulære udgangspunkt i opgraderingen gør, at det er lettere at konfigurere Loop ift. lokale behov. Link til [vedtægter](https://github.com/OS2offdig/about/blob/main/BYLAWS.md#-3-f%C3%A6llesskabets-filosofi-licensformer-og-form%C3%A5l)| 1 |
| [x] | S2 | Løsningen understøtter innovation og Open Source. | OS2Loop understøtter Innovation og Open Source ved at være 100% Open Source, og ved at gøre det muligt at samle viden ét sted gennem en intuitiv løsning til at organisere og dele viden.| 1 |
| [x] | S3 | Produktets (forventlige) kobling til OS2`s vision og strategi er beskrevet. | Se henvisning under S1. | 2 |
| [] | S4 | Produktets kobling til og overensstemmelse med OS2´s vision og strategi er tilstede og beskrevet. | Ikke relevant pt. | 3 |

## GOVERNANCE

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| [x] | G1 | Produktet er oprettet i OS2´s porteføljestyring | https://os2.eu/produkter | 1 |
| [x] | G2 | Der koordineres løbende med OS2-sekretariatet | Ja. | 1 |
| [x] | G3 | Der er udpeget en projektleder/tovholder | Tovholderfunktion ligger pt. hos Lasse Skjalm, Aarhus kommune og Martin Nygaard, Ballerup Kommune | 1 |
| [] | G4 | Bestyrelsen er orienteret | Afventer møde i bestyrelsen primo februar | 1 |
| [] | G5 | Bestyrelsen har godkendt produktet | Afventer møde i bestyrelsen primo februar | 2 |
| [x] | G6 | Der er nedsat en styregruppe | Styregruppen består pt af Jens Kjellerup, Ballerup Kommune og Poul Martin Christensen, Aarhus Kommune| 2 |
| [x] | G7 | Der er nedsat en koordinationsgruppe | Koordinationsgruppen består pt. af Lasse Skjalm, Århus kommune og Martin Nygaard, Ballerup Kommune| 2 |
| [x] | G8 | En projektmodel anvendes og er dokumenteret | Projektet anvender en agil tilgang til udvikling, der dokumenteres via Jira. | 2 |
| [x] | G9 | Review af koden foretages af tredjepart | Kodereview er foretaget af Reload A/S | 2 |
| [x] | G10 | Der er udarbejdet en tilslutningserklæring til sikring af økonomi | Se hensigtserklæring. | 2 |
| [] | G11 | Bestyrelsen har godkendt styregruppen | Ikke relevant pt. | 3 |
| [x] | G12 | Bestyrelsen er repræsenteret i styregruppen | Ja, ved Jens Kjellerup, Ballerup Kommune. | 3 |
| [] | G13 | Der foreligger en aftale der sikrer økonomi til koordinering og videreudvikling | Ikke relevant pt. | 3 |
| [] | G14 | Der etableres et fagligt fællesskab bag løsningen hvor erfaringer udveksles. | Ikke relevant pt. | 3 |

## LOG

| Dato | Handling | Udført af |
| --- | --- |--- |
| 2021-12-07 | Rapport oprettet | Martin Nygaard |
| 2023-01-26 | Rapport omformateret til Markdown og lagt på Github | Rasmus Frey, OS2-sekretariatet |