---
tags:
  - building
  - location
---
# Helyszínek
## Főbejárat (1)
A főkapu az 1-es és 2-es területek között bronzborítású fából készült, de korrodált és összeomlott.

> [!recite|background-color-brown no-t] 
> A kastély hét különböző méretű és magasságú omladozó toronyból áll, de a felső szintek különböző mértékben összeomlottak. Rövid lépcsősor vezet fel egy teraszra a főbejárat előtt. A kettétört kapuk maradványain túl egy árnyékos csarnok húzódik. A bejárat fölött kör alakú tornyok magasodnak, sötét nyílásrések merednek a teraszra.

Itt nem találhatóak szörnyek, de a 3-as területen lévő goblin őröknek figyelniük kellene. Azonban csak ritkán pillantanak ki a nyílásokon, így a csendesen mozgó karakterek könnyen átosonhatnak. Minden karakter dobjon egy Ügyesség (Rejtőzés) próbát. A legalacsonyabb dobás lesz a DC a goblinok Bölcsesség ellenőrzéséhez, hogy észreveszik-e a csoportot.

## Becsapdázott előtér (2)
Ez a széles csarnok, amely valaha a kastély előcsarnoka volt, most veszélyes harctérré vált.

> [!recite|background-color-brown no-t] 
>Az ajtók zárva vannak északon és délen, míg a déli csarnokot részben eltakart omladék borítja. Keleten egy széles folyosó végződik két további ajtóval, amelyek délre és keletre nyílnak. A folyosót poros törmelék és lehullott vakolat borítja, a mennyezet részleges beomlása miatt.

Ha a 3-as területen lévő goblin őrök riasztottak, a 4-es és 6-os területen lévő goblinok és hobgoblinok egyszerre rohannak ki az északi és déli ajtókon, hogy megtámadják a kalandozókat és kiszorítsák őket a kastélyból.

```encounter
name: Előtér nehezített harc - riasztott ellenségek
creatures:
 - 1: Hobgoblin Shaman
 - 3: Hobgoblin
 - 4: [[Goblin, Goblin archer]]
```

### Csapda

A vakolat és a törmelék, amely az 8-as területre vezető ajtó előtt található, egy réz huzalcsapdát rejt, amely rejtett tartóelemekhez van kötve a romos mennyezeten. A huzal észrevétele legalább 20-as passzív Bölcsesség (Észlelés) pontszámot, vagy egy sikeres DC 10-es Bölcsesség (Észlelés) próbát igényel, ha a karakterek aktívan keresik a csapdákat. Miután észrevették, a huzal könnyen kikerülhető és hatástalanítható (nem szükséges további próba).

Bármely lény, amely a törmelék fölött vagy között áthalad anélkül, hogy elkerülné a huzalt, beindít egy omlást, amely fagerendákból és nehéz kövekből áll. (Az omlás területe a térképen van jelölve.) Az érintett területen tartózkodó lényeknek DC 10-es Ügyesség mentődobást kell tenniük. Aki elbukik, 3d6 zuhanási sebzést szenved el, sikeres mentődobás esetén ennek felét. Az omlás zaja riasztja a 3-as, 7-es, 8-as és 9-es területeken lévő szörnyeket.

#### Fejlemények
A csapat triggerelte a csapdát, így riasztva lettek a környező területek.

## Főbástyák íjász állásokkal (3)
A Cragmaw Kastély fő védelme a titkos elhelyezkedése és az elhagyatottság látszata. Emellett Grol király őröket helyez el, hogy elijessze a túl közel merészkedő betolakodókat.

> [!recite|background-color-brown no-t] 
> Ez a kis szoba tele van törmelékkel. Az ajtóval szemben lévő nyílásrés kiváló tűzvonalat biztosít a kastélykapu előtti teraszra.

Minden szobában két [[Goblin|goblin]] őr található. Felváltva lőnek ki nyilakat, majd visszabújnak, így minden körben képesek támadni a kívül lévő célpontokat. Ha a karakterek belépnek a szobába, a goblinok eldobálják rövid íjaikat és közelharci fegyvereiket húzzák elő.

```encounter
creatures:
  - 2: [[Goblin, Goblin archer]]
```

## Beomlott barakkok (4)
A Cragmaw goblinok a kastély minden elérhető területét kihasználják.

> [!recite|background-color-brown no-t] 
>A kastély délnyugati tornya alig több, mint egy törmelékhalom. Több szakadt matrac hever a megmaradt padlófelületen, és egy kis, kanyargós átjáró vezet keletre a romokon keresztül.

Három goblin lakik itt. Bár a törmelék veszélyesnek tűnik, a torony stabil, és a keleti átjáró biztonságos.

```encounter
creatures:
  - 3: Goblin
```

### Fejlemények
Bármilyen nagyobb zaj itt felkelti a figyelmét a 7-es területen lévő goblinoknak. Egy goblin jön, hogy kivizsgálja a zavart. Ha nem tér vissza, vagy ha veszélyt észlel és riasztást ad, a többiek is elindulnak kivizsgálni.

## Raktár (5)
A Cragmaw törzsfőnökök a High Road és a Triboar Trail mentén fosztogattak, hogy ellássák a kastélyt élelemmel és felszereléssel.

> [!recite|background-color-brown no-t] 
> Régi hordók sózott húsokkal és rothadó gabonával teli zsákok töltik meg ezt a raktárhelyiséget. A készletek között egy véres láncinget, egy nehéz számszeríjat és egy hüvely nélküli hosszúkardot látsz, amelynek markolatába Neverwinter emblémája van belevésve.

Bár ezek a készletek emberi mértékkel mérve ehetetlenek, a goblinok még elviselik őket, ha nincs frissebb élelem.

Egy kisebb hordó azonban kivételes minőségű törpe pálinkával van tele, amelyet a goblinok figyelmen kívül hagytak a hordó mérete miatt. A hordó tartalma húsz pohárnyi pálinkának felel meg. Egy karakter, aki megiszik egy pohár pálinkát, visszanyer 1 életerő pontot. Azonban ha egy órán belül két pohárral fogyaszt, egy órára a [[Conditions#Poisoned|Mérgezett]] állapotot kapja.

### Sildar felszerelése
A láncing és a hosszúkard [[Sildar Hallwinter]] tulajdona. Sildar hálás, ha legalább a hosszúkardját visszakapja.

## Hobgoblin barakkok (6)
A Cragmaw törzs különböző goblinoidokból áll, néhány bugbear vezetősködik a nagyobb számú, nyomorúságos goblinok és néhány hobgoblin fölött. A hobgoblinok azon mesterkednek, hogy idővel elűzzék a bugbear-eket és átvegyék a hatalmat, de jelenleg a bugbear-ek még túl erős fenyegetést jelentenek.

> [!recite|background-color-brown no-t] 
> Négy egyszerű szalmával töltött ágy és matrac sorakozik a barakk padlóján. A falakon tartókban különféle fegyverek – lándzsák, kardok, buzogányok és más eszközök – találhatóak. Az északi falon sérülésnyomok láthatóak, de a padlót megtisztították a törmeléktől.

Négy hobgoblin van elszállásolva ebben a szobában. Mivel a goblin szomszédok állandóan összetűznek egymással, nem figyelnek a 2-es vagy 3-as területeken keletkező zajokra. Azonban gyorsan reagálnak, ha betolakodók tűnnek fel a tornyon belül, vagy ha a goblin őrök riasztást adnak.

```encounter
creatures:
  - 1: Hobgoblin Shaman
  - 3: Hobgoblin
```

### Kincs
A falakon öt lándzsa, négy hosszúkard, három buzogány, két nagy kard és egy díszes negyedbot van elhelyezve. A negyedbot stilizált tollakkal van díszítve, meglepően könnyű (kb. 0,5 kg), és 10 aranyat ér.

### Fejlemények
Mivel elbarikádozták magukat egy órára a kalandorok a 7-es terem kipucolását követően, az alatt az egy óra alatt rájöttek a 3-as területeken őrködő goblinok, hogy baj van, és riasztották a 6-os terem hobgoblinjait.

## Bankett terem (7)
A kastély ura egykor pazar banketteket és táncmulatságokat rendezett itt. Most ez a terem undorító goblin étkezővé vált.

> [!recite|background-color-brown no-t] 
> A nagy terem nyugati része egy törmelékfalban végződik, de a többi része még épen maradt. Ez egykor a kastély bankettterme lehetett, 7,5 méter magas boltíves mennyezettel. Két nagy faasztal egyszerű padokkal áll a terem közepén, és egy réz tűzrakó tele izzó parázsló szénnel van elhelyezve az egyik sarokban. A táblákon piszkos edények, félig megtöltött leveses fazekak, penészes kenyérsarkok és megrágott csontok hevernek.

Ebben a teremben hét szerencsétlen goblin tartózkodik, valamint a vezetőjük, egy kövér, zsémbes goblin, akinek neve [[Yegg]]. Yegg a [[Cragmaw Törzs]] fő szakácsa, és kegyetlenül terrorizálja a vonakodó segédeit, miközben az ételkészítéssel foglalatoskodnak. Ha Yegg meghal, a még élő goblinok keletre vagy nyugatra menekülnek, elkerülve a déli ajtót a 2-es területen lévő csapda miatt.

```encounter
creatures:
  - 1:
     creature: Goblin
     name: Yegg
     hp: 12
  - 6: Goblin
```

## Sötét terem (8)
Még nappal is teljesen sötét van ebben a teremben. A szöveg feltételezi, hogy a karakterek sötétlátással rendelkeznek vagy fényforrást használnak.

> [!recite|background-color-brown no-t] 
> Ez a magas, szűk csarnok egykor egy kápolna vagy szentély része lehetett. Angyali alakokat faragtak a terem felső részére, amelyek a padlóra tekintenek. Északon nehéz függönyök takarnak el két boltíves átjárót. Az átjárók között egy megrepedt, díszesen faragott kő tűzrakó található.

Ebben a teremben egy [[Grick]] nevű szörny található, a goblin [[Lhupo]] különleges kedvence. A Grick szeret a szobor árnyékos rejtekhelyére felmászni, és csendben figyelni az érkezőket, mielőtt lecsapna. A Grick Ügyesség (Rejtőzés) próbáját hasonlítsd össze a karakterek Bölcsesség (Észlelés) próbáival (vagy passzív pontszámaival), hogy meghatározd, ki lesz közülük meglepett. A Grick tudja, hogy goblinokat nem ehet meg, hacsak Lhupo nem ad engedélyt. A többi Cragmaw goblin retteg ettől a lénytől, és általában kettesével vagy hármasával mernek csak áthaladni ezen a termen.

Bármely pap, aki megvizsgálja a kápolna díszítését, megkísérelhet egy DC 10-es Intelligencia (Vallás) próbát, hogy azonosítsa azokat az isteneket, akiket egykor itt tiszteltek: [[Oghma]] (a tudás istene), [[Mystra]] (a mágia istennője), [[Lathander]] (a hajnal istene) és [[Tymora]] (a szerencse istennője). Ez nyilvánvaló jele annak, hogy a kastély építői emberek voltak.

```encounter
creatures:
  - 1: Grick
```

### Fejlemények
Ha harc tör ki itt, a 9-es területen lévő goblinok nem lephetőek meg.

### Kincs
A kő tűzrakó egy szénhalmot tartalmaz, amely alatt egy napelf aranyszobrocska van elrejtve (100 arany értékű), vörös vászonba csomagolva. Egy goblin rejtette el ide, hogy a társai ne lopják el tőle.

A [[Detect Magic]] varázslat felfedi, hogy a szobor jósló mágiával van átitatva. Bármely nem gonosz lény, amely megérinti a szobrot, kérdést tehet fel, és telepatikus választ kap, mintha [[Augury]] varázslatot használt volna. Miután egy lény egyszer kérdezett és választ kapott, soha többé nem aktiválhatja a szobrot.

## Goblin szentély (9)
A Cragmaw-klán ezt a helyet Maglubiyetnek, a goblinok és hobgoblinok hadistenének szentelte újra, megszentségtelenítve az egykori emberi szentélyt. Az oltárt primitív szimbólumok borítják, amelyek vérrel vagy vörös festékkel vannak festve. A kápolna közepén egy nagy, repedt kőoltár áll, amelyen szimbolikus áldozati maradványok találhatók: régi csontok, törött fegyverek, és néhány elhalványult mágikus aura nyoma. A falakon goblin nyelven írott ima- vagy háborús szövegek futnak végig, melyek Maglubiyet dicsőségét zengik. A levegő nehéz és fojtott, mintha a helyszín saját szándékkal rendelkezne.

> [!recite|background-color-brown no-t] 
> Ez a kamra a vár északi tornyában található. Egy kőoltár áll a szoba közepén, fekete, vérfoltos terítővel borítva. Az oltáron gondosan elrendezett arany rituális eszközök – egy kehely, egy kés és egy füstölő – találhatók. A két déli boltívet nehéz függönyök fedik.
> Ahogy beléptek a szentélybe, a levegő szinte azonnal nehezebbé válik. A tér közepén egy magas, vicsorgó hobgoblin áll, karjait a magasba emelve, miközben egy ismeretlen nyelven szónokol. Ahogy a sámán magasba emeli kezeit, a kápolna falain lévő rúnák egy pillanatra izzani kezdenek. Az oltárnál egy ismerős alakot láttok: Gundren Rockseeker remegve térdel a sámán előtt. A szemei kétségbeesést sugároznak, miközben felétek kiált:
> **„Siessetek! Meg akarnak ölni, hogy feláldozzanak Maglubiyetnek!”**
> A sámán kántálása tovább erősödik, az árnyékok sűrűsödnek, és a kápolnát nyomasztó légkör lengi be. Az összes goblin szövetséges testét átható, vörös árnyalatú mágikus pajzs veszi körbe. A sámán hangja Maglubiyet nevét zengi:
> **„Maglubiyet áldása védelmez minket! Addig nem árthattok nekünk, míg a szentély ereje fennmarad!”**
> Az árnyak megmozdulnak, mintha maguk is életre kelnének, és a kápolna sötét energiái egyre nyomasztóbbá válnak.

Ez a szentély [[Lhupo]] otthona, valamint két közönséges gobliné, akik a "tanítványai". Mindannyian koszos köpenyt viselnek páncéljuk fölött, de a goblinok egyike sem rendelkezik isteni hatalommal (Lhupo, a hobgoblin sámán azt állítja, hogy Maglubiyet beszél hozzá). Ha a goblinok hallották a karakterek harcát a 8-as területen lévő grickkel, az oltár mögé bújnak, és megpróbálják meglepni a karaktereket. Máskülönben mindhárom goblin térdelve imádkozik az oltár előtt gonosz istenükhöz.

A vérfoltos terítő teljesen fedi a kőoltárt, amelynek oldalait ugyanolyan istenek képei díszítik, mint amilyenek a 8-as területen láthatók.

### **A Rituálé Pajzsa**
Amíg a sámán rituáléja aktív, egy mágikus védelmező pajzs veszi körbe az összes goblin szövetségest (beleértve a bugbear-eket és íjászokat is).
- **Hatás:** Amíg a sámán rituáléja aktív, egy mágikus védelmező pajzs veszi körbe az összes goblin szövetségest (beleértve a bugbear-eket és íjászokat is).
- **Mechanika:**
    - A pajzs **teljesen elnyeli** a fizikai és mágikus sebzést.
    - A karakterek észlelhetik a pajzs jelenlétét már az első támadásaik során.

#### **Pajzs Felfedezése**
- **Arcana vagy Investigation próba (DC 14)**:  
    A sikeres próba után a karakterek megérthetik, hogy a pajzsot a sámán rituáléja táplálja.
> [!recite|background-color-brown no-t]
> Amint az első ütésed célt érne, a goblin/bugbear teste körül hirtelen egy halvány, vörös fény villan fel, és a támadásod nyom nélkül elenyészik. A pajzs suttogó hangja a távolból Maglubiyet nevét ismételgeti.

#### **A Pajzs Deaktiválása**
A pajzsot csak a rituálé megzavarásával lehet megtörni, ami két módon érhető el:
1. **Az Oltár Megszentségtelenítése**
    - A karakterek megpróbálhatják megszakítani a rituálét az oltár közvetlen megsemmisítésével.
    - **Religion vagy Strength próba (DC 16)**: Siker esetén az oltár mágikus ereje megtörik, a pajzs összeomlik.
2. **A Sámán Legyőzése**
    - Ha a sámánt kiiktatják, a pajzs automatikusan megszűnik.
    - A sámán ezt felismerve elrejtheti magát, vagy továbbra is koncentrálhat a varázslat fenntartására.

#### **A Rituálé Időzítése**
1. **Megidézés Előtt**
    - A sámán rituáléja kezdetben csak védelmező pajzsként működik.
    - **Körök száma**: A rituálé a harc 3-5. körében elér egy kritikus pontot, ahol a démon elkezd manifesztálódni.
2. **A Megidézés Menete**
    - A sámán egy démoni szöveget kezd kántálni, miközben az oltárból árnyékok gomolyognak elő.
    - A karakterek hallják az abyssal nyelven szóló szavakat (pl. _"Xul'han thar, oz mograth nah’ka!"_).
    - Ha a karakterek nem szakítják meg a rituálét időben, a démon megidéződik és azonnal belép a harcba.

> [!recite|background-color-brown] A Démon Megjelenése
> Az oltárhoz kötözött Gundrenből hirtelen sötét, gomolygó árnyékok emelkednek ki, mintha egy másik dimenzió hasadna fel. A törpe ordít fájdalmában, majd elájul az oltárhoz kötözve. a levegő megfagy körülöttetek, miközben egy torz, szárnyas alak kezd formálódni az árnyékok között. Mély, velőtrázó üvöltés rázza meg a kápolnát.
> **„Shar éhező gyermeke szolgálja most Maglubiyetet is! Pusztuljatok!”**
> A démon szemei izzanak a sötétségben, miközben szárnyai szétnyílnak, és egyetlen szempillantás alatt eltűnik az árnyak között.

``` encounter
name: Az Árnyak Oltára
creatures:
 - 1: [[Hobgoblin Shaman, Lhupo]]
 - 2: Bugbear
 - 2: [[Goblin, Lhupo's apprentice]]
---
name: Az Árnyak Oltára - A démon
creatures:
 - 1: Nightmare
```

### A Vérrel Írott Szimbólum
- A goblin sámán a vérrel írt szimbólummal próbálta megidézni Maglubiyet áldását. Ez a szimbólum lehet az egyik szükséges elem Caoimhe és a csapat rituáléjához.
- Amikor Caoimhe közelebb lép az oltárhoz, a szimbólum halványan ragyogni kezd, és érzi, hogy a hely még mindig őrzi az egykori szent hatalmát.
- **Vizsgálat**: Caoimhe egy **Arcana (DC 15)** vagy **Religion (DC 13)** próbát tehet, hogy azonosítsa a szimbólumot és annak szerepét a rituáléban.
- - A kápolna mágikus védelme még részben aktív, az emberek egykori isteneihez kötődően. - Ha Caoimhe nekromanta varázslatot próbál használni a helyszínen, a következő történhet:
    - **Wisdom Saving Throw (DC 14)**:
        - **Siker**: A varázslat normálisan működik.
        - **Kudarc**: A hely szellemi védelme bénítja őt 1 körre, mintha egy _Hold Person_ varázslat hatása alatt állna.

### **A Sámán Rituáléjának Megtörése**
- Ha a csapat megzavarja vagy megtöri a sámán rituáléját (pl. az oltáron lévő szimbólum deaktiválásával vagy a sámán legyőzésével), a hely szellemi energiái átmenetileg felszabadulnak.
- **Hatás Caoimhe Számára**:
    - Caoimhe látomást kap egy sötét és fényes szimbólumokkal teli térben. Selûne vagy egy másik jóindulatú isteni erő suttogó hangon közli vele, hogy létezik egy rituálé az árnyékszilánk eltávolítására.
    - Caoimhe varázskönyvében megjelenik az Árnyékszilánk eltávolítása varázslat szövege, amely később a fő rituáléban használható lesz.

> [!recite|background-color-brown] A Szimbólum felfedezése 
>Ahogy Caoimhe közelebb lép az oltárhoz, a vérrel írott szimbólum halvány vöröses fényben kezd derengeni. Egy pillanatra megragadja a figyelmét, mintha a szimbólum önálló életet élne. A tér megváltozik körülötte; egy mély, suttogó hang visszhangzik a kápolna falairól.
>**„Lásd, amit mások nem látnak. A sötétség és a fény egyaránt részed... de válassz bölcsen, mert az árnyak árat követelnek.”**
>Caoimhe fejében hirtelen megjelenik a varázslat szövege, amely az árnyékszilánk eltávolításához szükséges. A könyvében lassan, mintha láthatatlan kéz írná, feltűnik a titkos formula.

### Kincs
- A kehely, a kés és a füstölő emberi készítésű műalkotások, értékük: **150 arany**, **60 arany** és **120 arany**.
### Fejlemények

Bármely pap, aki megvizsgálja a kápolna díszítését, megkísérelhet egy DC 10-es Intelligencia (Vallás) próbát, hogy azonosítsa azokat az isteneket, akiket egykor itt tiszteltek: Oghma (a tudás istene), Mystra (a mágia istennője), Lathander (a hajnal istene) és Tymora (a szerencse istennője). Ez nyilvánvaló jele annak, hogy a kastély építői emberek voltak.

A sámán meghalt a rituálé végén, de a goblinja feláldozta magát, és így megidézték a démont, de az végül beolvadt az árnyak közé.

## Oldalsó bejárat (10)

Ez az oldalsó bejárat zárva van, de nincs őrizve.

> [!recite|background-color-brown no-t]
> A régi kastély déli oldalán egy benőtt ösvény vezet egy folyosóra, amely a falba kapaszkodik fel. Itt egy nagy vasajtó áll, amelyet közvetlen külső támadásoktól véd a környező fal. Nyílásrések találhatóak tíz láb magasan, ahonnan rálátni az ösvényre.

A vasajtó zárva van. Tolvajszerszámokkal és egy sikeres DC 15-ös Ügyesség próbával kinyitható, vagy egy DC 25-ös Erő próbával betörhető.

### Lőrések

Bármelyik karakter, aki megáll és hallgatózik a nyílásrések közelében, meghallhatja a 7-es területről érkező edénycsörömpölést és dühös goblinokat, akik azon vitatkoznak, hogy szükséges-e elmosni a tányérokat. A goblinok nem figyelnek a nyílásrésekből. Azonban ha a karakterek nagy zajt csapnak, például betörik az ajtót, a goblinok odamennek és megnézik, mi történik. Ha betolakodókat látnak, riasztást adnak.

## Romos torony (11)

Egy poros vászon (a térképen „C”-vel jelölve) rejti el az északi bejáratot ebbe a területbe, beleolvadva a környező kőfalba és törmelékbe. Egy karakter, aki sikeresen teljesít egy DC 15-ös Bölcsesség (Észlelés) próbát, észrevesz egy gyalogösvényt, amely a rejtett bejárathoz vezet. Ha a karakterek aktívan keresik a rejtett bejáratot a kastély körül, egy DC 10-es Bölcsesség (Észlelés) próbával észrevehetik a vászon „ajtót.”

>[!recite|background-color-brown no-t]
>Ez a torony szinte teljesen összeomlott, bár a földszinten még van egy kis nyitott tér. Rothadó ládák és ősi hordók utalnak arra, hogy itt egykor készleteket tároltak. Egy nehéz függöny takarja el a déli, omladozó részt, míg egy épen maradt ajtó keletre vezet. Északon egy rövid átjáró végződik egy vászonfüggöny mögött.

## Őrszoba (12)

Az itt lévő lények figyelik a nyílásrésből a kastély keleti oldalát, így nagy eséllyel észreveszik és megtámadják az arra lopakodó karaktereket.

>[!recite|background-color-brown no-t]
>Egy kőből készült tűzrakó izzó parázzsal világít ennek a kis barakknak a közepén. Négy szalmával töltött ágy sorakozik a keleti fal mentén. A déli fal beomlott, de egy elreteszelt faajtó még mindig tisztán áll. Egy függöny lóg egy északi boltívben.

Három [[Hobgoblin|hobgoblin]] őrzi ezt a szobát. Okosak, kemények és hűségesek Grol királyhoz. A harc kezdetén az egyik hobgoblin elrohan, hogy figyelmeztesse a királyt a 14-es területen, majd két körrel később visszatér, hogy csatlakozzon a küzdelemhez.

Ez a terület egykor egy szalon volt a kastély emberi lakói számára, de rothadó bútorait a Cragmaw goblinok összetörték és tűzifának használták.

```encounter
creatures:
  - 3: Hobgoblin
```

## Bagolymedve-torony (13)

A torony ajtaja egy nehéz fa rúddal van elzárva, ami finom figyelmeztetésként szolgál arra, hogy veszély leselkedik odabent. Amikor a rúd megemelkedik, a terem lakója felébred és borzalmas üvöltést hallat.

A lőrések be vannak zárva, így a terem sötét. A szöveg feltételezi, hogy a karakterek sötétlátással vagy fényforrással rendelkeznek.

>[!recite|background-color-brown no-t]
>A torony felső emeletei összeomlottak, így egy legalább harminc láb magas üreges silót hoztak létre, amelynek felső részei árnyékba vesznek. Por, törmelék és törött üveg borítja a padlót, míg régi munkapadok és könyvespolcok hevernek szétszórva délen. A terem közepén egy hatalmas lény áll, amely egy kopottas medvére emlékeztet, de egy bagoly fejével. Felemelkedik és üvölt, amikor meglát titeket.

A Cragmaw goblinok elfogtak egy [[Owlbear|bagolymedvét]] és ebbe a toronyba zárták. A szobát szándékosan sötétben tartják, hogy a lény nyugodt maradjon, de [[Grol Király]] még nem tudja, mit kezdjen vele. Ha egy karakter friss húst dob neki, a bagolymedve felfalja azt. Egyébként megtámadja az első élőlényt, amit az ajtóban lát.

Ez a szoba egykor könyvtár és műhely volt, de az eredeti berendezéséből semmi sem maradt épen.

```encounter
creatures:
  - 1: Owlbear
```

### Fejlemények

Ha a karakterek kinyitják az ajtót, de elkerülik a bagolymedvét, a lény elmenekül a kastélyból (valószínűleg a 11-es területen keresztül). Bármit megtámad, ami az útjába kerül.

### Kincs

A torony második emeletének maradványai között egy szaggatott szélű párkányon egy megrongált fa láda található. A ládát nehéz észrevenni a padlóról, egy sikeres DC 15-ös Bölcsesség (Észlelés) próba szükséges a felfedezéséhez. A láda nincs bezárva, és tartalma: 90 ezüst korona, 120 arany, egy gyógyital, egy [[Silence|csend]] varázstekercs és egy [[Revivify|újjáélesztés]] varázstekercs.

## Királyi lakosztály (14)

Eredeti felállás: Bármely karakter, aki hallgatózik az ajtónál, két hangot hall, akik heves vitát folytatnak. Egy mély, morgó hang fizetséget követel valamiért, míg egy selymesen sima hang válaszol neki.

>[!recite|background-color-brown no-t]
>Ez a terem egy kezdetleges lakótér, vastag szőrméket terítettek a padlóra szőnyegként, régi trófeák lógnak a falakon, és egy nagy ágy áll az északi oldalon. Egy izzó parázstartó világítja meg a helyiséget. Egy kerek asztal áll több székkel a délkeleti sarokban, közel az ajtóhoz.
>Ahogy beléptek a nagyterembe, a látvány azonnal sokkol. King Grol székében pihen, hatalmas buzogányát lazán a földnek támasztja. De ami igazán megdöbbentő: az asztalhoz közel, a padlón hever ájultan, jól összeverve Gundren Rockseeker.
> **King Grol:** _„Nos, hogy tetszik a kis játékunk? Azt hittétek, hogy egy ilyen helyen nem várunk rátok meglepetésekkel? Túlbecsültétek magatokat!”_
> A "Gundren" a ti oldalatokról ekkor kezd el hátrálni, arca eltorzul, és átváltozik egy veszélyesen gyönyörű drow nő alakjába. Halkan, vigyorogva jegyzi meg:
> **Doppelganger:** _„Olyan szépen játszottam, hogy magatokkal hoztatok ide. Köszönöm a bizalmat... most viszont már nincs több titkom számotokra, ideje távoznotok!”_

[[Grol Király]] egy vad, öreg [[Bugbear]], aki 70 életerő ponttal rendelkezik. A Cragmaw törzset puszta megfélemlítéssel tartja uralma alatt. Bár az életkor meggörnyesztette vállait és hátát, meglepően fürge és erős maradt. Követelőző és bosszúálló természetű, és egyetlen Cragmaw tag sem mer szembeszállni vele.

Grol mellett Snarl, egy hatalmas rémfarkas áll. Vyerith, egy alakváltó (doppelganger), aki női drowként álcázza magát, a csapattal van, az utolsó a sorban, meglepetésre készen. Vyerith a Fekete Pók üzenetvivője, aki azért jött, hogy begyűjtse Gundren Rockseekert és a Wave Echo Cave térképét. Grol azonban nem akarja átadni a térképet, inkább eladná. Ő és a drow éppen az árat tárgyalják. Vyerith először ki akarja hallgatni Gundrent, hogy megtudja, ismer-e más is a bánya helyét, majd szándékában áll megölni a törpét és megsemmisíteni a térképet.

Ha a gonosztevők figyelmeztetést kapnak egy közelgő támadásról, Vyerith elrejtőzik az északkeleti ajtó mögött, résnyire nyitva hagyja azt, hogy hátulról támadhassa meg a betolakodókat. Grol túszként tartja Gundrent, és megfenyegeti, hogy megöli, ha a karakterek nem vonulnak vissza.

```encounter
creatures:
  - 1: King Grol
  - 1: [[Dire Wolf, Snarl]]
  - 1: [[Doppelganger, Vyerith]]
```

### Lőrések

A lőrések 15 láb magasan találhatók a külső falon, és az itt lévő lények nem figyelnek rajtuk keresztül. Kicsi az esélye annak, hogy észreveszik a kastély körül mozgó betolakodókat.

### Északnyugati szoba

Ez a részlegesen beomlott helyiség egykor kényelmes fürdőszoba volt. Még mindig tartalmaz egy nagy csempézett fürdőkádat, amit a kastély jelenlegi lakói nem használnak.

### Eszméletlen törpe

A terem délnyugati sarkában található Gundren Rockseeker. Eszméletlen, de stabil állapotban van 0 életerő ponttal.

### Fejlemények

Ha Grolt megölik, Vyerith megpróbálja megölni Gundrent, majd a térképpel együtt a 11-es terület felé menekül, és a rejtett vászonajtón át elhagyja a kastélyt. Ha sarokba szorítják, az alakváltó inkább harcol a haláláig, mint hogy elfogják.

Ha Gundrent felélesztik, megköszöni a csapatnak, hogy megmentették, de nem hajlandó elhagyni a Cragmaw Kastélyt a térképe nélkül. Sajnos nem tudja, hová rejtette King Grol a térképet (lásd a "Kincs" szekciót).

### Kincs

Grol ágyának matraca alatt egy varrott bőrzsák található, amely 220 sp, 160 ep, három gyógyitalt és Gundren Wave Echo Cave térképét rejti.
Vyerithnél található a [[Holdárny köpeny]].

Grolnál van egy pajzs, is [[Exandyr]].