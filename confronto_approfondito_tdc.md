# Confronto Critico Approfondito: "RIASSUNTI TDC.pdf" vs "Appunti Nina" (Blocchi 1, 2 e 3)
### Laboratorio di Tecnica delle Costruzioni – Prof. Ing. Raffaele Landolfo

---

## 1. Quadro Generale e Sintesi Esecutiva

Il presente documento costituisce una **valutazione comparativa, analitica e rigorosa** tra due corpi documentali appartenenti al corso di *Laboratorio di Tecnica delle Costruzioni* (Prof. Ing. R. Landolfo):
1. **Documento Analizzato**: `RIASSUNTI TDC.pdf` (81 pagine, a.a. 2020-2021).
2. **Documento di Riferimento Ufficiale**: Gli appunti integrali delle lezioni frontali di Nina, suddivisi in tre blocchi:
   - `01-primo blocco 1-9.pdf` (131 pagine – Lezioni 2-9);
   - `02-secondo blocco 10-18.pdf` (134 pagine – Lezioni 10-18);
   - `03-terzo blocco 19-24.pdf` (134 pagine – Lezioni 19-24);
   - *Totale materiale di riferimento*: **399 pagine, 23 lezioni monografiche**.

### Verdetto Sintetico Globale
> [!WARNING]
> **I "RIASSUNTI TDC" NON sono completi e NON sono sufficienti per sostenere con successo l'esame di Laboratorio di Tecnica delle Costruzioni.** 
> Il documento dei riassunti rappresenta una sintesi di impianto prevalentemente **teorico-istituzionale** (meccanica delle sezioni, cinematica elastica/plastica, oscillatore semplice lineare), ma **OMETTE COMPLETAMENTE** l'intero nucleo tecnologico e progettuale su cui si fonda il *Laboratorio* del Prof. Landolfo:
> - **Totalmente assente l'intero capitolo delle Unioni e Connessioni in Acciaio** (Bulloni ordinari e ad alta resistenza, verifiche a taglio, rifollamento, trazione, punzonamento, attrito, unioni saldate a cordone d'angolo con formula direzionale di Von Mises, verifiche a block-tearing).
> - **Totalmente assente la Progettazione delle Scale Metalliche** (scale sospese vs montanti indipendenti, verifica dei gradini a sbalzo con carico concentrato di 2 kN, cosciali e tiranti).
> - **Totalmente assente la tecnologia dei Solai Avanzati** (Travi alveolari / cellular beams e solai integrati tipo Slim Floor / CoSFB).
> - **Totalmente assente la modellazione degli Impalcati nel Piano e Diaframmi Sismici** (funzionamento a diaframma, calcolo dei pioli connettori Nelson, travi-collettore e cordoli tesi/compressi).
> - **Totalmente assente la Torsione nel Calcestruzzo Armato** (traliccio spaziale a pareti sottili di Rausch).
> - **Presenza di GRAVI ERRORI dimensionali e concettuali**, come la formula dei link nei controventi eccentrici ($M/M$ anziché $M/V$) e l'inversione clamorosa delle prescrizioni del passo delle staffe in c.a. tra zona critica e zona corrente.

---

## 2. Matrice Sinottica di Corrispondenza Lezione per Lezione

Nella tabella seguente viene confrontata ciascuna delle 23 lezioni di Nina (da Lezione 2 a Lezione 24) con i contenuti presenti in `RIASSUNTI TDC.pdf`.

| Lez. Nina | Argomento Principale negli Appunti di Nina | Pagine Nina | Pagine Riassunti TDC | Stato di Copertura | Valutazione Critica Sintetica |
| :---: | :--- | :---: | :---: | :---: | :--- |
| **L2** | Introduzione NTC 2018, Azioni permanenti ($G_1, G_2$), Carichi variabili ($Q$), carichi per unità di superficie, neve (intro). | B1: 1–14 | 7–9 | **Meno Specifico** | Concetti qualitativi presenti; mancano le tabelle dei carichi accidentali e l'analisi dettagliata dei carichi dei solai. |
| **L3** | Carico Neve ($q_s$, zone, quota, coefficienti $\mu_i, c_e, c_t$); Carico Vento ($q_b, c_e, c_p, c_d$, turbolenza, vortici di Von Karman, galloping); Robustezza e Fuoco. | B1: 15–40 | 8–10 | **Cose Affrontate Male / Meno Specifico** | **Nessuna formula** per neve e vento nei riassunti. Omessi coefficienti di forma, profilo del vento e fenomeni aeroelastici. |
| **L4** | Tecnologia del C.A., componenti, legame $\sigma-\epsilon$, resistenza cilindrica/cubica, cono di Abrams, ritiro, fluage/viscosità, controlli accettazione (Tipo A/B), barre B450C. | B1: 41–54 | 31–35 | **Parzialmente Conforme** | Buona descrizione tecnologica; nei riassunti mancano le formule matematiche di evoluzione del fluage e i dettagli di prova dei controlli di Tipo A e B. |
| **L5** | Trave inflessa in c.a., Stadi I-II-III, legami parabola-rettangolo e stress-block, campi di rottura/regioni di crisi 1–5, $\xi \le 0.45$, rottura duttile vs fragile, SLU flessione semplice. | B1: 55–68 | 36–45 | **Conforme con Omissioni** | Spiegazione ben presente. Manca tuttavia l'esplicitazione della duttilità di curvatura $\mu_\phi$ e la limitazione di armatura minima/massima di norma. |
| **L6** | Sezione c.a. a doppia armatura, Pressoflessione e Dominio $M-N$, Verifiche SLE (Tensioni di esercizio, Fessurazione con calcolo di $w_k$, Deformazioni e frecce). | B1: 69–84 | 46–50 | **Meno Specifico** | Nel c.a. mancano i limiti tensionali numerici di norma ($0.60 f_{ck}, 0.45 f_{ck}, 0.80 f_{yk}$) e **manca la formula dell'ampiezza delle fessure $w_k$**. |
| **L7** | Taglio nel C.A. (travi senza staffe: pettine, arco, ingranamento inerti, spinotto; travi con staffe: traliccio di Mörsch ad inclinazione variabile $\theta$); Torsione nel C.A. (traliccio spaziale di Rausch); intro Slim Floor. | B1: 85–108 | 51–56 | **Cose Affrontate Male / Cose Assenti** | **Inversione clamorosa delle formule del passo staffe zona critica/corrente** a p. 56. Manipolazione del taglio senza staffe. **Torsione C.A. e Slim Floor TOTALMENTE ASSENTI**. |
| **L8** | Travi Alveolari (Cellular Beams), fabbricazione, vantaggi impianti; Meccanismi di crisi locali (Vierendeel, web-post buckling, saldatura anima); Solai Slim Floor (IFB, SFB, CoSFB). | B1: 109–118 | *Nessuna* | **TOTALMENTE ASSENTE** | Argomento non pervenuto in nessuna pagina dei Riassunti TDC. |
| **L9** | Collegamenti trave-colonna in acciaio, comportamento reale, classificazione nodi per rigidezza (rigidi, semirigidi, cerniere) e per resistenza, legame $M-\phi$, metodo delle componenti. | B1: 119–131 | *Nessuna* | **TOTALMENTE ASSENTE** | Nessuna trattazione della classificazione dei nodi né del metodo delle componenti. |
| **L10** | Sistemi a carico verticale vs sistemi orizzontali, elementi dissipatori, travi rastremate a sezione variabile, basamenti colonna con tirafondi, resistenza al fuoco e robustezza strutturale. | B2: 1–16 | 70, 73–74 | **Meno Specifico / Cose Assenti** | Travi a sezione variabile e basamenti con tirafondi omessi. Trattazione del fuoco e della robustezza ridotta a nozioni vaghe. |
| **L11** | Materiale Acciaio, diagramma $\sigma-\epsilon$ reale e ingegneristico, prove di resilienza Charpy, transizione duttile-fragile (JR, J0, J2), verifiche trazione (sezione lorda vs netta con fori) e compressione pura. | B2: 17–38 | 14–22 | **Conforme** | Buona corrispondenza teorica sulla trazione, resilienza e legami costitutivi dell'acciaio. |
| **L12** | Instabilità membrature in acciaio: instabilità flessionale globale (Eulero, curve di instabilità NTC/EC3 con $\chi, \alpha$), instabilità locale piastre, tensioni residue, classificazione sezioni (Classi 1-4). | B2: 39–45 | 19–24 | **Conforme con Semplificazioni** | Trattazione presente; mancano le spiegazioni sull'influenza delle tensioni residue termiche da laminazione/saldatura. |
| **L13** | Verifica a taglio sezioni in acciaio, instabilità anima a taglio, combinazione flessione-taglio ($V > 0.5 V_{pl}$), combinazione flessione-sforzo normale (domini $M-N$), instabilità flesso-torsionale ($M_{cr}, \chi_{LT}$). | B2: 46–62 | 25–29 | **Meno Specifico** | La verifica flesso-torsionale è solo descrittiva: manca la formulazione analitica del momento critico $M_{cr}$ e dei parametri di vincolo torsionale. |
| **L14** | Progetto esecutivo a carico verticale di edificio in acciaio (sistema pendolare): maglia strutturale, travi secondarie, travi principali, colonne HEB, predimensionamento ($L/h$), aree di influenza dei carichi. | B2: 63–82 | 7–8, 80 | **TOTALMENTE ASSENTE** | La procedura esecutiva di predimensionamento e scarico carichi del Laboratorio è del tutto assente nei riassunti. |
| **L15** | Unioni e collegamenti in acciaio (Parte 1): unioni vs collegamenti, organi meccanici (bulloni normali vs alta resistenza 8.8 e 10.9, chiodature), unioni saldate (tecnologia, difetti, controlli NDT: VT, PT, MT, UT, RT). | B2: 83–89 | *Nessuna* | **TOTALMENTE ASSENTE** | Nessuna trattazione della tecnologia dei bulloni né dei controlli non distruttivi sulle saldature. |
| **L16** | Saldature ad arco (elettrodo rivestito, arco sommerso, MIG/MAG), cordoni d'angolo vs penetrazione completa, meccanismi di rottura unioni a taglio (taglio bullone, rifollamento, block tear out, attrito). | B2: 90–100 | *Nessuna* | **TOTALMENTE ASSENTE** | Meccanismi di collasso a taglio dei bulloni e tecnologia delle saldature completamente ignorati nei riassunti. |
| **L17** | Verifiche analitiche saldature (cordoni d'angolo, componenti $\sigma_\perp, \tau_\perp, \tau_\parallel$, criterio di Von Mises con $\beta_w$), verifiche analitiche bulloni ($F_{v,Rd}, F_{b,Rd}, F_{t,Rd}, B_{p,Rd}$), modello a T-stub (3 modi). | B2: 101–115 | *Nessuna* | **TOTALMENTE ASSENTE** | **Lacuna gravissima**: nei riassunti non esiste mezza riga di calcolo analitico di bullonature e saldature. |
| **L18** | Dettagli costruttivi esecutivi struttura pendolare: squadrette d'anima (verificate a taglio, rifollamento e block-tearing; funzione di ritegno torsionale), giunti colonna, piastre di base con tirafondi. | B2: 116–134 | *Nessuna* | **TOTALMENTE ASSENTE** | Tutti i dettagli applicativi del progetto d'acciaio del laboratorio sono assenti. |
| **L19** | Progettazione e dimensionamento delle scale metalliche: disconnessione sismica, scale sospese con tiranti vs colonne indipendenti, gradino a mensola (carico 2 kN), cosciali a UPN, tiranti a trazione. | B3: 1–20 | *Nessuna* | **TOTALMENTE ASSENTE** | **Argomento cardine del laboratorio del tutto omesso.** La parola "scala" compare nei riassunti solo come "scalando lo spettro". |
| **L20** | Dinamica delle strutture e rischio sismico: SDOF, oscillazioni libere/smorzate/forzate, risonanza, PGA, spettri elastici NTC 2018 ($a_g, F_0, T_C^*$, suoli A–E, topografia T1–T4, periodi $T_B, T_C, T_D$). | B3: 21–38 | 57–66 | **Conforme** | Ottima corrispondenza per la dinamica lineare di base e la definizione dello spettro normativo elastico. |
| **L21** | Progetto sismico d'esame e telai sismo-resistenti (MRF): relazione e tavole d'esame, fattore $q$, gerarchia resistenze globale ($\sum M_c \ge 1.3 \sum M_b$) e locale ($\gamma_{Rd}$), verifiche di drift allo SLD ($d_r \le 0.005 h$). | B3: 39–80 | 67–71 | **Meno Specifico** | Principi di gerarchia citati; omessa la verifica quantitativa di drift interpiano allo SLD e l'organizzazione degli elaborati grafici d'esame. |
| **L22** | Controventi concentrici (CBF): tipologie a X, a V (chevron), divieto controventi a K; forza sbilanciata verticale post-buckling; $1.3 \le \bar{\lambda} \le 2.0$; sovraresistenza $\Omega$; fazzoletto a $2t$. | B3: 81–100 | 71 | **Cose Affrontate Male / Meno Specifico** | Omette la forza sbilanciata nei controventi a V, il divieto dei controventi a K, l'omogeneità $\Omega_{max}/\Omega_{min} \le 1.25$ e il dettaglio a $2t$ del gusset plate. |
| **L23** | Controventi eccentrici (EBF): definizione di link, cinematica e rotazione $\gamma_p$, link corti (taglio, $\gamma_p \le 0.08$), intermedi e lunghi (flessione, $\gamma_p \le 0.02$); irrigidimenti d'anima; gerarchia resistenze. | B3: 101–126 | 72 | **GRAVE ERRORE CONCETTUALE** | **Formula del link dimensionalmente assurda ($M/M$)**; inversione tra link lunghi e intermedi; omessi gli irrigidimenti d'anima e le rotazioni plastiche. |
| **L24** | Impalcato nel piano e diaframmi sismici: funzionamento a diaframma, soletta collaborante, pioli connettori Nelson (formule di calcolo), correnti (chords) e collettori (struts/ties), regolarità strutturale. | B3: 127–134 | 81 | **TOTALMENTE ASSENTE** | Omesse le verifiche dei pioli connettori a taglio, le travi-collettore e il comportamento a diaframma rigido. A p. 81 si parla solo di muratura! |

---

## 3. Analisi Critica Dettagliata: Errori Concettuali e Formule Errate ("Cose Affrontate Male")

Questa sezione isola e analizza nel dettaglio gli errori materiali, dimensionali e le impostazioni errate presenti all'interno di `RIASSUNTI TDC.pdf`.

### 3.1. Gravissimo Errore Dimensionale e Concettuale sui Controventi Eccentrici (EBF) [Pagina 72]
A pagina 72 dei `RIASSUNTI TDC.pdf`, nel paragrafo dedicato ai controventi eccentrici, compare la seguente classificazione dei link sismici:

> **Testo presente nei Riassunti (Pagina 72):**
> - **Corti**: quando la plasticizzazione avviene per $T$ $\longrightarrow$ $e \le 0.8(1+\alpha) \cdot \frac{M_{l,Rd}}{M_{l,Rd}}$
> - **Lunghi**: quando la plasticizzazione avviene per $M$ $\longrightarrow$ $0.8(1+\alpha) \cdot \frac{M_{l,Rd}}{M_{l,Rd}} < e < 1.5(1+\alpha) \cdot \frac{M_{l,Rd}}{M_{l,Rd}}$
> - **Intermedi**: quando la plasticizzazione è un effetto combinato di $V$ e $M$ $\longrightarrow$ $e \ge 1.5(1+\alpha) \cdot \frac{M_{l,Rd}}{M_{l,Rd}}$

#### Perché è un errore gravissimo:
1. **Errore Dimensionale Assurdo**: la lunghezza del link $e$ (espressa in metri o millimetri) viene uguagliata a una grandezza in cui compare la frazione $\frac{M_{l,Rd}}{M_{l,Rd}}$. Dividere un momento flettente per un momento flettente restituisce un **numero adimensionale puro**! La formula corretta di norma (NTC 2018 §7.5.4.3 / Eurocodice 8 §6.8.2) prevede a denominatore la **resistenza a taglio plastico** $V_{l,Rd}$ (o $V_{pl,Rd}$):
   $$\text{Dimensione corretta: } [m] = \frac{[kN \cdot m]}{[kN]} = \frac{M_{pl,Rd}}{V_{pl,Rd}}$$
2. **Inversione tra Link Lunghi e Intermedi**: 
   - Nei riassunti l'intervallo compreso tra $0.8(1+\alpha)\dots$ e $1.5(1+\alpha)\dots$ viene erroneamente etichettato come **"Lunghi"**, mentre i valori oltre $1.5(1+\alpha)\dots$ vengono etichettati come **"Intermedi"**.
   - Nella teoria strutturale e negli appunti di Nina (Lezione 23), è esattamente il contrario:
     - **Link Corti (Shear links)**: $e \le 0.8(1+\alpha) \frac{M_{pl,Rd}}{V_{pl,Rd}}$ (oppure $e \le 1.6 \frac{M_{pl}}{V_{pl}}$ per $\alpha=1$). La dissipazione avviene per puro taglio nell'anima con altissima duttilità ($\gamma_p \le 0.08\text{ rad}$).
     - **Link Intermedi**: $0.8(1+\alpha) \frac{M_{pl,Rd}}{V_{pl,Rd}} < e < 1.5(1+\alpha) \frac{M_{pl,Rd}}{V_{pl,Rd}}$ (oppure $1.6 \frac{M_p}{V_p} < e < 3.0 \frac{M_p}{V_p}$). Comportamento misto flessione-taglio.
     - **Link Lunghi (Flexural links)**: $e \ge 1.5(1+\alpha) \frac{M_{pl,Rd}}{V_{pl,Rd}}$ (oppure $e \ge 3.0 \frac{M_p}{V_p}$). La plasticizzazione avviene per flessione pura alle estremità con duttilità rotazionale contenuta ($\gamma_p \le 0.02\text{ rad}$).

---

### 3.2. Clamorosa Inversione delle Didascalie del Passo delle Staffe in C.A. [Pagina 56]
A pagina 56 dei `RIASSUNTI TDC.pdf`, all'interno della sintesi sulle armature trasversali a taglio per le travi in cemento armato, compare il seguente box normativo:

> **Didascalie presenti nei Riassunti (Pagina 56):**
> - $s < \min(250\text{ mm} ; 12 \Phi_L) \longrightarrow$ **"Limiti normativi del passo delle staffe in zona critica"**
> - $s < \min(H_p/2 ; B_p/2 ; 175\text{ mm} ; 8 \Phi_L) \longrightarrow$ **"Limiti normativi del passo delle staffe in zona corrente"**

#### Perché è un errore concettuale evidente:
Chiunque abbia studiato Tecnica delle Costruzioni sa che la **zona critica** (estremità di travi e pilastri dove si concentrano le cerniere plastiche e le sollecitazioni di taglio sismico) richiede un **passo delle staffe molto più fitto** per garantire il confinamento del calcestruzzo e impedire l'instabilità delle barre longitudinali compresse.
- **In Zona Critica** il passo deve essere **ridotto**: $s \le \min(H_p/4; 175\text{ mm}; 8 \Phi_L)$ per CD"B" (o $6 \Phi_L$ e $100\text{ mm}$ per CD"A").
- **In Zona Corrente** il passo può essere **più rado**: $s \le \min(0.75 d; 250\text{ mm}; 12 \Phi_L)$.
Nei `RIASSUNTI TDC.pdf` le due etichette sono state **completamente scambiate tra loro**, inducendo lo studente a progettare staffe rade nelle zone critiche e staffe fitte nelle zone correnti, una condizione pericolosa e bocciata all'esame.

---

### 3.3. Formulazione Spuria e Forzata del Taglio Senza Armatura Trasversale [Pagina 55]
A pagina 55 dei `RIASSUNTI TDC.pdf`, per il calcolo della resistenza a taglio di elementi senza staffe, si trova:
$$\sigma_c = 1.6 \cdot f_{ct} = \frac{6.2 \cdot V_{Rd}}{b \cdot d} \implies V_{Rd} = b \cdot d \cdot f_{ct} \cdot 0.258$$

#### Perché è inadeguata e fuorviante:
Questa espressione è un'estrapolazione semplificata basata sulla teoria classica delle tensioni principali di trazione, ma **NON corrisponde alla formula di calcolo imposta dalle NTC 2018 (§4.1.2.3.5.1) e dagli Eurocodici (EC2 §6.2.2)**, che tiene conto dell'effetto scala ($k$), dell'armatura longitudinale tesa ($\rho_l$) e dell'eventuale sforzo normale ($\sigma_{cp}$):
$$V_{Rd,c} = \left[ C_{Rd,c} \cdot k \cdot \left(100 \cdot \rho_l \cdot f_{ck}\right)^{1/3} + k_1 \cdot \sigma_{cp} \right] b_w \cdot d \ge \left( v_{min} + k_1 \cdot \sigma_{cp} \right) b_w \cdot d$$
Presentare agli esami la formula dei riassunti ($V_{Rd} = 0.258 \cdot b \cdot d \cdot f_{ct}$) fa apparire la preparazione obsoleta e disallineata dalle normative vigenti spiegate da Landolfo.

---

### 3.4. Assunzione Arbitraria sull'Inclinazione del Traliccio di Mörsch [Pagina 56]
A pagina 56 dei `RIASSUNTI TDC.pdf`, si afferma che per calcolare l'inclinazione $\theta$ dei puntoni compressi:
> *"la normativa impone il raggiungimento della rottura bilanciata così che l'unica incognita sarà l'angolo $\theta$ [...] eguagliando $V_{Rd,s} = V_{Rd,c}$"*.

#### Perché è una forzatura concettuale:
La normativa NTC 2018 **NON impone affatto** di eguagliare $V_{Rd,s} = V_{Rd,c}$ per trovare $\theta$. La norma consente al progettista di **scegliere liberamente** l'angolo di inclinazione $\theta$ all'interno del range:
$$21.8^\circ \le \theta \le 45^\circ \iff 1.0 \le \cot \theta \le 2.5$$
L'imposizione della rottura bilanciata ($V_{Rd,s} = V_{Rd,c}$) è semplicemente una scelta progettuale finalizzata a minimizzare l'armatura a taglio (portando il traliccio a $\cot \theta = 2.5$ compatibilmente con la resistenza a compressione delle bielle $V_{Rd,c}$). Presentarla come un "obbligo di norma per determinare l'unica incognita" denota un'incomprensione del grado di libertà concesso dal metodo del traliccio ad inclinazione variabile.

---

## 4. Analisi Critica: Argomenti "Meno Specifici" e Trattazioni Superficiali

In molti capitoli, i `RIASSUNTI TDC.pdf` affrontano l'argomento solo in maniera descrittiva o qualitativa, tralasciando le formule operative, i coefficienti e i criteri applicativi illustrati nelle lezioni del Prof. Landolfo.

### 4.1. Azioni del Vento e della Neve (Nina L2, L3 vs Riassunti pp. 8–9)
- **Neve**:
  - *Nei Riassunti*: A pagina 9 si dice solo che occorre conoscere la zona e l'altitudine. Non compare **alcuna formula**.
  - *Negli Appunti di Nina (L2–L3)*: Viene fornita l'espressione analitica completa $q_s = \mu_i \cdot q_{sk} \cdot c_e \cdot c_t$, con i valori del carico al suolo $q_{sk}$ per le 3 zone italiane (Zona I Alpina e Mediterranea, Zona II, Zona III), le formule in funzione dell'altitudine ($a_s \le 200\text{ m}$ vs $a_s > 200\text{ m}$), i coefficienti di forma $\mu_1, \mu_2$ per falde singole, doppie, coperture a botte e accumuli a sacca in adiacenza ad edifici più alti.
- **Vento**:
  - *Nei Riassunti*: Citato a p. 9 tra i carichi variabili senza alcuna equazione né spiegazione.
  - *Negli Appunti di Nina (L3)*: Viene sviscerata la pressione del vento $p = q_b \cdot c_e(z) \cdot c_p \cdot c_d$, con la pressione cinetica di riferimento $q_b = \frac{1}{2}\rho v_b^2$, il profilo di rugosità $c_e(z)$ nelle 5 classi di rugosità del terreno, i coefficienti di pressione esterni $c_{pe}$ (pareti sopravento $+0.8$, sottovento $-0.4$) e interni $c_{pi}$, il coefficiente dinamico $c_d$, e l'approfondimento essenziale sui **fenomeni aeroelastici** (distacco dei vortici di Von Karman, frequenza di Strouhal, velocità critica di risonanza, galloping e flutter).

---

### 4.2. Verifiche agli Stati Limite di Esercizio nel C.A. (Nina L6 vs Riassunti pp. 46–48)
- *Nei Riassunti*: Lo SLE è limitato all'analisi elastica di Stadio II (sezione parzializzata fessurata) con calcolo dell'asse neutro tramite il coefficiente di omogeneizzazione $n=15$.
- *Cosa manca rispetto a Nina (L6)*:
  1. **Limiti Tensionali di Esercizio**: assenti le verifiche obbligatorie per combinazione caratteristica/rara ($\sigma_c \le 0.60 f_{ck}$, $\sigma_s \le 0.80 f_{yk}$) e quasi permanente ($\sigma_c \le 0.45 f_{ck}$, fondamentale per evitare il fluage non lineare).
  2. **Stato Limite di Fessurazione**: assente la formulazione per l'apertura caratteristica delle fessure:
     $$w_k = s_{r,max} \cdot (\epsilon_{sm} - \epsilon_{cm})$$
     e i relativi limiti di norma ($w_{max} = 0.2\text{ mm}, 0.3\text{ mm}, 0.4\text{ mm}$) associati alle classi di esposizione ambientale (ordinaria, aggressiva, molto aggressiva).

---

### 4.3. Instabilità Flesso-Torsionale nelle Travi in Acciaio (Nina L13 vs Riassunti p. 20, 27)
- *Nei Riassunti*: L'instabilità latero-torsionale (sbandamento fuori piano) viene trattata in poche righe a p. 20 e p. 27, indicando solo la formula ridotta con $\chi_{LT}$ e $\bar{\lambda}_{LT} \le 0.4$.
- *Cosa manca rispetto a Nina (L13)*:
  - La formulazione del **Momento Critico Elastico** $M_{cr}$:
    $$M_{cr} = C_1 \frac{\pi^2 E I_z}{(k L)^2} \left[ \sqrt{ \left(\frac{k}{k_w}\right)^2 \frac{I_w}{I_z} + \frac{(k L)^2 G I_t}{\pi^2 E I_z} + (C_2 z_g)^2 } - C_2 z_g \right]$$
  - I parametri fisici che governano il fenomeno: la luce libera tra i ritegni torsionali ($L$), la rigidezza flessionale fuori piano ($I_z$), la rigidezza torsionale pura ($I_t$) e di ingobbamento ($I_w$), e soprattutto la **posizione del carico rispetto al centro di taglio** ($z_g$: carichi applicati all'ala superiore risultano destabilizzanti!).

---

### 4.4. Progettazione Sismica di Telai (MRF) e Controventi (CBF) (Nina L21, L22 vs Riassunti pp. 71–72)
- *Nei Riassunti*: Le verifiche sismiche sono riassunte in formule generiche di sovraresistenza ($M_{Ed} = M_{Ed,G} + 1.1 \gamma_{Rd} \Omega M_{Ed,E}$).
- *Cosa manca rispetto a Nina (L21–L22)*:
  1. **Verifiche di Spostamento Interpiano (Drift) allo SLD**: non compare la formula $d_r = d_e \cdot q \le 0.005 h$ per tamponamenti fragili (o $0.0075 h$ per flessibili).
  2. **Controventi a V (Chevron) e Forza Sbilanciata**: nei controventi a V, quando la diagonale compressa instabilizza post-buckling ($N_{b,Rd}$), la diagonale tesa eroga $N_{pl,Rd}$, scaricando sulla trave una **forza verticale sbilanciata residua** $\Delta N_v = (N_{pl,Rd} - N_{b,Rd}) \sin \theta$. La trave DEVE essere verificata in campo elastico per questa forza. **Nei riassunti ciò è totalmente taciuto.**
  3. **Divieto dei Controventi a K**: assente la spiegazione del perché le NTC 2018 vietano i controventi a K (formazione di cerniera plastica a metà colonna).
  4. **Condizione di Omogeneità dei Controventi**: omessa la prescrizione $\frac{\Omega_{max}}{\Omega_{min}} \le 1.25$ per evitare concentrazioni di danno a singoli piani (piano debole).
  5. **Dettaglio del Fazzoletto d'Attacco (Gusset Plate)**: omessa la regola della zona libera di cerniera pari a $2t$ per consentire l'instabilità fuori piano della diagonale.

---

## 5. Analisi Critica: Argomenti TOTALMENTE OMESSI ("Cose Assenti")

In questa sezione sono raccolti gli argomenti d'esame presenti negli appunti di Nina che nei `RIASSUNTI TDC.pdf` **non compaiono affatto** (zero pagine, zero formule).

```
========================================================================================
                          ARGOMENTI CHIAVE TOTALMENTE ASSENTI
========================================================================================
1. Unioni e Collegamenti in Acciaio (Bullonature, Saldature, T-Stub)       [Lez. 15, 16, 17]
2. Progettazione e Dimensionamento delle Scale Metalliche                 [Lez. 18, 19]
3. Dettagli Costruttivi della Struttura Pendolare (Squadrette, Basi)      [Lez. 18]
4. Travi Alveolari (Cellular Beams) e Solai Slim Floor (IFB/SFB/CoSFB)    [Lez. 7, 8]
5. Impalcato nel Piano, Diaframmi Sismici e Pioli Connettori Nelson      [Lez. 24]
6. Torsione nel Calcestruzzo Armato (Traliccio Spaziale di Rausch)        [Lez. 7]
7. Classificazione dei Nodi Trave-Colonna (EC3) e Nodi Semirigidi         [Lez. 9]
8. Predimensionamento Globale Struttura Pendolare a Carico Verticale      [Lez. 14]
========================================================================================
```

---

### 5.1. Unioni Bullonate in Acciaio [Assenti – Nina Lezioni 15, 16, 17]
Nei `RIASSUNTI TDC.pdf` la parola "bullonati" compare solo 3 volte, in una riga generica di prescrizione sismica. Non c'è **nemmeno una formula di calcolo**. Negli appunti di Nina, le lezioni 15, 16 e 17 illustrano tutto l'apparato normativo NTC/Eurocodice 3:
1. **Classi di bulloni**: bulloni normali (4.6, 5.6) vs ad alta resistenza (8.8, 10.9), con tensioni di snervamento $f_{yb}$ e rottura $f_{ub}$.
2. **Resistenza a Taglio sul gambo**:
   $$F_{v,Rd} = \frac{\alpha_v \cdot f_{ub} \cdot A}{\gamma_{M2}} \quad (\alpha_v = 0.6 \text{ per 8.8 se filettatura nel piano di taglio, } 0.5 \text{ per 10.9})$$
3. **Resistenza a Rifollamento della lamiera**:
   $$F_{b,Rd} = \frac{k_1 \cdot \alpha_b \cdot f_u \cdot d \cdot t}{\gamma_{M2}}$$
   con il calcolo dettagliato dei coefficienti $k_1$ e $\alpha_b$ in base alle distanze di bordo ($e_1, e_2$) e agli interassi ($p_1, p_2$).
4. **Resistenza a Trazione e Punzonamento**:
   $$F_{t,Rd} = \frac{0.9 \cdot f_{ub} \cdot A_s}{\gamma_{M2}}, \quad B_{p,Rd} = \frac{0.6 \cdot \pi \cdot d_m \cdot t_p \cdot f_u}{\gamma_{M2}}$$
5. **Interazione Taglio-Trazione**:
   $$\frac{F_{v,Ed}}{F_{v,Rd}} + \frac{F_{t,Ed}}{1.4 F_{t,Rd}} \le 1.0$$
6. **Unioni ad Attrito con Bulloni Precaricati**: calcolo della forza di serraggio $F_{p,C} = 0.7 f_{ub} A_s$, coefficienti di attrito $\mu$ (Classi di superficie A, B, C, D) e resistenza allo scorrimento $F_{s,Rd}$.
7. **Rottura per Taglio-Trazione (Block Tearing / Block Shear)**: rottura a strappo del blocco di bulloni per combinazione di trazione netta e taglio lordo/netto.

---

### 5.2. Unioni Saldate in Acciaio [Assenti – Nina Lezioni 15, 16, 17]
Totalmente assenti nei riassunti. Negli appunti di Nina:
1. **Tipologie**: saldature a completa penetrazione (a tutto spessore) vs **cordoni d'angolo**.
2. **Definizione geometrica**: altezza di gola $a$, cordoni frontali, laterali e d'angolo.
3. **Verifica analitica del cordone d'angolo col Metodo Direzionale (Von Mises)**:
   Scomposizione delle tensioni sul piano di gola:
   - $\sigma_\perp$: tensione normale ortogonale al piano di gola;
   - $\tau_\perp$: tensione tangenziale ortogonale all'asse del cordone;
   - $\tau_\parallel$: tensione tangenziale parallela all'asse del cordone.
   Criterio di verifica NTC 2018 / EC3:
   $$\sqrt{\sigma_\perp^2 + 3(\tau_\perp^2 + \tau_\parallel^2)} \le \frac{f_u}{\beta_w \cdot \gamma_{M2}} \quad \text{e} \quad \sigma_\perp \le 0.9 \frac{f_u}{\gamma_{M2}}$$
   con i valori del fattore di correlazione $\beta_w$ (0.80 per S235, 0.85 per S275, 0.90 per S355).
4. **Controlli Non Distruttivi (CND / NDT)**: esame visivo (VT), liquidi penetranti (PT), polveri magnetiche (MT), ultrasuoni (UT), radiografia (RT).
5. **Modello a T-Stub**: meccanismo fondamentale per nodi trave-colonna flangiati con 3 modi di rottura (Modo 1: plasticizzazione flangia; Modo 2: plasticizzazione flangia con rottura bulloni; Modo 3: rottura a trazione dei soli bulloni con effetto leva / *prying forces*).

---

### 5.3. Progettazione Strutturale delle Scale Metalliche [Assente – Nina Lezione 19]
Argomento esclusivo del Laboratorio del Prof. Landolfo, **completamente assente nei riassunti**:
1. **Concezione Sismica e Disconnessione Strutturale**: la scala costituisce un elemento iper-rigido che, se connesso monoliticamente all'edificio, attira enormi forze sismiche inducendo effetti torsionali incontrollati. Deve essere **disconnessa sismicamente** attraverso due schemi alternativi:
   - *Schema 1 (Scale Sospese)*: rampanti e pianerottoli sospesi tramite pendini/tiranti in acciaio vincolati agli impalcati superiori (trasmettono carichi a $L/4$ e $3/4 L$ delle travi di piano).
   - *Schema 2 (Scale su Colonne Indipendenti)*: corpo scala impostato su un traliccio verticale autonomo separato dall'edificio con giunto sismico.
2. **Dimensionamento del Singolo Gradino**:
   - Geometria a piastra piegata (a Z o scatolare).
   - Schema statico: mensola incastrata sul cosciale o profilo centrale portante.
   - Carichi di verifica: carico distribuito da folla ($4\text{ kN/m}^2$) e **carico concentrato isolato da normativa pari a $2\text{ kN}$** applicato nella posizione più sfavorevole (bordo libero).
   - Verifiche a flessione, torsione e deformabilità (freccia $\le L/300$ per prevenire sensazioni di vibrazione e insicurezza negli utenti).
3. **Cosciali di Rampa e Pianerottoli**: profili laminati a UPN o tubolari soggetti a pressoflessione.
4. **Tiranti e Pendini**: dimensionamento a pura trazione con manicotti tenditori per la regolazione del tiro.

---

### 5.4. Travi Alveolari (Cellular Beams) e Solai Slim Floor [Assenti – Nina Lezioni 7, 8]
Trattati estensivamente nelle lezioni 7 e 8 di Nina:
1. **Travi Alveolari**:
   - Processo produttivo: taglio longitudinale ad ossitaglio (a dente di sega o sinusoidale) dell'anima di un profilo IPE/HE, sfalsamento delle due metà e risaldatura per ottenere un profilo di altezza maggiorata con aperture circolari o esagonali regolari.
   - Vantaggi: risparmio di peso, aumento del momento d'inerzia, integrazione totale degli impianti tecnologici nello spessore della trave.
   - Meccanismi di rottura locali specifici da verificare:
     - Meccanismo Vierendeel (flessione locale dei correnti superiore e inferiore attorno all'apertura);
     - Instabilità per taglio e compressione del montante d'anima (*web-post buckling*);
     - Rottura della saldatura orizzontale per scorrimento tangenziale.
2. **Solai Slim Floor (IFB / SFB / CoSFB)**:
   - Travi integrate nello spessore del solaio (*Integrated Floor Beam* o *Slim Floor Beam* con piatto saldato all'ala inferiore) che fungono da appoggio diretto per solai alveolari o lamiere grecate.
   - Azzeramento dell'ingombro sottotrave, riduzione dell'altezza interpiano, ottimizzazione antincendio.

---

### 5.5. Impalcato nel Piano, Diaframmi Sismici e Pioli Connettori [Assenti – Nina Lezione 24]
A pagina 81 dei riassunti si parla di solaio rigido solo in 4 righe per gli edifici in muratura! Negli appunti di Nina (L24), il capitolo è fondamentale per l'acciaio:
1. **Funzione del Diaframma Rigido**: distribuzione delle forze sismiche orizzontali ai sistemi verticali sismo-resistenti proporzionalmente alle loro rigidezze (3 gradi di libertà per piano: $u_x, u_y, \theta_z$).
2. **Pioli Connettori Nelson (Studs)**:
   - Connettori a piolo con testa saldati alle travi attraverso la lamiera grecata.
   - Formula di resistenza a taglio del connettore secondo Eurocodice 4 / NTC:
     $$P_{Rd} = \min \left( \frac{0.8 \cdot f_u \cdot \frac{\pi d^2}{4}}{\gamma_V} \; ; \; \frac{0.29 \cdot \alpha \cdot d^2 \cdot \sqrt{f_{ck} E_{cm}}}{\gamma_V} \right)$$
   - Disposizione dei pioli per garantire la collaborazione mista trave-soletta e la trasmissione del taglio d'impalcato.
3. **Correnti (Chords) e Travi-Collettore (Struts/Ties)**:
   - *Chords*: elementi perimetrali tesi e compressi per assorbire il momento flessionale nel piano del solaio.
   - *Collettori*: elementi strutturali incaricati di raccogliere le forze d'inerzia distribuite sul diaframma e convogliarle direttamente ai controventi verticali.

---

### 5.6. Torsione nel Calcestruzzo Armato [Assente – Nina Lezione 7]
Totalmente assente nei riassunti. Negli appunti di Nina:
1. **Modello del Traliccio Spaziale a Pareti Sottili di Rausch**:
   - Sezione cava equivalente con spessore efficace $t_{ef} = 2c$ (doppio del copriferro) e area $A_k$ racchiusa dalla linea media della parete sottile.
   - Tensione tangenziale torsionale: $\tau_{t} = \frac{T_{Ed}}{2 A_k t_{ef}}$.
2. **Armatura a Torsione**:
   - Staffe chiuse perimetrali: $\frac{A_{st}}{s} = \frac{T_{Ed}}{2 A_k f_{yd} \cot \theta}$.
   - Barre longitudinali correnti distribuite sul perimetro: $\sum A_{sl} = \frac{T_{Ed} \cdot u_k \cdot \cot \theta}{2 A_k f_{yd}}$.
3. **Verifica Bielle Compresse e Interazione**:
   $$T_{Rd,max} = 2 \nu \alpha_c f_{cd} A_k t_{ef} \sin \theta \cos \theta, \quad \left(\frac{T_{Ed}}{T_{Rd,max}}\right)^2 + \left(\frac{V_{Ed}}{V_{Rd,max}}\right)^2 \le 1.0$$

---

### 5.7. Dettagli Costruttivi della Struttura Pendolare in Acciaio [Assenti – Nina Lezione 18]
Tutti i dettagli applicativi del progetto sono ignorati nei riassunti:
1. **Collegamento Trave Secondaria - Trave Principale a Squadretta**:
   - Squadretta bullonata sull'anima.
   - Necessità dell'**intaglio dell'ala superiore** (*scarpa/notching*) della secondaria per consentire il filo piano superiore.
   - Ruolo della squadretta come **ritegno torsionale** dell'ala compressa della trave principale.
2. **Piastra di Base della Colonna e Tirafondi**:
   - Piastra di base rettangolare, tirafondi sagomati ad ancora o con piastrina d'estremità, malta antiritiro di allettamento (*grout*), verifica della pressione di contatto calcestruzzo-acciaio.

---

## 6. Contenuti Presenti nei Riassunti ma ESTRANEI agli Appunti di Nina

Nel documento `RIASSUNTI TDC.pdf` sono presenti alcuni capitoli che **non trovano riscontro** nelle 23 lezioni di lezione tenute e verbalizzate negli appunti di Nina:
1. **Costruzioni Esistenti (Capitolo 8 NTC 2018) [Pagine 72–76 dei Riassunti]**:
   - Valutazione della sicurezza, Livelli di Conoscenza (LC1, LC2, LC3) e Fattori di Confidenza (FC = 1.35, 1.20, 1.00);
   - Distinzione tra interventi di riparazione locale, miglioramento e adeguamento;
   - Vulnerabilità tipiche degli edifici esistenti in c.a.
   *(Nota: Questo argomento è teorico-normativo generale ma non è stato svolto nelle lezioni di laboratorio di Nina dedicate al dimensionamento dell'edificio nuovo in acciaio).*
2. **Classificazione Generale delle Strutture e Muratura [Pagine 77–81 dei Riassunti]**:
   - Classificazione tipologica di sistemi di travi, archi, coperture e solai in muratura. Argomenti molto generici di livello elementare/istituzionale.

---

## 7. Verdetto Finale e Guida Operativa allo Studio

| Macro-Area del Corso | Affidabilità Riassunti TDC | Copertura Rispetto a Nina | Cosa Fare per la Preparazione |
| :--- | :---: | :---: | :--- |
| **Azioni e Sicurezza (Neve, Vento, NTC)** | 🟡 Parziale (50%) | Superficiale | Integrare da Nina L2-L3 tutte le formule di neve, vento e combinazioni di carico. |
| **Materiale Acciaio e Sezioni (Trazione, Compressione, Flessione)** | 🟢 Buona (85%) | Conforme | Si può studiare dai riassunti (pp. 14-30), integrando l'instabilità flesso-torsionale ($M_{cr}$). |
| **Unioni Bullonate e Saldate** | 🔴 ZERO (0%) | **TOTALMENTE ASSENTE** | **TASSATIVO studiare da Nina (L15, L16, L17)**: formule di taglio, rifollamento, trazione, attrito e Von Mises. |
| **Dettagli Pendolari, Basi e Scale Metalliche** | 🔴 ZERO (0%) | **TOTALMENTE ASSENTE** | **TASSATIVO studiare da Nina (L18, L19)**: verifica gradino a 2 kN, scale sospese, squadrette e tirafondi. |
| **Travi Alveolari e Slim Floor** | 🔴 ZERO (0%) | **TOTALMENTE ASSENTE** | **TASSATIVO studiare da Nina (L8)**: Vierendeel, web-post buckling, CoSFB. |
| **Calcestruzzo Armato (Flessione, Pressoflessione, Taglio)** | 🟡 Discreta con Errori (70%) | Conforme ma errori | **ATTENZIONE**: correggere l'errore del passo staffe a p. 56! Integrare SLE (tensioni e $w_k$) da Nina L6 e torsione da Nina L7. |
| **Dinamica e Spettro Sismico NTC** | 🟢 Ottima (90%) | Conforme | Molto ben fatto nei riassunti (pp. 57-66). Si può studiare con fiducia. |
| **Progetto Sismico (Telai MRF, Controventi CBF ed EBF)** | 🔴 Pericoloso (40%) | Errori gravi e lacune | **NON usare p. 72 dei riassunti (formula errata EBF)**! Studiare la forza sbilanciata CBF e i link EBF da Nina L21, L22, L23. |
| **Diaframmi nel Piano e Pioli Nelson** | 🔴 ZERO (0%) | **TOTALMENTE ASSENTE** | **TASSATIVO studiare da Nina (L24)**: pioli Nelson, correnti e travi-collettore. |

### Conclusione
I `RIASSUNTI TDC.pdf` possono essere impiegati come **ripasso rapido** per la dinamica lineare di base, per le verifiche classiche delle sezioni d'acciaio isolate e per la flessione del c.a., ma **presentano errori gravi da cui guardarsi** (EBF e passo staffe) e **tracollano completamente sull'intera progettazione esecutiva in acciaio** (unioni, scale, impalcati, solai avanzati e dettagli costruttivi), che costituisce il 60% della valutazione d'esame del Prof. Landolfo.
