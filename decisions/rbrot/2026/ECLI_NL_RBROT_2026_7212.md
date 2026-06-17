---
ecli: "ECLI:NL:RBROT:2026:7212"
court: "Rechtbank Rotterdam"
court_code: "RBROT"
docket: "C/10/694803 / HA ZA 25-162"
decided: "2026-06-17"
published: "2026-06-22"
type: "uitspraak"
procedure: "Eerste aanleg - meervoudig"
subject: "Civiel recht; Verbintenissenrecht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:RBROT:2026:7212"
published_in: ["Rechtspraak.nl"]
---

# ECLI:NL:RBROT:2026:7212 Rechtbank Rotterdam , 17-06-2026 / C/10/694803 / HA ZA 25-162

## Inhoudsindicatie

Gedaagde heeft aan eiseres laders voor elektrische auto’s verkocht en geleverd. Eiseres stelt dat gedaagde toerekenbaar is tekortgeschoten in de nakoming van de verbintenissen uit hun overeenkomst. Volgens eiseres verzenden de laders niet altijd alle laadgegevens naar haar systeem, waardoor de laders onbruikbaar zijn voor haar bedrijfsvoering. Gedaagde betwist dat zij tekort schiet. Eiseres vordert nakoming van de ongedaanmakingsverbintenis die is ontstaan door de door eiseres gestelde ontbinding van de overeenkomst, en schadevergoeding. Partijen hebben een verschil van mening over de uitleg van de overeenkomst en over de vraag of de laders van gedaagde zorgen voor het ontbreken van laadgegevens. Wat dit laatste betreft moet eiseres bewijs leveren.

## Uitspraak

RECHTBANK Rotterdam

Team handel en haven

Zaaknummer: C/10/694803 / HA ZA 25-162

Vonnis van 17 juni 2026

in de zaak van

ENECO EMOBILITY B.V.,

gevestigd in Rotterdam,

eisende partij,

hierna te noemen: EeM,

advocaat: mr. D. Becht,

tegen

VESTEL TICARET A.S.,

gevestigd in Istanbul, Turkije,

gedaagde partij,

hierna te noemen: Vestel,

advocaat: mr. A. Rosielle.

1
De zaak in het kort

Vestel heeft aan EeM laders voor elektrische auto’s verkocht en geleverd. EeM stelt zich op het standpunt dat Vestel toerekenbaar is tekortgeschoten in de nakoming van de verbintenissen uit hun overeenkomst. Volgens EeM verzenden de laders niet altijd alle laadgegevens naar haar systeem, waardoor de laders onbruikbaar zijn voor haar bedrijfsvoering. Vestel betwist dat zij tekort schiet. EeM vordert nakoming van de ongedaanmakingsverbintenis die is ontstaan door de door EeM gestelde ontbinding van de overeenkomst, en schadevergoeding. Partijen hebben een verschil van mening over de uitleg van de overeenkomst en over de vraag of de laders van Vestel zorgen voor het ontbreken van laadgegevens. Wat dit laatste betreft moet EeM bewijs leveren.

2
De procedure

2.1.

Het verloop van de procedure blijkt uit:

- de dagvaarding van 11 oktober 2024, met producties 1 tot en met 48;

- de conclusie van antwoord, met producties 1 tot en met 15;

- de brief van 25 juni 2025 van de rechtbank, waarbij een mondelinge behandeling is bepaald;

- de e-mail van 12 november 2025 van de rechtbank met een zittingsagenda voor de mondelinge behandeling;

- de akte aanvulling feiten en overlegging producties met producties 49 tot en met 57;

- de spreekaantekeningen van partijen voor de mondelinge behandeling op 9 december 2025.

2.2.

Ten slotte is vonnis bepaald.

3
De feiten

3.1.

In december 2020 zijn EeM en Vestel een samenwerking aangegaan, waarbij Vestel aan EeM laders voor het opladen van elektrische auto’s heeft verkocht en geleverd. Partijen hebben hiervoor een overeenkomst gesloten die eind januari/begin februari 2021 door hen is ondertekend (hierna: de overeenkomst).

3.2.

In artikel 8.1(b) van de overeenkomst, onder het kopje “Warrenty and conformity” is bepaald:

“The Contractor warrants Eneco, in addition to any other warranties or obligations provided by the Contractor or arising from the law, that all the Goods delivered on the ground of an Agreement will:

(…)

b) be suitable for Eneco’s intended use as agreed in these Terms and Conditions.”

3.3.

In artikel 11.2 van de overeenkomst is, onder meer, bepaald:

“The Contractor shall ensure that the Goods and maintenance and services indicated under Annex 3 of these Terms and Conditions comply at all times with all applicable laws, standards and regulations in force relating to the industry.”

3.4.

In hoofdstuk 3.7 van het OCPP staat:

“3.7. Transaction-related messages

This section is normative.

The Charge Point SHOULD deliver transaction-related messages to the Central System in chronological order as soon as possible. Transaction-related messages are StartTransaction req. StopTransaction.req and periodic or clock-aligned MeterValues.req messages.

When offline, the Charge Point MUST queue any transaction-related messages that it would have sent to the Central System if the Charge Point had been online.

In the event that a Charge Point has transaction-related messages queued to be sent to the Central System, new messages that are not transaction-related MAY be delivered immediately without waiting for the queue to be emptied. It is therefore allowed to send, for example, an Authorize request or a Notifications request before the transaction-related message queue has been emptied, so that customers are not kept waiting and urgent notifications are not delayed.

The delivery of new transaction-related messages SHALL wait until the queue has been emptied. This is to ensure that transaction-related messages are always delivered in chronological order.

When the Central System receives a transaction-related message that was queued on the Charge Point for some time, the Central System will not be aware that this is a historical message, other than by inference given that the various timestamps are significantly in the past. It SHOULD process such a message as any other.”

In navolging van partijen gebruikt de rechtbank ook wel de aanduiding “laadgegevens” voor de “transaction related messages” uit 3.7 van het OCCP.

3.5.

In artikel 16.6 van de overeenkomst staat:

“Notwithstanding anything to the contrary in any clause of the Terms and Conditions, Assignment or order, under no circumstances shall the Contractor be liable to Eneco for any indirect, incidental, consequential or special damages, losses, as well as loss of profit, loss of reputation, even if advised of the possibility of such damages.”

3.6.

Vestel heeft in totaal 3.733 laders aan EeM geleverd tegen betaling van € 1.776.345,00. Van dit totale aantal hebben 1.943 een MID-meter. Een MID-meter is een meetinstrument dat aan een keurmerk voldoet en het aantal kWh (de verbruikte elektriciteit) dat door het apparaat is gegaan, nauwkeurig registreert. De door Vestel geleverde laders met MID-meter hebben een display in de lader, waarop het verbruik kan worden afgelezen. Partijen zijn ten aanzien van de nauwkeurigheid van het registreren van de verbruikte elektriciteit door de MID-meters een maximale foutmarge van 1% overeengekomen.

3.7.

Van de 3.733 geleverde laders heeft EeM er 1.035 geïnstalleerd; 409 laders met MID-meter en 626 laders zonder MID-meter. De laders zonder MID-meter bevatten ook een meetinrichting. Ten aanzien daarvan zijn partijen geen nauwkeurigheidsgarantie overeengekomen. Deze meters registreren de hoeveelheid verbruikte elektriciteit ongeveer.

3.8.

EeM wordt, als exploitant van laders, aangeduid als Charge Point Operator (hierna: CPO). De laders van Vestel moeten communiceren met de systemen van een CPO. De laadgegevens worden verzonden door gebruik van de door Vestel geïnstalleerde firmware. Deze firmware maakt voor de communicatie gebruik van het internet en het zogenaamde Open Charge Point Protocol (hierna: OCPP). OCPP bevat regels en best practices die ervoor zorgen dat de laders van allerlei fabrikanten op een uniforme wijze kunnen communiceren met het Charge Point Management Systeem (hierna: CPMS) van een CPO.

3.9.

EeM werkt samen met Greenflux Assets B.V. (hierna: Greenflux) voor het CPMS. Greenflux heeft de opdracht van EeM om de gegevens die de laders verzenden te registreren en te verwerken, zodat deze gebruiksklaar bij EeM aankomen.

3.10.

Voor een correcte gegevensverwerking via het OCPP moet de communicatie tussen de laders en de server van EeM goed verlopen. Om voor stabiele communicatie te zorgen wordt het zogenaamde ‘ping-pong’ systeem gehanteerd. Dat is een mechanisme dat de status van de verbinding tussen de laders en de server controleert en onderhoudt. Een ‘ping’ is een bericht dat door de laders naar de server van EeM wordt gestuurd om te controleren of de server bereikbaar is. De server moet vervolgens antwoorden met een ‘pong’ bericht om te bevestigen dat de server actief is en de verbinding werkt. Het ‘pinginterval’ bepaalt hoe vaak de laders een ‘ping’ bericht sturen naar de server van EeM. Een korter ‘pinginterval’ zorgt voor een stabiele, responsievere verbinding, aangezien de laders en de server dan continu hun status naar elkaar rapporteren. Partijen hebben een pinginterval van 60 seconden afgesproken.

3.11.

Verder bestaat de communicatie tussen de laders en de server van EeM uit de transactiegerelateerde berichten, waaronder het startbericht, waarmee de lader aangeeft dat een laadsessie is begonnen, en het stopbericht, waarmee de lader aangeeft dat een laadsessie is afgelopen. Aan de hand van deze berichten genereert Greenflux een zogeheten Charge Detail Record (hierna: CDR), een soort digitale kassabonnetjes.

3.12.

Het bedrijfsmodel van EeM houdt het volgende in.

Zij levert en installeert op verzoek van haar zakelijke klanten – dat zijn leasemaatschappijen of werkgevers – laders met MID-meter bij werknemers van die partijen, die daarmee hun elektrische auto thuis kunnen opladen. Deze laders zijn aangesloten op de meterkasten van de werknemers. De verbruikte elektriciteit wordt eerst in rekening gebracht bij de werknemer via diens eigen energierekening. De laders houden bij hoeveel elektriciteit er verbruikt is en communiceren dat met de systemen van EeM. EeM vergoedt vervolgens de verbruikte elektriciteit aan de werknemer en factureert daarna zowel voor de elektravergoeding als haar dienstverlening aan de betrokken werkgever of leasemaatschappij. Alleen de laders met MID-meter waren bedoeld voor dit systeem van financiële afrekening. EeM, diens zakelijke klanten en de werknemers hebben via my.eneco-mobility.com toegang tot een portal waarin het verbruik van de lader kan worden ingezien.

De laders zonder MID-meter waren bedoeld voor consumenten. Ook aan de gebruikers van deze laders staat via my.eneco-mobility.com een portal ter beschikking, waarin zij hun verbruik kunnen zien en kunnen zien wanneer zij hebben geladen. De consumenten betalen EeM voor deze portal en voor de via EeM verbruikte elektriciteit.

3.13.

EeM heeft problemen ondervonden met de laders, die in eerste instantie zijn opgelost. Eind 2022 ontdekte EeM vervolgens afwijkingen tussen het werkelijke elektriciteitsverbruik van laders en het bij EeM geregistreerde elektriciteitsverbruik. Dit kwam aan het licht doordat een klant op het display van de lader een kWh-waarde aflas en daarna constateerde dat deze afweek van de kWh-waarde die door EeM was verwerkt en gefactureerd, of dat de laadsessie, geregistreerd op het display, volledig ontbrak op de afrekening. Hierdoor ontvingen werknemers vergoedingen van laadtransacties die niet klopten met de werkelijk gebruikte kWh en ook werden onjuiste kosten in rekening gebracht bij de werkgever/leasemaatschappij.

3.14.

EeM heeft in september 2023 172 laders (met en zonder MID-meter) onderzocht en geconstateerd dat er een verschil zit tussen het verbruikte aantal kWh van deze laders en de hoeveelheden die bij EeM zijn geregistreerd.

3.15.

Op 22 september 2023 schreef EeM aan Vestel:

“(…) Therefore, Eneco eMobility grants Vestel a thirty-day period in which the discussed issues with the chargers must have been solved by Vestel. The solution must be final and unconditional as I mentioned in my prior e-mail. Please consider this email as a notice as meant in clause 18.3 (first dash) of the agreement between Vestel and Eneco eMobility. This notice causes that this agreement will be terminated as from October 23, 2023 in case no effective and final solution has been provided in time (…).”

3.16.

Greenflux heeft op 13 mei 2024 in opdracht van EeM een technisch rapport opgesteld. Zij heeft voorts een analyse d.d. 27 november 2025 aan EeM ter beschikking gesteld.

3.17.

Op 2 september 2024 heeft EeM conservatoir beslag laten leggen op de aandelen die Vestel houdt in Vestel Holland B.V.

4
Het geschil

4.1.

EeM vordert dat de rechtbank bij vonnis uitvoerbaar bij voorraad Vestel veroordeelt tot betaling van € 2.407.058,83, bestaande uit:

1. betreffende (terug)betaling van Vestel-voorraad die niet langer bruikbaar is voor EeM;

2.	€ 1.304.298,00 betreffende vervanging van reeds geplaatste laders;

3.	€ 10.839,00 aan door EeM betaalde klantvergoedingen;

4. P.M. betreffende kosten voor warehousing, handling en eventuele vernietiging/recycling van Vestel-voorraad;

5.	€ 6.775,00 aan buitengerechtelijke kosten;

6.	€ 9.950,83 aan beslag- en vertaalkosten,

althans een door de rechtbank te bepalen bedrag, te vermeerderen met de wettelijke rente vanaf de datum van ontbinding, althans vanaf de datum van de dagvaarding voor wat betreft het bedrag van € 1.075.196,00 en vanaf de datum van de dagvaarding voor wat betreft de overige bedragen, met veroordeling van Vestel in de proceskosten.

4.2.

Vestel voert verweer en concludeert tot afwijzing van de vorderingen van EeM, met uitvoerbaar bij voorraad te verklaren veroordeling van EeM in de kosten van deze procedure, inclusief de nakosten.

4.3.

Op de stellingen van partijen wordt hierna, voor zover van belang voor de beslissing, nader ingegaan.

5
De beoordeling

Bevoegdheid en toepasselijk recht

5.1.

Vestel is gevestigd in Turkije. De rechtbank moet daarom ambtshalve beoordelen of zij internationaal bevoegd is en zo ja, welk recht van toepassing is.

5.2.

Partijen gaan – mede aan de hand van het forumkeuzebeding in artikel 22.3 van de overeenkomst – uit van de bevoegdheid van de Nederlandse rechter (in Rotterdam). De rechtbank ziet geen aanleiding daarover anders te oordelen.

5.3.

Tussen partijen is niet in geschil dat op grond van artikel 22.1 van de overeenkomst Nederlands recht van toepassing is en dat op grond van artikel 22.4 toepasselijkheid van het Weens Koopverdrag is uitgesloten. De rechtbank zal de vordering dan ook naar Nederlands recht beoordelen.

Inleiding

5.4.

EeM baseert haar vorderingen primair op toerekenbare tekortkoming in de nakoming van de verplichtingen van de overeenkomst. Zij stelt dat zij de overeenkomst rechtsgeldig heeft ontbonden en vordert nakoming van de daaruit voorvloeiende ongedaanmakingsverbintenis. Daarnaast vordert zij schadevergoeding.

5.5.

Subsidiair vordert EeM schadevergoeding op grond van productaansprakelijkheid als bedoeld in artikel 6:185 BW.

Productaansprakelijkheid

5.6.

Zoals uit het navolgende blijkt, kan de rechtbank op dit moment nog geen eindoordeel vellen over de primaire grondslag. Voor het geval de vorderingen in de toekomst worden afgewezen op de primaire grondslag wordt nu al in gegaan op de subsidiaire grondslag. De rechtbank zal de vorderingen op deze grondslag dan afwijzen. EeM heeft niet gesteld, en ook is niet gebleken, dat de laders een onveilig product vormen in de zin van de wettelijke regeling voor productaansprakelijkheid en er is geen sprake van schade door dood of lichamelijk letsel of schade die is toegebracht aan een andere zaak die gewoonlijk voor gebruik of verbruik in de privésfeer is bestemd (zie artikel 6:190 BW).

Toerekenbare tekortkoming

Wat verwijt EeM precies aan Vestel?

5.7.

Vast staat dat EeM verschillen heeft geconstateerd tussen het werkelijk verbruikte aantal kWh en het aantal in de systemen van EeM (zie 3.14). Tussen partijen is geen discussie over de accuraatheid van de meter in de laders. De advocaat van Vestel heeft hierover ter zitting verklaard: “Tussen partijen is niet in geschil dat op de laders de juiste informatie staat” en [naam 1] van EeM heeft verklaard: “Er is geen discussie over de accuraatheid van de meter, de gegevens op het display kloppen. Alleen de gegevens worden niet goed doorgegeven.” EeM verwijt Vestel dus niet dat zij tekortschiet in haar verbintenis tot het meten van de hoeveelheid verbruikte kWh door de meetinrichting (waarbij met MID meter een foutmarge van 1% geldt en zonder meter het verbruik ongeveer wordt geregistreerd). De rechtbank begrijpt de stellingen van EeM zo, dat zij Vestel uitsluitend verwijt dat deze tekortschiet in de nakoming van haar verbintenis tot het verzenden van de gemeten hoeveelheid kWh. Dit gebeurt bij laders met en zonder MID-meter en willekeurig, dus niet bij elke lader en niet bij elke laadsessie, aldus EeM.

5.8.

In het Greenflux rapport waar EeM naar verwijst, staat: “Vestel-chargers sometimes fail to transmit all transaction-related messages to Greenflux (CMS) as per the OCCP protocol. This failure leads to the inability to generate Charge Detail Record (CDRs), resulting in financial losses for the Charge Point Operator (CPO)”. De rechtbank begrijpt uit de stellingname van EeM dat het gevolg van dit in het rapport genoemde falen bij het verzenden van de laadgegevens is dat er verbruikte hoeveelheden kWh ontbreken in het systeem van EeM. Het gaat haar dus om ontbrekende kWh.

5.9.

Het geschil tussen partijen betreft de vraag of dit, zoals EeM stelt en Vestel betwist, aan de laders van Vestel ligt en of dit een tekortkoming van Vestel oplevert.

5.10.

EeM verwijst ter onderbouwing van haar stellingen naar de twee rapporten van Greenflux (zie 3.16). Hiermee voldoen de laders volgens haar niet aan de artikelen 8.1(b) en 11.2 van de overeenkomst.

Toetsing aan artikel 8.1(b)

5.11.

EeM stelt dat de laders niet “suitable for Eneco’s intended use” zijn, zoals vermeld in de garantie van artikel 8.1(b) van de overeenkomst (zie 3.2). Volgens haar is overeengekomen dat de laders – met en zonder MID-meter – de laadgegevens altijd correct zouden verzenden naar de systemen van EeM. De laadgegevens van laders met een MID-meter worden binnen haar bedrijfsmodel immers gebruikt voor de financiële afrekening en voor de inzage in de laadgegevens in de portal. Het is dus van groot belang dat de overzichten van verbruikte kWh kloppen. Dit geldt ook voor de laders zonder MID-meter omdat als transacties in het geheel ontbreken de consument de transactie ook niet terugziet in de portal. Vestel wist van dit bedrijfsmodel van EeM en het voorgenomen gebruik van de laders, omdat EeM dit voorafgaand aan het sluiten van de overeenkomst uitgebreid met Vestel heeft besproken, aldus EeM.

5.12.

Vestel betwist dat sprake is van schending van de garantie van artikel 8.1(b) van de overeenkomst. Zij wijst erop dat de “intended use” in de overeenkomst niet is gespecificeerd. Zij betwist het bedrijfsmodel van EeM op zichzelf niet, maar betoogt dat zij voorafgaand aan de overeenkomst niet wist wat dat inhield en dat dit voorafgaand aan de overeenkomst niet uitgebreid met haar is besproken. Het facturatiemodel is volgens haar helemaal niet besproken. Vestel voert aan dat zij enkel de verplichting op zich heeft genomen om elektriciteit te leveren, ten aanzien van de laders met MID-meter het kWh-verbruik juist te registreren (binnen de afgesproken foutmarge van 1%) en toegankelijk te zijn voor internet en OCCP-verkeer.

5.13.

Partijen hebben dus een verschil van mening over de vraag wat zij zijn overeengekomen en daarmee over de uitleg van de overeenkomst. Dat betreft de vraag wat onder “intended use” moet worden verstaan en de vraag of Vestel de verbruikte hoeveelheden kWh slechts correct hoefde te registreren of dat zij deze ook correct moest verzenden naar het systeem van EeM.

5.14.

Voor de beantwoording van deze vraag geldt het volgende als juridisch uitgangspunt. Het gaat hier om een commerciële overeenkomst tussen professionele partijen. Voor de uitleg zijn de bewoordingen van de overeenkomst – waar Vestel op wijst – van belang, maar beslissend is de zin die partijen in de gegeven omstandigheden over en weer redelijkerwijs aan de bepalingen mochten toekennen en hetgeen zij te dien aanzien redelijkerwijs van elkaar mochten verwachten.

5.15.

Voor de beoordeling zijn de volgende feiten van belang. Ter zitting heeft [naam 2], head of sales bij Vestel (hierna: [naam 2]), desgevraagd verklaard: “Wij wisten dat de MID-meterpalen gebruikt zouden worden voor de business to business en de andere palen, zonder MID-meter, voor de business to consumer. U vraagt mij wat ik wist over het b2b model van Eneco. Wij wisten dat de eindgebruikers hun auto’s konden laden en dat het aantal kWh aan de eindverbruikers zou worden vergoed. (…) Er werd bij de eindgebruiker een laadpaal met MID-meter geïnstalleerd. Stel, ik krijgt van mijn werkgever de beschikking over een auto. Mijn werkgever zorgt er dan voor dat er een laadpaal bij mijn woning wordt geïnstalleerd en dan kan ik de kosten voor het laden van de auto declareren bij de werkgever en die krijg ik dan vergoed.” Hieruit blijkt dat Vestel voorafgaand aan het sluiten van de overeenkomst goed wist hoe het bedrijfsmodel van EeM in elkaar zat en daarmee wat de “intended use” was.

Voorts heeft EeM tijdens de mondelinge behandeling gesteld dat partijen afspraken hebben gemaakt over welke partij de simkaarten zou plaatsen. Vestel heeft dit niet betwist. Uit productie 50 van EeM en hetgeen daarover, onbetwist, door partijen naar voren is gebracht, blijkt dat Vestel de laders met en zonder MID-meter heeft getest en dat op de laders de juiste gegevens stonden, waarbij Vestel noteerde “tested for all smart products”. De rechtbank begrijpt hieruit dat in alle laders een simkaart werd geplaatst. Productie 50 is weliswaar een e-mail die na het sluiten van de overeenkomst is gestuurd (22 juni 2021), maar ook in het Factory Pre-Configuration Document waarin gemaakte afspraken staan, staat al “SIM card will be installed to the unit during production”. [naam 2] heeft ter zitting verklaard dat het idee van de simkaart is om de lader “te connecten met de back-end” en dat dit nodig is om data te verzamelen. Beide type laders werken met dezelfde, door Vestel geïnstalleerde software.

5.16.

Ten aanzien van het business to business-gebruik van de laders overweegt de rechtbank het volgende. Gelet op wat hiervoor is overwogen, wist Vestel dat het voor EeM van belang was dat de laders hun laadgegevens konden versturen naar de server van EeM, en was Vestel op de hoogte van de financiële afwikkeling die bij het voorgenomen gebruik van EeM voor business to business hoorde. Naar het oordeel van de rechtbank moesten de laders met een MID-meter de per laadsessie verbruikte (d.w.z. door de meter geregistreerde) hoeveelheid kWh daarom altijd correct versturen. Als dat niet is gebeurd, leidde dat tot ontbrekende kWh en schoot Vestel tekort.

5.17.

Ten aanzien van het business to consumer-gebruik overweegt de rechtbank als volgt. Vestel wist dat in alle laders, ook die zonder MID-meter, een simkaart geïnstalleerd moest worden en dat een dergelijke simkaart enkel noodzakelijk is als de lader data moet kunnen verzamelen en moet kunnen delen met de server. Vast staat dat ook de consument-gebruikers van laders zonder MID-meter in hun portal het verbruik konden zien en konden zien wanneer zij hebben geladen. Vestel heeft niet betoogd dat zij dat voorafgaand aan het sluiten van de overeenkomst niet wist. Ook deze laders moesten de verbruikte (d.w.z. door de meetinrichting geregistreerde) hoeveelheden kWh daarom altijd correct versturen. Als dat niet is gebeurd en dus kWh ontbreken, dan is ook ten aanzien van deze laders niet voldaan aan het vereiste van “intended use” als bedoeld in artikel 8.1(b) van de overeenkomst. In dat geval is sprake van een tekortkoming.

Toetsing aan artikel 11.2

5.18.

Ook voldoen de laders volgens EeM niet aan de verplichting van Vestel om ‘conforme’ producten te leveren, zoals bedoeld in artikel 11.2 van de overeenkomst (zie 3.3), waarin is bepaald dat de laders moeten voldoen aan alle toepasselijke regelgeving, normen en voorschriften die van belang zijn in de industrie. De laders voldoen niet aan hoofdstuk 3.7 OCPP, waarin staat dat als een lader offline is, de transactie gerelateerde gegevens moeten worden opgeslagen in de lader zelf en daarna in chronologische volgorde moeten worden aangeboden bij het ontvangende systeem. Vestel betwist dat de laders niet voldoen aan artikel 11.2 van de overeenkomst.

5.19.

Het verzoek dat Vestel ter zitting deed om zich bij akte nader over deze (volgens haar: nieuwe) stellingen uit te laten vanwege haar beperkte voorbereidingstijd, wordt gepasseerd. EeM heeft hoofdstuk 3.7 van het OCCP al in de dagvaarding besproken en daarin ook verwezen naar het Greenflux rapport (EeM productie 44) waarin dit eveneens is besproken. Vestel heeft hier bij conclusie van antwoord ook al uitgebreid op gereageerd.

5.20.

Tussen partijen is niet in geschil dat het OCPP van toepassing is op alle laders. De rechtbank leidt uit hoofdstuk 3.7 van het OCPP af dat de laders van Vestel de transactie gerelateerde gegevens naar de systemen van EeM moeten versturen en dat in geval de lader offline is, deze gegevens in de wachtrij moeten worden geplaatst en vervolgens – als de lader weer online is – in de goede volgorde alsnog moeten worden verstuurd. Dit staat tussen partijen ook niet ter discussie. Als de lader de laadgegevens, en daarmee de per laadsessie geregistreerde hoeveelheid kWh conform het OCPP (in chronologische volgorde, in voorkomend geval na in de wachtrij te zijn geplaatst) heeft verstuurd, heeft Vestel dus aan haar verplichtingen voldaan. Zo niet, dan is zij tekortgeschoten in de nakoming van haar verbintenissen tegenover EeM.

Bewijs

5.21.

Zoals hiervoor is overwogen, is niet in geschil dat de laders met MID-meter de laadgegevens juist registeren. EeM heeft ter zitting bevestigd dat de laders de laadgegevens naar de systemen van EeM moeten versturen. Vestel betwist ook niet dát er afwijkingen voorkwamen tussen het door de laders gemeten verbruik en de gegevens in de systemen van EeM. Zij betwist wel dat dit aan haar laders ligt.

5.22.

Vestel betwist dat haar laders geen of onjuiste gegevens versturen naar de systemen van EeM en zij voert aan dat zij zelf niet heeft kunnen reproduceren dat de wachtrij niet werkt. Tot juli 2023 hebben partijen altijd goed samengewerkt om problemen gezamenlijk op te lossen, aldus Vestel. Volgens Vestel worden de laadgegevens correct, volgens het OCPP, naar EeM gezonden. Waarom de gegevens niet altijd (volledig) door EeM worden ontvangen, is niet duidelijk. Vestel heeft samen met EeM en Greenflux willen onderzoeken wat de oorzaak van het probleem is, maar EeM heeft Vestel daartoe niet de gelegenheid geboden.

5.23.

EeM verwijst ter onderbouwing van haar stelling dat de laders de laadgegevens niet correct versturen naar de resultaten van haar eigen onderzoek uit september 2023 (productie 24 EeM), het Greenflux-rapport van 13 mei 2024 (productie 44 EeM) en de analyse van Greenflux van 27 november 2025 (productie 52 EeM).

Vestel brengt tegen het eigen onderzoek van EeM in dat dit alleen laat zien dát er verschillen zijn geconstateerd tussen het werkelijke kWh verbruik en het verbruik dat bij de server van EeM werd bijgehouden. Dit zegt volgens Vestel niets over de oorzaak daarvan en daaruit blijkt niet over welke periode de afwijkingen zich hebben opgebouwd, waardoor niet kan worden uitgesloten dat deze zijn ontstaan door oudere, opgeloste, problemen. Vestel heeft voorts diverse bezwaren tegen het Greenflux-rapport en stelt dat dat rapport niet als bewijs kan dienen. Aangenomen mag worden dat haar bezwaren ook de Greenflux analyse betreffen. Zij betoogt dat uit het Greenflux rapport slechts blijkt dat twee laders zijn onderzocht – en niet hoe groot de steekproef is geweest – en dat weliswaar bleek dat er bij deze twee laders drie keer iets mis liep in de communicatie tussen de laders en de server, maar niet waarom dat gebeurde. Volgens Vestel is alleen het OCCP onderzocht (de communicatie) maar niet waarom er iets mis liep in die communicatie. Volgens Vestel heeft Greenflux alleen geconstateerd dat enkele Start en Stop berichten niet door het CMS zijn ontvangen, maar niet dat de laders deze berichten niet heeft verstuurd of door toedoen van de laders niet zijn ontvangen. Voorts merkt zij op dat zij niet bij het onderzoek door Greenflux en bij het opstellen van het rapport is betrokken. Greenflux kan niet worden gezien als een onafhankelijk en onpartijdig deskundige, omdat zij een dienstverlener is van EeM en als registratie- en verwerkingspunt een belangrijke rol speelt in het communicatieproces tussen de laders en de server van EeM. Greenflux heeft ook geen hoor en wederhoor gepleegd. Zij heeft dus niet kennisgenomen van, en is niet ingegaan op de bezwaren van Vestel tegen het rapport. Daarmee voldoet het Greenflux-rapport niet aan de standaard voor deskundigenbewijs, nog afgezien van het feit dat Vestel betwist dat uit het rapport blijkt dat de daarin geïdentificeerde problemen zijn te wijten aan de laders.

5.24.

Gelet op het voorgaande gemotiveerde verweer is niet duidelijk wat de oorzaak is van het probleem van de ontbrekende hoeveelheden kWh en staat niet vast dat dit door de laders van Vestel komt. Om te kunnen beoordelen of Vestel is tekortgeschoten in de nakoming van haar verbintenissen tegenover EeM, zal dus eerst moeten komen vast te staan dat de laders van Vestel, of een deel van die laders, de laadgegevens en daarmee de per laadsessie geregistreerde hoeveelheid kWh – in geval van offline situatie: na plaatsing in de wachtrij – niet altijd juist versturen naar de systemen van EeM, waarbij de bewijslast op EeM rust.

5.25.

De rechtbank geeft partijen in overweging om samen (een) expert aan te wijzen die, bijvoorbeeld door middel van een proefopstelling van laadpalen met de door EeM als laatst gebruikte versie van de firmware, versie 3.131, en met behulp van partijen, kan achterhalen of de in 5.24 weergegeven situatie zich voordoet en die daarover een voor partijen bindend advies kan geven. Als partijen hierover geen overeenstemming kunnen bereiken, benoemt de rechtbank een deskundige, waarbij het voorschot op het honorarium van de deskundige door EeM moet worden betaald.

5.26.

Als EeM niet slaagt in het in 5.24 genoemde bewijs, worden haar vorderingen afgewezen. In dat geval staat immers niet vast dat Vestel tekort is geschoten in de nakoming van de verbintenissen uit de overeenkomst, terwijl evenmin sprake is van aansprakelijkheid als bedoeld in artikel 6:185 BW.

5.27.

Als EeM wel slaagt in dit bewijs, dan staat daarmee vast dat Vestel is tekortgeschoten in de nakoming van haar verbintenissen uit de overeenkomst. Volgens Vestel zou EeM dan alsnog niet gerechtigd zijn geweest de overeenkomst te ontbinden, omdat Vestel niet in verzuim is en omdat sprake is van schuldeisersverzuim van EeM. Ook voert zij aan dat de tekortkoming te gering zou zijn om de ontbinding te rechtvaardigen. De rechtbank gaat hierna alvast op deze verweren in, zodat partijen op deze punten al weten waar zij aan toe zijn.

Is sprake van verzuim of schuldeisersverzuim?

5.28.

Als komt vast te staan dat Vestel tekort is geschoten in de nakoming van haar verbintenis zoals omschreven in 5.24, staat ook vast dat Vestel in verzuim is. EeM heeft Vestel immers op 22 september 2023 een termijn van dertig dagen gegeven om de overeenkomst alsnog correct na te komen en deze termijn is verstreken. Volgens Vestel verkeerde EeM in schuldeisersverzuim, door vanaf mei 2023 niet meer mee te werken aan het achterhalen van de oorzaak van de nog bestaande problemen en dus niet mee te werken aan het vinden van een oplossing. De rechtbank verwerpt dit verweer en overweegt daartoe als volgt.

5.29.

Van schuldeisersverzuim is sprake wanneer nakoming van een verbintenis wordt verhinderd doordat de schuldeiser (in dit geval: EeM) de daartoe noodzakelijke medewerking niet verleent of doordat een ander beletsel van de zijde van de schuldeiser opkomt, tenzij de oorzaak van de verhindering niet aan de schuldeiser kan worden toegerekend (artikel 6:58 BW). Voor het intreden van schuldeisersverzuim is een ingebrekestelling niet noodzakelijk, maar de schuldenaar (Vestel) dient wel alles gedaan te hebben wat in redelijkheid van haar verwacht mag worden om tot nakoming te kunnen overgaan. Onder omstandigheden kan daartoe ook behoren een uitdrukkelijk aanbod om tot nakoming over te gaan. Stelplicht en bewijslast ten aanzien van het bestaan van schuldeisersverzuim rusten op de schuldenaar.

5.30.

Vestel heeft naar het oordeel van de rechtbank onvoldoende onderbouwd gesteld dat EeM de nakoming van de verbintenissen van Vestel heeft verhinderd, omdat uit haar eigen stellingen blijkt dat EeM tot en met december 2023 gegevens is blijven versturen naar Vestel. Op 17 augustus 2023 heeft EeM aan Vestel medegedeeld dat zij niet langer wilde samenwerken, omdat zij geen vertrouwen meer had in de laders. Op 22 september 2023 heeft EeM Vestel een termijn van 30 dagen gesteld om de overeenkomst alsnog correct na te komen. Vervolgens, zo is door Vestel zelf aangevoerd, heeft EeM op 13 november 2023 aan Vestel gemeld dat met de firmware update V3.131 problemen waren opgelost, maar ook nog problemen resteerden en dat EeM vervolgens informatie is blijven delen met Vestel, met verwijzing naar e-mails in november en december 2023. Dat EeM niet heeft willen meewerken aan een workshop met Greenflux en Vestel, zoals ter zitting door Vestel aangevoerd, is, gelet op het voorgaande, niet onbegrijpelijk en onvoldoende om te kunnen oordelen dat EeM daarmee in schuldeisersverzuim verkeerde.

Rechtvaardigt de tekortkoming ontbinding?

5.31.

Vestel meent dat, zelfs al zou EeM in haar stellingen worden gevolgd dat sprake is van een tekortkoming door Vestel, de gestelde tekortkoming geen ontbinding van de overeenkomst rechtvaardigt. Zij voert hiertoe aan dat EeM ten aanzien van slechts 172 laders onderbouwd heeft gesteld dat deze afwijkingen vertonen tussen het werkelijke kWh-verbruik en het kWh-verbruik dat op de server van EeM werd geregistreerd, hetgeen slechts een fractie is van de 1.035 geïnstalleerde laders. Ook is de gestelde financiële impact van de vermeende afwijkingen volgens Vestel zo gering – slechts € 10.839,00 op een contract met een waarde van € 1.776.345,00 – dat dit een ontbinding niet rechtvaardigt.

5.32.

Als komt vast te staan dat Vestel is tekortgeschoten in de nakoming van haar verbintenis zoals vermeld in 5.24, rechtvaardigt dit naar het oordeel van de rechtbank de ontbinding. Zij overweegt daartoe het volgende.

5.33.

Zoals EeM onweersproken heeft gesteld, zijn de problemen willekeurig en onvoorspelbaar. Ook heeft zij onweersproken gesteld dat zij na onderzoek van 172 van de 1.035 geïnstalleerde laders, is gestopt met onderzoeken. De kans dat het om meer gevallen gaat, is dus zonder meer aanwezig, zeker gelet op het feit dat het probleem van de ontbrekende hoeveelheid kWh is geconstateerd bij alle 172 onderzochte laders. Dat is ruim 16% van het totaal aantal geïnstalleerde laders, en niet gering. Als er laders zijn die niet goed werken, laat staan zoveel, dan raakt dat aan de betrouwbaarheid van alle laders. Dit is voldoende om ontbinding te rechtvaardigen.

5.34.

Tot slot heeft EeM onweersproken gesteld dat het bedrag van € 10.839,00 een optelsom is van bedragen die EeM heeft betaald aan 200 werknemers. Dit zijn allemaal eindgebruikers die gebruik maken van laders met MID-meter, waarvan EeM er 409 heeft geïnstalleerd. Dat betekent dat aan bijna de helft van alle eindgebruikers met een MID-meter bedragen zijn betaald. Hoewel de schade die hieruit voortvloeit voor EeM gering is, vergeleken met de waarde van het contract, acht de rechtbank dit aantal van 200 op een totaal van 409 niet gering. Bovendien heeft EeM onweersproken gesteld dat ook klanten zonder MID-meter hebben geklaagd.

Kan de tekortkoming leiden tot schadevergoeding?

5.35.

De rechtbank geeft hierna ook al zoveel als mogelijk een oordeel over de gevorderde schade.

5.36.

Als vaststaat dat Vestel is tekortgeschoten in de nakoming van haar verbintenis, is de overeenkomst rechtsgeldig ontbonden en is Vestel gehouden tot ongedaanmaking en vergoeding van de schade die EeM heeft geleden. EeM vordert op grond van artikel 6:271 BW nakoming van de ongedaanmakingsverbintenissen van Vestel die volgens haar bestaan uit het terugnemen en terugbetalen van de voorraad (2.698) laders en vergoeding van de vervanging door EeM van 1.035 geplaatste laders. Daarnaast vordert zij schadevergoeding voor uitbetaalde klantvergoedingen en kosten van warehousing. Over de vorderingen tot vergoeding van buitengerechtelijke incassokosten en proceskosten, geeft de rechtbank in dit tussenvonnis nog geen oordeel.

- bestaande voorraad

5.37.

In artikel 6:271 BW is bepaald dat een ontbinding partijen bevrijdt van de daardoor getroffen verbintenissen en dat, voor zover die reeds zijn nagekomen, de rechtsgrond voor deze nakoming in stand blijft maar voor partijen een verbintenis ontstaat tot ongedaanmaking van de reeds door hen ontvangen prestaties. EeM vordert op grond hiervan terugbetaling van een bedrag van € 1.075.196,00 aan voorraad laders (2.698 stuks) die Vestel heeft geleverd en die EeM door de gestelde tekortkoming niet langer kan gebruiken. EeM heeft deze vordering voldoende onderbouwd en Vestel heeft hiertegen geen verweer gevoerd. Als de tekortkoming van Vestel vaststaat, komt deze vordering voor toewijzing in aanmerking.

- vervanging van laders

5.38.

Daarnaast vordert EeM op grond van artikel 6:271 BW betaling van een bedrag van € 1.304.298,00. Deze post bestaat volgens EeM uit de inkoopwaarde van de laders die zij heeft vervangen (in totaal 1.035 stuks) en uit de kosten voor de vervanging. Vestel betwist dat EeM recht heeft op dit bedrag, omdat dit vervangende schadevergoeding zou zijn.

5.39.

De rechtbank oordeelt hierover als volgt. Als gevolg van de ontbinding rust op partijen een ongedaanmakingsverbintenis. Voor EeM bestaat deze eruit dat zij alle laders aan Vestel moet teruggeven en voor Vestel betekent dit dat zij aan EeM de koopprijs van € 1.776.345,00 terug moet betalen. EeM vordert echter meer dan dat, omdat zij, naast het bedrag van € 1.075.196,00 (voorraad), nog een bedrag vordert van € 1.304.298,00. De rechtbank begrijpt het zo dat het meerdere, boven € 1.776.345,00, geen vordering op grond van ongedaanmaking is, maar een vordering tot aanvullende schadevergoeding op grond van artikel 6:74 jo. 6:277 BW. Anders dan Vestel meent, betreft ook dit geen vervangende schadevergoeding. EeM kan door de wanprestatie schade lijden (welke schade dus onafhankelijk van de ontbinding ontstaat), terwijl andere schadeposten eerst ontstaan ten gevolge van de ontbinding. Beide schadeposten komen voor vergoeding in aanmerking.

5.40.

De vordering van € 1.304.298,00 bestaat volgens EeM uit (1) de inkoopprijzen van 1.035 nieuwe laders, (2) de kosten voor nieuwe palen (waar nodig), (3) de kosten voor de technische modules voor aansluiting op de meterkast en (4) montagekosten. Vestel heeft betwist dat vervanging van 1.035 laders met een gemiddelde kostprijs van ongeveer € 400,00 kan leiden tot € 1.304.298,00 aan vervangingskosten. EeM heeft weliswaar aangeboden facturen in het geding te brengen, maar zij heeft dat niet gedaan. Nu Vestel deze gestelde schade en de omvang daarvan gemotiveerd heeft betwist, is het aan EeM om te bewijzen dat zij schade lijdt tot € 1.304.298,00. Deze bewijsopdracht is echter eerst aan de orde als vaststaat dat Vestel is tekortgeschoten, zoals hiervoor bedoeld.

5.41.

Voor schadevergoeding is, anders dan voor ontbinding en ongedaanmaking, niet alleen vereist dat Vestel is tekortgeschoten, maar ook dat de tekortkoming aan haar toerekenbaar is. Dat de gestelde tekortkoming niet aan Vestel is toe te rekenen, is aan Vestel om te stellen. Dat heeft zij niet gedaan zodat, in geval de tekortkoming komt vast te staan, ook vaststaat dat die tekortkoming toerekenbaar is aan Vestel.

- klantvergoedingen

5.42.

EeM vordert voorts een schadevergoeding van € 10.839,00. Volgens EeM is dit het totaalbedrag van vergoedingen aan klanten die vorderingen bij EeM hebben neergelegd voor het ontbreken van juiste vergoedingen als gevolg van de toerekenbare tekortkoming van Vestel. Volgens EeM heeft een werknemer bijvoorbeeld 20 kWh geladen, maar heeft de lader van Vestel maar 10 kWh doorgegeven. Die 10 kWh heeft EeM aan de werknemer vergoed en aan de werkgever/leasemaatschappij doorbelast, terwijl de werknemer 20 kWh aan zijn energieleverancier heeft betaald. EeM heeft dit hersteld en heeft zelf het missende bedrag aan vergoeding betaald aan de werknemer, terwijl zij dit niet heeft kunnen factureren aan de werkgever/leasemaatschappij. Dit bedrag betreft de schade die zij heeft geleden en deze is ontstaan doordat de laders van Vestel onjuiste of geen gegevens doorgeven, aldus EeM.

5.43.

De rechtbank oordeelt dat deze vordering niet toewijsbaar is. Zoals Vestel terecht heeft aangevoerd, leidt het niet kunnen factureren van verbruik aan werkgevers en leasemaatschappijen tot indirecte schade in de vorm van misgelopen winst, die ingevolge artikel 16.6 van de overeenkomst is uitgesloten van vergoeding (zie 3.5). Deze klantvergoedingen komen dus, evenals eventuele reputatieschade, niet voor vergoeding in aanmerking.

- opslagkosten

5.44.

EeM stelt dat Vestel ten onrechte de laders niet heeft teruggenomen na het moment van ontbinding en dat EeM daarom de laders ergens heeft moeten opslaan, waardoor zij kosten heeft gemaakt. In de dagvaarding is deze post een P.M. post en dus geen onderdeel van de totale vordering van € 2.407.058,83. Later, bij de akte aanvulling feiten en overlegging aanvullende producties, heeft EeM een overzicht overgelegd van de kosten die EeM heeft gemaakt voor de desbetreffende opslag, van € 25.168,00. Omdat geen eisvermeerdering is ingediend, komt dit bedrag niet voor vergoeding in aanmerking.

Slotsom

5.45.

De rechtbank zal de zaak naar de rol verwijzen, zodat beide partijen (ieder voor zich) de rechtbank bij akte kunnen informeren of zij gezamenlijk een expert aanwijzen en een bindend advies vragen als bedoeld in 5.25. Als dit niet zo is, kunnen partijen ieder in hun akte een voorstel doen omtrent de persoon van een door de rechtbank te benoemen deskundige en omtrent de te stellen vragen. Bij voorkeur delen partijen dan van tevoren de naam of namen van de door hen beoogde expert(s) en de volgens hen te stellen vragen met elkaar, en geven zij, als zij bezwaren hebben tegen de door de wederpartij beoogde expert of de door de wederpartij voorgestelde vragen, gemotiveerd aan waar die bezwaren uit bestaan. De rechtbank zal dan, na weging van de bezwaren en de motivering daarvan een door partijen aangedragen deskundige of een eigen deskundige benoemen en vragen formuleren.

5.46.

In afwachting van de nadere aktes van partijen en de bewijslevering houdt de rechtbank iedere verdere beslissing aan, ook de beslissing tot bewijslevering door EeM met betrekking tot de schade als bedoeld in 5.40.

5.47.

Het staat partijen uiteraard vrij om naar aanleiding van dit tussenvonnis te overleggen over een minnelijke regeling van hun geschil. Als zij daar meer tijd voor nodig hebben, kunnen zij de rechtbank vragen om de onder 6.2 bepaalde termijn te verlengen.

6
De beslissing

De rechtbank

6.1.

laat EeM toe te bewijzen dat de laders van Vestel, of een deel van die laders, de laadgegevens en daarmee de per laadsessie geregistreerde hoeveelheid kWh – in geval van offline situatie: na plaatsing in de wachtrij – niet altijd juist versturen naar de systemen van EeM,

6.2.

bepaalt dat de zaak weer op de rol zal komen van woensdag 9 september 2026 voor het nemen van een akte door partijen over wat is vermeld onder 5.45, en bepaalt dat als partijen gezamenlijk een expert hebben benoemd, de zaak wordt verwezen naar de parkeerrol en iedere partij de zaak weer kan opbrengen met gelijktijdig een bericht aan de rechtbank over de stand van zaken en hoe zij de procedure wens(en) te vervolgen,

6.3.

houdt iedere verdere beslissing aan.

Dit vonnis is gewezen door mr. W.J.M. Diekman, mr. W.A.M. Schellekens en mr. M.S. Polet. Het is ondertekend door de rolrechter en in het openbaar uitgesproken op 17 juni 2026.3242/2502/3310/2806

Vestel heeft het in haar conclusie van antwoord over 3.732 geleverde laders. De rechtbank gaat ervan uit dat dat een verschrijving is. Vestel erkent immers dat er 1.035 zijn geïnstalleerd en betwist niet dat er 2.698 als voorraad resteren.

HR 13 maart 1981, ECLI:NL:HR:1981:AG4158
