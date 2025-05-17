**1. Melyik alapvető strukturális modellezési koncepció összpontosít a rendszer részeinek összegeként történő reprezentálására?**
- A) Absztrakció
- B) Kompozíció
- C) Interfészek definiálása (Interfacing)
- D) Tokozás (Encapsulation)

**2. A strukturális modellek szintjei közül melyik foglalkozik a futásidejű tulajdonságokkal és az összeállított rendszerrel?**
- A) Definíció (Definition)
- B) Használat (Usage)
- C) Példány (Instance)
- D) Elrendezés (Layout)

**3. Mi a "bottom-up" (alulról felfelé építkező) dekompozíciós megközelítés egyik kulcsfontosságú jellemzője?**
- A) Az alkatrészeknek ismert a célja a tervezés elejétől.
- B) A rendszer csak akkor működőképes, ha minden része elkészült.
- C) Az alkatrészek azonnal működőképesek.
- D) Elsősorban szoftverfejlesztésben használatos.

**4. SysML-ben melyik diagramtípus használatos elsődlegesen típusok definiálására, beleértve a kompozíciót, általánosítást, interfészeket és portokat?**
- A) Internal Block Diagram (IBD)
- B) Block Definition Diagram (BDD)
- C) Activity Diagram
- D) Sequence Diagram

**5. Melyik SysML blokktulajdonság-típus kapcsolódik közvetlenül a logikai hierarchia ábrázolásához, amennyiben a sima kompozíción túl több hierarchia is létezik?**
- A) Part Properties (Rész tulajdonságok)
- B) Port Properties (Port tulajdonságok)
- C) Reference Properties (Referencia tulajdonságok)
- D) Value Properties (Érték tulajdonságok)

**6. Mi a ValueType elsődleges szerepe a SysML Value Properties (Érték tulajdonságok) körében?**
- A) Egy konkrét mérési egységet definiál (pl. méter).
- B) Egyfajta mérést képvisel (pl. hosszúság).
- C) Mennyiségek típusait definiálja, hivatkozhat mértékegységekre.
- D) Magát a blokkot reprezentálja kvantitatív jellemzőkkel.

**7. Miben különbözik egy InterfaceBlock egy standard Interface-től SysML-ben?**
- A) Az InterfaceBlock nem rendelkezhet műveletekkel.
- B) Az InterfaceBlock egy speciális blokk proxy portokhoz, és rendelkezhet flow tulajdonságokkal.
- C) Az Interface-t nem használhatják blokkok interfészként.
- D) Az InterfaceBlock mindig rendelkezik belső struktúrával.

**8. Melyik típusú SysML port használatos egy tokozott (encapsulated) blokk belső szolgáltatásaihoz való hozzáférés biztosítására anélkül, hogy maga a port belső struktúrával rendelkezne?**
- A) Full port
- B) Flow port
- C) Proxy port
- D) Deprecated port

**9. A bemutató alapján mi a helyes módja annak SysML-ben, hogy megmutassuk, egy port biztosít (provides) vagy igényel (requires) egy interfészt?**
- A) Asszociációval közvetlenül a portok között.
- B) Lollipop/ball-socket jelöléssel a porton, amely egy interfészhez kapcsolódik.
- C) Egy "connect" függőségi relációval a port és az interfész között.
- D) A port nevében szövegesen jelezve.

**10. Mi a célja egy "binding connector"-nak (kötő konnektor) egy Internal Block Diagram-on (IBD)?**
- A) Két különböző típusú blokk összekapcsolása.
- B) Annak jelzése, hogy egy blokk több példánya létezik.
- C) Annak jelzése, hogy több, látszólag különálló rész valójában ugyanazt a példányt képviseli.
- D) Adatfolyam irányának meghatározása két port között.

**11. Mi történik egy port flow (adatfolyam) tulajdonságaival, ha konjugáltként van megjelölve (pl. `port : ~PortType`)?**
- A) A port minden flow tulajdonsága törlődik.
- B) A port flow irányai megfordulnak (pl. `out` `in`-né válik és fordítva).
- C) A port csak `inout` típusú flow tulajdonságokkal rendelkezhet.
- D) A konjugálás nincs hatással a flow tulajdonságokra, csak az interfészekre.

**12. SysML-ben, ha egy blokk `encapsulated` (tokozott) jelölésű, hogyan biztosítható tipikusan a külső hozzáférés a belső szolgáltatásaihoz?**
- A) A tokozás ideiglenes feloldásával.
- B) Proxy portokon keresztül, amelyek továbbítják a hozzáférést.
- C) Közvetlen kapcsolattal a blokk belső részeihez.
- D) Egy speciális `access` művelet definiálásával a blokkon.

**13. A rendszerkontextus modellezésekor mi az Internal Block Diagram (IBD) elsődleges szerepe?**
- A) Meghatározza, hogy mely elemek részei a környezetnek.
- B) Megmutatja, hogyan lépnek kölcsönhatásba ezek az elemek (pl. adatfolyamokon keresztül).
- C) Definiálja a rendszer és a környezeti elemek típusait és tulajdonságait.
- D) A rendszer követelményeit ábrázolja a környezettel kapcsolatban.

**14. Melyik állítás írja le a strukturális modellek "Usage" (Használat) szintjét?**
- A) Típushierarchiákat, rendszerelemeket és alkatrészkatalógust tartalmaz.
- B) Adatfolyamot, fizikai kapcsolatokat és összeszerelési utasításokat definiál.
- C) Futásidejű tulajdonságokat és az összeállított rendszert írja le.
- D) A rendszer absztrakt nézetét mutatja be.

**15. Mi az "Abstraction" (Absztrakció) koncepciójának egyik meghatározó jellemzője a strukturális modellezésben?**
- A) A rendszert részeinek összességeként reprezentálja.
- B) A rendszernek csak egy bizonyos nézőpontját mutatja meg, elrejtve a részleteket.
- C) Standard együttműködési módokat definiál a komponensek között.
- D) Az alkatrészeket önálló, zárt egységekké teszi.

---
**Magyarázatok**

**1. Melyik alapvető strukturális modellezési koncepció összpontosít a rendszer részeinek összegeként történő reprezentálására?**
B) Kompozíció. A kompozíció az a modellezési elv, amely a rendszert az őt alkotó részek összességeként, azok kapcsolatrendszereként írja le (4. oldal). Az absztrakció a részletek elrejtését, az interfészek a kapcsolódási pontok definiálását, a tokozás pedig a belső működés elrejtését és a határon keresztüli interakciót jelenti.

**2. A strukturális modellek szintjei közül melyik foglalkozik a futásidejű tulajdonságokkal és az összeállított rendszerrel?**
C) Példány (Instance). A "Példány" szint az "Actual Manifestation"-t (Tényleges Megjelenés) képviseli, amely futásidejű tulajdonságokat és az összeállított, konkrét rendszert írja le (5. oldal). A "Definíció" a típusokat és alkatrészkatalógust, a "Használat" pedig az elrendezést és kapcsolatokat írja le.

**3. Mi a "bottom-up" (alulról felfelé építkező) dekompozíciós megközelítés egyik kulcsfontosságú jellemzője?**
C) Az alkatrészek azonnal működőképesek. A "bottom-up" megközelítésnél a kisebb, önmagukban is funkcionális komponensekből építkezünk nagyobb rendszerekké. Az interfészek gyakran generikusak (11. oldal). Ezzel szemben a "top-down" megközelítésnél az alkatrészeknek ismert a célja, de a rendszer csak a végén lesz működőképes.

**4. SysML-ben melyik diagramtípus használatos elsődlegesen típusok definiálására, beleértve a kompozíciót, általánosítást, interfészeket és portokat?**
B) Block Definition Diagram (BDD). A BDD a "Definition" (Definíció) szint eszköze, ahol a rendszer blokkjait (típusait), azok strukturális jellemzőit (kompozíció, attribútumok, értékek), kapcsolatait (általánosítás, asszociáció), valamint interfészeit és portjait definiáljuk (21. és 51. oldal). Az IBD a "Usage" (Használat) szinthez tartozik.

**5. Melyik SysML blokktulajdonság-típus kapcsolódik közvetlenül a logikai hierarchia ábrázolásához, amennyiben a sima kompozíción túl több hierarchia is létezik?**
C) Reference Properties (Referencia tulajdonságok). Míg a "Part Properties" (kompozíció) fa struktúrákat alkotnak (nincs többszörös tulajdonos), addig a "Reference Properties" lehetővé teszik további, logikai hierarchiák modellezését, ahol egy elem több hierarchiának is része lehet, referencia asszociációk segítségével (23. és 25. oldal).

**6. Mi a ValueType elsődleges szerepe a SysML Value Properties (Érték tulajdonságok) körében?**
C) Mennyiségek típusait definiálja, hivatkozhat mértékegységekre. A ValueType mennyiségek típusait írja le (pl. Hosszúság), hivatkozhat mértékegységekre (Unit, pl. méter) és aggregálhat más értékeket. A QuantityKind egyfajta mérést (pl. hossz), az Unit pedig egy konkrét mértékegységet (pl. m) jelöl (26. oldal).

**7. Miben különbözik egy InterfaceBlock egy standard Interface-től SysML-ben?**
B) Az InterfaceBlock egy speciális blokk proxy portokhoz, és rendelkezhet flow tulajdonságokkal. Az Interface-ek műveletek halmazát definiálják. Az InterfaceBlock-ok speciális blokkok, amelyeket proxy portok típusaként használnak, nincs belső struktúrájuk, de rendelkezhetnek flow (adatáramlási) tulajdonságokkal (pl. in/out/inout) (29. oldal).

**8. Melyik típusú SysML port használatos egy tokozott (encapsulated) blokk belső szolgáltatásaihoz való hozzáférés biztosítására anélkül, hogy maga a port belső struktúrával rendelkezne?**
C) Proxy port. A Proxy portok lehetővé teszik a hozzáférést a blokk belső szolgáltatásaihoz vagy részeihez anélkül, hogy felfednék a blokk belső struktúráját. Maguknak a proxy portoknak nincs belső struktúrájuk (ellentétben a Full portokkal) (30. oldal). A Flow port elavult.

**9. A bemutató alapján mi a helyes módja annak SysML-ben, hogy megmutassuk, egy port biztosít (provides) vagy igényel (requires) egy interfészt?**
B) Lollipop/ball-socket jelöléssel a porton, amely egy interfészhez kapcsolódik. A portok interfészeket biztosíthatnak vagy igényelhetnek. Ezt vizuálisan a lollipop (biztosított) és ball-socket (igényelt) jelöléssel ábrázolják a porton, amely az adott interfészhez (vagy InterfaceBlockhoz) kapcsolódik. Fontos, hogy portokat soha ne kössünk össze asszociációkkal, mert azok tulajdonságok, nem típusok (31. és 32. oldal).

**10. Mi a célja egy "binding connector"-nak (kötő konnektor) egy Internal Block Diagram-on (IBD)?**
C) Annak jelzése, hogy több, látszólag különálló rész valójában ugyanazt a példányt képviseli. A "binding connector" azt fejezi ki, hogy két vagy több, a tartalmazó blokkon belüli part property (rész) valójában ugyanarra a konkrét dologra, ugyanarra az instance-re (példányra) utal (35. oldal). Például egy kombinált hőmérséklet- és páratartalom-szenzor esetén.

**11. Mi történik egy port flow (adatfolyam) tulajdonságaival, ha konjugáltként van megjelölve (pl. `port : ~PortType`)?**
B) A port flow irányai megfordulnak (pl. `out` `in`-né válik és fordítva). Egy konjugált port úgy viselkedik, mintha "kifordították" volna. Ha a port eredeti típusa egy `out` irányú X típusú adatfolyamot definiál, akkor a konjugált portnak `in` irányú X típusú adatfolyama lesz, és fordítva. Ugyanez igaz a biztosított/igényelt interfészekre is (42. oldal).

**12. SysML-ben, ha egy blokk `encapsulated` (tokozott) jelölésű, hogyan biztosítható tipikusan a külső hozzáférés a belső szolgáltatásaihoz?**
B) Proxy portokon keresztül, amelyek továbbítják a hozzáférést. A tokozás (encapsulation) megtiltja a közvetlen hozzáférést a blokk belső részeihez. A megoldás a proxy portok használata, amelyek "továbbítják" a hozzáférést a belső szolgáltatásokhoz vagy teljes (full) portokhoz (44-46. oldal).

**13. A rendszerkontextus modellezésekor mi az Internal Block Diagram (IBD) elsődleges szerepe?**
B) Megmutatja, hogyan lépnek kölcsönhatásba ezek az elemek (pl. adatfolyamokon keresztül). Míg a BDD (Block Definition Diagram) a rendszerkontextusban azt definiálja, hogy mely elemek (aktorok, külső rendszerek) részei a környezetnek, addig az IBD azt mutatja be, hogy ezek az elemek és a vizsgált rendszer hogyan lépnek kölcsönhatásba egymással, jellemzően adatfolyamok (information flows) segítségével (61. oldal).

**14. Melyik állítás írja le a strukturális modellek "Usage" (Használat) szintjét?**
B) Adatfolyamot, fizikai kapcsolatokat és összeszerelési utasításokat definiál. A "Usage" szint az elrendezéssel és kapcsolatokkal foglalkozik, beleértve az adatfolyamot, fizikai kapcsolatokat és összeszerelési instrukciókat (5. oldal). Az A) a Definíció szint, a C) a Példány szint leírása.

**15. Mi az "Abstraction" (Absztrakció) koncepciójának egyik meghatározó jellemzője a strukturális modellezésben?**
B) A rendszernek csak egy bizonyos nézőpontját mutatja meg, elrejtve a részleteket. Az absztrakció lényege, hogy a rendszert egy egyszerűsített, magasabb szintű nézőpontból ábrázoljuk, elrejtve a komplexitást és a felesleges részleteket, csak a releváns információkat kiemelve (4. és 12. oldal).