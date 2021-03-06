# Ütemezés

Az órák csütörtökönként a BA.F.07-ben vannak, neptun szerint 08:00-10:35 között előadás és 10:45-11:30 között gyakorlat. (Ezek aránya valamint közte a szünet az aktuális előadásanyag és az igények szerint módosulhat). A „gyakorlat” nem labor, hanem sokkal inkább konzultáció!

|hét    |dátum        |előadás|gyakorlat|
|------:|:-----------:|:-----:|:-------:|
| 1.|09.&nbsp;12.|Bevezető, áttekintés; aSpice alapok|git, GitHub, IDEA ismertetés,
| 2.|09.&nbsp;19.|Agile/Scrum, [első feladat kiadás](sprint_1.md)|csapatsorsolás, Sprint Planning, Task Definition Workshop, Team commitment, Scheduling
| 3.|09.&nbsp;26.|Napi munka, verziókezelők|Branch review, status review, standup (did, will, blocking)
| 4.|10.&nbsp;03.|Unit Testing|Status review, standup, TDD kata
| **5.**|**10.&nbsp;10.**|**első demo**/retrospektív, [második feladat kiadás](sprint_2.md)|Sprint planning, Task Definition Workshop, Team commitment, Scheduling
| 6.|10.&nbsp;17.|Legacy Code, SOLID|Refactoring gyakorlat egy előre előkészített példán
| 7.|10.&nbsp;24.|Review|Random code review egy tetszőleges elfogadott pull requestből
| 8.|10.&nbsp;31.|TBD
| **9.**|**11. 07.**|**második demo**/retrospektív, [harmadik feladat kiadás](sprint_3.md)|Sprint planning, Task Definition Workshop, Team commitment, Scheduling
|10.|11.&nbsp;14.|Continous Integration|Set up a CI script running all implemented unit tests
|11.|11.&nbsp;21.|_Rektori/dékáni szünet_
|12.|11.&nbsp;28.|Összefoglalás, konzultáció, tárgy feedback|Retro + Pair programming
|**13.**|**12.&nbsp;05.**|**harmadik demo**/retrospektív|Coding Dojo, feedback
|**14.**|**12.&nbsp;12.**|**Zárthelyi dolgozat** 08:00-tól 09:30-ig (90 perc), BA.1.10 labor

## Gantt diagram

![gantt](images/gantt.png)


# Házi feladat - 1. hét

1. GitHub fiók létrehozása
    * ha még nincs
2. 11 JDK telepítése, mivel a szoftvert Java nyelven kell elkészíteni
    * ha nincs fönt
3. Fejlesztőkörnyezet telepítése és beállítása
    * IntelliJ IDEA az ajánlott és támogatott eszköz
4. Git és GitHub oktatóanyagok elolvasása
    * ha vannak hiányosságok
    * az órán nincs idő szájbarágósan git használatot oktatni, erre vannak interaktív oktatófelületek
    * ez mindenkinek egyéni felelőssége, ám ha konkrét kérdések merülnek fel, akkor ezekre természetesen kitérünk
5. Git repó klónozása
6. Kód futtatása a futtató- és a fejlesztőkörnyezet beállításainak tesztelése céljából
7. A jegyzet és az abban taglalt segédanyagok megismerése
8. Az elkészítendő szoftver átgondolása (lásd readme), statikus és dinamikus modell elkészítése komponens szinten
    * Ennek terjedeleme (az órái példa alapján): egy absztrakciós szint a négyfelé bontás (kb. user story szint), és egy az ez alatti egyel, minden komponens mégegy kibontása, kb. egyenrangú komponensek létrehozására - osztály szintre nem mennék le, még ha a végén ezekből akár osztály is lesz. Szóval kettő struktúra, kettő dinamikus viselkedést leíró diagram, egy magasabb és egy alacsonyabb absztrakciós szinten. Hogy konkrétan hány building block, azt mindenkinek "érzésre" kell megállapítania, ezért szubjektív az architektúra.
    * Ez egy egyéni feladat, hiszen még nincsenek csapatok. Az elkészíteshez javasolt eszközök: MS Visio, https://www.draw.io/.
    * Az elkészült diagramoknak a következő órán bemutatható állapotban kell lenniük.



# Demók

A félév során a csapatok három alkalommal prezentálják az elvégzett munkát. A „demók” az _elkészült_ szoftver megrendelőnek való bemutatását szimulálják. Nem a kódra vagyunk kíváncsiak, hanem működés közben szeretnénk látni, hogy a szoftver teljesíti feladatban foglalt követelményeket.
A bemutatás során, a `master` branchre befogadott kódot vesszük figyelembe, minden egyéb _„nem készült el határidőre”_, azaz értékelhetetlen.


# Zárthelyi

Ismert, Moodle-ös teszt, 50 kérdéssel, erre 90 perc áll majd a rendelkezésre. Minden kérdéshez 4 válaszlehetőség, amelyek közül pontosan egy a helyes. (Vannak „az alábbiak közül melyik NEM helyes” felépítésű kérdések is.) A rendelkezésre álló idő alatt kérdéseket tetszőleges alkalommal felül lehet vizsgálni, módosítani a teszt „lezárása” után azonnal kiértékelésre is kerül.
