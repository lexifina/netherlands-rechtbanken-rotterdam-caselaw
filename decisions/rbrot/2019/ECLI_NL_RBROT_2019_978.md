---
ecli: "ECLI:NL:RBROT:2019:978"
court: "Rechtbank Rotterdam"
court_code: "RBROT"
docket: "C/10/550890 / HA ZA 18-509"
decided: "2019-01-30"
published: "2019-02-11"
type: "uitspraak"
procedure: "Eerste aanleg - enkelvoudig"
subject: "Civiel recht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:RBROT:2019:978"
published_in: ["Rechtspraak.nl"]
---

# ECLI:NL:RBROT:2019:978 Rechtbank Rotterdam , 30-01-2019 / C/10/550890 / HA ZA 18-509

## Inhoudsindicatie

Is tussen partijen een factoringovereenkomst tot stand gekomen? Wilsvertrouwensleer. Geen onrechtmatige daad.

## Uitspraak

vonnis

RECHTBANK ROTTERDAM

Team handel en haven

zaaknummer / rolnummer: C/10/550890 / HA ZA 18-509

Vonnis van 30 januari 2019

in de zaak van

de besloten vennootschap met beperkte aansprakelijkheid

ADIVARE B.V.,

gevestigd te Groningen,

eiseres in conventie,

verweerster in reconventie,

advocaat mr. K. Konings te Groningen,

tegen

de besloten vennootschap met beperkte aansprakelijkheid

BILLINK B.V.,

gevestigd te Rotterdam,

gedaagde in conventie,

eiseres in reconventie,

advocaat mr. D.L.A. van Voskuilen te Rotterdam.

Partijen zullen hierna Adivare en Billink genoemd worden.

1
De procedure

1.1.

Het verloop van de procedure blijkt uit:

de dagvaarding van 3 mei 2018, met producties;

de conclusie van antwoord tevens voorwaardelijke conclusie van eis in reconventie, met producties;

de brief van de rechtbank van 19 september 2018, waarbij een comparitie van partijen is bepaald;

de conclusie van antwoord in voorwaardelijke reconventie tevens houdende akte van eiswijziging, met producties;

de antwoordakte tevens akte overlegging producties van Billink, met producties;

de brief van Billink van 12 november 2018, met producties 10 tot en met 12;

het proces-verbaal van de comparitie van partijen, gehouden op 26 november 2018;

de brieven van mr. Van Voskuilen van 24 december 2018 respectievelijk van mr. Konings van 27 december 2018 met opmerkingen naar aanleiding van het proces-verbaal;

de pleitnotitie van mr. Konings;

de pleitnota van mr. Van Voskuilen.

1.2.

Ten slotte is vonnis bepaald.

2
De feiten

2.1.

Adivare (voorheen genaamd [naam 2] Beheer Groep B.V.) exploiteert een aantal websites. Uit de verkoop van diensten via deze websites verkrijgt Adivare vorderingen op debiteuren.

2.2.

Billink is een ‘payment provider’ en houdt zich onder andere bezig met het op grote schaal incasseren van vorderingen voor haar klanten.

2.3.

In mei 2014 is tussen Adivare en Billink een e-invoicingovereenkomst gesloten, op grond waarvan Billink voor Adivare factureerde aan haar debiteuren en het incassotraject verzorgde tegen een factorloon van € 0,99 per vordering. Adivare maakte daarnaast gebruik van een andere ‘payment provider’, AfterPay, aan wie Adivare 80% van haar vorderingen op debiteuren overdroeg. De overige 20% bracht Adivare onder bij Billink onder de e-invoicingovereenkomst.

2.4.

Vanaf eind 2014 is Adivare in onderhandeling met Billink over het sluiten van een factoringovereenkomst. In dit verband heeft Billink (de heer [naam 1] ) aan Adivare (de heer [naam 2] ) het volgende e-mailbericht op 26 januari 2015 gestuurd:

“(…) Bijgesloten ontvang je de meest recente versie van de overeenkomst. Zou je deze met spoed kunnen tekenen en aan mij willen retournemen?

Eveneens ontvang je bijgesloten de implementatiehandleiding en [naam 3] neemt deze week contact met je op. Zou je mij kunnen doorgeven op welke dag en hoe laat je een uur of twee tijd hebt om de implementatie verder af te wikkelen? (…)”

2.5.

In de implementatiehandleiding van Billink, die aan Adivare is toegestuurd, staat in de inleiding vermeld “Billink beoordeelt uw debiteuren op kredietwaardigheid” en wordt uitgelegd hoe de kredietcheck door Adivare kan worden geïmplementeerd. In het kader van de implementatie heeft [naam 3] (van Billink) op 30 januari 2015 het volgende e-mailbericht aan Adivare gestuurd:

“As I see current integration of [naam 2] and Billink I see 1 issue which needs to be solved. This is regarding your new pricing (guarantee).

You will need to use a different workflow and a new way of supplying an order.

An order always exist of a check on our Check API. This Check will see if there are open invoices, if the consumer is creditable and if we accept the order. In some cases the check will result in a negative advice, which could have many reasons (Fraud / not creditable / bad debt situation). In that case we deny the order on our guarantee system, but you can still try it on our none guarentee flow. Although I would not recommend as these consumers are rejected for a reason.

If our Check API accepts the order, you will get a ChechUUID, which is a unique code. This unique code is a proof that an order is checked in our system. You have to enter this unique code into the Order API.

So after checking on our Check API you continue to enter in Order API like you currently do. Except you also enter CheckUUID you received at our Check API.

You also will use a different Workflownumber (Number 2) instead of number 1. For integration I think this is the first step we should take.

After this steps the orders are live and we can work on the next issues: (…)”.

2.6.

Op 5 februari 2015 heeft [naam 2] (Adivare) aan [naam 1] (Billink) - voor zover relevant – het volgende bericht gestuurd:

“(…) Ik vind het erg belangrijk dat ons contract voor beide partijen naar volle tevredenheid is afgerond voordat we een krabbel zetten.

Het grootste punt op dit moment voor mij is het stukje over de checks die niet vallen onder de 97% garantie. Het komt op mij over alsof het gaat over een mogelijkheid voor Billink om op basis van checks klanten te mogen weigeren.(…)”.

Hierop heeft [naam 1] op 5 februari 2015 om 20u18 als volgt gereageerd:

“(…) Voor wat betreft artikel 4 lid 3 kan ik geen wijzigingen aanbrengen. Dit zou namelijk inhouden dat iemand die één keer is afgewezen en nogmaals probeert en vervolgens eveneens wordt afgewezen dubbel telt! Dat kan natuurlijk niet. (…)”.

Vervolgens heeft [naam 1] op diezelfde dag aan [naam 2] per e-mail bericht dat in het betreffende artikel een verwijzing naar bovenstaande mail is opgenomen, met bijgesloten een gecorrigeerde versie van de overeenkomst.

2.7.

Op 10 februari 2015 heeft Adivare de factoringovereenkomst ondertekend naar Billink (ter attentie van [naam 1] , [naam 3] en [naam 4] ) gestuurd met het volgende bericht:

“Beste heren,

Hierbij de lang verwachte ondertekende overeenkomst.

Ik zie graag een geparafeerde en ondertekende kopie tegemoet.

(…)

Ps. Ik kreeg zojuist een melding dat de technische implementatie morgenochtend wordt afgerond.”.

In reactie hierop heeft [naam 1] (van Billink) een dag later - op 11 februari 2015 - aan [naam 2] (van Adivare) geschreven:

“(…) Dank voor het toesturen van de getekende overeenkomst! (…)

Zou je mij met betrekking tot de implementatie nog op de hoogte willen houden? Je gaf aan dat het vandaag of morgen is geprogrammeerd. Neem je ook nog even contact op met [naam 3] om het proces te bespreken en waterdicht te krijgen? (…)”.

2.8.

In de door Adivare getekende factoringovereenkomst (hierna: de factoringovereenkomst) staat - voor zover relevant -  het volgende opgenomen:

“(…)

Artikel 2 – Inhoud overeenkomst

(…)

2.2

De Klant zal vanaf de datum van ingang van deze overeenkomst al haar Vorderingen, die enkel betrekking hebben op de betaalmethode ‘achteraf betalen’, aan Billink verkopen en in eigendom overdragen. Billink is bereid om deze Vorderingen, onder de voorwaarden zoals vastgelegd in deze overeenkomst, te kopen en in eigendom te aanvaarden.

Artikel 3 – Koop, verkoop en levering

3.1

Koop, verkoop en levering van de Vorderingen vindt plaats door middel van een door Partijen te ondertekenen akte van ‘stille’ cessie en registratie van de akte bij de Belastingdienst, met het recht van Billink om de cessie aan de Debiteur van de Vordering mede te delen.

3.2

De Klant verstrekt Billink hierbij een onherroepelijke volmacht om namens Verkoper rechtsgeldig aktes van ‘stille’ cessie en computerprints te ondertekenen, de akte en de factoringovereenkomst te registreren bij de Belastingdienst en deze eventueel mede te delen aan Debiteuren van Vorderingen.

(…)

Artikel 4 – Koopsom, factorloon, kosten toetsing kredietwaardigheid

4.1

De Koopsom van de Vorderingen bedraagt 100% van het nominale bedrag van de Vorderingen, verminderd met een door de Klant aan Billink verschuldigd factorloon van € 2,33 per transactie excl. BTW.

(…)

4.3

Billink garandeert minimaal 97% van de aangeboden unieke Nederlandse vorderingen te kopen. Dubbele toetsingen op kredietwaardigheid (bijvoorbeeld maar niet uitsluitend op naam, ip-adres, e-mailadres) vallen buiten de gegarandeerd 97%. Zie aanvullende side note; mail 5 februari 2015 om 20u18.

(…)

Artikel 8 – Verplichtingen Klant

8.1

De Vorderingen worden 1 dag digitaal door de Klant aan Billink opgegeven via de beschikbaar gestelde API koppeling. De door de Klant aan te leveren gegevens zijn vastgelegd in de Business Rules en IT Specs
(Bijlage 1)
.

(…)

Artikel 11 – Eisen aan de Vorderingen en retrocessie

11.1

Billink draagt het debiteurenrisico van een Vordering, in die zin dat zij gehouden is tot aankoop van de Vordering  en betaling op de wijze en onder de voorwaarden als gesteld in deze Overeenkomst, indien sprake is van een Vordering:

a. waarvoor een rechtsgeldige koopovereenkomst is gesloten;

b. op een Debiteur die door Billink is geaccepteerd;

(…)

d. die gespecificeerd kan worden en met relevante bescheiden (waaronder onder meer de factuur, de koopovereenkomst) aantoonbaar kan worden gemaakt;

(…)

l. op een Debiteur die voorafgaand de overdracht door Billink kredietwaardig is bevonden;

(…) en

11.2

Indien een Vordering op enig moment niet (meer) voldoet aan de vereisten uit lid 1 van dit artikel, is Billink gerechtigd de Vordering aan de Klant te retrocederen (aan de Klant terug over te dragen) of een reservering te maken op de Koopsom.

(…)

Artikel 13 – Duur overeenkomst

13.1

De overeenkomst wordt aangegaan vanaf de datum van ondertekening (…).

Artikel 17 – Incentive

De eerste 3 maanden zijn de transacties kosteloos voor [naam 2] . Dit met een maximum van 4.000 transacties. Mocht het aantal transacties de 4.000 in de eerste 3 maanden overstijgen dan geldt het normale tarief.”.

Op de handtekeningenpagina onderaan de overeenkomst staat ‘namens Billink 	[naam 4] ’.

2.9.

De door Adivare getekende - en aan Billink toegestuurde - factoringovereenkomst

is door Billink ( [naam 4] ) niet ondertekend.

2.10.

Op 20 februari 2015 heeft Adivare per e-mail aan [naam 3] van Billink

gevraagd “When can we test the new workflows?” en vervolgens “Kun je een duidelijke

uitleg geven wat er nu precies moet gebeuren want op deze manier komen wij niet verder

(…) en wat wij moeten aanpassen”.

2.11.

Op 2 maart 2015 heeft een meeting plaatsgevonden tussen Billink, Adivare en Directpay. Naar aanleiding van die meeting heeft Billink het volgende e-mailbericht aan Adivare gestuurd:

“(…) Allereerst wil ik je namens Billink en Directpay hartelijk danken voor je tijd vandaag.

In navolging op onze meeting zijn wij momenteel de zaken aan het inventariseren. Morgenavond ontvang je voor 21u00 van ons een duidelijke eenduidige terugkoppeling over de voortgang en continuering van onze samenwerking. Naar aanleiding hiervan zullen we verder acties inplannen en afstemmen. (…)”.

2.12.

Bij e-mailbericht van 20 mei 2015 heeft Adivare aan Billink verzocht om de teveel in rekening gebrachte transactiekosten (€ 2,33 in plaats van € 0,99 per order) met terugwerkende kracht te crediteren. In dezelfde e-mail verzoekt Adivare aan Billink om aan te geven “welke orders er beschikbaar zijn voor een overname door DirectPay”.

2.13.

Op 26 juni 2015 heeft Billink naar Adivare een berekening gestuurd van de creditering van € 1,34 per order van alle orders tussen januari en juni 2015. In het e-mailbericht staat – voor zover relevant – het volgende vermeld:

“(…) Heb e.e.a. opgesomd naar aanleiding van jouw input en daarmee kom ik (volgens jouw berekening) tot de volgende cijfers:

Moet worden gecrediteerd (teveel in rekening gebracht):

- Van 26 jan – heden: 5475 transacties x 1,34 euro = 7336,50 euro

Nog te betalen door [naam 2]

- 4757 orders a 0,99 euro = 4709,43 euro

Korting voor [naam 2]

- 4000 orders a 0,99 euro = 3960 euro

Resultaat te betalen: 6587,07 euro

Zoals telefonisch aangegeven zijn wij akkoord gegaan om de 4000 orders

te crediteren op voorwaarde dat je zou overgaan naar de nieuwe overeenkomst.

Omdat dit niet het geval is geweest is in mijn ogen dit ‘cadeautje’ dus niet terecht.

Jouw argument dat je nu over een deel van de gedane orders van dit jaar geen

dekking hebt en daarmee omzet misloopt kan ik inkomen. Het niet slagen van de invoering van het nieuwe contract ligt zoals we zojuist concludeerden aan beide partijen. Roman is hier inderdaad akkoord gegaan met een credit van 4000 orders, wel ervan uitgaande dat we begin dit jaar zouden gaan rekenen met 2,33 euro per transactie. Volgens bovenstaande berekening is Billink de enige schuldige aan het niet slagen van de nieuwe samenwerking en daar ben ik het niet mee eens. Uiteraard wil ik toch graag een einde maken aan deze slepende kwestie en wil ik voorstellen om het bedrag af te ronden op 5000 euro. (…)”.

2.14.

Vanaf februari 2016 is Adivare overgestapt naar Directpay.

2.15.

Bij brief van 24 februari 2017 heeft Adivare Billink gesommeerd tot betaling van de kooprijs van 97% van alle door haar ‘ingeschoten’ vorderingen in de periode januari 2015 tot en met april 2016. Billink heeft aan de sommatie niet voldaan.

2.16.

Betalingen die nadien op de ‘ingeschoten’ vorderingen bij Billink zijn binnengekomen, zijn door Billink doorbetaald aan Adivare onder aftrek van een factorloon van € 0,99 overeenkomstig de bepalingen van de e-invoicingovereenkomst.

3
Het geschil

in conventie

3.1.

Adivare vordert – na wijziging van eis – om bij vonnis uitvoerbaar bij voorraad:

“I 	Primair: voor recht te verklaren dat partijen op 10 februari 2015, althans

Subsidiair: voor recht te verklaren dat partijen op een andere datum dan 10 februari 2015 een geldige factoringovereenkomst hebben gesloten ter vervanging van hun e-invoicingovereenkomst.

II	Primair: voor recht te verklaren dat de factoringovereenkomst tussen partijen per 18 mei 2016 rechtsgeldig is ontbonden, althans

Subsidiair: voor recht te verklaren dat de factoringovereenkomst  tussen partijen per 6 maart 2017 rechtsgeldig is ontbonden, althans

Meer subsidiair: voor recht te verklaren dat de factoringovereenkomst tussen partijen rechtsgeldig is opgezegd tegen 25 maart 2017.

III	Primair: gedaagde in conventie te veroordelen om aan eiseres tegen behoorlijk bewijs van kwijting te betalen de schadevergoeding van € 169.237,23 te vermeerderen met de wettelijke handelsrente vanaf de 21e dag na de respectievelijke factuurdata, per 23-02-2018 € 28.604,15 bedragend, een en ander te verminderen met de sinds de dagvaarding ontvangen betalingen van gedaagde in conventie, althans

Subsidiair: gedaagde in conventie te veroordelen om aan eiseres tegen behoorlijk bewijs van kwijting te betalen de schadevergoeding van € 169.237,23 te vermeerderen met de wettelijke rente vanaf het moment dat gedaagde in verzuim is geraakt, een en ander te verminderen met de sinds de dagvaarding ontvangen betalingen van gedaagde in conventie, althans

Meer subsidiair: gedaagde in conventie te veroordelen om aan eiseres tegen behoorlijk bewijs van kwijting te betalen de schadevergoeding van € 169.237,23 te vermeerderen met de wettelijke rente vanaf de dag der dagvaarding tot aan de dag der algehele voldoening, een en ander te verminderen met de sinds de dagvaarding ontvangen betalingen van gedaagde in conventie, althans

Nog meer subsidiair: in het geval eiseres in conventie geen aanspraak zou kunnen maken op schadevergoeding, gedaagde in conventie te veroordelen om tegen behoorlijk bewijs van kwijting alsnog haar betalingsverplichtingen uit de factoringovereenkomst na te komen en derhalve de aan haar aangeleverde vorderingen uit te betalen à € 169.237,23 te vermeerderen met de wettelijke handelsrente vanaf de 21e dag na de respectievelijke factuurdata, per 23-02-2018

€ 28.604,15 bedragend, een en ander te verminderen met de sinds de dagvaarding ontvangen betalingen van gedaagde in conventie, althans.

Uiterst subsidiair: in het geval eiseres in conventie geen aanspraak zou kunnen maken op schadevergoeding, gedaagde in conventie te veroordelen om tegen behoorlijk bewijs van kwijting alsnog haar betalingsverplichtingen uit de factoringovereenkomst na te komen en derhalve de aan haar aangeleverde vorderingen uit te betalen à € 169.237,23 te vermeerderen met de wettelijke rente vanaf het moment dat gedaagde in verzuim is geraakt, een en ander te verminderen met de sinds de dagvaarding ontvangen betalingen van gedaagde in conventie, althans vanaf de dag der dagvaarding tot aan de dag der algehele voldoening.

IV	Voor recht te verklaren dat géén ongedaanmakingsverplichting bestaat voor eiseres in conventie op basis waarvan zij de vóór het moment van ontbinding van de overeenkomst tussen partijen overgedragen vorderingen zou moeten terugnemen van gedaagde in conventie.

V	Gedaagde te veroordelen tot betaling van de kosten van dit geding in zowel conventie als reconventie”.

3.2.

Billink voert verweer en concludeert tot afwijzing van de vorderingen, met veroordeling van Adivare in de kosten van de procedure in conventie.

3.3.

Op de stellingen van partijen wordt hierna, voor zover van belang, nader ingegaan.

in reconventie

3.4.

Billink vordert voorwaardelijk - voor het geval de rechtbank van mening zou zijn dat er een factoringovereenkomst tot stand zou zijn gekomen én dat de onderhavige vorderingen aan Billink in eigendom zouden zijn overgedragen -, om

“primair Adivare te veroordelen tot betaling aan Billink de som ten hoogte waarvan Billink is veroordeeld in conventie, e.e.a. uit hoofde van haar recht tot retrocessie van de vorderingen welke Billink in eigendom zou hebben verkregen van Adivare, waarbij Billink het recht toekomt om deze betaling te doen geschieden middels verrekening met hetgeen zij in conventie aan Adivare verschuldigd zou zijn,

subsidiair voor recht te verklaren dat [naam 2] tekort is geschoten in de op haar rustende verplichtingen om de schade te beperken, althans daartoe al het nodige te doen, op grond waarvan Adivare schadeplichtig is geworden jegens Billink waarbij de schade die Billink in reconventie vordert, gelijk is aan hetgeen Uw Edelachtbare in conventie zou toewijzen dan wel een door Uw Edelachtbare in goede justitie te bepalen bedrag op grond van de verhaalbaarheid van de onderhavige vorderingen en

meer subsidiair in het geval dat Uwe Edelachtbare meent dat het onderhavige geding zich niet leent om hetgeen primair en subsidiair in reconventie geëist toe te kunnen wijzen,

voor recht te verklaren dat Billink bevoegd is de onderhavige vorderingen aan Adivare te retrocederen en de veroordeling van Billink in conventie niet uitvoerbaar te verklaren eerder dan dat Billink deze retrocessie redelijkerwijs heeft kunnen effectueren en voor de hoogte van het bedrag dat zij te vorderen heeft uit hoofde van de retrocessie wordt bevrijd van het voldoen van hetgeen waartoe zij is veroordeeld in conventie”,

met veroordeling van Adivare in de kosten van de procedure in reconventie.

3.5.

Adivare voert verweer en concludeert tot afwijzing van de vorderingen, met veroordeling van Billink in de kosten van de procedure in reconventie.

3.6.

Op de stellingen van partijen wordt hierna, voor zover van belang, nader ingegaan.

4
De beoordeling

in conventie

4.1.

Adivare legt aan haar vordering tot schadevergoeding primair wanprestatie ten grondslag. Zij stelt – kort samengevat – het volgende. Op 10 februari 2015 is tussen partijen een factoringovereenkomst tot stand gekomen. Dit blijkt uit de onder 2.7 opgenomen e-mail van die datum, waarbij Adivare de door Billink opgestelde factoringovereenkomst ondertekend aan Billink heeft geretourneerd. Hiermee heeft Adivare het aanbod van Billink aanvaard en is de factoringovereenkomst tot stand gekomen, aldus Adivare. Hoewel Adivare vanaf 13 januari 2015 al haar vorderingen op debiteuren aan Billink heeft overgedragen, heeft Billink de daar tegenoverstaande verkoopprijs onbetaald gelaten. Billink is aldus toerekenbaar tekortgeschoten in de nakoming van haar verplichting uit artikel 4.3 van de factoringovereenkomst om de koopprijs van 97% van de door Adivare aangeboden vorderingen – onder vermindering van het factorloon – aan Adivare uit te keren. Hierdoor heeft Adivare schade geleden voor datzelfde bedrag.

Adivare heeft ter zitting erkend dat is gebleken dat de vorderingen op de klanten van Adivare niet aan Billink zijn gecedeerd, maar stelt dat dat Billink niet ontslaat van haar verbintenisrechtelijke garantie van 97% uitbetaling van de ingeschoten vorderingen onder de factoringovereenkomst.

4.2.

Billink betwist dat er een factoringovereenkomst tussen haar en Adivare tot stand is gekomen. Zij voert daartoe – kort samengevat – aan dat Billink enkel bereid was om met Adivare een factoringovereenkomst te sluiten onder de uitdrukkelijke voorwaarde dat de kredietcheck door Adivare zou worden geïmplementeerd. Billink verwijst hiervoor naar de onder 2.4 opgenomen e-mail van 26 januari 2015, waarbij Billink de API alsmede de handleiding van de kredietcheck aan Adivare heeft toegezonden, en naar latere correspondentie en overleg tussen partijen over de wijze van implementatie. Omdat de technische implementatie van de kredietcheck door Adivare niet is gelukt, kon de samenwerking op basis van de factoringovereenkomst geen doorgang vinden en zijn partijen onder de bestaande e-invoicingovereenkomst verder gegaan, aldus Billink. Billink heeft daarom de factoringovereenkomst niet ondertekend geretourneerd aan Adivare.

4.3.

Vooropgesteld wordt dat de vordering uit wanprestatie alleen toewijsbaar kan zijn als komt vast te staan dat er een factoringovereenkomst tussen partijen tot stand is gekomen. Kernvraag is aldus of de factoringovereenkomst waarop Adivare zich beroept tussen haar en Billink rechtsgeldig tot stand is gekomen. Dienaangaande wordt als volgt overwogen.

4.4.

Een overeenkomst komt tot stand door een aanbod en de aanvaarding daarvan (artikel 6:217 BW). Daarbij dient de inhoud van het aanbod en de vraag of er overeenstemming is, bepaald te worden aan de hand van de wilsvertrouwensleer (artikel 3:33 en 3:35 BW). Er komt in beginsel geen rechtshandeling tot stand als de wil van de handelende persoon ontbreekt, tenzij er sprake is van een bij de wederpartij opgewekt gerechtvaardigd vertrouwen.

4.5.

De rechtbank is van oordeel dat er tussen partijen geen factoringovereenkomst tot stand is gekomen. De rechtbank is tot dat oordeel gekomen op grond van het volgende.

Uit de stellingen van Billink kan afgeleid worden dat - hoewel er overeenstemming was over de inhoud van de factoringovereenkomst - haar aanbod om een factoringovereenkomst met Adivare te sluiten onderworpen was aan de uitdrukkelijke voorwaarde dat de kredietcheck door Adivare zou worden geïmplementeerd. Nu vaststaat dat de implementatie van de kredietcheck niet is gelukt, kan aangenomen worden dat de wil van Billink om gebonden te zijn aan een factoringovereenkomst met Adivare ontbrak. Dat er geen sprake was van wilsovereenstemming blijkt ook uit het feit dat Billink de factoringovereenkomst niet heeft ondertekend en geretourneerd aan Adivare. Ter zitting heeft Billink hierover verklaard dat zij dit bewust niet heeft gedaan omdat de overeenkomst zonder kredietcheck niet ten uitvoer kon worden gebracht. De stelling van Adivare dat ondertekening geen vereiste is voor de totstandkoming van een overeenkomst kan haar dan ook niet baten. Voor de totstandkoming van een overeenkomst is immers wel wilsovereenstemming vereist, die gelet op het voorgaande ontbrak.

4.6.

Op grond van de wilsvertrouwensleer kan ook het bij een ander opgewekte vertrouwen een rechtshandeling doen ontstaan. De vraag is of er sprake was van een bij Adivare opgewekt vertrouwen dat Billink de factoringovereenkomst met haar wilde aangaan zonder kredietcheck. De rechtbank is van oordeel dat Adivare daarop niet mocht vertrouwen. In dat verband is het volgende van belang.

Uit de - onder 2.4 tot en met 2.7 opgenomen - emailcorrespondentie tussen partijen kan worden afgeleid dat Adivare wist of althans behoorde te weten dat de (implementatie van de) kredietcheck voor Billink een essentiële voorwaarde voor het aangaan van de factoringovereenkomst uitmaakte. Hieruit blijkt immers dat, voordat Adivare de door haar ondertekende factoringovereenkomst aan Billink heeft toegezonden, partijen uitvoerig en veelvuldig overleg hebben gehad over het implementeren van de kredietcheck. Daarbij heeft Adivare ook de API koppeling en de implementatiehandleiding van Billink ontvangen waarin expliciet staat opgenomen dat Billink “uw debiteuren op kredietwaardigheid beoordeelt” en waarin uitgelegd wordt hoe die API koppeling (inclusief kredietcheck) door Adivare geïmplementeerd kan worden. Uit de e-mails tussen partijen van 5 februari 2015 kan voorts worden afgeleid dat Adivare zich ervan bewust was dat er onder de factoringovereenkomst voor Billink een mogelijkheid was om op basis van checks klanten te mogen weigeren en dat dit voor Billink van wezenlijk belang was nu [naam 1] aangaf dat dit artikel niet gewijzigd kon worden. Dat Adivare wist dat Billink zonder kredietcheck geen vorderingen zou overnemen kan tevens opgemaakt worden uit de tekst van de factoringovereenkomst waarin in artikel 11.1 sub l staat opgenomen dat Billink alleen vorderingen koopt “op een Debiteur die voorafgaand de overdracht door Billink kredietwaardig is bevonden”.

Op het moment dat Adivare de ondertekende factoringovereenkomst naar Billink terugstuurde per e-mail van 10 februari 2015 – op welke e-mail Adivare haar stelling berust dat er overeenstemming was – was de technische implementatie van de kredietcheck echter nog niet afgerond. Dit blijkt immers uit de tekst onderaan die e-mail in een ‘ps’ dat de technische implementatie morgenochtend wordt afgerond en ook uit de latere (onder 2.10 opgenomen) e-mails van 20 februari 2015. De stelling van Adivare dat de technische implementatie al vanaf 13 januari 2015 gereed was aangezien zij vanaf die datum orders kon inschieten wordt dan ook verworpen. Deze stelling strookt bovendien niet met het feit dat eerst op 26 januari 2015 de API koppeling aan Adivare is toegestuurd welke koppeling benodigd is om de vorderingen onder de factoringovereenkomst door Adivare te kunnen inschieten (artikel 8.1 van de factoringovereenkomst). Nu de technische implementatie niet was voltooid, mocht Adivare er op 10 februari 2015 dan ook niet op vertrouwen dat er reeds overeenstemming was. Daar komt bij dat de factoringovereenkomst ook niet door Billink ondertekend aan Adivare is geretourneerd zoals zij zelf in de mail van die datum heeft verzocht.

Vaststaat dat de implementatie van de kredietcheck uiteindelijk niet is gelukt Ook staat vast dat Adivare reeds op 2 maart 2015 - binnen drie weken nadat de implementatie voltooid had moeten zijn - door Billink in contact is gebracht met een andere payment provider, Directpay, naar wie Adivare uiteindelijk is overgestapt. Uit de - onder 2.12 en 2.13 opgenomen - correspondentie tussen partijen kan voorts opgemaakt worden dat de door Billink ter voorbereiding op de te sluiten overeenkomst aangepaste tarifering - op verzoek van Adivare – in juni 2015 weer is teruggedraaid. Uit het voorgaande kan dan ook afgeleid worden dat voor beide partijen duidelijk was geworden dat de factoringovereenkomst tussen hen geen doorgang zou vinden.

4.7.

Aangezien uit het voorgaande volgt dat er tussen partijen geen factoringovereenkomst tot stand is gekomen, zal de vordering tot schadevergoeding uit wanprestatie worden afgewezen. Hetzelfde geldt voor het onder I, II en IV gevorderde, nu uitgangspunt van deze vorderingen is dat er een factoringovereenkomst tot stand is gekomen. Ook de onder III (nog meer subsidiair en uiterst subsidiair) gevorderde nakoming van de factoringovereenkomst zal op die grond worden afgewezen.

4.8.

Subsidiair heeft Adivare aan haar schadevergoedingsvordering ten grondslag gelegd dat Billink jegens haar onrechtmatig heeft gehandeld door aan de debiteuren van de onderhavige vorderingen mede te delen dat zij enkel nog bevrijdend aan Billink konden betalen, terwijl Billink wist althans behoorde te weten dat zij geen rechthebbende was met betrekking tot die vorderingen. Adivare stelt dat zij hierdoor schade heeft geleden en stelt deze schade op een bedrag gelijk aan 97% van de ingeschoten vorderingen minus de van Billink ontvangen betalingen. Adivare heeft echter niet onderbouwd dat zij daadwerkelijk schade heeft geleden. Adivare heeft weliswaar betoogd dat zij schade heeft geleden doordat de debiteuren niet rechtstreeks aan Adivare betaalden als gevolg van de mededeling van Billink aan deze debiteuren, maar zij heeft niet aangegeven op welke wijze zij als gevolg daarvan schade heeft ondervonden noch inzichtelijk gemaakt welk bedrag daarmee zou zijn gemoeid. Niet gesteld of gebleken is immers dat als Adivare zelf aan haar debiteuren zou hebben gefactureerd, een groter percentage daarvan zou hebben betaald. Daar komt bij dat Billink de bedragen die zij heeft ontvangen vanwege de door haar aan debiteuren van Adivare gestuurde facturen, heeft doorbetaald aan Adivare. De rechtbank is van oordeel dat Billink niet anders heeft gehandeld dan Adivare in de gegeven omstandigheden van haar mocht verwachten. De vordering tot schadevergoeding op grond van onrechtmatige daad zal daarom worden afgewezen.

4.9.

Adivare zal als de in het ongelijk gestelde partij in de proceskosten in conventie worden veroordeeld. De kosten aan de zijde van Billink worden begroot op:

- griffierecht	            €	         3.946,00

- salaris advocaat		6.005,00 (2,5 punt × tarief € 2.402,00)

Totaal	€ 	9.951,00

in reconventie

4.10.

De eis in reconventie is voorwaardelijk ingesteld. Uit de beslissing in conventie vloeit voort dat de voorwaarde niet is vervuld, zodat op de vordering in reconventie geen beslissing hoeft te worden gegeven. In reconventie zal geen proceskostenveroordeling worden uitgesproken, nu geen van beide partijen als in reconventie in het ongelijk gestelde partij kan worden beschouwd.

5
De beslissing

De rechtbank

in conventie

5.1.

wijst de vorderingen af,

5.2.

veroordeelt Adivare in de proceskosten, aan de zijde van Billink tot op heden begroot op € 9.951,00,

in reconventie

5.3.

verstaat dat de vordering geen behandeling behoeft.

Dit vonnis is gewezen door mr. C. Bouwman en in het openbaar uitgesproken op 30 januari 2019.

[1729/2891]
