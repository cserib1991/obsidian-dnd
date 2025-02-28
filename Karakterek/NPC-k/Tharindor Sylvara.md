---
tags:
 - npc
Gender: Férfi
Race: Elf#Wood Elf
RaceDisplay: Wood Elf
Age: 453
Class: Ranger
SecondaryClass: Fighter
Alignment: Kaotikus jó 
Character-Role: Nyugalmazott katona, a Sylvara család feje
Location: 
AssociatedGroup: Nyílvesszők Árnyai (former)
NoteIcon: npc
status: egészséges
image: Tharindor Sylvara.webp
---

> [!infobox|wikipedia right]
> # `=this.file.name`
> `="![[" + this.image + "|cover hsmall]]"`
>> [!info|background-plain no-t no-print]
>>> `=link(this.image, "Megnyitás játékosoknak")`
> ###### Alap információk
> Típus |  Érték |
> ---|---|
> Tartózkodási hely | `=this.Location` |
> Csapat | `=this.AssociatedGroup` |
> Neme | `=this.gender` |
> Faj | `=link(this.race, this.racedisplay)` |
> Kor | `=this.age` |
> Állapot | `=this.status` |
> ###### Rules Info
> Típus |  Érték |
> ---|---|
> Jellem | `=this.alignment` |
> Osztály | `=link(this.class)` lvl6, `=link(this.secondaryclass)` lvl4 |
> Szerep | `=this.character-role` |

>[!quote|author mark] [[Rialleynn Sylvara]]
>_"Apám mindig is az erdők árnyékának és a természet egyensúlyának őrzője volt. Az íja sosem csak fegyver volt a kezében – inkább az igazság és a harmónia eszköze. Gyerekkoromban hallgattam, ahogy mesélt a csatákról, ahol nem a harag vezette a kezét, hanem az erdők védelme és a törvények betartatása. Ő vezette azt a különleges osztagot, akiknek hűsége és ügyessége legendássá tette őket. Bár a harcban könyörtelen volt, sosem vesztette el azt a nyugodt erőt, amely mindig áthatotta a tekintetét. Azt hiszem, ő tanított meg arra, hogy minden lövés, minden döntés egyensúlyt kell, hogy teremtsen. Talán sosem mondta ki, de mindig remélte, hogy én is az ő nyomdokaiba lépek. És még most is, amikor az árnyékok és a fény között egyensúlyozom, érzem az ő tanításának súlyát és erejét a kezemben tartott íjon keresztül."_

> [!info|background-plain left no-t] Statblock
> ```statblock
> columns: 2
> forceColumns: true
> name: Thalindor Sylvara
> size: medium
> type: Humanoid (wood elf)
> subtype: lvl 6 Ranger (Colossus Slayer), lvl 4 Fighter (Battle Master)
> alignment: chaotic good
> ac: 20 (elven armor)
> hp: 90
> hit_dice: 10d10 + 30
> speed: 35 ft. (Fleet of Foot)
> cr: 6
> stats: 
> - 14
> - 16
> - 14
> - 12
> - 16
> - 10
> senses: passive perception 17
> saves:
> - Strength:  6
> -  Dexterity: 7
> - Constitution: 6
> - Intelligence: 5
> - Wisdom: 7
> - Charisma: 4
> skillsaves:
> - Survival: 10
> - Perception: +7
> - Stealth: +7
> - Athletics: +6
> image: [[Tharindor Sylvara.webp]]
> languages: Elvish, Common, Orcish, Dwarvish
> monster: Commoner
> traits:
> - [Darkvision,You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can’t discern color in darkness, only shades of gray.]
> - [Fey Ancestry, You have advantage on saving throws against being charmed, and magic can’t put you to sleep.]
> - [Mask of the Wild, You can attempt to hide even when you are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.]
> - [Favored enemy,Advantage against orcs and goblinoids.]
> - [Colossus Slayer,"You can deal one extra damage if the target is wounded."]
> spells:
> - 3 lvl1, 2 lvl2 spell slots.
> - [[Hunter's Mark]]
> - [[Cure Wounds]]
> - [[Pass Without Trace]]
> - [[Lesser Restoration]]
> actions:
> - name: Longbow
>   desc: "Ranged Weapon Attack: +9 to hit, range 150 ft./600 ft., one target. Hit: `dice: 1d8 + 5`  piercing damage."
> - name: Shortsword
>   desc: "Melee Weapon Attack: +8 to hit, on target. Hit: `dice: 1d6 + 3` piercing damage."
> - name: Extra Attack
>   desc: "Tharindor can attack twice for one action."
> - name: Second Wind
>   desc: "As a bonus action, you can heal yourself for `dice: 1d10 + 4`. To be able to use this again you must take a short or long rest."
> - name: Action Surge
>   desc: "On your turn, you can take one additional action on top of your regular action and a possible bonus action. To be able to use this again you must take a short or long rest."
> - name: Superiority dice
>   desc: "You can use 4 superiority dice for combat maneuvers."
> - name: Maneuvers
>   desc: "[[Battle Master Maneuvers#Riposte|Riposte]], [[Battle Master Maneuvers#Precision Attack|Precision Attack]],[[Battle Master Maneuvers#Disarming Attack|Disarming Attack]]"
> dice: true
> ```

## Profil
**Személyiségjegyek:** Bölcs, visszafogott, természetközeli. Mély szeretetet táplál Rialleynn iránt, még ha ritkán mutatja is ki nyíltan.

#### **Ifjúság és Katonai Pálya**

Tharindor Sylvara a Sylvara család hagyományainak büszke őrzője, amely generációk óta a természet védelmét és az egyensúly fenntartását tartja életcéljának. Már fiatal korában kiemelkedett tehetségével az íjászatban és a túlélési képességeiben, ezért gyorsan a helyi katonai alakulatok figyelmébe került.

#### **Különleges Osztag – A Nyílvesszők Árnyai**

Tharindor a wood elf hadsereg egy különleges osztagának vezető tagjává vált, amelyet **A Nyílvesszők Árnyai** néven ismertek. Az osztag a wood elfek diplomáciai és kémelhárító küldetéseinek gerincét adta, és gyakran dolgoztak együtt más fajok képviselőivel, például emberekkel és törpékkel. Ők voltak az előőrsei és védelmezői a béketárgyalásoknak, de ha szükség volt rá, különleges bevetéseken sem riadtak vissza.

---

#### **Kapcsolata Rialleynn anyjával**

Tharindor egy kémelhárító küldetés során találkozott Rialleynn anyjával, egy **dűne elf nővel**, aki az Anauroch sivatag peremén élt. A két elf közös értékrendet és célokat talált: mindketten a természet egyensúlyának védelmét tartották életük legfontosabb küldetésének. Kapcsolatukból született meg Rialleynn, aki a két elf kultúra különleges egyensúlyát hordozza magában.

---

#### **Család és Rialleynn Kiképzése**

Tharindor, felismerve Rialleynn képességeit, kiskorától kezdve edzette őt, hogy egyszer majd átvehesse helyét a különleges osztagban. Szigorú, de igazságos tanítóként igyekezett átadni Rialleynn számára mindazt a tudást, amit az évek során felhalmozott, szívvel-lélekkel készítette fel Rialleynnt a természet védelmére és az egyensúly fenntartására. Kiképzése nemcsak a harcra és a túlélésre terjedt ki, hanem arra is, hogy megértse a Sylvara család örökségét és felelősségét.

Amikor Rialleynn készen állt saját útjára, Tharindor egy **különleges íjat adott át neki – [[Ila'nodel|Ila’nodelt]]**, a Hold Énekét. Az íj történetének csak egy részét osztotta meg vele, de megjegyezte, hogy:  
_"Ez az íj csak azokat választja ki, akik méltók rá. Talán egyszer felismeri benned azt a fényt, amit én már látok."_
Rialleynn végül egy új osztagot vezetett, amely nagyrészt a korábbi Nyílvesszők Árnyainak leszármazottaiból állt. Tharindor büszkén figyelte lánya sikereit, amíg be nem következett az Evermoors-i tragédia.


---

#### **Az Evermoors-i Tragédia és Tharindor Reakciója**

Amikor Rialleynn csapata az Evermoors lápvidékén egy sötét küldetés során elbukott, Tharindor szívét mély szomorúság töltötte el. Bár Rialleynn túlélte, a veszteségek terhét magával cipelte, és önkéntes száműzetésbe vonult. Tharindor sosem haragudott rá a kudarcért, de nem tudta rávenni magát, hogy elérje a lányát. Úgy érezte, Rialleynn-nek magának kell megtalálnia az utat, amely visszavezeti az örökségéhez.

Tharindor szívében mindig büszke volt Rialleynn-re, de úgy gondolta, hogy a lánynak előbb meg kell értenie saját helyét az egyensúlyban, mielőtt visszatérne a Sylvara családhoz. Bízik abban, hogy Ila’nodel végül segíteni fog Rialleynn-nek megtalálni a helyét, és hogy a múlt tragédiái nemcsak árnyékot, hanem erőt is adnak majd neki.

---

### **Jellemzői és Képességei**

- **Harci Tapasztalat:** Mesteri íjász és taktikus, aki évtizedeken át a vadon törvényei szerint élt és harcolt.
- **Diplomácia:** Tharindor sokszor vett részt béketárgyalásokon, így nemcsak a harcban, hanem a szavak erejében is jártas.
- **Hűség:** Bár távolságtartó Rialleynn-nel, Tharindor mélyen szereti a lányát, és a szívében reméli, hogy egyszer visszatér a családhoz.
- **Bölcs vezető:** Tharindor inkább tanácsadó, mint harcos, de szükség esetén képes visszatérni az íjhoz és kardhoz.
- **Természet iránti elkötelezettség:** Élete minden döntésében a természet harmóniájának védelme vezérli.
- **Csendes szeretet:** Nem mutatja ki nyíltan érzelmeit, de Rialleynn minden sikerére és fejlődésére mélyen büszke.

---

### **Jelentősége a kampányban**
Tharindor háttérben meghúzódó, de kulcsfontosságú figura lehet Rialleynn fejlődése szempontjából. Ha Rialleynn visszatérne hozzá, vagy találkozna vele a kampány során:

- Segíthet elmélyíteni az íj legendáját.
- További útmutatást nyújthat Rialleynn-nek Selûne és Shar konfliktusában.
- Megoszthatná Rialleynn-nel saját tapasztalatait az egyensúly kereséséről és arról, hogyan lehet feldolgozni a veszteséget.

---
> [!column|no-t]
>
>> [!blank]
>> ## Kapcsolatok
>>> [!kith|friend] [[Reidoth]] _Régi csapattárs_
>>
>>> [!kith|romantic] [[Kaelynne]] _házastárs_
>>
>>> [!kith|family] [[Rialleynn Sylvara|Rialleynn]] _gyermek_
>
>> [!blank]
>> ## **Kapcsolódó jegyzetek**
>>> [[Rialleynn Sylvara|Rialleynn]]
>>> [[Kaelynne]]
>>> [[Reidoth]]