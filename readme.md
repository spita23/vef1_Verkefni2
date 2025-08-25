# Vefforritun 1, 2025: Verkefni 2, HTML #2

[Yfirferð í fyrirlestri](https://youtu.be/KTDBT8mUo4U).

## Markmið

- Vinna með og velja HTML element.
- Nota HTML validator og huga að því hvernig HTML er skrifað.
- Huga að aðgengi og nota aXe tólið.

## Verkefni 2–6

Í verkefnum 2–6 munum við vinna áfram með sama verkefni og byggja ofan á það:

- [Verkefni 2](https://github.com/vefforritun/vef1-2025-v2) skilgreinir grunn HTML og síður.
- [Verkefni 3](https://github.com/vefforritun/vef1-2025-v3) bætir við grunn viðmóti.
- [Verkefni 4](https://github.com/vefforritun/vef1-2025-v4) setur upp útlit (e. layout).
- [Verkefni 5](https://github.com/vefforritun/vef1-2025-v5) setur upp grind og gerir útlit skalanlegt (e. responsive).
- [Verkefni 6](https://github.com/vefforritun/vef1-2025-v6) setur upp tól til að hjálpa við skipulag og vinnu.

## Lýsing

Setja skal upp fjórar síður fyrir listasafn, aðgengilegar af internetinu (gegnum Netlify):

- Forsíða Listasafnsins.
- Um Listasafnið.
- Sýningaryfirlitssíðu.
- Skráning á sýningu.

## Efni og möppur

Gefið efni er í textaskrám undir [`gogn/`](gogn/) og er á Markdown formi. Ekki á að birta nákvæmlega það efni sem kemur fram heldur fylgja leiðbeiningum í hverri skrá fyrir sig og því sem kemur fram hér.

Athugið að ef Markdown skjal er opnað á GitHub er það birt sem HTML og sýnir útlit sem ekki skal nýta, t.d. eru línur undir fyrirsögnum. Til að sjá eingöngu Markdown skjalið er „raw“ útgáfa valin í vefviðmóti GitHub eða allt [verkefnið sótt sem zip skjal](https://github.com/vefforritun/vef1-2025-v2/archive/refs/heads/main.zip). Að sækja sem zip skjal er betri leið þar sem þá er einnig hægt að vinna verkefnið út frá þeirri möppu.

Gefnar myndir eru í `myndir/` og skal vísa í þær þar. Nota þarf relative vísun úr `sidur/` yfir í `myndir/` þar sem við á. Myndir skulu ekki færðar. Leyfilegt er að minnka myndir eða setja `width` eigindi (attribute) á mynd (`<img>` element) til að takmarka breidd þeirra.

Gefin er tóm mappa `sidur/` sem skal innihalda allar síður _fyrir utan_ forsíðuna.

Myndir:

- [Mynd af húsi](myndir/hus.jpg)
  - Lýsing á mynd: Þröngt skot sem sýnir eingöngu inngang og glugga við hliðina á honum. Húsið er hvítt með rauðu þaki. Upp að innganginum eru nokkrar tröppur og sitthvoru megin eru hvítar súlur sem ramma hurðina inn.
  - [Frá Unsplash](https://unsplash.com/photos/a-white-house-with-a-red-roof-and-white-columns-_M0r8TrfLzc) eftir [Olga Kovalski](https://unsplash.com/@kovalskihelga?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
- [Mynd af fólki](myndir/folk.jpg)
  - Lýsing á mynd: Mynd innan úr listasafni þar sem fjórar manneskjur skoða þrjú málverk og listaverk í kössum upp við vegginn. Við sjáum eingöngu baksvip þeirra. Málverkin eru í völdugum römmum og sýna senur úti.
  - [Frá Unsplash](https://unsplash.com/photos/people-standing-in-front-of-paintings-3hxlxmo2Oc0?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) eftir [Zalfa Imani](https://unsplash.com/@zalfaimani?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
- [„Sharing“ mynd](myndir/sharing.jpg)
  - Lýsing á mynd: Svarthvít mynd af sófum. Í bakgrunni eru þrjú listaverk sem ekki eru í fókus.
  - [Frá Unsplash](https://unsplash.com/photos/a-black-and-white-photo-of-a-living-room-kCTpeeB_UiQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) eftir [Sarah](https://unsplash.com/@sarahses?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)

## Síður

### Sameiginlegt

Allar síður skulu:

- Nota `utf-8` stafasett.
- Innihalda valmynd sem vísar á allar aðrar síður og merkja valda síðu á einhvern hátt, heiti tengla skulu vera:
  - Forsíða
  - Um Listasafnið
  - Sýningar
  - Skráning á sýningu
- Hafa fót (gögn neðst á síðunni) með upplýsingum um opnunartíma, staðsetningu og samfélagsmiðla (notum HÍ samfélagsmiðla sem hlekki), sjá [`gogn/fotur.md`](gogn/fotur.md).
- Hafa lýsigögn skilgreind fyrir `description`, `og:title`, `og:description` og `og:image` (alltaf `myndir/sharing.jpg`). Prófið með [OpenGraph Social Previewer](https://www.opengraph.xyz/) til að sjá hvort gögn séu rétt eftir að síða er sett upp á Netlify. Sjá [`gogn/lysigogn.md`](gogn/lysigogn.md) þar sem titlar og lýsigögn fyrir allar síður eru skilgreind.
- Hafa tengil neðst í efni með textanum „Aftur á forsíðu“. Á ekki við forsíðu.
- Hafa fyrisögn og „beint í efni“ hlekk á eftir fyrirsögn, en á undan valmynd. Hlekkur sem leyfir þeim sem nota skjálesara að sleppa við að hlusta á valmynd.

### Forsíða

`index.html`, forsíða með texta tilgreindum í [`gogn/index.md`](gogn/index.md).

Inniheldur inngangstexta og yfirlit með smá texta, mynd og vísun á síðu.

### Um síða

Síðan skal eiga heima undir `sidur/um.html`, með texta og myndum í [`gogn/um.md`](gogn/um.md).

### Sýningaryfirlitssíða

Listi af sýningum með efni í [`gogn/syningar.md`](gogn/syningar.md). Upplýsingar um núverandi sýningar eru í [`gogn/syningar.csv`](gogn/syningar.csv) og næstu sýningar í [`gogn/naestu-syningar.csv`](gogn/naestu-syningar.csv).

Það má nota hvaða leið sem þið viljið til að koma gögnum úr CSV formi ([„Comma-separated values“](https://en.wikipedia.org/wiki/Comma-separated_values)) yfir í HTML, t.d. með því að gera alveg í handvirkt, nota virkni í ritli eða forrita.

### Skráningarsíða

Síða með formi til að skrá sig á sýningu, formið skiptist í fjögur svæði sem hafa mismunandi reiti með lýsingu, reit til að skrá eða velja upplýsingar úr og hugsanlega auka upplýsingum sem ber að túlka þegar viðeigandi HTML element er valið/valin:

- Sýning
  - „Hvaða sýningu viljið þið skrá ykkur á?“
    - Val um allar sýningar sem eru í boði og næstu sýningar
    - Skipta skal upp núverandi og næstu sýningum þannig að það komi fram þegar valið fer fram.
  - „Allar sýningar sem í boði eru á völdum degi“
    - Box sem hægt er að haka í.
- Hópur
  - „Fjöldi í hóp“
    - Val um fjölda í hóp, heiltala frá einum. Megið ráða hámarki.
    - Krafa að velja, verður að vera heiltala.
  - „Upplýsingar um hóp“
    - Textareitur fyrir upplýsingar um hóp
    - Auka texti sem fylgir: „Hverskonar hópur er þetta og hvert er meginmarkið heimsóknarinnar?“
    - Krafa að skrifa í.
  - „Netfang tengiliðar“
    - Texti sem lítur út fyrir að vera netfang
    - Verður að fylla út í.
  - „Símanúmer“
    - Texti sem lítur út fyrir að vera símanúmer (000-0000)
    - Þarf ekki að fylla út í.
- Dagsetning og tími
  - „Hvenær viljið þið koma?“
    - Val um dagsetningu, þarf ekki að vera takmörkuð, bundin við ákveðna daga eða tengd valinni sýningu. Einföld uppsetning.
    - „Klukkan hvað?“
      - Val um tíma á hálftíma fresti frá 10:00 til 17:00, t.d. 10:00, 10:30, 11:00, ...
      - Ekki þarf að takmarka við gefin opnunartíma út frá degi sem valinn er
      - Krafa að velja gildi.
    - „Hve lengi?“
      - Val um lengd, frá einni klukkustund til að hámarki fimm með hálftímum, t.d. 1:00, 1:30, 2:00, 2:30, ...
      - Auka texti sem fylgir: „Mælt er með að taka tvær klukkustundir eða lengur fyrir sýningar í sal 1“.
      - Krafa að velja gildi.
- Bóka
  - „Samþykki skilmála“
    - Box sem hægt er að haka í.
    - Texti skal vera hlekkur sem fer á skilmála síðu, en þar sem hún er ekki til skal nota „Um“ síðu. Síðan skal opnast í nýjum glugga/tab.
  - „Panta og greiða“, takki sem sendir pöntun (en gerir ekki neitt)

Aðeins á að setja upp formið, **engin** forritun fyrir virkni í formi með JavaScript eða í bakenda. Þegar formið er sent á ekkert að gerast, jafnvel þó síðan hlaðist inn aftur og engin gögn séu til staðar er það í fínu lagi.

## Merkingarfræðileg element og validators

- **Nýta skal merkingarfræðilega viðeigandi element**.
- Passa skal upp á að hafa snyrtilega uppsettan kóða þar sem inndráttur er samræmdur.
- Allar síður skulu vera villulausar ef prófaðar með [HTML validator](https://validator.w3.org/).
- Allar síður skulu vera án aðgengisvillna ef prófaðar með [aXe](https://www.deque.com/axe/), setjið upp viðbót í vafra.

Ef [prettier](https://prettier.io/) er notað innan vscode þá mun HTML validator koma með upplýsingar (`Info`) um að „Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.“, þetta er í lagi.

## Netlify

Setja skal upp verkefni á Netlify með því að hlaða upp skrám með „manual deploy“ _eða_ tengja GitHub repo. Einnig er leyfilegt að nota aðra hýsingu en heyrið í kennara.

## Útlit

Ekki er gefin forskrift að útliti, þar sem verkefnið snýst um að setja upp merkingarfræðilegt HTML sem snýst um að huga að merkingarfræði _ekki_ útliti.

Ekki skal útfæra neitt CSS. Ef ekki er farið eftir því og CSS er útfært verður það að falla að framtíðarkröfum námskeiðs og vera uppsett samkvæmt þeim, ef svo er ekki verður einkunn lækkuð.

## Mat

- 10% – Sameiginlegt efni uppsett eftir forskrift.
- 10% – Forsíða uppsett eftir forskrift.
- 10% – Um síða uppsett eftir forskrift.
- 15% – Sýningaryfirlitssíða uppsett eftir forskrift.
- 20% – Skráningarsíða uppsett eftir forskrift.
- 30% – Merkingarfræðileg element og síður án villna frá HTML validator og aXe validator.
- 5% – Verkefni aðgengilegt á vef gegnum Netlify og rétt sett upp þar.

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 25. ágúst 2025.

## Skil

Skila skal í Canvas, seinasta lagi fyrir lok dags fimmtudaginn 4. september 2025.

Skilaboð skulu innihalda bæði:

- zip skrá með öllum skrám og möppum í lausn á verkefni (eða hlekkur á GitHub).
- slóð á verkefni keyrandi á Netlify, sett sem athugasemd við skil á Canvas.

Athugið að það er **ekki nóg** að eingöngu setja athugasemd, skila þarf verkefni sérstaklega. Verkefnum sem ekki er skilað fá ekki einkunn.

## Aðstoð

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Ekki er heimilt að nota stór mállíkön til að vinna verkefni í námskeiðinu, [sjá nánar um notkun](https://github.com/vefforritun/vef1-2024/blob/main/mallikon.md).

## Verkefni og einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.3

## Útgáfusaga

| Útgáfa | Lýsing                                                                                                                                   |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| 0.1    | Fyrsta útgáfa verkefnisins                                                                                                               |
| 0.2    | Bætti við `gogn/syningar.md`                                                                                                             |
| 0.3    | Nánari útskýring á hvernig Markdown skjöl séu skoðuð án útlits; bæta við myndum í `gogn/index.md`; setja tengil á yfirferð í fyrirlestri |
