**1. Melyek a grafikus szcenáriónyelvek fő céljai a kommunikációmodellezésben?**
- A) Objektumok belső logikájának modellezése
- B) Objektumok közötti viselkedés modellezése
- C) Adatbázis sémák definiálása
- D) Hardver komponensek elosztása

**2. A platform-alapú rendszertervezés során melyik modellből generálódik tipikusan a forráskód (Source code)?**
- A) Funkcionális modell (Functional model)
- B) Platform modell (Platform model)
- C) Komponens viselkedési modell (Component behav. model)
- D) Követelmények (Requirements)

**3. Mi a legfontosabb szempont az objektumok közötti kommunikáció modellezésekor a bemutatott célok szerint?**
- A) Az üzenetekben átadott adatok és paraméterek részletes specifikációja
- B) Az üzenetek sorrendje és típusa
- C) Az egyes objektumok belső állapotváltozásainak teljes leírása
- D) A rendszer teljesítményének optimalizálása

**4. Melyik NEM tartozik a kommunikációs diagramok alkalmazási területei közé?**
- A) Használati esetek (use cases) finomítása
- B) Protokollok tervezése
- C) Tesztesetek specifikációja
- D) Részletes adatstruktúrák tervezése

**5. Milyen strukturális modellelemeket használhatnak fel az interakciós diagramok?**
- A) Csak állapotgépeket és tevékenységdiagramokat
- B) Osztály (Class), Blokk (Block), Komponens (Component)
- C) Csak jeleket (Signals) és műveleteket (Operations)
- D) Adatfolyam diagramokat és entitás-kapcsolat diagramokat

**6. Melyik interakciós diagramtípus fókuszál elsődlegesen az időzítésre?**
- A) Szekvencia Diagram (Sequence Diagram)
- B) Kommunikációs Diagram (Communication Diagram)
- C) Időzítési Diagram (Timing Diagram)
- D) Interakció Áttekintő Diagram (Interaction Overview Diagram)

**7. Mit jelöl egy résztvevő (Participant) életvonala (lifeline) egy szekvencia diagramon?**
- A) A résztvevő által végrehajtott műveletek számát
- B) A résztvevő létezésének időtartamát
- C) A résztvevőhöz rendelt memória méretét
- D) A résztvevő prioritását a rendszerben

**8. Mit jelöl az "Execution specification" (végrehajtás specifikáció) egy szekvencia diagramon?**
- A) Egy objektum létrehozásának pillanatát
- B) Azt az időtartamot, amíg egy résztvevő aktív (feldolgoz vagy szinkron válaszra vár)
- C) Egy aszinkron üzenet küldését
- D) Egy üzenet elvesztését a kommunikáció során

**9. Melyik kombinált fragmens operátor használatos választásra a megadott operandusok között?**
- A) loop
- B) opt
- C) alt
- D) par

**10. Mi a "ref" (Interaction Use) elem célja egy szekvencia diagramon?**
- A) Egy kritikus, megszakíthatatlan műveletsort jelöl
- B) Egy másik, már létező interakció újrafelhasználását és beágyazását teszi lehetővé
- C) Egy feltételes végrehajtást definiál, ahol az operandus opcionális
- D) Párhuzamosan futó eseménysorozatokat modellez

**11. Mit fejez ki egy állapot invariáns (State Invariant) egy szekvencia diagramon?**
- A) Azt, hogy egy komponens állapota soha nem változhat meg.
- B) Egy feltételt, aminek igaznak kell lennie egy adott időpillanatban a komponens életvonalán.
- C) Az eltelt időt két esemény között.
- D) Egy üzenet maximális várakozási idejét.

**12. Hogyan definiálják a szekvencia diagramok szemantikáját?**
- A) Az érvényes, érvénytelen vagy nem eldönthető trace-ek (nyomvonalak) halmazaként
- B) A résztvevők állapotváltozásainak sorozataként
- C) Az üzenetekhez rendelt prioritások alapján
- D) Egy formális nyelvtani leírással, mint a Backus-Naur forma

**13. Mit jelent a "gyenge (részleges) sorrendiség" (weak partial ordering) alapelve a szekvencia diagramok szemantikájában?**
- A) Minden esemény pontosan meghatározott időbeli sorrendben történik.
- B) Az események sorrendje csak ugyanazon életvonalon belül kötött, illetve az üzenet fogadása a küldés után történik.
- C) Az üzenetek küldése és fogadása tetszőleges sorrendben történhet.
- D) Csak a szinkron üzenetek sorrendje kötött.

**14. A "strict" (szigorú) kombinált fragmens operátor esetén hogyan értelmezendő az operandusokban lévő események sorrendje?**
- A) Az események sorrendje csak ugyanazon az életvonalon belül kötött.
- B) Az operandusokban lévő események sorrendje minden érintett életvonalon megmarad.
- C) Az események tetszőleges sorrendben végrehajthatók az operandusok között.
- D) Csak az első operandus eseményeinek sorrendje kötött.

**15. Melyik kombinált fragmens használatos egy olyan viselkedés modellezésére, amely vagy végrehajtódik, vagy nem?**
- A) alt
- B) loop
- C) opt
- D) break

**16. Mit jelent a "break" kombinált fragmens használata egy szekvencia diagramon?**
- A) A ciklus következő iterációjára ugrik.
- B) Ha a fragmens viselkedése illeszkedik, a tartalmazó fragmens hátralévő része nem illeszkedik.
- C) Párhuzamos végrehajtást indít.
- D) Egy opcionális viselkedést jelöl.

**17. Milyen viselkedést modellez a "par" (parallel) kombinált fragmens?**
- A) Az operandusok viselkedésének szigorúan kötött sorrendű végrehajtását.
- B) Az operandusok viselkedésének tetszőleges összefésülését (interleaving).
- C) Egyetlen operandus feltételes végrehajtását.
- D) Egy ciklikus viselkedést, amely legalább egyszer lefut.

**18. Mi a "neg" (negative) kombinált fragmens célja?**
- A) Olyan viselkedést specifikál, amelynek pontosan meg kell történnie.
- B) Olyan viselkedést specifikál, amelynek nem szabad megtörténnie.
- C) Egy feltételes elágazást modellez.
- D) Egy atomi, megszakíthatatlan műveletet jelöl.

**19. Mikor tekinthető érvényesnek (valid) egy trace egy "assert" (állítás) fragmens esetén?**
- A) Ha a trace tartalmazza a fragmensben specifikált eseménysorozat komplementerét.
- B) Ha a trace pontosan illeszkedik a fragmensben specifikált eseménysorozatra.
- C) Ha a trace egyáltalán nem tartalmazza a fragmens eseményeit.
- D) Az "assert" fragmens mindig inkonkluzív trace-eket eredményez.

**20. Mi a fő célja a "consider" és "ignore" fragmenseknek?**
- A) Időzítési megszorítások definiálása.
- B) Az irreleváns üzenetek kiszűrése a trace elemzésekor.
- C) Objektumok létrehozásának és törlésének modellezése.
- D) Párhuzamos folyamatok szinkronizálása.

**21. Mi jellemző leginkább az aktor-rendszer interakciók modellezésére szekvencia diagramokkal?**
- A) Komplex logika és kombinált fragmensek intenzív használata.
- B) Főként egyszerű elemek használata, a szemantika kevésbé hangsúlyos.
- C) A belső állapotváltozások részletes modellezése.
- D) Erős fókusz a formális verifikáción.

**22. Tesztesetek definiálásakor mire szolgál a "trigger/setup" fázis?**
- A) Arra, hogy a trace-t érvénytelennek minősítse, ha eltér.
- B) Arra, hogy eldöntse, az észlelt trace a tesztesethez tartozik-e.
- C) Arra, hogy garantálja a teszt sikeres lefutását.
- D) Arra, hogy a rendszer belső állapotait naplózza.

**23. Ha egy teszteset "setup" fázisa bekövetkezik, de az "assertion" fázis nem, milyen eredményt kapunk?**
- A) Érvényes (valid)
- B) Érvénytelen (invalid)
- C) Nem eldönthető (inconclusive)
- D) Figyelmen kívül hagyott (ignored)

**24. Mi a legfontosabb teendő a szekvencia diagramok használata előtt egy csapatban, a dokumentum utolsó figyelmeztetése szerint?**
- A) Kiválasztani a legújabb UML verziót.
- B) Rögzíteni az interpretációt.
- C) Minden lehetséges kombinált fragmenst használni.
- D) Minimalizálni az üzenetek számát.

---
**Magyarázatok:**

**1. Melyek a grafikus szcenáriónyelvek fő céljai a kommunikációmodellezésben?**
- B) Objektumok közötti viselkedés modellezése
- Magyarázat: A 2. oldal szerint a grafikus szcenáriónyelvek az "inter-object behavior" (objektumok közötti viselkedés) modellezésére szolgálnak.

**2. A platform-alapú rendszertervezés során melyik modellből generálódik tipikusan a forráskód (Source code)?**
- C) Komponens viselkedési modell (Component behav. model)
- Magyarázat: A 3. oldalon látható ábra szerint a "Component behav. model"-ből indul egy nyíl a "code generation" felirattal a "Source code" felé.

**3. Mi a legfontosabb szempont az objektumok közötti kommunikáció modellezésekor a bemutatott célok szerint?**
- B) Az üzenetek sorrendje és típusa
- Magyarázat: Az 5. oldal említi: "Order and type of messages are important". Az adatok és paraméterek nem a fő fókusz ("Data and parameters are not the main focus").

**4. Melyik NEM tartozik a kommunikációs diagramok alkalmazási területei közé?**
- D) Részletes adatstruktúrák tervezése
- Magyarázat: A 6. oldal sorolja az alkalmazási területeket: use case-ek finomítása, metódushívási szekvenciák modellezése, protokollok tervezése, végrehajtási trace-ek vizualizálása, tesztesetek specifikációja. A részletes adatstruktúrák tervezése inkább osztálydiagramok feladata.

**5. Milyen strukturális modellelemeket használhatnak fel az interakciós diagramok?**
- B) Osztály (Class), Blokk (Block), Komponens (Component)
- Magyarázat: A 7. oldal szerint az interakciós diagramok strukturális elemekként "Class, Block, Component"-et használnak.

**6. Melyik interakciós diagramtípus fókuszál elsődlegesen az időzítésre?**
- C) Időzítési Diagram (Timing Diagram)
- Magyarázat: A 8. oldal szerint a "Timing Diagram" - "Focuses on timing".

**7. Mit jelöl egy résztvevő (Participant) életvonala (lifeline) egy szekvencia diagramon?**
- B) A résztvevő létezésének időtartamát
- Magyarázat: A 12. oldal szerint a résztvevőknek "Have a lifeline that denotes the span of their existence".

**8. Mit jelöl az "Execution specification" (végrehajtás specifikáció) egy szekvencia diagramon?**
- B) Azt az időtartamot, amíg egy résztvevő aktív (feldolgoz vagy szinkron válaszra vár)
- Magyarázat: A 14. oldal definiálja: "Denotes the duration when a participant is active - Either processing or waiting for a synchronous response".

**9. Melyik kombinált fragmens operátor használatos választásra a megadott operandusok között?**
- C) alt
- Magyarázat: A 16. oldal szerint az "alt: choice between the operands".

**10. Mi a "ref" (Interaction Use) elem célja egy szekvencia diagramon?**
- B) Egy másik, már létező interakció újrafelhasználását és beágyazását teszi lehetővé
- Magyarázat: A 17. és 18. oldalakon az "Interaction Use" és "References" cím alatt szerepel, hogy az interakciók támogatják a dekompozíciót és újrafelhasználást. A "ref" kulcsszóval hivatkozunk egy másik szekvencia diagramra.

**11. Mit fejez ki egy állapot invariáns (State Invariant) egy szekvencia diagramon?**
- B) Egy feltételt, aminek igaznak kell lennie egy adott időpillanatban a komponens életvonalán.
- Magyarázat: A 19. oldalon a "State invariants" alatt szerepel, hogy "States of components can be asserted". A 41. oldal pontosítja, hogy a "constraint must evaluate to true".

**12. Hogyan definiálják a szekvencia diagramok szemantikáját?**
- A) Az érvényes, érvénytelen vagy nem eldönthető trace-ek (nyomvonalak) halmazaként
- Magyarázat: A 23. oldal szerint: "Semantics is defined as the sets of traces that are – valid, invalid, or inconclusive – for the Sequence Diagram."

**13. Mit jelent a "gyenge (részleges) sorrendiség" (weak partial ordering) alapelve a szekvencia diagramok szemantikájában?**
- B) Az események sorrendje csak ugyanazon életvonalon belül kötött, illetve az üzenet fogadása a küldés után történik.
- Magyarázat: A 25. oldal kifejti: "Weak (partial) ordering: „happens-before” 1. Occurrences on the same lifeline are ordered 2. Receiving a message occurs after sending it (causality)".

**14. A "strict" (szigorú) kombinált fragmens operátor esetén hogyan értelmezendő az operandusokban lévő események sorrendje?**
- B) Az operandusokban lévő események sorrendje minden érintett életvonalon megmarad.
- Magyarázat: A 32. oldal szerint a strict sequencing esetén: "Occurrences are ordered on all lifelines - In the order of the operands".

**15. Melyik kombinált fragmens használatos egy olyan viselkedés modellezésére, amely vagy végrehajtódik, vagy nem?**
- C) opt
- Magyarázat: A 16. oldal szerint az "opt: choice between the sole operand or nothing". Tehát az operandusban lévő viselkedés vagy lefut, vagy nem.

**16. Mit jelent a "break" kombinált fragmens használata egy szekvencia diagramon?**
- B) Ha a fragmens viselkedése illeszkedik, a tartalmazó fragmens hátralévő része nem illeszkedik.
- Magyarázat: A 35. oldal szerint: "If fragment behavior is matched, then Rest of the enclosing fragment is not matched".

**17. Milyen viselkedést modellez a "par" (parallel) kombinált fragmens?**
- B) Az operandusok viselkedésének tetszőleges összefésülését (interleaving).
- Magyarázat: A 36. oldal szerint a parallel fragment: "Arbitrary interleaving of operand behaviors".

**18. Mi a "neg" (negative) kombinált fragmens célja?**
- B) Olyan viselkedést specifikál, amelynek nem szabad megtörténnie.
- Magyarázat: A 39. oldal szerint a negative fragment: "Specifies what must not happen". Az invalid trace-ek azok, amik illeszkednek a fragmensre.

**19. Mikor tekinthető érvényesnek (valid) egy trace egy "assert" (állítás) fragmens esetén?**
- B) Ha a trace pontosan illeszkedik a fragmensben specifikált eseménysorozatra.
- Magyarázat: A 38. oldal szerint az "Assertion fragments: Specifies exactly what must happen". A valid trace-ek azok, amik illeszkednek erre: "{ (!x, ?x) }".

**20. Mi a fő célja a "consider" és "ignore" fragmenseknek?**
- B) Az irreleváns üzenetek kiszűrése a trace elemzésekor.
- Magyarázat: A 42. oldal szerint: "Consider and Ignore filter out the irrelevant messages".

**21. Mi jellemző leginkább az aktor-rendszer interakciók modellezésére szekvencia diagramokkal?**
- B) Főként egyszerű elemek használata, a szemantika kevésbé hangsúlyos.
- Magyarázat: A 46. oldal szerint: "Mostly using simple elements only - No complex logic (Combined fragments) - Semantics is not very important here".

**22. Tesztesetek definiálásakor mire szolgál a "trigger/setup" fázis?**
- B) Arra, hogy eldöntse, az észlelt trace a tesztesethez tartozik-e.
- Magyarázat: A 49. oldal szerint a Trigger/setup phase (may): "Decides if the observed trace belongs to the test case".

**23. Ha egy teszteset "setup" fázisa bekövetkezik, de az "assertion" fázis nem, milyen eredményt kapunk?**
- B) Érvénytelen (invalid)
- Magyarázat: Az 50. oldalon lévő ábra jobb alsó részén: "If setup occurs and assertion does not -> invalid (test failure)".

**24. Mi a legfontosabb teendő a szekvencia diagramok használata előtt egy csapatban, a dokumentum utolsó figyelmeztetése szerint?**
- B) Rögzíteni az interpretációt.
- Magyarázat: Az 51. oldal (Summary) utolsó pontja és a 44. oldal (Final Word of Caution) is hangsúlyozza: "But interpretation has to be fixed in the team!" illetve "Fix your interpretation prior to using Sequence Diagrams".