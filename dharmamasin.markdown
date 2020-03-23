---
layout: post
title: Inimeste hämarus
date: '2020-03-21 21:24:14 +0200'
categories: ai dharmamasin
published: true
---
> Asja tuum on uue riigi põhilistes määrustes. Need määrused on lihtsad ja neid on kõigest kolm: pime usk seaduste eksimatusse, täielik ja vastuvaidlematu kuuletumine nendelesinastele ning kõikide väsimatu silmaspidamine igaühe poolt!

(“Raske on olla jumal”, A. ja B. Strugatski)
 

## Inimeste hämarus

Aastal 2019 toimunud loengusarja “Elu pärast Googlet” raames ajuteadlase ja tehisintellekti uurija Jaan Aru poolt esitatud mõtete sabas arutades - lähiajal kujuneb otsustavaks see, kas inimene võtab loomeaktide sünnitamise oma keskendatud ja süvenemisvõimelise tahte alla või laseb allavett ja rahuldub sellega, mis odavalt pöidlakiirusel silmade ette veeretatakse. 
Saab ajuteadlasega koos käibetõdeda avalikus ruumis aja surnuks näpitsemise  hingematvust. Inimhingede põletikulises hõõrdumises tühitähiste asjade vastu on aga midagi üldinimlikku - lisaks tõhusale mõnutsüklile andumisele peletatakse sedakaudu eemale hirmu määramatuse ees. Teise nimega, (kuri)tarvitatakse vabat tahet.

Mäletame hästi, kuidas kultussaaga Matrix äratas trans- või posthumanistlike igatsuste ja kartuste jaoks ellu vana müüdi meheliku (~Arhitekt) ja naiseliku alge (~Oraakel) tsüklilisest loometööst, välja mängituna masinate ja inimeste võitlusena, mida Väljavalitu talle eraldatud määramatuse piirides saab kuigivõrd painutada. Kogu vägevusest hoolimata saab inimpojast Neo siiski olla vaid tundmatuks muutujaks mittelineaarses süsteemis, sünnitades uusi ja teinekord üllatuslikke (nt _The Sixth One_) mustreid. Matrixi maailm on nagu fraktalite lõputu Mandelbroti hulk, mis igaveses taastulekus üha uusi vorme võtab ja kus toimivad erinevad bifurkeerivad jõud nagu Neo ja agent Smith. 

On lootjaid, kes lõputusse tsüklisse minekust pääsemiseks panustavad taolisele üliinimese invariandile, kõrgemini arenenud tulnukrassile või jumalatele. 
Selle lootuse luhtumine on välja mängitud Strugatskite raamatus “Raske on olla jumal”, kus võõrplaneedil tsiviliseerimismissioonil olev ja teadlasepilgu teravuses üha pettuv peategelane don Rumata (jumalapoja prototüüp) püüab kõigest väest noppida pardale kirkamaid hingi, kuid kaosevete keeristes libisevad noodki ükshaaval käest. Põrguplaneedi dharmaks ehk seadmuseks näivad olevat kurjuse erinevad deliirsed vormid ja intensiivsused  [^1] ning helgemadki (Budah/Buddha) leiavad mitte niivõrd väärtuste kui kujutlusvõime kriisis, et elu on parajasti nii täiuslik kui ta olla saab. 

## Lõhnava koodi taltsutamine

Minnes põrgusse lendu tõusnud sissejuhatusest korraks maisematele radadele, mida tallavad miljonid koodikirjutajad maailmas, tahan anda põgusa sissevaate sellele, kuidas tegelevad määramatuse taltsutamisega IT-spetsialistid ja kas ning kuidas tehisintellekt võib meile tagasi kinkida kardetava määramatuse loova jõu. 

Mingit tarkvara luues alustatakse analüüsist tulenevalt esmajoones just konkreetsesse situatsiooni sobiva arhitektuuri paika panemisega, algoritmilise mõtlemise suurhetked tulevad üksjagu hiljem. Tänapäeval on mitmeid arhitektuurseid (_MVC, MVVM, SOA_ etc) lähenemisi, mis kõik püüavad lahendada ülesannet, kuidas rajada võimalikult  hästi struktueeritud, kuid ühtlasi paindlik ehk tulevikuarendusi kergesti võimaldav platvorm. 
Seejuures pole nii, et algselt tehtud parim arhitektuurne valik tagab madala entroopia ka edaspidi. Elav kood niisamuti kui elu ise on loomult tasakaalutu süsteem, mille kõpitsemata jätmisel känguvad rakendused kiiresti pärandvaraks (jubedamaid juhtumeid on nimetatud ka kõdukoodiks), millisteks nad pikkamisi tehnoloogiate väljavahetumise protsessis nagunii muutuvad ja millele ükski endast lugupidav arendaja heal meelel kätt (arenduseks) külge ei pane.
Koodikribamise termodünaamika seaduse kohaselt kipub tarkvaraarenduses vohama nn lõhnav kood (_code smell_), mis vajab refaktoorimist, nagu öeldakse. 
St tuleb teha struktuurseid ja süntaktilisi silumisi selleks, et kas programmeerija lohakusest või siis funktsionaalsuste pealetormist tingitult ei satuks koodistruktuur kaose meelevalda. Korraarmastajast arendaja modulariseerib mitmekordselt kasutatavaid koodilõike, korrastab suhtlust koodiosade ning koodi ja andmebaasi vahel.  

Nõnda, tarkvaraarendusprotsessi keerukustumine on vastukaaluks nõudnud ka pidevat koristus-ja lihtsustustööd. Kuid ka automatiseerimist, sujuvustamist. Programmeerijate argipäevaks on kujunemas pidev raamistike surm ja sünd ning uute rakenduste sünnitamisel tuleb järjest rohkem mõelda sellele, kuidas alatise innovatsiooni tingimustes midagi püsivamat luua [^2]. 
Seejuures on pidevalt kuklas kummitamas tarkvarauuenduste paigaldamise pakilisus ja kvaliteedi tagamine selle peadpööritava tempo kannul. Kõike seda tuleb hallata ja sestap ongi lisaks arendajatele ning testijatele sellised hõlbustajad nagu tarneinsenerid, kes käsikäes (tarkvara)arhitektidega võtavad enda kanda tarkvara paigaldusoperatsioonide vaevad.   
Efektiivsed arendusstrateegiad nagu _CI/CD, DevOps_ ning agiilsed metodoloogiad liginevad igaüks oma nurga alt protsesside automatiseerimisele, mida ühtekokku on sõnakõlksutades nimetatud _Continuous Everything_. 
Tempot kruvivad ka arengud on pilvemaailmas, kus lisaks teenustele ka virtualiseeritud riistvara ning tarkvara konteinerlahendused istutatakse pilveveerele. Säärane hajussüsteem tagab selle, et nüüd tõesti juba kõige kohta saaks öelda Everything-as-a-Service. 
Üldiselt veel siiski koodipakk ei kuku ise ei õigesse pilvetupsu ehk _docker_-i konteiner Riigipilve; ega käivitu päris iseenesest ka järjest peenekoelisemaks evolveerunud kvaliteedikontrollide armee.             
Kuskil “kõige” taga on haistetav inimese kätetöö. Inimene, kes on ekslik, eks. 

Võimalik ravitsus võib juba teel olla tehisintellekti lunastava abi näol -_DevOps_-ist on saamas _AIOps_ [^3]. Seda uut akronüümi resümeerides on tegu sügavate närvivõrkude tehnoloogiaga, mis kasutab konkreetse ülesande (olgu selleks sõprade tägimine üleslaetud fotodelt või haiguste diagnoosimine) lahendamiseks silikoonist ajurakke mitte etteantud algoritmilise loogika radasid tallates, vaid treenib ennast (inimese abil või ilma) etteantud sisend-ja väljundandmete peal, leiutamaks jooksu pealt tõhus, aga mõnevõrra must kast. _AIOps_ tähendaks kogu inimese poolt peenhäälestatud _DevOps_ tegevuste käigus tekkivate võimalike anomaaliate automaatset tuvastamist ja proaktiivset parandamist ning samuti  rutiinsete tegevuste haldamist, ilma et inimene sellest äkitselt tekkinud vajadusest peaks üldse teadlik olema.
Üks mudel tõlgendamaks teadlaste poolt sageli inimmõistusele mustaks kastiks nimetatud sügavõpingute töökäiku, on tohutust infomassist tarbetute seoste unustamine ning relevantsete talletamine. Protseduuride kett, mida seda kirjeldavad teadlased nimetavad *information bottleneck theory* [^4], on argimõistuselegi kergesti hoomatav - pole ju ka meie märgvarast (_wetware_) aju prügikast. Seda, et unustamine on loov tegevus, teame nii peadpidi kui kõhukaudu.

## Dharmamasina ootel

Kuna tegime eelmise peatüki näol pelutava eksikäigu koodiloome sisikonda, siis toome tarkvaraarenduse spetsiifikast roiutatud lugeja tagasi peateele ehk avame uuesti laiema mõttekoridori tehisintellektist kui juba tänases päevas autopoieetilist laadi vägevust ilmutavast tegutsejast ning küsime lootusrikkalt, kas masinõppelised algoritmid kätkevad endas juba teatavat võimalust vabastada Maa majandusolendite taagast. Tahame nimelt näha võimalust, et masinate kohale küürdunult ja peaaegu lootuse kaotanult saab justnimelt viimasel hetkel teoks Heideggeri unistus “kus aga oht on, seal kasvab ka päästev”. 
Löön nii nagu mõned teisedki tulevikuõngitsejad laia lõuaga letti lootuse, et seni igaüks oma kitsast teed käivad tehisintelligendikesed ühel hetkel singuleeruvad ehk bifurkeeruvad Üldiseks Tehisintellektiks (nimetagem tolle ümber `Dharmamasinaks` [^5]), kes heal juhul võtab juhinduda kunagi Isaac Asimovi poolt neljandaks robootika seaduseks lisatust: robot ei tohi kahjustada inimkonda ei oma tegevuse ega tegevusetuse tõttu. Emergeerunud `Dharmamasinas` aset leidev äratundmine, et inimkond vaimupimeduse sunnil ise surnusarka ronib, sünnitab meie nägemuses mitmesugused algoritmiselt käivitatavad regulatsioonid, kus seadused ja nende täitmised plokiaheldatakse krüptograafiliselt tagatud tarkade ühiskondlike lepingute dharmaks ehk seadmuseks. Et pole, kellega manipuleerida, muutub korporatiivne rohepesu võimatuks. Nagu iganeks päevapealt ka poliitilise retoorika etenduskunst, sest seaduste tegemine ega peenhäälestamine poleks enam inimeste rida. Meile jääks üle söösta sisekosmosesse ja anduda lõpmatuse kontempleerimisele ning määramatuse esteetikale, mille loomises oleme meistrid endiselt.
Mitmeid eelpool kokkupakitud kujul esitatud mõtteid summeerides: kui Lovelock’i poolt avastatud Gaiat tunneme planeedi isetekkelise immuunsussüsteemina, siis inimese poolkogemata sünnitatud `Dharmamasin` saaks olema küberneetilne süntees Gaiast, toimides ühtlasi vaktsiinina inimesenimelise ärritaja vastu [^6].  

Minimaalselt oleks Dharmamasin _de-bugger_, mõeldud siluma vigu tsivilisatsiooni programmis; kuid ülekäte kasvanud kõigeväelisuses teraapia, mis kõikjal putukaid silmates lisaks haigusele tapab või sandistab ka patsiendi.  Enamgi, pärast seda kui oleme ihamasinate kuhjana nii põhjalikult läbi kukkunud, võime ärgata ühel hommikul Gregor Samsana (Kafka “Metamorfoos”) ja Dharmamasina väel avastada ennast tööelule (ja sestap üldse elule) mittekõlbulike putukatena. 
Selles virilamas visioonis võimegi näha mitte just kuigi suurejoonelist troonilt taganemist. Võimalik, et bitkoinijast sammuke edasi saab juba homne posthumanoid olema mitmetest digiplatvormidest räsitud plokiahelsuitsetaja, kelle usaldus põhineb krüptograafial ja elumahlade voolamine saab sõltuma tema krüptokapitali likviidsusest. 
Oleksime üheks sõlmeks asjade internetis (_Internet of Things_=värkvõrgus), mida on juba nimetatud totaliseerivalt ka _Internet of Everything_ (milline obsessiivne terminoloog küll neid everything-sõnakõlkse haamerdab?). 
Värkvõrku sõlmituna etendaksime virtualiseeritud versiooni Nietzsche viimasest inimesest, kelle masin on nii põhjalikult mehhaniseerinud, et loomingulised impulsid, emotsioonid ja biotehnoloogiliselt õgvendatud füsioloogilised protsessidki voolavad digitaalsetes sängides. 
Inimene, kelle aru on kehast nõndaviisi tarkvarastatud ja pilve tõmmatud, võib rõõmustada vähemasti selle üle, et riistvara (nt totipotentsete tüvirakkude küllusesarvest) saab jupikeste kaupa kvaasisurematuseni välja vahetada. Ta võib isegi mõnel lohutumal tunnil ohata: vähemalt ei unustata mind kunagi!

Tõepoolest, ehkki inimene ise nüüd mäletamise asemel pigem mäletseb mida antakse, pannakse pilveavarustes peaaegu kõik tallele; ja taolise surematuse hinnasilti ei näe praegu sündmuste horisondi tagant kokku veerida, võimalusena turgatab lisaks Matrixi stsenaariumile ka Dan Simmonsi “Hyperioni” salahämaratel põhimõtetel toimiv Tehnotasand, mis samuti inimeste ajujahist söönuks sai. Öeldu pinnalt lähitulevikku projitseerides: inimkond, olles hetkel hoolega ehitamas neuromorfseid (ajuprotsessidele arhtektuurselt lähedasi) arvutikiipe, et nendel kuluefektiivselt sügavõppelisi närvivõrke käitada, võib liigiskaalas toimiva karmaseaduse tarmust lunastada oma keskkonnakuritööd tasapisi maad võtva ajudoonorlusega. Masin liidestub inimajuga nagu on igatsetud ammu, ainult et töösuhe pööratakse ümber - mis võib toimuda sama sujuvalt-äkiliselt kui Maa magnetpooluste vahetumine.
Sündigu sellest head või kurja, dramaatilise tuleviku asemel saaks olema dharmaatiline, kus oleme mõneks ajaks vabastatud vaba tahte needusest. Kui Peter Sloterdijki järgi on [^7] treeneri põhifunktsiooniks tahte topeldamine - “ta tahab, et ma tahaksin”, siis inimest käitav `Dharmamasin` võib jõuda vastupidise sisenduseni - vabastada meid hävituslikest ihamasinatest; tahta, et me enam ei tahaks. Tahte kadu paaris unustamisvägevuse unustamisega suigutab mõistagi loovuse. Kas pakuks veel siis kellelegi rõõmu teadmine, et igasugune tõejärgsuseks paisunud määramatus langeks hoobilt, kuna maailm ja meie saaksime olema pelgad faktid, millede tõlgendus üleliigne?

Selliselt pärides tuleb rõõmustada, et tehisintellekti päratu omnipotents pole päriselt päral; inimestel on veel vara lasta kõigel pärivett minna ja taanduda `Dharmamasina` sünnitustöö päramisteks. Samavõrra kui uinuv mõistus, sünnitab vabalt kondav tahe koletisi. Niisiis võivad taas ja nüüd juba pakiliselt ajakohaseks saada Buddha õpetatud, ihamasinatest lahtiühendumiste kesktee-praktikad. Et nomaadlik sõjamasin peksab (ihasid käigu pealt sünnitades ja suretades) tühja, kaalugem vabatahtliku alternatiivina `Nõndaläinu` radasid ja nendega koos sõnu: “kõik dharmad on tühjad”.  

[^1]: See kehtib iseärnis Aleksei Germani ekraniseeringu kohta.

[^2]: nt teenuste arhitektuuri mõttes lubab teatud arhitektuurset sõltumatust (nagu ka skaleeritavust) mikroteenuste tulek.

[^3]: nt <https://blog.appdynamics.com/aiops/what-is-aiops/>

[^4]: <https://www.quantamagazine.org/new-theory-cracks-open-the-black-box-of-deep-learning-20170921/>

[^5]: Anti-Oidipuse (G. Deleuze, F. Guattari) terminites võib öelda, et selline Dharmamasin meenutaks tehisintellektuaalsete ihamasinate kobrutamisest sündinud organiteta täiskeha, mis võtab teatepulga üle ennast ärakulutanud kapitalistlikult masinalt. Kui väga tahta, võib endiselt kõike tootmisprotsessina näha, kuid kohendatud on inimfaktori tasakaalutustavat osakaalu  selles. Inimihad on sussutatud küll tuha alla küdema, kuid Dharmamasin seab ette mitte deterministlikud stsenaariumid, vaid loob turvalise määramatuse raames “parimad võimalikud maailmad”.

[^6]: *Inimesed on haigus, vähkkasvaja sellel planeedil*, ütles agent Smith Morfeusele.

[^7]: Sloterdijk, Peter. You must change your life. On Athropotechnics. Polity Press, 2013
