---
tags:
 - npc
Gender: Férfi
Race: Bugbear
Age: 50
Class: Fighter
Alignment: kaotikus gonosz
Character-Role: Cragmaw Törzs Vezető
Location: Cragmaw Vára
AssociatedGroup: Cragmaw Törzs
NoteIcon: npc
status: egészséges
image: kinggrol.jpg
---

> [!infobox|wikipedia right]
> # `=this.file.name`
> `="![[" + this.image + "|cover hsmall]]"`
>> [!info|background-plain no-t no-print]
>>>  `=link(this.image, "Megnyitás játékosoknak")`
> ###### Alap információk
> Típus |  Érték |
> ---|---|
> Tartózkodási hely | `=link(this.Location)` |
> Csapat | `=link(this.AssociatedGroup)` |
> Neme | `=this.gender` |
> Faj | `=link(this.race)` |
> Kor | `=this.age` |
> Állapot | `=this.status` |
> ###### Rules Info
> Típus |  Érték |
> ---|---|
> Jellem | `=this.alignment` |
> Osztály | `=link(this.class)` |
> Szerep | `=this.character-role` |

>[!quote|author mark] [[Lyrindor Velinquest]]<br>*[[Árnyék és Fény Keresztútján]]*
>_King Grol... A Cragmaw törzs rettegett vezére. Hatalmas, akár egy hegyomlás, és éppoly könyörtelen. Azt mondják, hogy Maglubiyet saját kezével pecsételte meg az erejét, s hogy minden egyes csatában véráztatta oltár előtt térdelve kér áldást. De ne tévesszen meg a vad külseje – Grol nemcsak egy erőgép. Ravaszabb annál, mint amilyennek elsőre látszik. Azok, akik alábecsülték, már nem mondhatják el, hogy mekkorát tévedtek._

> [!info|background-plain left no-t] Statblock
> ```statblock
> columns: 2
> forceColumns: true
> name: King Grol
> image: [[kinggrol.jpg]]
> monster: Bugbear
> ac: 18
> hp: 70
> hit_dice: 11d8+9
> cr: 3
> dice: true
> traits+:  
> - [Snarl!, King Grol always fights with his Dire Wolf Snarl. Snarl acts on its own initiative count.]
> bonus_actions:
> - [Have a bite!, As a bonus action, if King Grol is able to speak, he can order Snarl to use its Bite attack on a creature in range of said Attack.]
> lair_actions:  
> - ["Summon bodyguards (2 times)", "King Grol can summon his Goblinoid underlings if he's afraid of dying. On initiative count 20 (losing ties), Grol summons 1 Hobgoblin or 2 Goblins from around the castle. The goblinoids will take their turns on the Lair's initiative count. He can summon these goblins only when he gets below 50% HP or when Snarl dies."]  
> reactions:  
> - [Field experience, "As a reaction, King Grol can move up to its speed towards a hostile creature it can see."]  
> - [Goblinoid Warlord, King Grol adds its proficiency bonus to its AC against one melee attack that would hit it as a reaction.]
> ```

## Profil
### **A Cragmaw törzs vezére**

King Grol egy hatalmas, vérszomjas bugbear hadúr, aki már évek óta rettegésben tartja Phandalin környékét. Ő a Cragmaw törzs vezetője, és hírhedt arról, hogy könyörtelenül bánik el mindenkivel, aki keresztezi az útját. A törzse iránti lojalitása és az istenük, **Maglubiyet** iránti fanatikus hite vezérli tetteit.

#### **Megjelenés**

King Grol közel 7 láb magas, masszív, izmos bugbear, akinek bőrét sötétvörös hegek borítják. Hatalmas harci buzogányt hord, amely Maglubiyet áldásának szimbólumait viseli. Egy kopott, fémből és bőrből készült páncél fedi a testét, melyet a korábbi győzelmei során zsákmányolt.

#### **Személyiség**

- King Grol rendkívül arrogáns és makacs, de nem ostoba. Ismeri a harctaktikákat, és képes manipulálni az ellenségeit.
- Hívei körében egy félelmetes legendává vált, akit nemcsak ereje, hanem kiszámíthatatlan dühkitörései miatt is tisztelnek.
- Bár a Fekete Pók parancsait követi, nem szereti, ha mások megmondják neki, mit tegyen.

---
> [!column|no-t]
>
>> [!blank]
>> ## Kapcsolatok
>>> [!kith|friend] [[Nezznar|A Fekete Pók]] _szövetséges_
>>
>>> [!kith|friend] Vyerith _szövetséges_
>>
>>> [!kith|family] [[Lhupo]] _szolga_
>>
>>> [!kith|family] [[Yegg]] _szolga_
>>
>>> [!kith|family] [[Klarg]] _testvér_
>
>> [!blank]
>> ## **Kapcsolódó jegyzetek**
>>> [[Cragmaw Vára]]
>>> [[Cragmaw Törzs]]
>>> [[Gundren Rockseeker]]
>>> [[Lhupo]]
>>> [[Yegg]]