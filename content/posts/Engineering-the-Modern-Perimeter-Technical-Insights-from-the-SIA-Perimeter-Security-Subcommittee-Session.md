---
title: "Hönnun nútíma perimetra: Tæknileg innsýn frá undirnefnd SIA um jaðaröryggi"
date: 2026-05-15T09:00:00+08:00
draft: false
type: "posts"
description: "Innsýn frá opnu húsi SIA um staðla og tækni (undirnefnd um jaðaröryggi) varðandi TVRA-ramma, auð svæði og fjarlægðarmörk frá lóðamörkum fyrir faglega hönnun öryggiskerfa."
keywords: ["jaðaröryggi", "SIA staðlar", "hönnun öryggiskerfa", "innbrotsviðvörunarkerfi", "innbrotsstjórnstöðvar"]
---

Fyrir faglega hönnuði öryggiskerfa og sérfræðinga í innkaupum í B2B geiranum á Íslandi – sérstaklega þá sem stýra flutningamiðstöðvum, gagnaverum eða iðnaðarsvæðum á Reykjanesi, Grundartanga eða við hafnirnar – er jaðaröryggi (perimeter) oft litið á sem einfalda líkamlega línu: girðingu, vegg eða hlið. Hins vegar sýndu tæknilegar umræður á **Opnu húsi SIA um staðla og tækni (14. maí 2026)** – sérstaklega innan **undirnefndar um jaðaröryggi (Perimeter Security Subcommittee)** – að iðnaðurinn er að færast yfir í flóknari „rýmisrökfræði“ (spatial logic).

Vegna krefjandi aðstæðna á Íslandi, þar sem aftakaveður, saltúði, jarðskjálftavirkni og sveiflur í fjarskiptakerfum á afskekktum stöðum skapa raunverulegar áskoranir, verður hönnun jaðaröryggis að vera tæknilega áreiðanleg. **[Athenalarm](https://athenalarm.com/)** tók þátt í þessum fundi til að brúa bilið á milli háþróaðs vélbúnaðar og vaxandi staðla fyrir mikilvæga innviði. Niðurstaðan er skýr: árangursríkt jaðaröryggi er nákvæmlega reiknað kerfi sem samanstendur af **fjarlægðarmörkum (setbacks), auðum svæðum (clear zones) og lögmætum ásetningsbufrum (legal intent buffers)**.

---

## 1. TVRA-ramminn: Sveigjanleg nauðsyn fyrir iðnaðarsvæði

Grunnurinn að hönnun hvers kyns háöryggissvæðis er **Ógnar-, veikleika- og áhættumat (TVRA — Threat, Vulnerability, and Risk Assessment)**. James, formaður TVRA-vinnuhópsins, benti á að iðnaðurinn stefni að staðluðum ramma sem hægt er að mæla og aðlaga allt frá almennum vöruhúsum til flókinna orkuvera og gagnavera.

James lagði ríka áherslu á mikilvægi skipulegrar nálgunar og benti á að markmið hópsins sé að veita **„leiðbeiningar fyrir almenna sérfræðinga til að móta hvernig þeir meta ógnir og áhættu... fyrir hvers kyns svæði.“** Þegar hannað er fyrir innviði eins og **orku- og veitukerfi** (t.d. jarðvarmavirkjanir eða tengivirki á Íslandi) verður matið að fella inn **NERC-samræmi** (eða evrópskar tilskipanir um mikilvæga innviði) og sérstakar kröfur um samfellda raforkuframleiðslu.

Á svæðum þar sem hætta er á truflunum á jarðstrengjum eða miklum rafsegulsviðum, tryggja **blendingstengi innbrotskerfi** (hybrid intrusion systems) stöðuga virkni staðbundinna skynjara. Til að tryggja að viðvaranir berist tafarlaust til **miðlægrar vöktunarstöðvar** (central monitoring station), verður hugbúnaðurinn að styðja staðlaðar **samskiptareglur viðvarana** (alarm communication protocols), eins og **Contact ID** eða **SIA-samskiptareglu**, sem lágmarkar hættuna á gagnatapi ef aðalnetsamband rofnar.

---

## 2. Formúlan fyrir „Auða svæðið“: Fjarlægð = Tími

„Auða svæðið“ (Clear Zone) – hindranalaust svæði beggja vegna girðingarinnar – er mikilvægt hernaðarlegt og tæknilegt rými. Þó að hernaðarstaðlar (**UFC**) krefjist oft gríðarlegra 15 metra (50 feta) svæða, é það sjaldan raunhæft á íslenskum iðnaðarlóðum vegna landrýmis og skipulags.

Tæknileg samstaða náðist um hagnýta nálgun. Nicholas, samræmingarstjóri SIA, fullyrti að **„fjarlægð eða autt svæði eingöngu fjarlægðarinnar vegna... er óhagkvæmt og sóun á dýrmætu landi.“** Þess í stað verður breiddin að vera tilgangsdrifin:
* **Seireloogika:** Ef þörf er á myndbandavöktun og greiningu, verður auða svæðið að tryggja fullkomið sjónsvið án blindra punkta (t.d. laust við gáma eða snjóskafla).
* **Mælikvarðinn:** Fjarlægðin verður að kaupa nægilegan **viðbragðstíma (Response Time)**. Ef [Athenalarm netkerfi fyrir viðvörunarvöktun](https://athenalarm.com/network-alarm-system/network-alarm-monitoring-system-application/) virkjar viðvörun á ytri girðingu, verður auða svæðið að vera nógu breitt til að öryggisverðir eða viðbragðsaðilar geti stöðvað snytingjann áður en hann nær að verðmætum innviðum. Þetta er sérstaklega mikilvægt á Íslandi þar sem **GSM-sendir** gæti orðið fyrir örfárra sekúndna töf vegna staðbundinna truflana á farsímakerfum í slæmu veðri, sem hefur áhrif á heildar **viðvörunarvöktun**.

[![Athenalarm netkerfi fyrir viðvörunarvöktun](https://img.youtube.com/vi/FouMQpGDZNk/0.jpg)](https://www.youtube.com/watch?v=FouMQpGDZNk) 

---

## 3. 5 metra fjarlægðarmörkin: Forðist gildru lóðamarkanna

Alvarleg viðvörun á fundinum snéri að hættunni á að setja öryggisgirðingar beint á lóðamörk (Property Line). Nicholas benti á hernaðarlegan galla: **„Að setja jaðargirðinguna nákvæmlega á eignamörk þín eru mistök, vegna þess að þá... missir þú getuna til að stjórna því hvað er safnað eða lagt upp við girðinguna þína hinum megin.“**

Í íslensku viðskiptaumhverfi (t.d. í nágrenni við flutningafyrirtæki eða verkstæði) geta safnast upp bretti, gámar eða tæki hinu megin við girðinguna. Á veturna geta myndast miklir snjóskaflar upp við girðinguna sem ekki aðeins skemma vandaðar vafningalagnir heldur valda einnig fölskum viðvörunum (false alarms) í óæðri **innbrotsviðvörunarkerfi** sem skortir snjalla síun á umhverfishávaða.

**Tæknileg besta tækni (Technical Best Practice):**
* **5 metra fjarlægðarmörk (Setback):** Þetta er ráðlagður „gullni staðallinn“.
* **Af hverju?** Það tryggir að girðingin sé laus við neðanjarðarlagnir (ljósleiðara, rafmagn, heitt og kalt vatn), kemur í veg fyrir lagalega ábyrgð á friðhelgi einkalífs (myndavélar sem slysast til að vaka yfir nágrannalóð) og myndar „gult svæði“ sem sýnir fram á ásetning sönnuðu snytingjarins um leið og farið er yfir línuna.
* **Álit sérfræðinga:** Mark, gamalreyndur sérfræðingur, bætti við: **„Ég hef aldrei á ferli mínum mælt með því að setja girðingu... nær en 3 metra (10 fet) frá raunverulegum lóðamörkum þínum, vegna þess að þú verður að geta sýnt fram á ásetning snytingjarins.“**

![Athenalarm lausn fyrir jaðarviðvörunarvöktun](https://athenalarm.com/wp-content/uploads/2022/05/network-perimeter-alarm-system-solution-1024.jpg)

---

## 4. Lagalegur ásetningur mældur með þéttleika skilta

Til ega hægt sé að sækja snytingja til saka samkvæmt íslenskum lögum verður jaðarinn að sýna fram á vísvitandi brot. Þetta er tryggt með skipulögðum þéttleika viðvörunarskilta („Bannað að fara inn“, „Rafræn vöktun“).

* **30-jarda (u.þ.b. 27 metra) viðmið:** Nicholas mælti með því að líta til staðla umhverfisstofnana: **„Skilti eða merki verða að vera innan við 30 jarda (u.þ.b. 27 metra), með skýra sjónlínu og óhindrað.“** Hann kallaði þetta **„lágmarksásættanlegan staðal.“**
* **10-jarda (u.þ.b. 9 metra) háöryggisstaðall:** Fyrir mikilvæga innviði útilokar það að tvöfalda þennan þéttleika – eitt skilti á fresti **9 metra (10 jarda)** – nánast alla lagalega vörn um að viðkomandi hafi „gengið inn fyrir slysni“. Þetta styrkir lagalegan grundvöll fyrir **innbrotsvörn fyrir fyrirtæki**.
* **Viðmið fyrir gagnaver:** Samkvæmt **ANSI/BICSI 002** staðlinum eru 30 metra (100 feta) millibil staðall fyrir merkingar utanhúss.

---

## 5. Sérhæfðir staðlar: Gagnaver og TEMPEST-vörn

Fyrir stafræna innviði (sem er vaxandi iðnaður á Íslandi vegna hagstæðs loftslags og grænnar orku) virkar jaðarinn einnig sem rafræn skjöldur. Sérfræðingar ræddu **TEMPEST** (merki- og upplýsingastýringu), þar sem auð svæði eru reiknuð út til að koma í veg fyrir að rafræn hlustunartæki (sniffing tæki) geti numið og magnað upp merki frá innri netþjónum eða **innbrotsstjórnstöðvar** (intrusion alarm panels).

| Staðall | Helsta tæknilega atriði |
| :--- | :--- |
| **ANSI/BICSI 002** | Kveður á um ákveðin fjarlægðarmörk og skiltatíðni fyrir ytri innviði gagnavera. |
| **NIST 800-53** | Einblínir á líkamlegt jaðaröryggi með skyldubundnum aðgangsskrám og öryggisfjarlægð. |
| **TEMPEST rökfræði** | Breið, auð svæði koma í veg fyrir að andstæðingar geti komið næmum skynjurum nálægt vélbúnaði. |

---

## 6. Hamlandi gróður: Græna hindrunin

Nýstárlegur hápunktur fundarins var samþætting **CPTED** (forvarnir gegn afbrotum með umhverfishönnun) með því að nota **hamlandi gróður (Hostile Vegetation)**. Nicholas vinnur nú að gagnagrunni yfir plöntur sem veita líkamlega mótstöðu (þéttar, gaddaðar) en eru samt vistfræðilega öruggar og standast harðgert norðurslóðaloftslag á Íslandi – þar með talið frost og mikinn vind.

Markmiðð er að hreyfa sig í átt að landslagsarkitektúr sem þjónar öryggishlutverki: **„Nei, við veljum ekki venjulegan skrautgróður – við notum þurrkþolinn, jarðvegsverndandi... og óyfirstíganlegan hamlandi gróður.“** Þetta bætir við skilvirkri vörn sem eyðir ekki rými og hindrar ekki sjónsvið hitamyndavéla, ale hægir verulega á snytingjum.

---

## Samantekt: Hönnun á verjanlegum perimetra

Sérfræðifundur undirnefndar SIA um jaðaröryggi sýndi að nútíma jaðaröryggi er samspil nákvæmrar verkfræði og lagalegrar stefnumótunar. Með þátttöku í þessum hágæða umræðum tryggir **Athenalarm** og samstarfsaðilar okkar að [lausnir fyrir jaðarviðvörunarvöktun](https://athenalarm.com/network-alarm-system/network-perimeter-alarm-system-solution/) eru hannaðar fyrir raunverulegar áskoranir ársins 2026 og framtíðarinnar.

**Tæknilegur gátlisti fyrir hönnuði:**
1. **Fjarlægðarmörk (Setback):** 5 metrar frá lóðamörkum til að viðhalda fullri stjórn.
2. **Auð tskon (Clear Zone):** 5 metrar að innan og utan (Fjarlægð = Tími til viðbragðs).
3. **Merkingar (Signage):** 9 til 30 metra millibil til að tryggja lagalegan ásetning.
4. **Vélbúnaður (Hardware):** Notið öflugar stjórnstöðvar eins og **[AS-9000 innbrotsstjórnstöð](https://athenalarm.com/burglar-alarm/intrusion-alarm-panel/alarm-control-panel/)** til að stýra aukinni álagi skynjara á þessum stækkuðu jaðarsvæðum.

---

## Biežák uzdotie jautājumi (FAQ)

### Hvernig koma blendingsinbrotakerfi í veg fyrir falskar viðvaranir í miklum hviðum og stormum á Íslandi?
**Með því að nota krossvöktun (cross-zoning) og snjalla merkjasíu í innbrotsstjórnstöðinni.** Í miklum roki á íslenskum iðnaðarsvæðum dugar ekki að einn skynjari virkist. AS-9000 kerfið krefst þess að tveir ólíkir skynjarar (t.d. innrauðir geislar og örbylgja) fari af stað innan ákveðins tíma glugga. Þessi tækni síar út hreyfingar á girðingum eða fuku, og minnkar falskar viðvaranir um meira en 95%, sem verndar heildar **viðvörunarvöktun**.

### Hvernig tryggja fyrirtæki á afskekktum stöðum á Íslandi stöðugt viðvörunarsamband ef ljósleiðari rofnar í jarðhræringum?
**Með því að innleiða tvíþætta flutningsleið (Dual-Path) með sjálfvirku varasambandi.** Ef aðalnetsambandið rofnar, skiptir innbrotsstjórnstöðin samstundis yfir í samþættan **GSM-sendi** sem notar tvö virk SIM-kort frá mismunandi fjarskiptafyrirtækjum (t.d. Nova og Síminn). Með því að nota **SIA-samskiptareglu** berast allar mikilvægar upplýsingar áfallalaust til **miðlægrar vöktunarstöðvar**, jafnvel við erfiðustu umhverfisaðstæður.
