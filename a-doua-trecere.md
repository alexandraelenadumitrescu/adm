# A doua trecere — găuri de aprofundat

> Tracker pentru examenul ASE CSIE2 (Statistică Aplicată și Data Science) — 23 iulie.
> Aici aduni ce a rămas **subțire** după prima trecere: zone atinse teoretic dar netestate pe
> probleme numerice complete, capcane recurente, și subpuncte care merită un tur în plus.
>
> **Regula de aur a celei de-a doua treceri:** prima trecere = teorie + grile + recunoaștere.
> A doua trecere = **probleme numerice complete, cronometrate, rezolvate cap-coadă cu cifre.**
> Diferența dintre „știu materia" și „iau punctele" stă fix aici (vezi indici de grup, examen real 2024).

---

## Legendă stare
- ✅ solid (multiple seturi, scor mare, testat pe probleme)
- 🟡 acoperit teoretic + grilă, dar **netestat pe calcul aplicat complet**
- 🔴 slab / neînceput / sursă absentă
- ⚠️ capcană recurentă — de flagat la fiecare recapitulare

---

## CAP. 2 — SONDAJE  *(prima trecere: ~92% mediu pe 6 blocuri)*

Tematica acoperită integral la nivel teorie+grilă. Ce rămâne pentru trecerea 2:

### De insistat (probleme numerice complete, tip S3–S5)
- [ ] 🟡 **Interval de încredere pentru medie** — o problemă completă cu cifre, cronometrată
- [ ] 🟡 **Interval de încredere pentru proporție** — idem
- [ ] 🟡 **Determinarea volumului eșantionului** — pentru medie ȘI pentru proporție, cu/fără revenire
- [ ] 🟡 **Sondaj de serii cu η²** — calcul complet + verificarea relației η² < 1/N₀ (tip S4/S5 becuri)
- [ ] 🟡 **Estimatori serii de talie diferită** (PPS/PPM, totaluri) — numai numiți în trecerea 1, fără calcul aplicat
- [ ] 🟡 **Poststratificare cu calcul numeric** — concept + penalizare acoperite, dar fără exercițiu complet
- [ ] 🟡 **Verificarea reprezentativității** — testele z / χ² / Kolmogorov-Smirnov aplicate pe date

### Capcane de re-flagat (au apărut ca greșeli în trecerea 1)
- [ ] ⚠️ **Eroare = √(dispersie/n)** — radical jos. NU sări radicalul (greșit de mai multe ori)
- [ ] ⚠️ **Volum = totul la pătrat** (z²·S²/Δ²), niciun radical — inversul erorii
- [ ] ⚠️ **Δ = z · σ** — produs, NU sumă (greșit grila „z+σ")
- [ ] ⚠️ **Dispersia proporției = p(1−p)**, niciodată p²
- [ ] ⚠️ **Neyman = abaterea standard σ**, NU dispersia σ² (capcană din diagnostic + 2024)
- [ ] ⚠️ **Fără revenire → ×√(1−n/N)**; la n<0,05N ≈ 1, se ignoră

### Detalii conceptuale de fixat la spaced repetition
- [ ] **Bază de sondaj** = toți | **eșantion** = aleșii (confundate în grila 3, Bloc 1)
- [ ] **Întrebări factologice** = la sfârșit | **excepție pe cote** = la început
- [ ] **Nominal → modul** | **Ordinal → mediană** (inversate în grila 18, Bloc 1)
- [ ] **Testul χ² / Kolmogorov-Smirnov** = compară distribuții întregi (greșit grila 8, Bloc 6)
- [ ] **Durbin-Watson** = autocorelare reziduuri, e din REGRESIE, nu sondaj (distractor)
- [ ] **Erori sistematice NU scad cu n** (doar cele întâmplătoare scad) — greșit grila 3, Bloc 6

### Distincții-oglindă de ținut separate
- [ ] **serii vs stratificat**: serii = câteva grupuri întregi; stratificat = din fiecare grup
- [ ] **omogenitate inversată**: strat omogen în interior | serie eterogenă în interior (= omogenă între serii)
- [ ] **multistadial vs multifazic**: stadii = unități diferite | faze = aceeași unitate, program extins
- [ ] **la stratificat eroarea depinde de variația DIN interior** | la serii de variația DINTRE serii

---

## CAP. 1 — SERII DE REPARTIȚIE  *(diagnostic 3/3 — solid)*
- [ ] ✅ Consolidare prin grile directe (reading doar pe ce ratez)
- [ ] **Indici de grup** — 🔴 punct slab istoric (0/3 examen real 2024). Laspeyres/Paasche,
      relația Iv = Ip × Iq, sume de produse NU sume de rapoarte. *Sesiune dedicată 26 iunie.*

---

## CAP. 3 — SERII DE TIMP
### a–d (Țițan): particularități, indicatori, componente, indici statistici
- [ ] 🟡 **Cald de la examen recent (~o săptămână)** — verificare cu UN set de grile,
      probabil nu necesită zi întreagă. Confirmă cât a rămas fixat.

### e–g (Bourbonnais [5] — SURSĂ ABSENTĂ): autoregresive, Box-Jenkins, nestaționare
- [ ] 🔴 **Cea mai grea zonă a materiei.** ACF/PACF, identificare model, staționaritate
- [ ] 🔴 Abordare prin rezumate + pattern din examene (Bourbonnais lipsește din bibliotecă)
- [ ] ❓ **Sourcing Bourbonnais [5]** — de rezolvat. Highest-risk material gap.

---

## CAP. 4 — REGRESIE ȘI CORELAȚIE
### a–b: regresie + corelație de bază
- [ ] ✅ Solid (diagnostic 3/3). Consolidare prin grile.

### c–d (Bourbonnais [5] — SURSĂ ABSENTĂ): ipoteze model clasic + inferență
- [ ] 🔴 Verificarea ipotezelor: homoscedasticitate, autocorelare (Durbin-Watson), normalitate
- [ ] 🔴 Inferența pe coeficienți (testul t pe β, interval de încredere pentru β)
- [ ] ❓ Dependent de sourcing Bourbonnais [5]

---

## CAP. 5 — DEMOGRAFIE  *(diagnostic 1/3 — slab, sursă [3] disponibilă integral)*
- [ ] 🔴 Capitol slab, de la zero. Sursa Mihăescu [3] e disponibilă — randament maxim
- [ ] ⚠️ **Natalitate vs fertilitate** (greșit la diagnostic) — natalitate/pop. totală; fertilitate/femei fertile
- [ ] ⚠️ **Unitatea de observare la recensământ = persoana** (greșit la diagnostic)
- [ ] Subpuncte: efectiv/dinamică/densitate, structură, îmbătrânire, natalitate/fertilitate, mortalitate
- [ ] *Zi dedicată tip-azi. Mai intuitiv decât sondaje (rate, piramide — concrete).*

---

## CAP. 6 — ANALIZĂ MULTIVARIATĂ  *(diagnostic 3/3 — pattern recognition)*
- [ ] ✅ Solid pe recunoaștere. Nu atac în profunzime, doar tipul de problemă
- [ ] ⚠️ **Analiza cluster**: omogen în interior, eterogen între grupuri
      (NU confunda cu sondajul de serii — logică inversată!)
- [ ] Cluster / ACP / discriminantă — câte un set de grile de verificare

---

## PLAN TEMPORAL (de la 25 iunie)

| Perioadă | Disponibilitate | Focus |
|---|---|---|
| 25 iunie → 8 iulie | fereastră de aur (~13 zile, împărțită cu licența) | **zonele grele: demografie, Box-Jenkins, ipoteze regresie, indici de grup** |
| 9 iulie | muncă 8h începe + pregătire licență | minim |
| 10 iulie | **licență** | — |
| 11 iulie | muncă + pregătire training | minim |
| 12–19 iulie | **training Germania** + muncă | întreținere seara (~1h) |
| 20–22 iulie | muncă ziua | **simulări timed finale** (seri) |
| 23 iulie | **EXAMEN** | — |

**Țintă:** 28–29/30 garantat, 30/30 fezabil cu marja existentă.
**Slăbiciunea de bătut:** neatenția (greșeli de structură formulă), nu necunoașterea.
A doua trecere = repetiție până devine reflex + probleme numerice complete cronometrate.

---

## CHECKLIST SIMULĂRI TIMED
- [ ] Simulare 1 — ~14 iulie (dacă prinde o seară liberă în Germania)
- [ ] Simulare 2 — ~18 iulie
- [ ] Simulare 3 (completă, cap-coadă, cronometrată) — 22 iulie, verificare finală
- [ ] Examene reale de reluat: 2019, 2024 (deja în proiect, folosite ca diagnostic)

---

*Ultima actualizare: 25 iunie. Adaugă găuri noi pe măsură ce parcurgi capitolele.*
