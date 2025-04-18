---
tags:
  - location
  - settlement
image: -
age: -
race: Human
AssociatedGroup: -
---


- **Helyszín**: Thundertree egy elhagyatott falucska, amelyet régen egy vulkánkitörés és az azt követő élőholt járvány sújtott. Az évek során a természet visszahódította a területet, a romos épületek körül burjánzó növényzet nőtt.
- **Hangulat**: Nyugodt, de enyhén baljós légkör. A falu körül susogó fák, néhol romok között bujkáló állatok, és a természet lassú regenerálódásának jelei láthatók.

Thundertree egykor egy virágzó falu volt a Neverwinter-erdő szélén, de egy vulkánkitörés és az azt követő zombijárvány elpusztította. A romok között most veszélyes növények és élőholtak tanyáznak.

## Általános jellemzők

- A romok között sűrű aljnövényzet és fiatal fák nőttek.
    
- A kőépületek falai még állnak, de a tetők és a faszerkezetek összeomlottak.
    
- Hamu és vulkáni törmelék borítja a területet.
    
- Mérgező gázok szivárognak a földből, különösen esős időben.
    

## Megközelítés

>[!recite|no-t]
>Az ösvény fokozatosan egy régi, benőtt úttá válik, amely omladozó, indákkal és bozóttal benőtt épületek között kanyarog. Előttetek, a település közepén egy meredek domb emelkedik, amelynek tetején egy kőtorony áll részben beomlott tetővel és egy hozzá csatlakozó kunyhóval. Egy földút öleli körbe a domb alját, és kanyarog régi kőházak között, melyek közül sok tetőtlen rom, belsejük ki van téve az időjárás viszontagságainak. Más épületek többé-kevésbé épnek tűnnek. Az egész hely kísértetiesen csendes.
>
>Egy közeli oszlopra fából készült tábla van szögezve. Ez áll rajta: "VESZÉLY! Növényszörnyek ÉS zombik! Fordulj vissza most!"

## Fontos helyszínek

1. **Druid tornya**: Reidoth, a druida itt lakik.
    
2. **Zombik háza**: Két zombi rejtőzik itt.
    
3. **Ash Zombik**: Négy ash zombi kóborol a romok között.
    
4. **Twig Blightok fészke**: Hat twig blight rejtőzik a romok között.
    
5. **Zöld sárkány fészke**: Venomfang, a fiatal zöld sárkány itt telepedett le.
    

## Találkozások

- **Ash Zombik**: Lassú, de veszélyes élőholtak.
    
- **Twig Blightok**: Apró, agresszív növénylények.
    
- **Kultisták**: Venomfangot imádó fanatikusok.
    
- **Venomfang**: Fiatal zöld sárkány, ravasz és veszélyes ellenfél.
    

## Kalandötletek

- A karakterek segíthetnek Reidoth-nak megtisztítani a területet.
    
- Megpróbálhatják elűzni vagy legyőzni Venomfangot.
    
- Felkutathatják az elveszett kincset a romok között.
    

Ez a helyszín számos veszélyt és lehetőséget rejt a kalandozók számára, miközben felfedezik Thundertree tragikus történetét és jelenlegi állapotát.


# Helyszínek

## 1. Westernmost Cottage

Ez a kunyhó látott már jobb napokat.

>[!recite|no-t] 
>Egy ősi, göcsörtös fa árnyékában egy omladozó kőkunyhó áll magányosan, teteje rég a múlt emlékévé vált. Körülötte a természet visszahódította birodalmát: burjánzó gyomnövények és vadvirágok szőnyege borítja a földet, mintha csak magához ölelné az egykor emberkéz alkotta építményt. A falak repedéseiből indák kúsznak elő, lassan, de biztosan visszakövetelve a teret az erdő számára.

Két [[twig blight]] rejtőzik a gyomok között, amelyek a kunyhó nyitott ajtaját szegélyezik. Dobj egy Ügyesség (Lopakodás) próbát a blightok számára, és hasonlítsd össze az eredményt a karakterek passzív Bölcsesség (Észlelés) értékeivel, hogy meghatározd, észreveszik-e őket.

A blightok nem támadnak maguktól (kivéve önvédelemből), de gyorsan a 2-es területen lévő twig blightok segítségére sietnek, ha ott harc tör ki.

```encounter
creatures:
  - 2: Twig Blight
```

## 2. Blighted Cottages

A szél és az időjárás elvégezte a munkáját, és kevés maradt ezekből a házakból vagy egykori tartalmukból.

>[!recite|no-t]
>Ezek a romos, egymás mellett álló kunyhók úgy tűnnek, mintha valaha jómódú kereskedők vagy tehetős gazdálkodók otthonai lehettek volna. Mindössze összeomlott falak és törmelékhalmok maradtak. Több fiatal fa is kinőtt a romok közepén.

A burjánzó növényzet halálos veszélyt rejt - hat [[Twig Blight]] lapul a közönséges lombok között. Észrevételükhöz sikeres Bölcsesség (Észlelés) próba szükséges, amelyet a blight-ok Ügyesség (Lopakodás) próbája ellenez.

Ezek a növényszörnyek éhesek, és harcolnak, amíg el nem pusztulnak. Egy körrel azután, hogy támadnak, az 1-es területen lévő twig blightok is csatlakoznak a küzdelemhez.

```encounter
creatures:
  - 6: Twig Blight
```

### Kincs

A kereskedő egykori otthonában, a keleti kunyhó belsejében egy értékes kincs rejtőzik. A padló kőlapjai alatt egy régi láda bújik meg, amelyet a házon keresztülnövő fa gyökerei között lehet felfedezni. A láda megtalálásához alapos kutatás és egy sikeres Bölcsesség (Észlelés) próba szükséges, 10-es nehézségi fokkal.

A szerencsés felfedező a következő értékeket találhatja a ládában:

- 700 rézpénz
    
- 160 ezüstpénz
    
- 90 aranypénz

## 7. Dragon's Tower

Ez a torony egykor egy emberi varázsló otthona volt, aki harminc évvel ezelőtt halt meg, miközben az Thundertree-t elözönlő hamuzombikat próbálta legyőzni.

>[!recite|no-t]
>A domb tetején egy kerek torony áll, hozzá csatlakozó kunyhóval. Mindkettő jó állapotban van, bár a torony tetejének fele hiányzik. Egy ajtó vezet a kunyhóba, és több nyílpuska-lőrés ablak látható a tornyon. Nem lehet nem észrevenni a környék hátborzongató csendjét és a levegőben terjengő furcsa, csípős szagot.
>
>Két hatalmas, undorító pók teteme hever szétterülve az ösvény szélén, láthatóan odavonszolva. Felpuffadt testük ráncos és hólyagos, úgy tűnik, mintha egy nagy állat marcangolta volna szét őket.

Egy fiatal zöld sárkány, Méregagyar nemrég foglalta el a tornyot, miután átrepült Thundertree felett, miközben a Neverwinter-erdőben keresett megfelelő búvóhelyet. Az óriáspókok tetemei a torony korábbi lakói voltak, akiket a sárkány ölt meg, miután áttörte magát a tetőn. Azóta Méregagyar meghúzta magát.

```encounter
creatures:
  - 1: [[Young Green Dragon, Venomfang]]
```

### Torony
A sárkány a toronyban él – egy egyetlen helyiségből álló, 40 láb magas mennyezetű térben. Egy 5 láb széles lépcső kanyarog körbe a belsejében, felvezetve a most már nyitott tetőre, ami könnyű bejutást biztosít a sárkánynak új otthonába. Nehéz fagerendák és lépcsőtámaszok keresztezik egymást a torony belsejében.

Méregagyar nem akar lemondani egy ilyen ígéretes búvóhelyről, de ha a karakterek a sárkány életerejének felére csökkentik, az felmászik a torony tetejére és elrepül, hogy egy másik napon harcoljon.

### Kunyhó
A kunyhóban poros, pókhálóval borított bútorok találhatók, de semmi értékes. Ha a karakterek sok zajt csapnak a kunyhóban, a sárkány meghallja őket és felkészül a harcra.

### Kincs
Egy régi, feltört faláda a torony padlóján tartalmazza a halott varázsló utolsó kincseit: 800 ezüstpénz, 150 aranypénz, négy ezüst serleg holdkövekkel díszítve (egyenként 60 aranypénz értékben), egy ködfátyol tekercs és egy villámcsapás tekercs. Méregagyar ideje nagy részét azzal tölti, hogy mohón csodálja a zsákmányt.

A sárkány alig vette észre a kincshalmaz legérdekesebb darabját. Az érmék alatt egy rozsdás, régi csatabárd fekszik, törp készítmény. Törp rúnák a bárd fején azt írják: "Hasító", és a rozsda megtévesztő. A Hasító egy +1-es csatabárd, amely maximális sebzést okoz, ha a viselője növényi lényt vagy fából készült tárgyat talál el vele. A bárd készítője egy törp kovács volt, aki viszályban állt az erdő driádjaival, ahonnan tűzifát vágott. Aki a bárdot hordozza, nyugtalanságot érez, valahányszor erdőn halad át.

### Tapasztalati pontok kiosztása
Osszanak szét 2000 TP-t egyenlően a karakterek között, ha a csapat elűzi Méregagyart. Tekintettel a szintjükre, a karakterek valószínűleg nem fogják megölni a sárkányt, de az 3900 TP-t ér.


## Bónusz: Temető
- **Leírás**: A temető a falu határán található, egy kis domb tetején, amelyet burjánzó fák és bokrok vesznek körül. A sírkövek többsége benőtt mohával és indákkal, a hely csendes és békés.
- **A Szimbólum**: Egy ősi sírkőre van vésve az _"Istenek Találkozása"_ szimbólum, amely halványan izzik, amikor Rialleynn vagy Thalion megközelíti - ez a szimbólum érdekes módon a fényszilánkra reagál. A szimbólumot Caoimhe képes azonosítani a korábban látott álmok és jelek alapján.

[[Reidoth]] druida vezetheti őket ide - egy sírkövön talált egy különleges szimbólumot ([[A szimbólumok]]) - a többi sírkövön nem látott hasonló írást.

Megkérdezhetik a titokzatos betegségről a druidát, de nem fog tudni infót adni nekik.