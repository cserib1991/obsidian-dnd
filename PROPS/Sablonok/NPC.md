---
tags:
 - npc
Gender: 
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Location: 
AssociatedGroup: 
NoteIcon: npc
status: egészséges
image: 
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
>***flavor text helye***

> [!info|background-plain left no-t] Statblock
> ```statblock
> name: Npc
> image: [[Commoner.png]]
> monster: Commoner
> columns: 1
> dice: false
> ```

> [!info|no-print]- statblock params
>  name: string  
> size: string  
> type: string  
> subtype: string  
> alignment: string  
> ac: number  
> hp: number  
> hit_dice: string  
> speed: string  
> stats: [number, number, number, number, number, number]  
> fage_stats: [number, number, number, number, number, number, number, number, number]  
> saves:  
> - *ability-score*: number  
> skillsaves:  
> - *skill-name*: number  
> damage_vulnerabilities: string  
> damage_resistances: string  
> damage_immunities: string  
> condition_immunities: string  
> senses: string  
> languages: string  
> cr: number  
> spells:  
> - *description*
> - *spell level*: *spell-list*
> traits:  
> - [trait-name, trait-description]  
> - ...  
> actions:  
> - [trait-name, trait-description]  
> - ...  
> legendary_actions:  
> - [legendary_actions-name, legendary_actions-description]  
> - ...  
> reactions:  
> - [reaction-name, reaction-description]  
> - ...

## Profil
**Leírás helye**


---
> [!column|no-t]
>
>> [!blank]
>> ## Kapcsolatok
>>> [!kith|friend] Barát _barát leírása_
>>
>>> [!kith|antagonist] Ellenség _ellenség leírása_
>>
>>> [!kith|romantic] Románc _románc leírása_
>>
>>> [!kith|family] Családtag _családtag leírása_
>
>> [!blank]
>> ## **Kapcsolódó jegyzetek**
>>> [[NPC]]