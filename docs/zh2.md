# Tavalyi ZH/pótZH-n látott kérdések

Köszi a fotókért _<span class="info">@Duncan</span>_

---
Mit jelent az, hogy ROI?

1. Rector Out of Institiute
2. A képnek a legvilágosabb része
3. Azon részét jelöli a képnek, ahol a legjobban látszanak az élek
4. Egy téglalap alakú izémizé, amit néha felrakunk egy képre, majd esetleg le is szedjük
5. A képen levő legnagyobb objektumot tartalmazó téglalap alakú rész
6. <span class="correct">Azon része a képnek, amelyen műveleteket akarunk végrehajtani</span>
7. Azon része a képnek, amelyet megmódosítottunk, de még nem mentettük ki az eredményt
8. KIRÁLY, dán nyelven
9. A képnek a legsötétebb része

---

Ha egy nyolcbites színmélységú intenzitásképen, melyen csak a páros intenzitások vannak jelen de azok mind jelen vannak, eróziót hajtunk végre 7x7-es struktúráló elemmel

1. A képen megtalálható színek száma biztosan növekszik
2. A képen megtalálható színek száma biztosan csökken
3. A képen megtalálható színek száma biztosan nem változik
4. A képen megtalálható színek száma biztosan nem csökken de növekedhet
5. <span class="correct">A képen megtalálható színek száma biztosan nem növekszik de csökkenhet</span>
6. Az eredmény képen csak páratlan intenzitások lesznek jelen, és abból sem mindegyik
7. Az eredmény kép három színcsatornás színes kép lesz
8. Ekkora struktúráló elemmel nem is lehet eróziót számolni
9. Az eredmény képen csak 49-es intenzitású képpontok lesznek

---

A $\begin{bmatrix}0 & -k & 0 \\-k & 1+4k & -k \\0 & -k & 0 \\\end{bmatrix}$ maszkkal való szűrés melyik műveleteket képes elvégezni az alábbiak közül és milyen k érték kell ehhez? (Több is jó)

<span class="info">:octicons-info-16: A kernel elemeinek összege 1, a kép színvilága nem változik meg</span>

1. <span class="correct">Homályosít és zajt szűr, ha $-\frac{1}{4} < k < 0$</span>
2. Feketére festi át a képet, ha $k = 0$
3. Az adott képpontra ható gravitációs erő kiszámítása, ahol k az egyetemes tömegvonzási állandó
4. <span class="correct">Élesíti a képet, ha $k > 0$</span>
5. Hisztogram kiegyenlítés, ha $k = 0$
6. Vázkeresés, ha $k = -1$
7. Megkeresi a legrelevánsabb kört a képen, ha $k = 2\pi$
8. Hiperbolát illeszt a képen levő legvilágosabb pontokra, ha $k = exp(1) = 2.7182...$
  
---

Az alábbi műveletek közül melyik __HÁROM__ használ struktúráló elemet?

1. $F(x) = (x+18)/2$ színtranszformáció
2. <span class="correct">Tágítás (dilatáció)</span>
3. Képek összeadása
4. Medián szűrő
5. Gauss-szűrő
6. Blur szűrő
7. Alul áteresztő szűrő
8. <span class="correct">Morfológiai zárás</span>
9. Felül áteresztő szűrő
10. <span class="correct">Blackhat transzformáció</span>
11. Elforgatás tetszőleges szöggel
12. Főátló menti tükrözés

---

Igaz vagy hamis?

| Állítás | Igaz | Hamis |
| --- | --- | --- |
| A gradiens számító maszkokban a számok összege mindig 1 | Igaz | <span class="correct">Hamis</span> |
| Bármely főirány (vízszintes, függőleges, főátló, mellékátló) menti tükörkép előállítható a vízszintes tengely menti tükörkép elforgatásával | <span class="correct">Igaz</span> | Hamis |
| A Roberts-féle maszkokkal gradienseket szoktunk számolni. | <span class="correct">Igaz</span> | Hamis |
| Amikor színes képeken végzünk medián szűrést, egymástól függetlenül kezeljük a színcsatornákat. | Igaz | <span class="correct">Hamis</span> |
| A morfológiai zárás (closing = dilation + erosion) múvelet során a világos szinú objektumok növekedése kizárt, csak csökkenni tudnak. | Igaz | <span class="correct">Hamis</span> |
| A medián szűrőt többek között hisztogram kiegyenlítésére is használjuk. | Igaz | <span class="correct">Hamis</span> |
| Ha vágást (thresholding) alkalmazunk egy képre, akkor eredményként több kisebb képet kapunk. | Igaz | <span class="correct">Hamis</span> |
| A blackhat transzformáció világos színű hernyókat tud megkeresni a képen, ha a háttér sötétebb a hernyónál. | <span class="correct">Igaz</span> | Hamis |
| A Gauss-szűrő maszkjában előfordulnak pozitív számok. | <span class="correct">Igaz</span> | Hamis |
| A histogram kiegyenlítő módszerek közül egyik sem használ struktúráló elemet. | <span class="correct">Igaz</span> | Hamis |
| A Gauss-féle szűrővel képeket szoktunk élesíteni. | Igaz | <span class="correct">Hamis</span> |
| Amelyik színtranszformáció egy 188-as intenzitású képpontot 99-esre módosít, az az összes 188-as intenzitású képpontot 99-esre módosítja. | <span class="correct">Igaz</span> | Hamis |
| A determinisztikus hisztogram kiegyenlítő módszernek szüksége van véletlen számok generálására. | Igaz | <span class="correct">Hamis</span> |
| Vázkereséskor a legnagyobb köröket a morfológiai gradiens segítségével szokás megkeresni. | Igaz | <span class="correct">Hamis</span> |

---

Ha egy színes kép színcsatornáit felcseréljük egy véletlenszerűen kiválasztott permutáció szerint, és azt tapasztaljuk, hogy a Mikulás kék ruhát visel és a karácsonyfa piros lett.

1. Milyen színű a tányérban levő áfonya (ami eredetileg kék volt)?
     - Kék
     - Fehér
     - Piros
     - <span class="correct">Zöld</span>
     - Narancssárga
     - Fekete
     - Rózsaszín
     - Sárga
     - Nem lehet megállapítani

2. Milyen színű a képen a jegesmedve (ami eredetileg fehér volt)?
     - Kék
     - <span class="correct">Fehér</span>
     - Piros
     - Zöld
     - Fekete
     - Rózsaszín
     - Barna
     - Grizli
     - Panda

---

Amennyiben egy saját implementációt akarunk megvalósítani egy általános alakú és méretű struktúráló elemet használó morfológiai tágításnak, melyik algoritmusra lesz egész biztosan szükségünk az alábbiak közül?

1. Integrálok numerikus megközelítése
2. Szinuszüggvény számítása
3. Egész szám törzstényezőire bontása
4. Maximum kiválasztás
5. Rendező algoritmus
6. Backtracking
7. Nagy felbontású véletlenszám generálás
8. Exponenciális függvény számítása
9. <span class="correct">Minimum kiválasztás</span>
10. Eratosztenész szitája