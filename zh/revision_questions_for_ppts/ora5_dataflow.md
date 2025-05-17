**1. Mi a folyamatmodellezés egyik elsődleges célja?**
- A) A hardverkomponensek fizikai elrendezésének meghatározása.
- B) A bemenetek kimenetekké alakítása műveletek sorozatán keresztül.
- C) A felhasználói felület (UI) részletes tervezése.
- D) A rendszer költségvetésének optimalizálása.

**2. Mit jelent egy atomi tevékenység (action) a folyamatmodellezésben?**
- A) Egy olyan tevékenység, amelyet több párhuzamos szálon hajtanak végre.
- B) Egy olyan tevékenység, amely mindig hibával végződik.
- C) Egy olyan tevékenység, amelyet nem részleteznek tovább az adott absztrakciós szinten.
- D) Egy olyan tevékenység, amely kizárólag adatbevitelt reprezentál.

**3. Mire szolgál az adatfolyam (data-flow) modellezése?**
- A) A tevékenységek közötti vezérlés átadásának sorrendjét határozza meg.
- B) Meghatározza, hogy egy adott adatelem hogyan áramlik a tevékenységek között.
- C) A rendszer biztonsági réseinek azonosítására szolgál.
- D) A tevékenységek fizikai helyét specifikálja a rendszerben.

**4. Mi a különbség a Fork és Join csomópontok között egy aktivitási diagramon?**
- A) A Fork egyetlen bejövő folyamatot oszt szét több kimenőre, míg a Join több bejövőt egyesít egyetlen kimenővé.
- B) A Fork több bejövő folyamatot egyesít egyetlen kimenővé, míg a Join egyetlen bejövőt oszt szét több kimenőre.
- C) A Fork egy döntési pontot reprezentál, míg a Join egy ciklus végét jelöli.
- D) A Fork adatokat generál, míg a Join adatokat fogyaszt.

**5. Hogyan jelölik az adatfolyamot (data flow) az UML/SysML aktivitási diagramokon?**
- A) Szaggatott nyilakkal.
- B) Folytonos nyilakkal.
- C) Hullámos vonalakkal.
- D) Dupla vonalú nyilakkal.

**6. Hogyan lehet adat tokeneket replikálni (többszörözni) az aktivitási diagramokon?**
- A) Egy Merge csomópont használatával.
- B) Egy Decision csomópont használatával.
- C) Egy Fork csomópont használatával.
- D) Kizárólag «centralBuffer» használatával.

**7. Helyettesítheti-e az adatfolyam a vezérlési folyamatot?**
- A) Nem, a kettő teljesen független egymástól.
- B) Igen, az adatfolyam helyettesítheti a vezérlési folyamatot, mivel az adatszükséglet implicit sorrendiséget definiál.
- C) Csak akkor, ha «stream» típusú adatfolyamról van szó.
- D) Nem, a vezérlési folyamat mindig kötelezően modellezendő, még adatfolyam megléte esetén is.

**8. Mi jellemző a SysML «datastore» típusú objektum csomópontra?**
- A) Átmeneti üzenetsort modellez, ahol a tokenekért verseny van.
- B) Tartós adattárolást jelöl (amíg a tartalmazó szülő aktív), és a tokenek másolódnak lekérdezéskor.
- C) Kizárólag a «continuous» stream adatfolyamokkal használható.
- D) Nem kapcsolódik tevékenységhez, és csak vezérlési tokeneket tárolhat.

**9. Milyen típusú megszakításra hasonlít leginkább az "Interruptible Activity Region" megszakítása?**
- A) Hardveres megszakításra (HW interrupt).
- B) Egy adatbázis tranzakció visszagörgetésére.
- C) Egy SIGINT jelzésre (Linux), ahol a régió végrehajtása leáll.
- D) Egy függvény rekurzív meghívására.

**10. Mi NEM szükséges feltétlenül egy akció (action) végrehajtásához (fire)?**
- A) Adat token minden bemeneti pin-en.
- B) Vezérlési token minden bejövő vezérlési folyamat összekötőn.
- C) Egy bejövő esemény minden akció típus esetén.
- D) A tartalmazó szülő (aktivitás vagy régió) aktív állapota.

**11. Mi a Final node (befejező csomópont) szerepe egy aktivitási diagramban?**
- A) Új vezérlési tokent generál az aktivitás végén.
- B) Eltávolítja az összes vezérlési tokent és visszatér az aktivitásból.
- C) Kizárólag egy adatfolyam végét jelzi.
- D) Egy párhuzamos végrehajtási ágat indít.

**12. Hogyan viselkedik egy Join csomópont, ha adat tokeneket vár minden bemenetén?**
- A) Csak egyetlen adat tokent továbbít az egyik bemenetről.
- B) Megvárja, amíg minden bemenetén megjelenik egy adat token, majd az összeset továbbítja.
- C) Átalakítja az adat tokeneket vezérlési tokenekké.
- D) Véletlenszerűen választ egy adat tokent a továbbításhoz.

**13. Mit jelent az "Unambiguity" (egyértelműség) egy aktivitási diagram döntési pontjainál?**
- A) Minden döntési pontnak pontosan két kimenő ága lehet.
- B) Soha nem lehet egynél több feltétel igaz ugyanazon döntési pontnál egyidejűleg.
- C) Minden lehetséges bemeneti adatra léteznie kell egy kimenő ágnak.
- D) A döntési feltételeknek egyszerű logikai kifejezéseknek kell lenniük.

**14. Mi az ajánlott első lépés egy folyamatmodell felépítésekor a "Best Practices" szerint?**
- A) Az alternatív és kivételes útvonalak hozzáadása.
- B) Az adatok és adatfolyamok azonosítása és modellezése.
- C) A tipikus (elsődleges) vezérlési folyamat modellezése.
- D) A tevékenységek funkcionális blokkokhoz rendelése.

**15. Milyen tipikus hibához vezethet, ha egy döntési (Decision) csomópont ágait közvetlenül egy Join csomópontba vezetjük vissza anélkül, hogy mindkét ág lefutna?**
- A) Végtelen ciklus kialakulásához.
- B) Az egyik tevékenység kétszeres végrehajtásához.
- C) Deadlock (holtpont) kialakulásához.
- D) Adatvesztéshez a Join csomópontban.

---
**Magyarázatok**

**1. Mi a folyamatmodellezés egyik elsődleges célja?**
- **Válasz és magyarázat:** B) A bemenetek kimenetekké alakítása műveletek sorozatán keresztül. A folyamatmodellezés alapvető célja a bemeneteknek kimenetekké történő átalakításának modellezése, egy meghatározott műveletsorozaton keresztül (5. oldal). Ez magában foglalja a vezérlési és adatfolyamok modellezését is.

**2. Mit jelent egy atomi tevékenység (action) a folyamatmodellezésben?**
- **Válasz és magyarázat:** C) Egy olyan tevékenység, amelyet nem részleteznek tovább az adott absztrakciós szinten. Az atomi tevékenység (action) egy olyan tevékenység, amelyet az adott absztrakciós szinten nem bontanak tovább kisebb részekre (6. oldal). Később finomítható (dekompozícióval).

**3. Mire szolgál az adatfolyam (data-flow) modellezése?**
- **Válasz és magyarázat:** B) Meghatározza, hogy egy adott adatelem hogyan áramlik a tevékenységek között. Az adatfolyam (data-flow) azt specifikálja, hogy az adatok hogyan áramlanak az egyes tevékenységek között (7. oldal), és elősegíti az adatáramlás elemzését, például optimalizálási lehetőségek feltárása vagy a helytelen adathasználatból eredő hibák elkerülése érdekében.

**4. Mi a különbség a Fork és Join csomópontok között egy aktivitási diagramon?**
- **Válasz és magyarázat:** A) A Fork egyetlen bejövő folyamatot oszt szét több kimenőre, míg a Join több bejövőt egyesít egyetlen kimenővé. A Fork csomópont egy bejövő vezérlési vagy adatfolyamot több párhuzamos kimenő folyamatra oszt szét. A Join csomópont ezzel ellentétben megvárja, amíg az összes bejövő párhuzamos folyamat befejeződik, majd egyetlen kimenő folyamatként halad tovább (14. oldal, 42. oldal).

**5. Hogyan jelölik az adatfolyamot (data flow) az UML/SysML aktivitási diagramokon?**
- **Válasz és magyarázat:** B) Folytonos nyilakkal. Az adatfolyamot (data flow) az Input/Output pinek között folytonos (solid) nyilak jelölik az UML/SysML aktivitási diagramokon (18. oldal). A szaggatott nyilak általában a vezérlési folyamatot (control flow) jelölik.

**6. Hogyan lehet adat tokeneket replikálni (többszörözni) az aktivitási diagramokon?**
- **Válasz és magyarázat:** C) Egy Fork csomópont használatával. Az adat tokenek replikálására (többszörözésére) egy Fork csomópontot használnak (20. oldal). Ez lehetővé teszi, hogy ugyanaz az adat több párhuzamos tevékenység bemenetévé váljon.

**7. Helyettesítheti-e az adatfolyam a vezérlési folyamatot?**
- **Válasz és magyarázat:** B) Igen, az adatfolyam helyettesítheti a vezérlési folyamatot, mivel az adatszükséglet implicit sorrendiséget definiál. Az adatfolyam helyettesítheti a vezérlési folyamatot (21. oldal). Ha egy tevékenységnek szüksége van egy másik tevékenység által előállított adatra, az implicit módon meghatározza a végrehajtási sorrendet.

**8. Mi jellemző a SysML «datastore» típusú objektum csomópontra?**
- **Válasz és magyarázat:** B) Tartós adattárolást jelöl (amíg a tartalmazó szülő aktív), és a tokenek másolódnak lekérdezéskor. A «datastore» egy beépített objektum csomópont típus a SysML-ben, amely tartós adattárolást jelöl (amíg a szülő aktivitás fut), és az itt tárolt adat tokenek lekérdezéskor másolódnak (24. oldal).

**9. Milyen típusú megszakításra hasonlít leginkább az "Interruptible Activity Region" megszakítása?**
- **Válasz és magyarázat:** C) Egy SIGINT jelzésre (Linux), ahol a régió végrehajtása leáll. Az "Interruptible Activity Region" megszakítása nem hardveres értelemben vett megszakítás, hanem inkább a Linux SIGINT jelzéséhez hasonló, ahol egy esemény bekövetkezésekor a régió végrehajtása leáll (26. oldal).

**10. Mi NEM szükséges feltétlenül egy akció (action) végrehajtásához (fire)?**
- **Válasz és magyarázat:** C) Egy bejövő esemény minden akció típus esetén. Egy akció végrehajtásához (fire) általában adat tokenek kellenek a bemeneti pineken, vezérlési tokenek a bejövő vezérlési folyamatokon, és a szülő aktivitásnak/régiónak aktívnak kell lennie. Bejövő esemény kifejezetten az "accept" actions (pl. Accept event) típusú akciókhoz szükséges, nem minden akcióhoz (40. oldal).

**11. Mi a Final node (befejező csomópont) szerepe egy aktivitási diagramban?**
- **Válasz és magyarázat:** B) Eltávolítja az összes vezérlési tokent és visszatér az aktivitásból. A Final node (befejező csomópont) azt jelzi, hogy az aktivitás befejeződött. Eltávolítja az összes vezérlési tokent az aktivitásból és az aktivitásból való visszatérést eredményezi (41. oldal).

**12. Hogyan viselkedik egy Join csomópont, ha adat tokeneket vár minden bemenetén?**
- **Válasz és magyarázat:** B) Megvárja, amíg minden bemenetén megjelenik egy adat token, majd az összeset továbbítja. Ha egy Join csomópont adat tokeneket vár minden bemenetén, megvárja, amíg mindegyik bemenetén rendelkezésre áll egy adat token, majd az összes (all) beérkezett adat tokent továbbítja (42. oldal).

**13. Mit jelent az "Unambiguity" (egyértelműség) egy aktivitási diagram döntési pontjainál?**
- **Válasz és magyarázat:** B) Soha nem lehet egynél több feltétel igaz ugyanazon döntési pontnál egyidejűleg. Az "Unambiguity" (egyértelműség) azt jelenti, hogy egy adott döntési pontnál soha nem fordulhat elő, hogy egynél több kimenő ág feltétele egyszerre teljesüljön (61. oldal).

**14. Mi az ajánlott első lépés egy folyamatmodell felépítésekor a "Best Practices" szerint?**
- **Válasz és magyarázat:** C) A tipikus (elsődleges) vezérlési folyamat modellezése. A "Best Practices" szerint a modellépítés első lépése a tipikus (elsődleges) vezérlési folyamat (control-flow) modellezése (62. oldal).

**15. Milyen tipikus hibához vezethet, ha egy döntési (Decision) csomópont ágait közvetlenül egy Join csomópontba vezetjük vissza anélkül, hogy mindkét ág lefutna?**
- **Válasz és magyarázat:** C) Deadlock (holtpont) kialakulásához. Ha egy Decision csomópont után az elágazó vezérlési folyamatok közül csak az egyik fog lefutni, és ezeket egy Join csomópont próbálja meg egyesíteni, az deadlock-hoz (holtpont) vezet, mert a Join minden bemenetén várja a tokent (64. oldal). Ehelyett Merge csomópontot kellene használni.