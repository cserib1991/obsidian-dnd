```calendarium
calendar: Calendar of Harptos
```

> [!timeline|t-l] **Az Eldrin-rituálé kudarca** _Hammer 13, 1491 DR_
> - Eldrin mester megpróbálta feltárni a szent és arkán mágia kapcsolatát, de a rituálé kudarcot vallott.
> - Malgorath megszerezte a rituálé egyes titkait, és Azraeth-t bízta meg Calderyx manipulálásával.

> [!timeline|t-r] **Találkozás a Vihar Tűzhelyében** _Ches 25, 1491 DR_
> - Thalion, Caoimhe, Sir Edrik, Ailith és Calderyx sorsdöntő találkozása Neverwinterben.
> - Gundren Rockseeker felbéreli a kalandorokat egy rizikós melóra.

> [!timeline|t-l t-1] **Rajtaütés a Triboar Trail-en** _Ches 27, 1491 DR_
> - Első, közös megbízásuk során goblinok és ghoul-ok támadják meg a társaságot.
> - [[Álmok Cragmaw hideout előtt]]

> [!timeline|t-r] **Cragmaw Hideout megtisztítása** _Ches 28, 1491 DR_
> - A csapat sikeresen legyőzte a goblinokat, és megszerezte az első szimbólumot, amely a "Fiatal lélek" jelképét hordozta.
> - Sildar Hallwintert kiszabadították, aki elárulja Gundren igazi küldetésének természetét.
> - Yeemik végül nem lett Klarg helyett a vezér...
> - [[Látomások Cragmaw hideoutban]]
> - [[Álmok a Stonehill fogadóban]]

> [!timeline|t-l] **Megérkezés Phandalinba** _Ches 28, 1491 DR_
> - Leszállítják Barthrennek a szállítmányt Neverwinterből.
> - Este a fogadóban Sildar vendégei. Megtudnak pár pletykát a helyiektől.
> - [[Álmok a Stonehill fogadóban]]

> [!timeline|t-l] **Tresendar Manor felfedezése**  _Ches 29, 1491 DR_
> - A csapat találkozik Phandalin helyi lakosaival, küldetéseket kapnak tőlük. [[Alfred Merridon|Alfred]] rátalál régi bajtársára, [[Daran Edermath|Daranra]].
> - A csapat megtisztítja a Tresendar Manor alatti katakombákat, kiszabadítják Thel Dendrar családját.
> - Elfogják [[Iarno Albrek|Glasstaffot]], akit átadnak A [[Lords' Alliance|Lordok Szövetségének]].
> - [[Sir Edrik Owlshield|Sir Edrik]] [[Alfred Merridon|Alfred]] kíséretében elkísérik a bűnös [[Iarno Albrek|Iarno Albreket]] [[Neverwinter]] városába, hogy bíróság elé állíthassák.
> - [[Ailith Galanodel]] üzenetet kap [[Holdfény Liget tanács|Holdfény ligetből]], hogy sürgősen térjen vissza segíteni a közösségen.
> - [[Rialleynn Sylvara|Ria]] csatlakozik a csapathoz.
> - [[Közös álom a Stonehill fogadóban]]
> - Thalion megvakul egy jó időre.

> [!timeline|t-r] **Vaenor és Ria találkozása** _Tarsakh 1, 1491 DR_
> Útban Cragmaw vára felé, a Triboar Trail és az erdő között egy tisztáson egy lemészárolt karavánt találnak, bugbear-ek őrzik a zsákmányt, köztük egy karakált.
> Kiszabadítják a karakált, és Ria hű társa lesz.

> [!timeline|t-l] **Cragmaw várának ostroma** _Tarsakh 2, 1491 DR_
> - A csapat megpróbál beszivárogni a várba dél felől a cselédjáraton keresztül. Thalion leleményesen beolvad a bankett terem goblinjai közé, mint újonc, és jól odapörkölnek nekik.
> - A vár keményebb falatnak bizonyul - esnek-kelnek hőseink, elszabadítanak egy rémálom démont, viszont legyőzik Vyerith-et és Grol királyt, valamint kiszabadítják Gundrent.

> [!dataview|no-t background-plain]
> ## Játékosok
> ```dataview
> table without id
>   file.link as "Karakter neve",
>   class as "Osztály",
>   raceDisplay as "Faj",
>   level as "Szint",
>   hp as "Életerő",
>   alignment as "Jellem"
> from "Karakterek/PC-k"
> where contains(tags, "pc")
> sort file.name asc
> ```

```meta-bind-button
label: Új PC létrehozása
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: PROPS/Sablonok/PC.md
    folderPath: Karakterek/PC-k
    fileName: newPC
    openNote: true
    openIfAlreadyExists: false

```

Nem-játékos karakterek

```meta-bind-button
label: Új NPC létrehozása
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: PROPS/Sablonok/NPC.md
    folderPath: Karakterek/NPC-k
    fileName: newNPC
    openNote: true
    openIfAlreadyExists: false
```

Tárgyak

```meta-bind-button
label: Új tárgy létrehozása
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: PROPS/Sablonok/Item.md
    folderPath: Tárgyak
    fileName: NewItem
    openNote: true
    openIfAlreadyExists: false
```