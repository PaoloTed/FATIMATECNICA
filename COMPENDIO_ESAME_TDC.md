# COMPENDIO DEFINITIVO D'ESAME: LABORATORIO DI TECNICA DELLE COSTRUZIONI
### Corso del Prof. Ing. Raffaele Landolfo — NTC 2018 & Eurocodici (EC2, EC3, EC4, EC8)
*Documento integrato basato sugli appunti integrali delle lezioni frontali (Appunti Nina, 399 pag.), sui riassunti corretti e sul confronto critico analitico.*

---

## INDICE GENERALE DEI MODULI

1. [MODULO 1: Azioni sulle Costruzioni e Combinazioni di Carico (NTC 2018)](#modulo-1-azioni-sulle-costruzioni-e-combinazioni-di-carico-ntc-2018)
2. [MODULO 2: Calcestruzzo Armato – Meccanica della Sezione, Taglio, Torsione e SLE](#modulo-2-calcestruzzo-armato--meccanica-della-sezione-taglio-torsione-e-sle)
3. [MODULO 3: Acciaio – Membrature, Verifiche di Resistenza e Instabilità](#modulo-3-acciaio--membrature-verifiche-di-resistenza-e-instabilità)
4. [MODULO 4: Unioni e Collegamenti in Acciaio (Bullonature, Saldature, T-Stub e Nodi)](#modulo-4-unioni-e-collegamenti-in-acciaio-bullonature-saldature-t-stub-e-nodi)
5. [MODULO 5: Sistemi Innovativi per Impalcati (Travi Alveolari e Solai Slim Floor)](#modulo-5-sistemi-innovativi-per-impalcati-travi-alveolari-e-solai-slim-floor)
6. [MODULO 6: Progettazione e Calcolo delle Scale Metalliche](#modulo-6-progettazione-e-calcolo-delle-scale-metalliche)
7. [MODULO 7: Dinamica delle Strutture e Definizione dell'Azione Sismica (NTC 2018)](#modulo-7-dinamica-delle-strutture-e-definizione-dellazione-sismica-ntc-2018)
8. [MODULO 8: Progettazione Sismica e Gerarchia delle Resistenze (MRF, CBF, EBF)](#modulo-8-progettazione-sismica-e-gerarchia-delle-resistenze-mrf-cbf-ebf)
9. [MODULO 9: Impalcato nel Piano, Diaframmi Sismici e Pioli Connettori Nelson](#modulo-9-impalcato-nel-piano-diaframmi-sismici-e-pioli-connettori-nelson)
10. [MODULO 10: Vademecum Rapido d'Esame, Formulario Salvavita e 10 Domande Trabocchetto](#modulo-10-vademecum-rapido-desame-formulario-salvavita-e-10-domande-trabocchetto)

---

## MODULO 1: Azioni sulle Costruzioni e Combinazioni di Carico (NTC 2018)

### 1.1. Classificazione delle Azioni e Filosofia Semiprobabilistica
Le NTC 2018 classificano le azioni in base alla loro variazione nel tempo:
- **Permanenti Strutturali ($G_1$)**: peso proprio degli elementi portanti (travi, pilastri, solai collaboranti).
- **Permanenti Non Strutturali ($G_2$)**: tamponature, tramezzi, massetti, pavimenti, intonaci, impianti fissi.
  - *Incidenza tramezzi interni*: per tramezzi con peso proprio $\le 1.0\text{ kN/m}^2$, si assume un carico equivalente distribuito $g_2 = 0.80\text{ kN/m}^2$; per pesi tra $1.0$ e $2.0\text{ kN/m}^2$, $g_2 = 1.20\text{ kN/m}^2$; se $> 2.0\text{ kN/m}^2$ si calcola il carico lineare effettivo lungo la trave.
- **Variabili ($Q_k$)**: carichi d'uso antropici, neve, vento, variazioni termiche.
- **Eccezionali ($A$)**: incendi, esplosioni, urti.
- **Sismiche ($E$)**: azioni d'inerzia derivanti dal moto del terreno.

### 1.2. Combinazioni di Carico secondo NTC 2018 (§2.5.3)

#### 1. Combinazione Fondamentale SLU (Stati Limite Ultimi):
$$\sum_{j\ge 1} \gamma_{G1,j} G_{1,j} + \sum_{j\ge 1} \gamma_{G2,j} G_{2,j} + \gamma_{Q,1} Q_{k,1} + \sum_{i>1} \gamma_{Q,i} \psi_{0,i} Q_{k,i}$$
- $\gamma_{G1} = 1.30$ (favorevole: $1.00$); $\gamma_{G2} = 1.50$ (favorevole: $0.80$, o $1.30/0.00$ se ben definito); $\gamma_{Q} = 1.50$ (favorevole: $0.00$).

#### 2. Combinazioni SLE (Stati Limite di Esercizio):
- **Caratteristica (Rara)**: per stati limite irreversibili (es. snervamento iniziale, prima fessurazione):
  $$\sum G_{1} + \sum G_{2} + Q_{k,1} + \sum_{i>1} \psi_{0,i} Q_{k,i}$$
- **Frequente**: per stati limite reversibili (es. apertura temporanea fessure, deformazioni dinamiche):
  $$\sum G_{1} + \sum G_{2} + \psi_{1,1} Q_{k,1} + \sum_{i>1} \psi_{2,i} Q_{k,i}$$
- **Quasi Permanente**: per effetti a lungo termine (fluage/viscosità, frecce differite):
  $$\sum G_{1} + \sum G_{2} + \sum_{i\ge 1} \psi_{2,i} Q_{k,i}$$

#### Tabella Coefficienti di Combinazione $\psi$ (NTC Tabella 2.5.I):
| Categoria d'uso | $\psi_{0}$ (Rara) | $\psi_{1}$ (Frequente) | $\psi_{2}$ (Quasi Perm.) | $q_k\text{ [kN/m}^2\text{]}$ |
| :--- | :---: | :---: | :---: | :---: |
| **Cat. A (Residenziale)** | 0.70 | 0.50 | 0.30 | 2.00 |
| **Cat. B (Uffici)** | 0.70 | 0.50 | 0.30 | 2.00–3.00 |
| **Cat. C (Luoghi aperti al pubblico)** | 0.70 | 0.70 | 0.60 | 3.00–4.00 |
| **Cat. D (Negozi, centri commerciali)** | 0.70 | 0.70 | 0.60 | 4.00–5.00 |
| **Cat. E (Archivi, magazzini, biblioteche)** | 1.00 | 0.90 | 0.80 | $\ge 6.00$ |
| **Neve (quota $\le 1000\text{ m s.l.m.}$)** | 0.50 | 0.20 | 0.00 | secondo zona |
| **Vento** | 0.60 | 0.20 | 0.00 | secondo zona |

---

### 1.3. Azione della Neve (NTC 2018 §3.4)
Il carico della neve sulla copertura si calcola come:
$$q_s = \mu_i \cdot q_{sk} \cdot c_e \cdot c_t \quad [\text{kN/m}^2]$$
- **Valore caratteristico al suolo $q_{sk}$** in funzione della zona geografica e della quota sul livello del mare $a_s\text{ [m]}$:
  - *Zona I - Alpina* (Aosta, Belluno, Bolzano, Sondrio, Trento, ecc.):
    - Se $a_s \le 200\text{ m}$: $q_{sk} = 1.50\text{ kN/m}^2$
    - Se $a_s > 200\text{ m}$: $q_{sk} = 1.39 \left[1 + \left(\frac{a_s}{728}\right)^2\right]\text{ kN/m}^2$
  - *Zona I - Mediterranea* (altre province Nord Italia):
    - Se $a_s \le 200\text{ m}$: $q_{sk} = 1.50\text{ kN/m}^2$
    - Se $a_s > 200\text{ m}$: $q_{sk} = 1.35 \left[1 + \left(\frac{a_s}{602}\right)^2\right]\text{ kN/m}^2$
  - *Zona II* (Centro Italia, Emilia, Liguria, Campania, Basilicata, Puglia, ecc.):
    - Se $a_s \le 200\text{ m}$: $q_{sk} = 1.00\text{ kN/m}^2$
    - Se $a_s > 200\text{ m}$: $q_{sk} = 0.85 \left[1 + \left(\frac{a_s}{481}\right)^2\right]\text{ kN/m}^2$
  - *Zona III* (Calabria, Sicilia, Sardegna):
    - Se $a_s \le 200\text{ m}$: $q_{sk} = 0.60\text{ kN/m}^2$
    - Se $a_s > 200\text{ m}$: $q_{sk} = 0.51 \left[1 + \left(\frac{a_s}{481}\right)^2\right]\text{ kN/m}^2$
- **Coefficiente di forma $\mu_i$**:
  - *Falda singola o due falde (condizione simmetrica non ventata)*:
    $$\mu_1 = 0.80 \quad \text{per } 0^\circ \le \alpha \le 30^\circ; \quad \mu_1 = 0.80 \cdot \frac{60^\circ - \alpha}{30^\circ} \quad \text{per } 30^\circ < \alpha < 60^\circ; \quad \mu_1 = 0 \quad \text{per } \alpha \ge 60^\circ$$
  - *Copertura a due falde con accumulo asimmetrico da vento*: su una falda $\mu_1 = 0.80$, sull'altra $\mu_2 = 0.5 \mu_1 = 0.40$ (o $1.2$ in accumulo).
  - *Coperture a sacca (adiacenti a edifici più alti)*: si genera accumulo triangolare con $\mu_s = \mu_w + \mu_s'$, con valori fino a $2.0\text{–}4.0$.
- **Coefficiente di esposizione $c_e$**: $1.0$ (normale); $0.9$ (ventosa); $1.1$ (riparata).
- **Coefficiente termico $c_t$**: $1.0$ (salvo coperture ad alta trasmittanza termica).

> [!NOTE]
> **Esempio Numerico Breve (Carico Neve):**
> Edificio a doppia falda con pendenza $\alpha = 25^\circ$, sito a Benevento (Zona II), quota $a_s = 400\text{ m s.l.m.}$, esposizione normale ($c_e = 1.0$), termico ($c_t = 1.0$).
> 1. Quota $> 200\text{ m}$: $q_{sk} = 0.85 \cdot [1 + (400/481)^2] = 0.85 \cdot [1 + 0.6916] = 1.438\text{ kN/m}^2$.
> 2. Pendenza $\alpha = 25^\circ \le 30^\circ \implies \mu_1 = 0.80$.
> 3. Carico neve di progetto sulla copertura:
>    $$q_s = 0.80 \cdot 1.438 \cdot 1.0 \cdot 1.0 = 1.15\text{ kN/m}^2$$

---

### 1.4. Azione del Vento (NTC 2018 §3.3)
La pressione statica equivalente del vento che agisce normalmente sulle superfici dell'edificio è data da:
$$p = q_b \cdot c_e(z) \cdot c_p \cdot c_d \quad [\text{kN/m}^2]$$
- **Pressione cinetica di riferimento $q_b$**:
  $$q_b = \frac{1}{2} \rho v_b^2 \quad [\text{N/m}^2]$$
  dove $\rho = 1.25\text{ kg/m}^3$ (densità aria) e $v_b$ è la velocità base del vento al livello del mare per tempo di ritorno $T_R = 50\text{ anni}$ (in Italia tra $25\text{ e }30\text{ m/s}$ a seconda della zona). Per $v_b = 27\text{ m/s} \implies q_b = 0.5 \cdot 1.25 \cdot 27^2 = 455.6\text{ N/m}^2 = 0.456\text{ kN/m}^2$.
- **Coefficiente di esposizione $c_e(z)$**: tiene conto della quota dal suolo $z$ e della rugosità del terreno (Classi A, B, C, D):
  $$c_e(z) = k_r^2 \cdot c_t \cdot \ln\left(\frac{z}{z_0}\right) \left[ 7 + c_t \cdot \ln\left(\frac{z}{z_0}\right) \right] \quad \text{per } z \ge z_{min}$$
- **Coefficiente di pressione $c_p$**:
  - Parete sopravento (impatto frontale): pressione positiva $c_{pe} = +0.80$.
  - Parete sottovento (depressione/suzione): depressione $c_{pe} = -0.40 \text{ a } -0.50$.
  - Pareti laterali: depressione $c_{pe} = -0.80 \text{ a } -0.40$.
  - Pressione interna $c_{pi}$: varia tra $+0.20$ e $-0.30$ in base alla percentuale di aperture.
- **Coefficiente dinamico $c_d$**: tiene conto della non contemporaneità delle raffiche e della risposta risonante della struttura. Per edifici tozzi e rigidi ($H < 25\text{ m}$ e periodo $T < 1\text{ s}$), si assume cautelativamente $c_d = 1.00$.
- **Fenomeni di Instabilità Aeroelastica (Lezione 3 Nina)**:
  - *Distacco dei vortici di Von Kármán (Vortex Shedding)*: per strutture cilindriche o snelle (ciminiere, pile da ponte), i vortici alternati creano forze trasversali con frequenza $f_s = \frac{St \cdot v}{b}$ ($St \approx 0.2$ numero di Strouhal). Se la frequenza dei vortici coincide con la frequenza propria flessionale $f_n$, si ha risonanza a velocità critica $v_{cr} = \frac{f_n \cdot b}{St}$.
  - *Galoppo (Galloping)*: instabilità divergente trasversale tipica di sezioni non circolari (es. cavi ghiacciati, profili a D o rettangolari).
  - *Flutter*: accoppiamento instabile flesso-torsionale tipico di impalcati sospesi e ali.

---

## MODULO 2: Calcestruzzo Armato – Meccanica della Sezione, Taglio, Torsione e SLE

### 2.1. Materiali e Legami Costitutivi
- **Calcestruzzo**:
  - Classi di resistenza: indicate con $C_{fck,cyl} / R_{ck,cube}$ (es. C25/30 ha $f_{ck} = 25\text{ MPa}$, $R_{ck} = 30\text{ MPa}$; relazione: $f_{ck} = 0.83 R_{ck}$).
  - Resistenza a compressione di calcolo:
    $$f_{cd} = \alpha_{cc} \frac{f_{ck}}{\gamma_c} = 0.85 \cdot \frac{f_{ck}}{1.5} = 0.567 f_{ck} \quad [\text{MPa}]$$
    dove $\alpha_{cc} = 0.85$ tiene conto dei carichi di lunga durata.
  - Resistenza a trazione media: $f_{ctm} = 0.30 \cdot f_{ck}^{2/3}$; resistenza caratteristica a trazione: $f_{ctk,0.05} = 0.7 f_{ctm}$.
  - Modulo elastico secante: $E_{cm} = 22000 \cdot (f_{cm}/10)^{0.3}\text{ [MPa]}$.
  - Lavorabilità e Slump (Cono di Abrams): classi da S1 (terra umida, $10\text{–}40\text{ mm}$) a S5 (fluido, $\ge 220\text{ mm}$).
  - Legame $\sigma-\epsilon$: modello Parabola-Rettangolo con deformazione allo snervamento plastico $\epsilon_{c2} = 2.0\text{‰}$ e rottura $\epsilon_{cu} = 3.5\text{‰}$. Modello semplificato Stress-Block: profondità efficace $0.8 x$ e tensione costante $\eta f_{cd} = 1.0 f_{cd}$.
- **Acciaio B450C (ad alta duttilità)**:
  - Tensione caratteristica di snervamento $f_{yk} = 450\text{ MPa}$; tensione di rottura $f_{tk} \ge 540\text{ MPa}$.
  - Resistenza di calcolo:
    $$f_{yd} = \frac{f_{yk}}{\gamma_s} = \frac{450}{1.15} = 391.3\text{ MPa}$$
  - Deformazione limite elastica: $\epsilon_{yd} = \frac{f_{yd}}{E_s} = \frac{391.3}{210000} = 1.86\text{‰} \approx 1.96\text{‰}$.
  - Requisiti sismici di duttilità: $(f_t/f_y)_k \ge 1.15$ e allungamento a rottura $(\epsilon_{uk})_k \ge 7.5\%$.

---

### 2.2. Flessione Semplice e Pressoflessione SLU

#### 1. Ipotesi di Calcolo (De Saint Venant - Bernoulli):
1. Conservazione delle sezioni piane (deformazioni linearmente variabili lungo l'altezza).
2. Perfetta aderenza tra calcestruzzo e armatura.
3. Resistenza a trazione del calcestruzzo trascurata allo SLU.

#### 2. Campi di Rottura (Regioni di Crisi 1–5):
- **Campo 1**: Trazione pura o con piccola eccentricità. Asse neutro esterno alla sezione. Rottura lato acciaio con allungamento $\epsilon_s = 10\text{‰}$ (o $\epsilon_{ud} = 67.5\text{‰}$).
- **Campo 2**: Flessione con modesta armatura. Trazione dominante. $\epsilon_s = 10\text{‰}$, calcestruzzo compresso tra $0$ e $3.5\text{‰}$.
- **Campo 3 (CAMPO OTTIMALE DI PROGETTO)**: Rottura duttile per contemporaneo o successivo schiacciamento del calcestruzzo $\epsilon_c = 3.5\text{‰}$ e snervamento dell'acciaio $\epsilon_s \ge \epsilon_{yd}$. Posizione asse neutro:
  $$0 < \xi = \frac{x}{d} \le \xi_{lim} = \frac{3.5}{3.5 + \epsilon_{yd}} \approx 0.64$$
  *Prescrizione NTC per garantire duttilità*: $\xi = \frac{x}{d} \le 0.45$ (per CD"B") e $\xi \le 0.25$ (per CD"A").
- **Campo 4 (SEZIONE FORTE / SOVRA-ARMATA)**: Rottura fragile. Calcestruzzo schiacciato $\epsilon_c = 3.5\text{‰}$, ma acciaio ancora in campo elastico $\epsilon_s < \epsilon_{yd}$ ($\sigma_s = E_s \epsilon_s < f_{yd}$). Da evitare assolutamente in zona sismica.
- **Campo 5**: Compressione semplice o con piccolissima eccentricità. Tutta la sezione compressa. Accorciamento al baricentro $\epsilon_c = 2.0\text{‰}$, alla fibra estrema fino a $3.5\text{‰}$.

#### 3. Formule di Verifica allo SLU (Sezione Rettangolare $b \times h$, armatura semplice $A_s$, altezza utile $d$):
- Profondità asse neutro $x$ dall'equilibrio alla traslazione ($N_{Ed} = 0$):
  $$0.8 x \cdot b \cdot f_{cd} = A_s f_{yd} \implies x = \frac{A_s f_{yd}}{0.8 b f_{cd}}$$
- Momento resistente ultimo $M_{Rd}$:
  $$M_{Rd} = A_s f_{yd} \left( d - 0.4 x \right)$$

---

### 2.3. Verifiche agli Stati Limite di Esercizio (SLE) nel C.A.
1. **Verifiche Tensionali (Stadio II fessurato con $n = E_s/E_c = 15$)**:
   - Asse neutro elastico $x$:
     $$\frac{1}{2} b x^2 + n A_s' (x - d') - n A_s (d - x) = 0$$
   - Momento d'inerzia omogeneizzato:
     $$I_{II} = \frac{1}{3} b x^3 + n A_s (d - x)^2 + n A_s' (x - d')^2$$
   - Tensioni di esercizio:
     $$\sigma_c = \frac{M_{SLE}}{I_{II}} x \le 0.60 f_{ck} \text{ (Comb. Rara)} \quad \text{e} \quad \sigma_c \le 0.45 f_{ck} \text{ (Comb. Quasi Perm.)}$$
     $$\sigma_s = n \frac{M_{SLE}}{I_{II}} (d - x) \le 0.80 f_{yk} \text{ (Comb. Rara)}$$
2. **Stato Limite di Fessurazione**:
   - Apertura caratteristica delle fessure:
     $$w_k = s_{r,max} \cdot (\epsilon_{sm} - \epsilon_{cm})$$
   - Valori limite di norma:
     - Condizioni ordinarie (interni asciutti): $w_k \le w_{max} = 0.40\text{ mm}$ (Comb. Quasi Perm.)
     - Condizioni aggressive (ambienti umidi, esterni): $w_k \le 0.30\text{ mm}$ (Comb. Frequente)
     - Condizioni molto aggressive (sali disgelanti, mare): $w_k \le 0.20\text{ mm}$ (Comb. Frequente)

---

### 2.4. Verifica a Taglio SLU nel C.A. (NTC 2018 §4.1.2.3.5)

#### 1. Modello a Traliccio di Ritter-Mörsch ad Inclinazione Variabile $\theta$:
Il calcestruzzo fessurato opera come un traliccio isostatico composto da:
- Corrente superiore compresso in calcestruzzo;
- Corrente inferiore teso in acciaio ($A_s$ longitudinale);
- Bielle compresse inclinate di calcestruzzo ad angolo $\theta$ ($21.8^\circ \le \theta \le 45^\circ \implies 1.0 \le \cot\theta \le 2.5$);
- Tiranti tesi verticali o inclinati (armature a taglio: staffe ad inclinazione $\alpha = 90^\circ$).

#### 2. Formule di Calcolo con Staffe Verticali ($\alpha = 90^\circ$):
- **Resistenza a trazione delle staffe (Rottura lato acciaio)**:
  $$V_{Rd,s} = 0.9 \cdot d \cdot \frac{A_{sw}}{s} \cdot f_{yd} \cdot \cot\theta$$
- **Resistenza a compressione delle bielle di calcestruzzo (Rottura lato calcestruzzo per schiacciamento)**:
  $$V_{Rd,c} = 0.9 \cdot d \cdot b_w \cdot \alpha_c \cdot \nu \cdot f_{cd} \cdot \frac{\cot\theta}{1 + \cot^2\theta}$$
  dove $\alpha_c = 1.0$ (per membrature non precompresse), $\nu = 0.50 \left(1 - \frac{f_{ck}}{250}\right)$ è il coefficiente riduttivo per trazione trasversale.
- **Condizione di Verifica**:
  $$V_{Ed} \le V_{Rd} = \min(V_{Rd,s} ; V_{Rd,c})$$

> [!WARNING]
> ### ⚠️ ERRORE TIPICO DA EVITARE ALL'ESAME: PASSO DELLE STAFFE
> Nei riassunti informali le didascalie sono invertite! Ricorda all'esame le **regole corrette**:
> - **In ZONA CRITICA (estremità di travi e pilastri con lunghezza $L_{cr} = 2 h$)**:
>   Il passo deve essere **FITTO**:
>   $$s \le \min \left( \frac{h}{4} ; 175\text{ mm} ; 8 \Phi_{L,min} \right) \quad \text{[per CD\"B\"]}$$
>   $$(s \le \min(h/4; 100\text{ mm}; 6 \Phi_L) \text{ per CD\"A\"})$$
> - **In ZONA CORRENTE (mezzeria della campata)**:
>   Il passo è **RADO**:
>   $$s \le \min \left( 0.75 d ; 250\text{ mm} ; 12 \Phi_{L,min} \right)$$

---

### 2.5. Torsione nel Calcestruzzo Armato (NTC 2018 §4.1.2.3.6)
Trattata con il **Modello del Traliccio Spaziale a Pareti Sottili di Rausch**:
- **Sezione cava equivalente**: spessore efficace della parete:
  $$t_{ef} = \max \left( 2 c ; \frac{A}{u} \right) \quad (c = \text{copriferro})$$
  $A_k$: area racchiusa dalla linea media della parete sottile; $u_k$: perimetro della linea media.
- **Flusso di taglio e tensione tangenziale di torsione**:
  $$q = \frac{T_{Ed}}{2 A_k} \implies \tau_t = \frac{T_{Ed}}{2 A_k t_{ef}}$$
- **Armatura trasversale a torsione (staffe chiuse perimetrali con braccio a 90° e ganci a 135°)**:
  $$\frac{A_{st}}{s} = \frac{T_{Ed}}{2 A_k f_{yd} \cot\theta}$$
- **Armatura longitudinale a torsione (barre correnti distribuite lungo $u_k$)**:
  $$\sum A_{sl} = \frac{T_{Ed} \cdot u_k \cdot \cot\theta}{2 A_k f_{yd}}$$
- **Verifica delle bielle compresse di calcestruzzo e interazione con il taglio**:
  $$\left( \frac{T_{Ed}}{T_{Rd,max}} \right)^2 + \left( \frac{V_{Ed}}{V_{Rd,c}} \right)^2 \le 1.00$$
  dove $T_{Rd,max} = 2 \nu \alpha_c f_{cd} A_k t_{ef} \sin\theta \cos\theta$.

---

> [!NOTE]
> ### Esempio Numerico Breve (Verifica a Taglio C.A.):
> Trave rettangolare in cls C28/35 ($f_{cd} = 0.85 \cdot 28 / 1.5 = 15.87\text{ MPa}$), base $b_w = 300\text{ mm}$, altezza utile $d = 450\text{ mm}$. Staffe $\Phi 8$ a due bracci ($A_{sw} = 2 \cdot 50.3 = 100.6\text{ mm}^2$), passo $s = 150\text{ mm}$, acciaio B450C ($f_{yd} = 391.3\text{ MPa}$). Taglio sollecitante $V_{Ed} = 180\text{ kN}$. Si assume $\cot\theta = 2.0$ ($\theta \approx 26.6^\circ$).
> 1. Resistenza lato staffe:
>    $$V_{Rd,s} = 0.9 \cdot 450 \cdot \frac{100.6}{150} \cdot 391.3 \cdot 2.0 = 212520\text{ N} = 212.5\text{ kN}$$
> 2. Coefficiente $\nu = 0.50 (1 - 28/250) = 0.444$. Resistenza lato calcestruzzo:
>    $$V_{Rd,c} = 0.9 \cdot 450 \cdot 300 \cdot 1.0 \cdot 0.444 \cdot 15.87 \cdot \frac{2.0}{1 + 2.0^2} = 855364 \cdot \frac{2}{5} = 342.1\text{ kN}$$
> 3. $V_{Rd} = \min(212.5 ; 342.1) = 212.5\text{ kN} > V_{Ed} = 180\text{ kN} \implies$ **Verifica soddisfatta.**

---

## MODULO 3: Acciaio – Membrature, Verifiche di Resistenza e Instabilità

### 3.1. Materiale Acciaio da Carpenteria
- **Acciai strutturali laminati a caldo (UNI EN 10025-2)**: S235, S275, S355, S450.
  - La lettera "S" indica *Structural Steel*; il numero indica lo snervamento caratteristico $f_{yk}$ in MPa per spessori $t \le 40\text{ mm}$.
  - Modulo di Young: $E = 210000\text{ MPa}$; Modulo di taglio: $G = \frac{E}{2(1+\nu)} \approx 81000\text{ MPa}$; Coefficiente di Poisson: $\nu = 0.30$; Coefficiente di dilatazione termica: $\alpha = 1.2 \cdot 10^{-5}\text{ }^\circ\text{C}^{-1}$.
- **Coefficienti parziali di sicurezza del materiale ($\gamma_M$)**:
  - $\gamma_{M0} = 1.05$ (resistenza delle sezioni trasversali a snervamento);
  - $\gamma_{M1} = 1.05$ (resistenza delle membrature nei confronti dei fenomeni di instabilità);
  - $\gamma_{M2} = 1.25$ (resistenza a rottura delle sezioni nette forate e dei collegamenti).
- **Prova di Resilienza (Pendolo di Charpy)**:
  - Misura l'energia assorbita $KV\text{ [J]}$ da un provino intagliato a V sotto carico dinamico impulsivo, quantificando la suscettibilità alla rottura fragile.
  - Sigle di resilienza: $KV \ge 27\text{ J}$ a $+20^\circ\text{C}$ (**JR**), a $0^\circ\text{C}$ (**J0**), a $-20^\circ\text{C}$ (**J2**), oppure $KV \ge 40\text{ J}$ a $-20^\circ\text{C}$ (**K2**). In zona sismica o per elementi tesi all'esterno si richiede almeno J2.

---

### 3.2. Verifiche di Resistenza delle Sezioni Trasversali allo SLU

#### 1. Trazione Semplice ($N_{Ed}$ positivo):
La resistenza di calcolo $N_{t,Rd}$ è il minimo tra la plasticizzazione della sezione lorda e la rottura della sezione netta forata:
$$N_{t,Rd} = \min \left( N_{pl,Rd} = \frac{A \cdot f_y}{\gamma_{M0}} \; ; \; N_{u,Rd} = \frac{0.9 \cdot A_{net} \cdot f_u}{\gamma_{M2}} \right)$$
*In zona sismica (per garantire duttilità)*: deve sempre risultare $N_{pl,Rd} < N_{u,Rd}$, affinché la barra si plasticizzi prima di rompersi fragilmente in corrispondenza dei fori dei bulloni!

#### 2. Compressione Semplice (senza instabilità):
$$N_{c,Rd} = \frac{A \cdot f_y}{\gamma_{M0}} \quad (\text{per Classi 1, 2, 3}); \quad N_{c,Rd} = \frac{A_{eff} \cdot f_y}{\gamma_{M0}} \quad (\text{per Classe 4})$$

#### 3. Flessione Retta ($M_{y,Ed}$):
$$M_{c,Rd} = M_{pl,Rd} = \frac{W_{pl,y} \cdot f_y}{\gamma_{M0}} \quad (\text{Classi 1 e 2}); \quad M_{c,Rd} = M_{el,Rd} = \frac{W_{el,y} \cdot f_y}{\gamma_{M0}} \quad (\text{Classe 3})$$
Per sezioni di Classe 4: $M_{c,Rd} = \frac{W_{eff,y} \cdot f_y}{\gamma_{M0}}$.

#### 4. Taglio Semplice ($V_{Ed}$):
Il taglio è assorbito prevalentemente dall'anima del profilo ($A_v$ area a taglio, per profili IPE/HE $A_v \approx A - 2 b t_f + (t_w + 2r) t_f$ oppure cautelativamente $A_v \approx h \cdot t_w$):
$$V_{pl,Rd} = \frac{A_v \cdot (f_y / \sqrt{3})}{\gamma_{M0}} = \frac{A_v \cdot f_{yd}}{\sqrt{3}}$$
*Verifica all'instabilità da taglio dell'anima*: se l'anima è molto snella, cioè $\frac{h_w}{t_w} > 72 \frac{\epsilon}{\eta}$ (con $\eta = 1.20$, $\epsilon = \sqrt{235/f_y}$), si deve verificare l'anima a instabilità per taglio secondo EC3-1-5 (metodo del campo di tensione).

#### 5. Interazione Flessione e Taglio ($M-V$):
- Se $V_{Ed} \le 0.50 V_{pl,Rd}$, il taglio non influenza la capacità flessionale: $M_{V,Rd} = M_{pl,Rd}$.
- Se $V_{Ed} > 0.50 V_{pl,Rd}$, si calcola la resistenza flessionale ridotta utilizzando una tensione di snervamento ridotta dell'area a taglio:
  $$M_{V,Rd} = \left[ W_{pl,y} - \frac{\rho \cdot A_v^2}{4 t_w} \right] \frac{f_y}{\gamma_{M0}} \le M_{pl,Rd} \quad \text{con } \rho = \left( \frac{2 V_{Ed}}{V_{pl,Rd}} - 1 \right)^2$$

#### 6. Interazione Flessione e Sforzo Normale ($M-N$ per sezioni a doppio T):
Per profili ad I o H inflesse rispetto all'asse forte $y-y$:
- Se $N_{Ed} \le 0.25 N_{pl,Rd}$ e $N_{Ed} \le \frac{0.5 h_w t_w f_y}{\gamma_{M0}}$, lo sforzo normale non riduce il momento plastico ($M_{N,y,Rd} = M_{pl,y,Rd}$).
- Altrimenti:
  $$M_{N,y,Rd} = M_{pl,y,Rd} \cdot \frac{1 - n}{1 - 0.5 a} \le M_{pl,y,Rd}$$
  dove $n = \frac{N_{Ed}}{N_{pl,Rd}}$ e $a = \frac{A - 2 b t_f}{A} \le 0.50$ (quota di area dell'anima).

---

### 3.3. Instabilità Globale Flessionale per Compressione (Aste di Eulero)
- **Carico Critico Elastico di Eulero**:
  $$N_{cr} = \frac{\pi^2 \cdot E \cdot I}{L_0^2}$$
  dove $L_0 = \beta \cdot L$ è la lunghezza libera d'inflessione (asta doppiamente incernierata $\beta = 1.0$; incastro-libero $\beta = 2.0$; incastro-cerniera $\beta = 0.7$; incastro-incastro $\beta = 0.5$).
- **Snellezza geometrica e adimensionale**:
  $$\lambda = \frac{L_0}{i} \quad \left(i = \sqrt{\frac{I}{A}} \text{ raggio d'inerzia}\right), \quad \lambda_1 = \pi \sqrt{\frac{E}{f_y}} = 93.9 \cdot \epsilon \quad \left(\epsilon = \sqrt{\frac{235}{f_y}}\right)$$
  $$\bar{\lambda} = \sqrt{\frac{A \cdot f_y}{N_{cr}}} = \frac{\lambda}{\lambda_1} \beta_A^{0.5} \quad (\beta_A = 1.0 \text{ per Classi 1, 2, 3})$$
- **Coefficiente di riduzione per instabilità $\chi$**:
  $$\chi = \frac{1}{\Phi + \sqrt{\Phi^2 - \bar{\lambda}^2}} \le 1.00 \quad \text{con } \Phi = 0.5 \left[ 1 + \alpha(\bar{\lambda} - 0.2) + \bar{\lambda}^2 \right]$$
  - $\alpha$: fattore di imperfezione dipendente dalla curva di instabilità:
    - Curva **$a_0$**: $\alpha = 0.13$
    - Curva **$a$**: $\alpha = 0.21$ (sezioni laminate ad I con $h/b > 1.2$ per inflessione asse forte)
    - Curva **$b$**: $\alpha = 0.34$ (sezioni laminate ad I per inflessione asse debole o tubolari)
    - Curva **$c$**: $\alpha = 0.49$ (profili HE con $h/b \le 1.2$ per asse debole)
    - Curva **$d$**: $\alpha = 0.76$ (profili saldati molto spessi)
- **Verifica di Stabilità SLU**:
  $$N_{Ed} \le N_{b,Rd} = \frac{\chi \cdot A \cdot f_y}{\gamma_{M1}}$$

---

### 3.4. Instabilità Locale e Classificazione delle Sezioni Trasversali (Classi 1–4)
Le pareti compresse delle sezioni metalliche possono instabilizzarsi localmente prima del raggiungimento dello snervamento. La norma classifica le sezioni in base al rapporto larghezza/spessore ($c/t$):
- **Classe 1 (Duttile/Plastica)**: consente la formazione della cerniera plastica con elevatissima capacità rotazionale ($\theta_{pl} > 3\text{–}4 \theta_y$) senza instabilità locale. Può essere impiegata nell'analisi plastica e nelle zone dissipative sismiche in Alta Duttilità (CD"A").
  - *Ali compresse*: $c/t_f \le 9 \epsilon$ ($\epsilon = \sqrt{235/f_y}$).
  - *Anima inflessa*: $c/t_w \le 72 \epsilon$.
- **Classe 2 (Compatta)**: raggiunge il momento plastico $M_{pl}$, ma ha limitata capacità di rotazione plastica. Impiegabile in CD"B".
  - *Ali compresse*: $c/t_f \le 10 \epsilon$; *Anima inflessa*: $c/t_w \le 83 \epsilon$.
- **Classe 3 (Elastica)**: le tensioni nella fibra più compressa raggiungono lo snervamento elastico ($M_{el}$), ma l'instabilità locale impedisce lo sviluppo del momento plastico.
  - *Ali compresse*: $c/t_f \le 14 \epsilon$; *Anima inflessa*: $c/t_w \le 124 \epsilon$.
- **Classe 4 (Snella)**: l'instabilità locale insorge in pieno campo elastico prima ancora del raggiungimento di $f_y$. La sezione deve essere analizzata sottraendo le parti instabili tramite la teoria delle larghezze efficaci ($A_{eff}, W_{eff}$).

---

### 3.5. Instabilità Flesso-Torsionale delle Travi Inflesse (Sbandamento Laterale)
Se una trave inflessa nel piano di massima rigidezza ha una limitata rigidezza flessionale o torsionale fuori piano e la flangia compressa non è trattenuta lateralmente, la trave sbanda lateralmente ruotando attorno all'asse longitudinale.
- **Momento Critico Elastico $M_{cr}$**:
  $$M_{cr} = C_1 \frac{\pi^2 E I_z}{(k L)^2} \left[ \sqrt{ \left(\frac{k}{k_w}\right)^2 \frac{I_w}{I_z} + \frac{(k L)^2 G I_t}{\pi^2 E I_z} + (C_2 z_g)^2 } - C_2 z_g \right]$$
  - $L$: distanza tra i ritegni torsionali;
  - $I_z$: momento d'inerzia attorno all'asse debole fuori piano;
  - $I_t$: inerzia torsionale primaria (Saint Venant);
  - $I_w$: inerzia settoriale di ingobbamento (warping);
  - $C_1, C_2$: coefficienti dipendenti dal diagramma del momento flettente (per momento costante $C_1 = 1.0, C_2 = 0$; per carico uniforme $C_1 = 1.13, C_2 = 0.45$);
  - $z_g$: quota del punto di applicazione del carico rispetto al centro di taglio ($z_g > 0$ se il carico è applicato all'ala superiore $\implies$ **effetto destabilizzante**, riduce drasticamente $M_{cr}$!).
- **Verifica con Momento Resistente di Instabilità $M_{b,Rd}$**:
  $$\bar{\lambda}_{LT} = \sqrt{\frac{W_{pl,y} f_y}{M_{cr}}}, \quad \Phi_{LT} = 0.5 [1 + \alpha_{LT}(\bar{\lambda}_{LT} - 0.2) + \bar{\lambda}_{LT}^2], \quad \chi_{LT} = \frac{1}{\Phi_{LT} + \sqrt{\Phi_{LT}^2 - \bar{\lambda}_{LT}^2}} \le 1.0$$
  $$M_{Ed} \le M_{b,Rd} = \frac{\chi_{LT} \cdot W_{pl,y} \cdot f_y}{\gamma_{M1}}$$
  *Nota*: se $\bar{\lambda}_{LT} \le 0.4$, l'instabilità flesso-torsionale può essere trascurata ($\chi_{LT} = 1.0$).

---

> [!NOTE]
> ### Esempio Numerico Breve (Instabilità Asta Compressa):
> Colonna HEB 200 in S275 ($f_y = 275\text{ MPa}$, $\epsilon = \sqrt{235/275} = 0.924$, $\gamma_{M1} = 1.05$). Lunghezza $L = 3.50\text{ m}$, vincoli cerniera-cerniera ($L_0 = 3500\text{ mm}$). Dati geometrici: $A = 7808\text{ mm}^2$, $i_z = 50.7\text{ mm}$ (asse debole).
> 1. Snellezza: $\lambda_z = \frac{3500}{50.7} = 69.03$. Snellezza di riferimento: $\lambda_1 = 93.9 \cdot 0.924 = 86.8$.
> 2. Snellezza adimensionale: $\bar{\lambda}_z = \frac{69.03}{86.8} = 0.795$.
> 3. Profilo HEB con $h/b = 200/200 = 1.0 \le 1.2$ flesso attorno ad asse debole $\implies$ Curva di instabilità **$c$** ($\alpha = 0.49$).
> 4. $\Phi = 0.5 \cdot [1 + 0.49 \cdot (0.795 - 0.2) + 0.795^2] = 0.5 \cdot [1 + 0.2915 + 0.632] = 0.962$.
> 5. $\chi = \frac{1}{0.962 + \sqrt{0.962^2 - 0.795^2}} = \frac{1}{0.962 + \sqrt{0.925 - 0.632}} = \frac{1}{0.962 + 0.541} = \frac{1}{1.503} = 0.665$.
> 6. Resistenza a compressione con instabilità:
>    $$N_{b,Rd} = \frac{0.665 \cdot 7808 \cdot 275}{1.05} = 1360175\text{ N} = 1360.2\text{ kN}$$

---

## MODULO 4: Unioni e Collegamenti in Acciaio (Nucleo Centrale del Laboratorio)

### 4.1. Unioni con Organi Meccanici (Bullonature)
Le unioni con bulloni collegano le membrature trasmettendo forze per taglio, trazione o combinazione delle due.

#### 1. Classificazione dei Bulloni (Tabella NTC 4.2.X):
- Bulloni ordinari: classi 4.6, 5.6 ($f_{yb} = 240\text{–}300\text{ MPa}$, $f_{ub} = 400\text{–}500\text{ MPa}$).
- **Bulloni ad alta resistenza (HR / HV)**: classi **8.8** ($f_{yb} = 640\text{ MPa}, f_{ub} = 800\text{ MPa}$) e **10.9** ($f_{yb} = 900\text{ MPa}, f_{ub} = 1000\text{ MPa}$). Obbligatori per unioni ad attrito e collegamenti in zona sismica.

#### 2. Geometria dei Fori e Distanze Minime/Massime di Bordo (Eurocodice 3-1-8):
- Diametro foro: $d_0 = d + 1\text{ mm}$ (per bulloni M12, M14); $d_0 = d + 2\text{ mm}$ (per bulloni M16, M20, M24).
- Distanza dal bordo nella direzione del carico: $1.2 d_0 \le e_1 \le 4 t + 40\text{ mm}$.
- Distanza dal bordo perpendicolare al carico: $1.2 d_0 \le e_2 \le 4 t + 40\text{ mm}$.
- Interasse nella direzione del carico: $2.2 d_0 \le p_1 \le \min(14 t; 200\text{ mm})$.
- Interasse perpendicolare al carico: $2.4 d_0 \le p_2 \le \min(14 t; 200\text{ mm})$.

#### 3. Verifiche Analitiche per Singolo Bullone:
- **Resistenza a Taglio sul Gambo ($F_{v,Rd}$)**:
  $$F_{v,Rd} = \frac{\alpha_v \cdot f_{ub} \cdot A}{\gamma_{M2}}$$
  - Se il piano di taglio attraversa la parte non filettata: $A = A_{gambo}$, $\alpha_v = 0.60$.
  - Se il piano di taglio attraversa la parte filettata: $A = A_s$ (area resistente resistente), $\alpha_v = 0.60$ per classi 4.6, 5.6, 8.8; $\alpha_v = 0.50$ per classe 10.9. ($\gamma_{M2} = 1.25$).
- **Resistenza a Rifollamento della Lamiera ($F_{b,Rd}$)**:
  $$F_{b,Rd} = \frac{k_1 \cdot \alpha_b \cdot f_u \cdot d \cdot t}{\gamma_{M2}}$$
  dove $d$ è il diametro nominale del bullone, $t$ lo spessore della piastra, $f_u$ la tensione di rottura della piastra collegata e:
  - $\alpha_b = \min \left( \frac{e_1}{3 d_0} \; ; \; \frac{p_1}{3 d_0} - \frac{1}{4} \; ; \; \frac{f_{ub}}{f_u} \; ; \; 1.0 \right)$
  - $k_1 = \min \left( 2.8 \frac{e_2}{d_0} - 1.7 \; ; \; 2.5 \right)$ per bulloni di bordo; $k_1 = \min \left( 1.4 \frac{p_2}{d_0} - 1.7 \; ; \; 2.5 \right)$ per bulloni interni.
- **Resistenza a Trazione del Bullone ($F_{t,Rd}$)**:
  $$F_{t,Rd} = \frac{0.9 \cdot f_{ub} \cdot A_s}{\gamma_{M2}}$$
- **Resistenza a Punzonamento della Piastra ($B_{p,Rd}$)**:
  $$B_{p,Rd} = \frac{0.6 \cdot \pi \cdot d_m \cdot t_p \cdot f_u}{\gamma_{M2}}$$
  ($d_m$: diametro medio tra vertici del dado o della testa del bullone).
- **Interazione Taglio e Trazione**:
  $$\frac{F_{v,Ed}}{F_{v,Rd}} + \frac{F_{t,Ed}}{1.4 \cdot F_{t,Rd}} \le 1.00$$
- **Unioni ad Attrito con Bulloni Precaricati ad Alta Resistenza**:
  - Forza di serraggio controllato di precarico:
    $$F_{p,C} = 0.70 \cdot f_{ub} \cdot A_s$$
  - Resistenza di calcolo allo scorrimento per piano di contatto:
    $$F_{s,Rd} = \frac{k_s \cdot n \cdot \mu}{\gamma_{M3}} \cdot F_{p,C}$$
    dove $k_s = 1.0$ (fori normali), $n$ numero piani d'attrito, $\mu$ coefficiente di attrito (Classe A: $\mu = 0.50$ per sabbiatura fine; Classe B: $\mu = 0.40$; Classe C: $\mu = 0.30$ per spazzolatura; Classe D: $\mu = 0.20$ su superficie non trattata), $\gamma_{M3} = 1.25$ allo SLU ($\gamma_{M3} = 1.10$ allo SLE).
- **Resistenza a Rottura a Strappo dell'Estremità (Block Tearing / Block Shear $V_{eff,1,Rd}$)**:
  $$V_{eff,1,Rd} = \frac{f_u \cdot A_{nt}}{\gamma_{M2}} + \frac{1}{\sqrt{3}} \frac{f_y \cdot A_{nv}}{\gamma_{M0}}$$
  ($A_{nt}$: area netta tesa soggetta a trazione; $A_{nv}$: area netta soggetta a taglio lungo la linea di strappo dei fori).

---

### 4.2. Unioni Saldate
- **Tipologie di Saldatura**:
  - *A completa penetrazione*: il materiale d'apporto riempie interamente lo spessore delle lamiere smussate (a V, a X). Non altera il flusso delle tensioni. Resistenza assunta pari a quella del materiale base più debole.
  - *A cordone d'angolo*: eseguite all'intersezione tra due piatti senza smusso. Molto diffuse ma soggette a concentrazioni di tensioni all'apice.
- **Geometria del Cordone d'Angolo**:
  - Altezza di gola $a$: altezza del triangolo isoscele inscritto nella sezione del cordone ($a \ge 3\text{ mm}$ e $a \le 0.7 t_{min}$). Lunghezza efficace: $L_{eff} \ge \max(30\text{ mm}; 6 a)$.
- **Verifica Analitica col Metodo Direzionale (Von Mises)**:
  Sul piano di gola ribaltato si scompongono le tensioni in:
  - $\sigma_\perp$: tensione normale ortogonale al piano di gola;
  - $\tau_\perp$: tensione tangenziale ortogonale all'asse del cordone;
  - $\tau_\parallel$: tensione tangenziale parallela all'asse del cordone;
  - $\sigma_\parallel$: tensione normale parallela (non influenza la rottura del cordone).
  **Criterio di verifica NTC 2018 (§4.2.8.2.4) ed Eurocodice 3 (EC3-1-8)**:
  $$\sqrt{\sigma_\perp^2 + 3 \left( \tau_\perp^2 + \tau_\parallel^2 \right)} \le \frac{f_u}{\beta_w \cdot \gamma_{M2}} \quad \text{e contemporaneamente} \quad \sigma_\perp \le 0.90 \frac{f_u}{\gamma_{M2}}$$
  | Acciaio | $f_u\text{ [MPa]}$ | Fattore di correlazione $\beta_w$ | $\frac{f_u}{\beta_w \cdot \gamma_{M2}}\text{ [MPa]}$ |
  | :--- | :---: | :---: | :---: |
  | **S235** | 360 | 0.80 | $360 / (0.80 \cdot 1.25) = 360.0$ |
  | **S275** | 430 | 0.85 | $430 / (0.85 \cdot 1.25) = 404.7$ |
  | **S355** | 510 | 0.90 | $510 / (0.90 \cdot 1.25) = 453.3$ |

---

### 4.3. Nodo Flangiato con Modello a T-Stub (EC3-1-8)
Nel collegamento trave-colonna flangiato soggetto a momento flettente, la trazione dell'ala superiore tesa viene modellata come una mensola a T (T-stub) bullonata alla colonna:
- **Modo 1 (Plasticizzazione completa della flangia)**:
  Meccanismo duttile a 4 cerniere plastiche nella piastra flangiata prima della rottura dei bulloni:
  $$F_{T,1,Rd} = \frac{4 M_{pl,1,Rd}}{m} \quad \text{con } M_{pl,1,Rd} = 0.25 \sum l_{eff,1} \cdot t_f^2 \cdot \frac{f_y}{\gamma_{M0}}$$
- **Modo 2 (Plasticizzazione parziale della flangia con rottura dei bulloni a trazione)**:
  Si formano 2 cerniere plastiche nella flangia e intervengono le forze di leva (*prying forces* $Q$):
  $$F_{T,2,Rd} = \frac{2 M_{pl,2,Rd} + n \sum B_t}{m + n}$$
- **Modo 3 (Rottura a trazione pura dei soli bulloni)**:
  Rottura fragile senza deformazione plastica della flangia:
  $$F_{T,3,Rd} = \sum B_t = \sum F_{t,Rd}$$
- **Resistenza di progetto della zona tesa**:
  $$F_{T,Rd} = \min \left( F_{T,1,Rd} \; ; \; F_{T,2,Rd} \; ; \; F_{T,3,Rd} \right)$$

---

### 4.4. Dettagli Costruttivi Esecutivi della Struttura Pendolare in Acciaio
1. **Collegamento Trave Secondaria - Trave Principale a Squadretta**:
   - Collegamento a cerniera realizzato mediante una o due squadrette angolari bullonate sull'anima della secondaria e sull'anima della principale.
   - *Intaglio dell'ala (Scarpa o Notching)*: l'ala superiore della trave secondaria viene scantonata per consentire la perfetta planarità del piano di posa della lamiera grecata.
   - *Ruolo strutturale fondamentale della squadretta*: la squadretta **non deve essere troppo bassa** (altezza $\ge 0.6 h_{trave}$) perché costituisce il **ritegno torsionale** che blocca lo sbandamento latero-torsionale dell'ala compressa della trave principale!
2. **Basamento Colonna con Piastra di Base e Tirafondi**:
   - Trasmissione dello sforzo assiale di compressione tramite pressione di contatto sulla malta antiritiro (*grout*) interposta tra la piastra d'acciaio e il plinto di fondazione in c.a.
   - Resistenza di contatto calcestruzzo: $f_{jd} = \beta_j \cdot k_j \cdot f_{cd} \approx 1.0 \cdot 1.5 \cdot f_{cd}$.
   - Spessore minimo della piastra di base $t_p$: calcolato considerando la piastra a sbalzo oltre il profilo metallico soggetta alla pressione $f_{jd}$.
   - Tirafondi ancorati nel plinto: barre filettate ad alta resistenza sagomate ad ancora (o con piastra d'ancoraggio terminale) per resistere all'eventuale trazione temporanea in fase di montaggio o dovuta a momenti parassiti.

---

> [!NOTE]
> ### Esempio Numerico Breve (Verifica Bullone a Taglio e Rifollamento):
> Squadretta d'anima su profilato IPE 300 ($t_w = 7.1\text{ mm}$, acciaio S275: $f_y = 275\text{ MPa}$, $f_u = 430\text{ MPa}$). Bulloni **M20 classe 8.8** ($d = 20\text{ mm}$, $d_0 = 22\text{ mm}$, $A_s = 245\text{ mm}^2$, $f_{ub} = 800\text{ MPa}$, filettatura nel piano di taglio). Distanze: $e_1 = 40\text{ mm}$, $p_1 = 70\text{ mm}$, $e_2 = 35\text{ mm}$.
> 1. Resistenza a Taglio per singolo bullone:
>    $$F_{v,Rd} = \frac{0.60 \cdot 800 \cdot 245}{1.25} = 94080\text{ N} = 94.08\text{ kN}$$
> 2. Coefficienti di rifollamento:
>    - $\alpha_b = \min \left( \frac{40}{3 \cdot 22} = 0.606 \; ; \; \frac{70}{3 \cdot 22} - 0.25 = 0.811 \; ; \; \frac{800}{430} = 1.86 \; ; \; 1.0 \right) = 0.606$
>    - $k_1 = \min \left( 2.8 \cdot \frac{35}{22} - 1.7 = 2.75 \; ; \; 2.5 \right) = 2.50$
> 3. Resistenza a Rifollamento per singolo bullone sull'anima da $7.1\text{ mm}$:
>    $$F_{b,Rd} = \frac{2.50 \cdot 0.606 \cdot 430 \cdot 20 \cdot 7.1}{1.25} = \frac{92497}{1.25} = 73998\text{ N} = 74.00\text{ kN}$$
> 4. Resistenza critica del singolo bullone: $F_{Rd} = \min(94.08 ; 74.00) = 74.00\text{ kN}$ (governa il rifollamento).

---

## MODULO 5: Sistemi Innovativi per Impalcati (Travi Alveolari e Solai Slim Floor)

### 5.1. Travi Alveolari (Cellular Beams / Castellated Beams)
Le travi alveolari sono profili metallici ad altezza maggiorata dotati di aperture regolari (circolari o esagonali) disposte lungo l'anima:
- **Processo di Fabbricazione**:
  1. Si parte da un profilo laminato standard (es. IPE o HEB);
  2. L'anima viene tagliata longitudinalmente ad ossitaglio lungo una linea continua a dente di sega (per fori esagonali/ottagonali) o sinusoidale (per fori circolari/cellulari);
  3. I due semiprofili a T (*tees*) vengono sfalsati e risaldati in corrispondenza dei denti combacianti;
  4. L'altezza finale della trave diventa circa $1.4\text{–}1.6$ volte l'altezza originaria ($h_{tot} \approx 1.5 h_0$), aumentando il momento d'inerzia di oltre il $100\text{–}150\%$ a parità di peso!
- **Vantaggi Architettonici e Funzionali**:
  - Consente il superamento di grandi luci ($L = 12\text{–}20\text{ m}$) senza colonne intermedie;
  - Totale **integrazione impiantistica**: canali di ventilazione, condotte idrauliche e canaline elettriche passano direttamente all'interno delle aperture senza ridurre l'altezza utile interpiano;
  - Ottimizzazione del materiale: soletta compressa in c.a. superiormente e trave tesa inferiormente.
- **I Tre Meccanismi di Collasso Locale da Verificare (Lezione 8 Nina)**:
  1. **Meccanismo Vierendeel**:
     In corrispondenza dell'apertura, il taglio globale $V_{Ed}$ si ripartisce tra il corrente superiore e il corrente inferiore (ciascuno assorbe $V_i \approx V_{Ed}/2$), generando un momento secondario di flessione locale (*Vierendeel bending*) alle estremità dei correnti:
     $$M_{Vierendeel} = \frac{V_{Ed}}{2} \cdot \frac{d_0}{2}$$
     I correnti devono essere verificati per la combinazione dello sforzo normale globale ($N_{Tee} \approx M_{Ed}/h_{eff}$) e del momento secondario Vierendeel.
  2. **Instabilità del Montante d'Anima (Web-Post Buckling)**:
     La porzione d'anima compresa tra due aperture adiacenti (*web post*) è soggetta a taglio orizzontale e a compressione diagonale. Può instabilizzarsi per sbandamento flessionale fuori piano, limitando la capacità portante a taglio della trave.
  3. **Rottura per Taglio Orizzontale della Saldatura**:
     Lungo la linea di risaldatura dei denti si sviluppa un flusso di taglio orizzontale $v_h = \frac{V_{Ed} \cdot S}{I}$. La saldatura a completa penetrazione o a doppio cordone deve resistere a tale sforzo di scorrimento.

---

### 5.2. Solai Integrati Tipo Slim Floor (IFB, SFB, CoSFB)
Soluzione innovativa per edifici multipiano mirata ad annullare l'ingombro sottotrave:
- **Tipologie Costruttive**:
  - **IFB (Integrated Floor Beam)**: profilo laminato asimmetrico o IPE/HE con un piatto d'acciaio allargato saldato all'ala inferiore.
  - **SFB (Slim Floor Beam)**: profilo a doppio T con piatto inferiore sporgente su cui poggiano direttamente i pannelli del solaio.
  - **CoSFB (Composite Slim Floor Beam)**: trave composta integrata con aperture nell'anima attraverso cui passano barre di armatura e calcestruzzo colato in opera, creando connettori chimico-meccanici continui.
- **Vantaggi Strutturali e di Cantiere**:
  - *Spessore nullo della trave*: la trave è interamente contenuta all'interno dello spessore del solaio ($25\text{–}35\text{ cm}$), massimizzando l'altezza netta interpiano o consentendo di ricavare un piano in più a parità di altezza totale dell'edificio;
  - *Intrinseca resistenza al fuoco*: l'anima e l'ala superiore della trave sono annegate nel calcestruzzo del solaio, lasciando esposta all'eventuale incendio solo la faccia inferiore del piatto di base (facilmente protetta con vernice intumescente o controsoffitto);
  - *Assenza di casserature temporanee*.

---

## MODULO 6: Progettazione e Calcolo delle Scale Metalliche

### 6.1. Concezione Strutturale e Disconnessione Sismica
La scala rappresenta una macro-struttura a gradoni inclinata estremamente rigida nel proprio piano. Se collegata rigidamente alla struttura principale dell'edificio, si comporta come un gigantesco controvento parassita non previsto, attirando una percentuale sproporzionata del taglio sismico e generando pericolose eccentricità torsionali d'impalcato.
- **Regola Progettuale del Laboratorio**: la scala metallica deve essere **strutturalmente disconnessa** dalla risposta sismica dell'edificio principale.
- **I Due Schemi Alternativi di Realizzazione**:
  1. **Schema a Scale Sospese (Suspended Stairs)**:
     - Le travi rampanti e i pianerottoli sono sospesi a ciascun livello mediante **pendini/tiranti verticali in acciaio** ancorati alle travi principali d'impalcato soprastanti.
     - La scala non scarica reazioni orizzontali e trasmette i carichi verticali delle rampanti come carichi concentrati (generalmente a $L/4$ e $3/4 L$) sulle travi di piano.
  2. **Schema su Colonne Autonome Indipendenti**:
     - Il corpo scala poggia su quattro colonne dedicate continue dalla fondazione alla copertura, separate strutturalmente dai telai dell'edificio tramite un **giunto sismico calibrato** (ampiezza giunto $\ge d_{r,edificio} + d_{r,scala}$).

---

### 6.2. Progetto e Dimensionamento del Singolo Gradino
Il gradino metallico costituisce l'elemento base del sistema scale.
- **Schema Statico**:
  - Mensola a sbalzo collegata rigidamente (saldata o bullonata con piastra di testa) al cosciale centrale o al profilo tubolare/scatolare portante della rampa.
- **Geometria Tipica**:
  - Piastra in lamiera d'acciaio piegata a freddo con sagomatura a Z o a scatolare (spessore $t = 3\text{–}5\text{ mm}$, alzata $a \approx 16\text{–}17\text{ cm}$, pedata $p \approx 30\text{ cm}$, larghezza sbalzo $L = 1.00\text{–}1.20\text{ m}$).
- **Carichi di Verifica secondo NTC 2018**:
  - *Carico distribuito d'uso (Cat. C/scale)*: $q_k = 4.00\text{ kN/m}^2$;
  - **CARICO CONCENTRATO ISOLATO DI NORMA DA $2.00\text{ kN}$**:
    Applicato nell'impronta quadrata $50 \times 50\text{ mm}$ posta sul **bordo libero esterno più sfavorevole del gradino** (estremità della mensola).
- **Verifiche di Resistenza SLU**:
  - *Flessione retta alla radice dell'incastro*:
    $$M_{Ed} = \gamma_Q \cdot Q_k \cdot L = 1.50 \cdot 2.00\text{ kN} \cdot L$$
    $$\sigma_{max} = \frac{M_{Ed}}{W_{el}} \le f_{yd} = \frac{f_y}{\gamma_{M0}}$$
  - *Torsione d'estremità*: la forza concentrata applicata sul bordo anteriore del gradino genera un braccio torsionale rispetto al centro di taglio della sezione a Z o scatolare pari a $e \approx p/2 \approx 150\text{ mm}$, inducendo un momento torcente $T_{Ed} = 1.5 \cdot 2.0 \cdot 0.15 = 0.45\text{ kNm}$.
- **Verifiche di Deformabilità SLE (Rigidezza e Comfort Dinamico)**:
  - Per evitare vibrazioni sgradevoli ed una percezione psicologica di insicurezza durante la salita/discesa, la freccia elastica massima all'estremità libera sotto carico concentrato di esercizio ($Q = 2\text{ kN}$) deve rispettare il limite restrittivo:
    $$f_{max} = \frac{Q \cdot L^3}{3 E I} \le \frac{L}{300} \quad (\text{o } f_{max} \le 3\text{–}4\text{ mm})$$

---

### 6.3. Dimensionamento dei Cosciali e dei Pendini
- **Cosciali di Rampa**:
  - Travi inclinate (profili laminati ad UPN 200–240 o tubolari rettangolari) disposte lungo l'inclinazione della rampa ($\alpha \approx 30^\circ$).
  - Sollecitati a flessione $M$ e sforzo normale $N$ (dovuto alla scomposizione del carico lungo l'asse inclinato).
- **Pendini / Tiranti di Sospensione**:
  - Barre tonde piene o tubolari sottili soggetti a pura trazione.
  - Verifica di resistenza a trazione:
    $$N_{Ed} \le N_{t,Rd} = \frac{A \cdot f_y}{\gamma_{M0}}$$
  - Presenza di occhielli terminali con perni o manicotti filettati con tenditori (*turnbuckles*) per consentire la perfetta messa in tiro e il livellamento millimetrico dei pianerottoli durante la fase di montaggio.

---

> [!NOTE]
> ### Esempio Numerico Breve (Verifica Gradino a Mensola):
> Gradino a mensola a sbalzo in acciaio S275 ($f_{yd} = 275 / 1.05 = 261.9\text{ MPa}$), lunghezza $L = 1.10\text{ m}$. Sezione scatolare in lamiera piegata con modulo di resistenza $W_{el} = 22.5\text{ cm}^3 = 22500\text{ mm}^3$ e momento d'inerzia $I = 112\text{ cm}^4 = 1.12 \cdot 10^6\text{ mm}^4$. Carico concentrato di norma $Q_k = 2.0\text{ kN}$ in punta.
> 1. Momento flettente di calcolo allo SLU:
>    $$M_{Ed} = 1.50 \cdot 2.0\text{ kN} \cdot 1.10\text{ m} = 3.30\text{ kNm} = 3.30 \cdot 10^6\text{ Nmm}$$
> 2. Tensione massima di flessione alla radice:
>    $$\sigma_{max} = \frac{3.30 \cdot 10^6}{22500} = 146.7\text{ MPa} \le f_{yd} = 261.9\text{ MPa} \implies \text{Verifica SLU ampiamente soddisfatta.}$$
> 3. Freccia elastica in punta allo SLE ($Q = 2.0\text{ kN} = 2000\text{ N}$):
>    $$f_{max} = \frac{2000 \cdot 1100^3}{3 \cdot 210000 \cdot 1.12 \cdot 10^6} = \frac{2.662 \cdot 10^{12}}{7.056 \cdot 10^{11}} = 3.77\text{ mm}$$
>    Limite di comfort: $f_{lim} = \frac{L}{300} = \frac{1100}{300} = 3.67\text{ mm} \approx 3.77\text{ mm} \implies$ **Rigidezza adeguata.**

---

## MODULO 7: Dinamica delle Strutture e Definizione dell'Azione Sismica (NTC 2018)

### 7.1. Fondamenti di Dinamica delle Strutture (Oscillatore Semplice SDOF)
L'oscillatore semplice a un grado di libertà (SDOF - *Single Degree of Freedom*) è il modello teorico di base per studiare la risposta sismica degli edifici:
- **Equazione Differenziale del Moto**:
  $$m \ddot{x}(t) + c \dot{x}(t) + k x(t) = -m \ddot{x}_g(t)$$
  dove:
  - $m$: massa concentrata del piano [kg];
  - $c$: coefficiente di smorzamento viscoso [N·s/m];
  - $k$: rigidezza laterale delle colonne del telaio [N/m];
  - $x(t)$: spostamento relativo della massa rispetto alla base [m];
  - $\ddot{x}_g(t)$: accelerogramma del terreno impresso alla base [m/s$^2$].
- **Parametri Caratteristici**:
  - Pulsazione naturale propria: $\omega_n = \sqrt{\frac{k}{m}}\text{ [rad/s]}$;
  - Periodo proprio fondamentale: $T = \frac{2\pi}{\omega_n} = 2\pi \sqrt{\frac{m}{k}}\text{ [s]}$;
  - Frequenza propria: $f = \frac{1}{T} = \frac{\omega_n}{2\pi}\text{ [Hz]}$;
  - Rapporto di smorzamento critico $\xi$:
    $$\xi = \frac{c}{c_{cr}} = \frac{c}{2 m \omega_n} = \frac{c}{2 \sqrt{k m}}$$
    Per le strutture civili ordinarie: $\xi \approx 0.05$ ($5\%$).
- **Regimi di Oscillazione**:
  1. *Libere non smorzate ($c=0, \ddot{x}_g=0$)*: moto armonico continuo con ampiezza costante $x(t) = x_0 \cos(\omega_n t) + \frac{\dot{x}_0}{\omega_n} \sin(\omega_n t)$.
  2. *Libere smorzate ($\xi < 1$)*: oscillazione pseudo-armonica con decadimento esponenziale $e^{-\xi \omega_n t}$.
  3. *Forzate armoniche ($F(t) = F_0 \sin(\Omega t)$)*: quando la frequenza dell'eccitante coincide con la frequenza propria ($\Omega \approx \omega_n$), si verifica il fenomeno della **risonanza**, con amplificazione massima dello spostamento limitata unicamente dallo smorzamento ($D_{max} = \frac{1}{2\xi} \approx 10$ per $\xi = 0.05$).

---

### 7.2. Lo Spettro di Risposta Elastico secondo NTC 2018 (§3.2.3.2)
Lo spettro di risposta fornisce il massimo valore della risposta (in termini di accelerazione $S_e(T)$, velocità o spostamento $S_d(T)$) di un insieme di oscillatori semplici aventi diverso periodo $T$ e identico smorzamento ($\xi = 5\%$) sottoposti al medesimo evento sismico.
- **Parametri Sismici di Base del Sito** (individuati da latitudine e longitudine nella griglia dell'Allegato B NTC):
  - $a_g$: accelerazione orizzontale massima al suolo su terreno rigido pianeggiante (PGA);
  - $F_0$: valore massimo del fattore di amplificazione dello spettro in accelerazione orizzontale (generalmente tra $2.3$ e $2.6$);
  - $T_C^*$: periodo di inizio del tratto a velocità costante.
- **Parametri di Modificazione Stratigrafica e Topografica**:
  - Categorie di sottosuolo: **A** (roccia, $V_{s,30} > 800\text{ m/s}$), **B** (suoli molto densi, $360 < V_s \le 800$), **C** (suoli densi o mediamente compatti, $180 < V_s \le 360$), **D** (suoli sciolti, $V_s < 180$), **E** (strato alluvionale soffice $5\text{–}20\text{ m}$ sopra roccia).
  - Categorie topografiche: **T1** (superficie pianeggiante, $S_T = 1.0$), **T2** (pendii con inclinazione $> 15^\circ$, $S_T = 1.2$), **T3** (rilievi montuosi con cresta stretta, $S_T = 1.2$), **T4** (rilievi isolati con pendenze $> 30^\circ$, $S_T = 1.4$).
  - Coefficiente complessivo del suolo: $S = S_S \cdot S_T$.
- **Periodi Caratteristici dello Spettro**:
  $$T_B = \frac{T_C}{3}, \quad T_C = C_C \cdot T_C^*, \quad T_D = 4.0 \cdot \frac{a_g}{g} + 1.6$$
- **Forma Spettrale in Accelerazione $S_e(T)$**:
  - Tratto 1 ($0 \le T < T_B$): $S_e(T) = a_g \cdot S \cdot \eta \cdot F_0 \cdot \left[ \frac{T}{T_B} + \frac{1}{\eta F_0} \left(1 - \frac{T}{T_B}\right) \right]$
  - Tratto 2 ($T_B \le T < T_C$, Plateau di massima accelerazione): $S_e(T) = a_g \cdot S \cdot \eta \cdot F_0$
  - Tratto 3 ($T_C \le T < T_D$, Velocità costante): $S_e(T) = a_g \cdot S \cdot \eta \cdot F_0 \cdot \left(\frac{T_C}{T}\right)$
  - Tratto 4 ($T \ge T_D$, Spostamento costante): $S_e(T) = a_g \cdot S \cdot \eta \cdot F_0 \cdot \left(\frac{T_C \cdot T_D}{T^2}\right)$
  *(con $\eta = \sqrt{10 / (5 + \xi)} = 1.0$ per $\xi = 5\%$)*.

---

## MODULO 8: Progettazione Sismica e Gerarchia delle Resistenze (MRF, CBF, EBF)

### 8.1. Filosofia della Progettazione Antisismica Moderna
1. **Comportamento Non Dissipativo (Elastico)**:
   - Tutta la struttura (membrature e collegamenti) rimane in campo elastico.
   - Fattore di comportamento basso: $q \le 1.50$.
   - Richiede membrature molto grandi e costose.
2. **Comportamento Dissipativo (Plastico)**:
   - La struttura è concepita per dissipare gran parte dell'energia sismica in ingresso tramite la plasticizzazione ciclica di specifiche zone duttili prescelte (**zone dissipative**), mentre il resto della struttura (**zone non dissipative**) viene sovradimensionato per rimanere rigorosamente in campo elastico.
   - Fattore di comportamento elevato: $q > 1.5$ (fino a $4\text{–}6.5$ per alta duttilità).
   - Classi di duttilità: **CD"A" (Alta)** e **CD"B" (Media)**.

### 8.2. Gerarchia delle Resistenze (*Capacity Design*)
Il principio fondamentale evita meccanismi di collasso fragili imponendo due livelli gerarchici:
1. **Gerarchia Globale**: selezione del meccanismo di collasso cinematico favorevole (meccanismo globale di piano a trave debole - colonna forte), impedendo la formazione di meccanismi a piano soffice.
2. **Gerarchia Locale**: protezione di ciascun modo di collasso fragile (rottura a taglio, instabilità locale/globale, rottura delle connessioni) rispetto al corrispondente modo di collasso duttile (snervamento a trazione o flessione).

---

### 8.3. Edifici a Telaio Sismo-Resistenti (Moment Resisting Frames - MRF)
- **Meccanismo di Collasso Desiderato**: cerniere plastiche concentrate alle estremità delle travi; colonne che rimangono elastiche (salvo alla base del piano terra).
- **Criterio Colonna Forte - Trave Debole (NTC 2018 §7.5.4.1)**:
  In ciascun nodo trave-colonna deve essere verificata la disuguaglianza:
  $$\sum M_{c,pl,Rd} \ge 1.30 \cdot \sum M_{b,pl,Rd}$$
  (somma dei momenti resistenti plastici delle colonne $\ge 1.3$ volte la somma dei momenti plastici delle travi concorrenti nel nodo).
- **Sovraresistenza dei Collegamenti Trave-Colonna**:
  I nodi rigidi flangiati o saldati devono avere una resistenza flessionale:
  $$M_{j,Rd} \ge 1.10 \cdot \gamma_{ov} \cdot M_{b,pl,Rd} \quad (\gamma_{ov} = 1.25 \implies 1.1 \cdot 1.25 = 1.375 M_{pl})$$
- **Verifica del Pannello d'Anima della Colonna a Taglio ($V_{wp}$)**:
  Il taglio nodale derivante dalla trazione dell'ala superiore e compressione dell'ala inferiore della trave inflessa ($V_{wp,Ed} \approx \frac{M_{b,1} + M_{b,2}}{z} - V_{col}$) deve risultare inferiore alla resistenza a taglio del pannello $V_{wp,Rd}$. Se non verificato, occorre saldare piatti di raddoppio (*doubler plates*).
- **Verifica di Deformabilità allo Stato Limite di Danno (SLD - Drift Interpiano)**:
  Lo spostamento d'interpiano calcolato moltiplicando lo spostamento elastico per il fattore di comportamento $q$ ($d_r = d_e \cdot q$) deve rispettare:
  $$d_r \le 0.005 \cdot h \quad \text{per tamponamenti rigidi fragili}$$
  $$d_r \le 0.0075 \cdot h \quad \text{per tamponamenti duttili}$$
  $$d_r \le 0.010 \cdot h \quad \text{per tamponamenti isolati o assenza di tamponature}$$

---

### 8.4. Edifici con Controventi Concentrici (CBF - Concentrically Braced Frames)
Nei telai CBF la rigidezza e la resistenza alle azioni orizzontali sono affidate a triangolazioni reticolari le cui aste convergono in un punto comune:
- **Tipologie di Configurazione**:
  1. *Controventi a X (con diagonali tese attive)*: in ciascun ciclo di carico, la diagonale compressa si instabilizza immediatamente, mentre la diagonale tesa entra in trazione plastica ($N_{pl,Rd}$). La dissipazione avviene per snervamento della diagonale tesa.
  2. *Controventi a V (o a V rovescia / Chevron)*: le due diagonali convergono in mezzeria della trave di piano.
  3. **DIVIETO DEI CONTROVENTI A K**: la normativa NTC 2018 **VIETA TASSATIVAMENTE** i controventi a K in zona sismica poiché il vertice converge a metà altezza del pilastro, scaricando una forza sbilanciata orizzontale che provocherebbe una cerniera plastica a metà colonna con conseguente collasso di piano!
- **LA FORZA SBILANCIATA VERTICALE NEI CONTROVENTI A V**:
  Quando la diagonale compressa raggiunge il carico critico, la sua capacità portante crolla al valore residuo post-buckling ($N_{b,Rd}$). La diagonale tesa, invece, continua a incrementare la propria forza fino a plasticizzarsi a trazione ($N_{pl,Rd}$).
  Poiché la componente verticale delle due diagonali non è più in equilibrio, sulla trave di mezzeria si scarica una **FORZA VERTICALE SBILANCIATA NON COMPENSATA**:
  $$\Delta N_v = \left( N_{pl,Rd} - N_{b,Rd} \right) \cdot \sin\theta$$
  *Regola di Progetto fondamentale*: la trave NON È un elemento dissipativo. La trave deve essere dimensionata in campo elastico per sostenere l'azione dei carichi gravitazionali sommata alla forza concentrata $\Delta N_v$ in mezzeria, garantendo che non si formino cerniere plastiche prima della completa plasticizzazione delle diagonali!
- **Limitazione di Snellezza delle Diagonali**:
  $$1.30 \le \bar{\lambda} \le 2.00$$
  - $\bar{\lambda} \ge 1.30$: evita che la diagonale compressa abbia una capacità portante iniziale eccessiva, che scaricherebbe forze sbilanciate intollerabili sulle colonne prima di instabilizzarsi;
  - $\bar{\lambda} \le 2.00$: previene un degrado ciclico precoce per fatica a bassi cicli.
- **Condizione di Omogeneità di Piano**:
  $$\frac{\Omega_{max}}{\Omega_{min}} \le 1.25 \quad \text{con } \Omega_i = \frac{N_{pl,Rd,i}}{N_{Ed,E,i}}$$
  (garantisce una distribuzione uniforme della plasticizzazione lungo l'altezza dell'edificio).
- **Dettaglio del Fazzoletto d'Attacco (Gusset Plate)**:
  La diagonale deve essere interrotta ad una distanza libera pari a **$2 t_p$** (due volte lo spessore del piatto fazzoletto) dalla linea di piegatura teorica, per consentire la libera rotazione della cerniera plastica di instabilità fuori piano senza lacerare la saldatura di base.

---

### 8.5. Edifici con Controventi Eccentrici (EBF - Eccentrically Braced Frames)
Nei telai EBF le diagonali non convergono nel medesimo nodo, ma lasciano deliberatamente un segmento isolato di trave chiamato **LINK (Elemento Fusibile Sismico)**, che costituisce l'unica zona dissipativa dell'intero sistema.

> [!WARNING]
> ### ⚠️ ERRORE GRAVE DEI VECCHI RIASSUNTI SUI LINK EBF CORRETTO
> Nei vecchi riassunti informali compariva l'assurda formula con momento diviso momento ($M/M$) e le definizioni di link lunghi e intermedi erano invertite!
> Ecco la **FORMULAZIONE CORRETTA NTC 2018 (§7.5.4.3) / Eurocodice 8**:

#### 1. Classificazione Geometrica e Comportamentale del Link di Lunghezza $e$:
- **LINK CORTI (Shear Links - Dominati dal Taglio)**:
  $$e \le e_s = 1.60 \cdot \frac{M_{p,link}}{V_{p,link}} \quad \left( \text{oppure } e \le 0.8(1+\alpha)\frac{M_p}{V_p} \right)$$
  - Il link si plasticizza per **scorrimento tangenziale uniforme nell'anima** prima che le ali raggiungano lo snervamento per flessione;
  - Hanno una straordinaria capacità di dissipazione energetica e possono sopportare una **rotazione plastica d'interpiano massima**:
    $$\gamma_p \le 0.08\text{ radianti (pari all'8% di distorsione angolare!)}$$
- **LINK LUNGHI (Flexural Links - Dominati dalla Flessione)**:
  $$e \ge e_l = 3.00 \cdot \frac{M_{p,link}}{V_{p,link}} \quad \left( \text{oppure } e \ge 1.5(1+\alpha)\frac{M_p}{V_p} \right)$$
  - Il link si plasticizza per formazione di **due cerniere plastiche flessionali alle estremità**;
  - Minore capacità di deformazione plastica a taglio: rotazione massima limitata a:
    $$\gamma_p \le 0.02\text{ radianti}$$
- **LINK INTERMEDI (Flesso-Taglio)**:
  $$1.60 \cdot \frac{M_p}{V_p} < e < 3.00 \cdot \frac{M_p}{V_p}$$
  - Comportamento accoppiato taglio-flessione con rotazione limite interpolata linearmente tra $0.08$ e $0.02\text{ rad}$:
    $$\gamma_p = 0.08 - 0.06 \cdot \frac{e - 1.6 M_p/V_p}{1.4 M_p/V_p}\text{ rad}$$

#### 2. Dettagli Costruttivi OBBLIGATORI del Link:
1. **Irrigidimenti d'Anima Verticali Fitti (Web Stiffeners)**:
   - Devono essere saldati su entrambi i lati dell'anima a passo ridotto ($a \le 30 t_w - d/5$ per link corti);
   - Funzione vitale: impediscono l'instabilità per taglio ciclica dell'anima (*shear web buckling*), consentendo al materiale di raggiungere l'incrudimento plastico stabile senza cali isteretici.
2. **Ritegni Torsionali ad Entrambe le Estremità del Link**:
   - Sia l'ala superiore che l'ala inferiore devono essere bloccate contro la traslazione fuori piano per impedire lo sbandamento torsionale durante i grandi cicli plastici.

#### 3. Gerarchia delle Resistenze negli EBF:
Le membrature non dissipative (colonne, diagonali di controvento e la porzione di trave esterna al link) devono rimanere rigorosamente elastiche e sono dimensionate per resistere alle massime sollecitazioni erogate dal link incrudito:
- Per link corti:
  $$V_{design} = 1.50 \cdot \gamma_{ov} \cdot V_{p,link} \quad (\gamma_{ov} = 1.25 \implies V_{design} \approx 1.875 V_p)$$
  (dove il fattore $1.50$ tiene conto del potente incrudimento plastico dell'acciaio a taglio).

---

> [!NOTE]
> ### Esempio Numerico Breve (Classificazione e Calcolo Link EBF):
> Link ricavato da profilo **HE 240 A** in acciaio S275 ($f_y = 275\text{ MPa}$, $f_{yd} = 261.9\text{ MPa}$). Dati profilo: $h = 230\text{ mm}$, $b = 240\text{ mm}$, $t_w = 7.5\text{ mm}$, $t_f = 12.0\text{ mm}$, $A_v \approx 2520\text{ mm}^2$, $W_{pl,y} = 744.6\text{ cm}^3 = 744600\text{ mm}^3$. Lunghezza del link $e = 750\text{ mm}$.
> 1. Capacità a taglio plastico:
>    $$V_p = \frac{A_v \cdot (f_y / \sqrt{3})}{\gamma_{M0}} = \frac{2520 \cdot 158.77}{1.05} = 381048\text{ N} = 381.0\text{ kN}$$
> 2. Capacità a momento plastico:
>    $$M_p = \frac{W_{pl,y} \cdot f_y}{\gamma_{M0}} = \frac{744600 \cdot 275}{1.05} = 195.0 \cdot 10^6\text{ Nmm} = 195.0\text{ kNm}$$
> 3. Rapporto $M_p / V_p$:
>    $$\frac{M_p}{V_p} = \frac{195.0\text{ kNm}}{381.0\text{ kN}} = 0.5118\text{ m} = 511.8\text{ mm}$$
> 4. Lunghezza limite link corto:
>    $$e_s = 1.60 \cdot 511.8\text{ mm} = 818.9\text{ mm}$$
>    Poiché la lunghezza reale $e = 750\text{ mm} < 818.9\text{ mm} \implies$ **Il link è CORTO (Shear Link)**.
> 5. Prestazione: dissipa a taglio puro, ammette la massima distorsione angolare $\gamma_p = 0.08\text{ rad}$ e richiede irrigidimenti d'anima verticali fitti saldati a passo $\le 200\text{ mm}$.

---

## MODULO 9: Impalcato nel Piano, Diaframmi Sismici e Pioli Connettori Nelson

### 9.1. Ruolo Strutturale del Diaframma di Piano
Nelle costruzioni soggette a forze sismiche, l'impalcato (solaio) non svolge soltanto il compito gravitazionale di sorreggere i carichi verticali, ma funge da **diaframma orizzontale rigido**:
1. **Ripartizione delle Forze Orizzontali**: raccoglie le forze d'inerzia generate dalle masse distribuite di piano ($F_i = m_i \cdot a_i$) e le ridistribuisce ai sistemi verticali sismo-resistenti (telai a momento e controventi) proporzionalmente alla loro rigidezza laterale traslazionale e torsionale.
2. **Ipotesi di Diaframma Infinitamente Rigido nel Proprio Piano**:
   - Comportamento cinematico a corpo rigido 2D: l'impalcato ha solo **3 gradi di libertà per piano** (due traslazioni nel piano $u_x, u_y$ e una rotazione attorno all'asse verticale $\theta_z$);
   - Affinché tale ipotesi sia valida secondo NTC 2018 (§7.2.6), il solaio deve avere:
     - Una soletta collaborante in calcestruzzo armato gettata in opera di spessore minimo $t \ge 40\text{–}50\text{ mm}$;
     - Rete elettrosaldata di armatura continua (almeno $\Phi 6/200 \times 200\text{ mm}$ o $\Phi 8/200 \times 200\text{ mm}$) adeguatamente ancorata ai cordoli perimetrali;
     - Un adeguato sistema di connessione a taglio tra travi metalliche e soletta (pioli connettori a taglio).

---

### 9.2. Pioli Connettori a Taglio Tipo Nelson (Studs)
Nelle strutture miste acciaio-calcestruzzo con lamiera grecata, i connettori cilindrici a piolo con testa tipo Nelson trasferiscono lo scorrimento longitudinale all'interfaccia acciaio-calcestruzzo.
- **Resistenza a Taglio di Calcolo del Singolo Piolo $P_{Rd}$ (Eurocodice 4 / NTC 2018)**:
  La resistenza di calcolo è il minimo tra la rottura per taglio dell'acciaio del piolo e lo schiacciamento del calcestruzzo circostante:
  $$P_{Rd} = \min \left( P_{Rd,1} = \frac{0.80 \cdot f_u \cdot \frac{\pi d^2}{4}}{\gamma_V} \; ; \; P_{Rd,2} = \frac{0.29 \cdot \alpha \cdot d^2 \cdot \sqrt{f_{ck} \cdot E_{cm}}}{\gamma_V} \right)$$
  dove:
  - $d$: diametro del gambo del piolo (tipicamente $16\text{ mm}$ o $19\text{ mm}$);
  - $f_u$: tensione di rottura dell'acciaio del piolo ($\ge 450\text{ MPa}$, solitamente $500\text{ MPa}$);
  - $\gamma_V = 1.25$: coefficiente parziale di sicurezza del connettore;
  - $\alpha = 1.0$ se l'altezza del piolo $h_{sc} / d \ge 4$;
  - $f_{ck}, E_{cm}$: parametri elastici del calcestruzzo della soletta.
- **Coefficiente Riduttivo per Lamiere Grecate con Nervature Trasversali $k_t$**:
  Se i pioli sono saldati attraverso una lamiera grecata con nervature ortogonali alla trave:
  $$P_{Rd,ridotto} = k_t \cdot P_{Rd} \quad \text{con } k_t = \frac{0.70}{\sqrt{N_r}} \frac{b_0}{h_p} \left( \frac{h_{sc}}{h_p} - 1 \right) \le 1.00$$
  ($N_r$: numero di pioli per nervatura; $b_0$: larghezza media nervatura; $h_p$: altezza greca).

---

### 9.3. Funzionamento Statico del Diaframma: Correnti e Collettori
Il diaframma di piano può essere schematizzato come una **trave a parete piena orizzontale a mensola o su più appoggi**:
1. **Correnti Tesi e Compressi (Chords / Cordoli di Piano)**:
   - Posizionati lungo i bordi perimetrali dell'impalcato ortogonali alla direzione del sisma;
   - Assorbono la coppia interna del momento flettente d'impalcato nel piano:
     $$T_{cordolo} = C_{cordolo} = \frac{M_{piano}}{B_{edificio}}$$
   - Sono costituiti dalle travi perimetrali d'acciaio verificate a sforzo assiale o da armature aggiuntive collocate nei cordoli di getto della soletta.
2. **Travi-Collettore (Collectors / Struts and Ties)**:
   - Travi d'impalcato allineate direttamente con le linee dei controventi sismo-resistenti verticali;
   - Compito essenziale: raccolgono il flusso di taglio diffuso sull'ampia superficie dell'impalcato e lo "convogliano" come forza assiale concentrata direttamente alle testate dei controventi (o alle pareti sismiche). Devono essere verificate a forte sforzo assiale di trazione e compressione sommato ai carichi gravitazionali.

---

### 9.4. Criteri di Regolarità Strutturale secondo NTC 2018 (§7.2)
Per garantire una risposta sismica prevedibile ed evitare amplificazioni dinamiche torsionali:
- **Regolarità in Pianta**:
  1. *Simmetria*: configurazione geometrica approssimativamente simmetrica rispetto a due direzioni ortogonali;
  2. *Compattezza e Convessità*: forma in pianta compatta (rettangolare o poligonale regolare); eventuali rientranze non devono superare il $25\%$ della dimensione totale;
  3. *Rapporto tra i lati*: $L_{max} / L_{min} < 4.0$;
  4. *Rigidezza di piano*: impalcato con soletta continua indeformabile;
  5. *Eccentricità accidentale di norma*: il centro di massa di ciascun piano deve essere traslato di un'eccentricità accidentale pari a **$\pm 5\%$ della dimensione dell'edificio** ($e_{ax} = \pm 0.05 L_x$, $e_{ay} = \pm 0.05 L_y$) per coprire le incertezze sulla distribuzione reale dei carichi e la rotazione torsionale del terreno.
- **Regolarità in Altezza**:
  1. Tutti i sistemi sismo-resistenti (colonne, controventi) devono proseguire senza interruzioni dalla fondazione alla sommità;
  2. La massa e la rigidezza di piano devono ridursi gradualmente dal basso verso l'alto (variazione di rigidezza tra piani adiacenti entro il $30\%$, variazione di massa entro il $10\%$);
  3. Assoluta assenza di piani a rigidezza bruscamente ridotta (*piano soffice*).

---

## MODULO 10: Vademecum Rapido d'Esame, Formulario Salvavita e 10 Domande Trabocchetto

### 10.1. Formulario Compatto "Salvavita"

| Meccanismo / Verifica | Formula di Progetto / Limite Normativo | Parametri e Unità di Misura |
| :--- | :--- | :--- |
| **Carico Neve** | $q_s = \mu_i \cdot q_{sk} \cdot c_e \cdot c_t$ | $[kN/m^2]$, $\mu_1 = 0.8$, $q_{sk}$ da zona e quota $a_s$ |
| **Pressione Vento** | $p = q_b \cdot c_e(z) \cdot c_p \cdot c_d$ | $[kN/m^2]$, $q_b = 0.5 \rho v_b^2$, $c_{pe} = +0.8 / -0.4$ |
| **SLU Flessione C.A.** | $M_{Rd} = A_s f_{yd} (d - 0.4 x)$ | $x = \frac{A_s f_{yd}}{0.8 b f_{cd}}$, $\xi = x/d \le 0.45$ (CD"B") |
| **Taglio C.A. (Staffe)** | $V_{Rd,s} = 0.9 d \frac{A_{sw}}{s} f_{yd} \cot\theta$ | $1.0 \le \cot\theta \le 2.5$, $V_{Ed} \le \min(V_{Rd,s}; V_{Rd,c})$ |
| **Passo Staffe C.A. Z. Critica** | $s \le \min(h/4 ; 175\text{ mm} ; 8 \Phi_L)$ | Passo **fitto**, estensione $L_{cr} = 2h$ |
| **Passo Staffe C.A. Z. Corrente**| $s \le \min(0.75 d ; 250\text{ mm} ; 12 \Phi_L)$| Passo **rado** in campata |
| **Torsione C.A. (Rausch)** | $\frac{A_{st}}{s} = \frac{T_{Ed}}{2 A_k f_{yd} \cot\theta}$ | $t_{ef} = 2c$, $\sum A_{sl} = \frac{T_{Ed} u_k \cot\theta}{2 A_k f_{yd}}$ |
| **Asta Compressa Acciaio** | $N_{b,Rd} = \frac{\chi A f_y}{\gamma_{M1}}$ | $\bar{\lambda} = \frac{\lambda}{\lambda_1}$, curve instabilità $a, b, c, d$ |
| **Momento Plastico Acciaio** | $M_{pl,Rd} = \frac{W_{pl} f_y}{\gamma_{M0}}$ | $[kNm]$, sezioni Classe 1 e 2 |
| **Taglio Bullone** | $F_{v,Rd} = \frac{\alpha_v f_{ub} A}{\gamma_{M2}}$ | $\alpha_v = 0.6$ (8.8 su filetto), $\gamma_{M2} = 1.25$ |
| **Rifollamento Bullone** | $F_{b,Rd} = \frac{k_1 \alpha_b f_u d t}{\gamma_{M2}}$ | $\alpha_b$ e $k_1$ da distanze $e_1, e_2, p_1, p_2$ |
| **Saldatura Cordone Angolo** | $\sqrt{\sigma_\perp^2 + 3(\tau_\perp^2 + \tau_\parallel^2)} \le \frac{f_u}{\beta_w \gamma_{M2}}$ | $\sigma_\perp \le 0.9 \frac{f_u}{\gamma_{M2}}$, $\beta_w = 0.85$ (S275) |
| **Gradino Scala Metallica** | $M_{Ed} = 1.50 \cdot (2\text{ kN}) \cdot L$ | Carico concentrato $2\text{ kN}$ in punta, $f \le L/300$ |
| **Gerarchia Nodi MRF** | $\sum M_{c,pl,Rd} \ge 1.30 \sum M_{b,pl,Rd}$ | Colonna forte – Trave debole |
| **Drift SLD (Spolamento)** | $d_r = d_e \cdot q \le 0.005 h$ | Tamponamenti rigidi fragili |
| **CBF Chevron Sbilanciamento**| $\Delta N_v = (N_{pl,Rd} - N_{b,Rd}) \sin\theta$ | Forza verticale applicata in mezzeria trave |
| **EBF Link Corto** | $e \le 1.60 \frac{M_p}{V_p} \implies \gamma_p \le 0.08\text{ rad}$ | Dissipa a taglio puro, irrigidimenti d'anima fitti |
| **EBF Link Lungo** | $e \ge 3.00 \frac{M_p}{V_p} \implies \gamma_p \le 0.02\text{ rad}$ | Dissipa a flessione pura alle estremità |
| **Connettore Piolo Nelson** | $P_{Rd} = \min(P_{Rd,1}; P_{Rd,2})$ | Taglio piolo vs Schiacciamento cls soletta |

---

### 10.2. Le 10 Domande Trabocchetto Più Frequenti del Prof. Landolfo con Risposta Esatta

#### 1. Perché nei controventi eccentrici (EBF) la formula del link divide per il taglio e non per il momento?
> **Risposta Esatta**: La lunghezza $e$ è una dimensione lineare $[m]$. Poiché il momento plastico ha dimensione $[kN \cdot m]$ e il taglio plastico $[kN]$, il rapporto $\frac{M_p}{V_p}$ restituisce una lunghezza espressa in metri. Dividere per il momento darebbe un numero puro, dimensionalmente privo di significato fisico.

#### 2. Nei controventi a V (Chevron), perché la trave deve essere verificata in campo elastico e non può essere dissipativa?
> **Risposta Esatta**: Perché quando la diagonale compressa si instabilizza post-buckling ($N_{b,Rd}$), la diagonale tesa continua a caricarsi fino a $N_{pl,Rd}$. La differenza genera una **forza sbilanciata verticale concentrata** $\Delta N_v = (N_{pl,Rd} - N_{b,Rd})\sin\theta$ sulla mezzeria della trave. Se la trave cedesse plasticamente, si formerebbe un cinematismo instabile di piano; la trave deve quindi rimanere elastica per garantire l'equilibrio del sistema.

#### 3. Perché la normativa NTC 2018 vieta i controventi a K in zona sismica?
> **Risposta Esatta**: Nei controventi a K le diagonali convergono a metà altezza del pilastro. La forza sbilanciata orizzontale scaricata dalla diagonale post-buckling agirebbe a metà colonna, innescando una cerniera plastica flessionale nel pilastro e conducendo rapidamente al collasso catastrofico di piano.

#### 4. Dove si mettono le staffe fitte nel cemento armato e perché?
> **Risposta Esatta**: Le staffe fitte ($s \le \min(h/4; 175\text{ mm}; 8 \Phi_L)$) si collocano obbligatoriamente nelle **zone critiche** (lunghezza $2h$ alle estremità di travi e pilastri), dove si sviluppano le cerniere plastiche sismiche, per confinare il nucleo di calcestruzzo compresso, impedire l'instabilità delle barre longitudinali compresse e assorbire il massimo taglio da gerarchia delle resistenze. In zona corrente il passo è più rado ($s \le \min(0.75d; 250\text{ mm}; 12 \Phi_L)$).

#### 5. Che cos'è l'altezza di gola "a" in un cordone d'angolo e qual è la formula di verifica di Von Mises?
> **Risposta Esatta**: L'altezza di gola $a$ è l'altezza del triangolo isoscele inscritto nella sezione trasversale del cordone di saldatura. La verifica direzionale impone: $\sqrt{\sigma_\perp^2 + 3(\tau_\perp^2 + \tau_\parallel^2)} \le \frac{f_u}{\beta_w \gamma_{M2}}$ e $\sigma_\perp \le 0.9 \frac{f_u}{\gamma_{M2}}$, dove $\beta_w$ vale $0.80$ per S235, $0.85$ per S275 e $0.90$ per S355.

#### 6. Perché le scale metalliche devono essere disconnesse sismicamente dall'edificio?
> **Risposta Esatta**: Perché la scala a soletta inclinata o cosciali triangolari possiede una rigidezza membranale nel proprio piano enormemente superiore a quella dei telai dell'edificio. Se collegata rigidamente, si comporterebbe come un controvento rigido non dimensionato per il sisma, attirando quote sproporzionate di taglio sismico e generando violente torsioni d'impalcato. Si adotta quindi lo schema a scala sospesa con tiranti o su montanti autonomi con giunto sismico.

#### 7. Per quale carico concentrato va verificato il gradino a sbalzo metallico?
> **Risposta Esatta**: Oltre al carico distribuito da folla ($4\text{ kN/m}^2$), la norma NTC 2018 impone la verifica per un **carico concentrato isolato di $2.00\text{ kN}$** applicato sul bordo libero più sfavorevole del gradino (impronta $50 \times 50\text{ mm}$), controllando sia la flessione e torsione allo SLU che la deformabilità elastica allo SLE ($f \le L/300$) per evitare sgradevoli vibrazioni sotto il passo dell'utente.

#### 8. Quali sono i tre modi di collasso del modello a T-stub nei collegamenti bullonati?
> **Risposta Esatta**: 
> - **Modo 1**: plasticizzazione completa della piastra di flangia con formazione di 4 cerniere plastiche (meccanismo duttile, nessun sovraccarico sui bulloni);
> - **Modo 2**: parziale plasticizzazione della flangia (2 cerniere) con comparsa delle forze di leva (*prying forces*) e successiva rottura a trazione dei bulloni;
> - **Modo 3**: rottura a trazione pura dei soli bulloni senza deformazione plastica della flangia (meccanismo fragile da evitare).

#### 9. Che cosa sono e a cosa servono le travi-collettore (collectors / struts-ties) nei diaframmi di piano?
> **Risposta Esatta**: Sono le travi d'impalcato allineate con le pareti sismiche o i controventi. Raccolgono il flusso continuo di taglio distribuito che scorre lungo la soletta collaborante rigida e lo trasferiscono come sforzo assiale diretto alle testate dei controventi verticali, evitando concentrazioni di fessurazione nel solaio.

#### 10. Perché nelle travi alveolari compaiono i momenti secondari di Vierendeel?
> **Risposta Esatta**: Perché in corrispondenza del foro dell'anima viene a mancare la continuità della parete per assorbire il taglio $V_{Ed}$. Il taglio è costretto a dividersi tra i due correnti a T superiore e inferiore ($V/2$ ciascuno), e moltiplicandosi per il semibraccio del foro ($d_0/2$) genera un momento flettente locale secondario che induce flessione e taglio parassiti nei correnti, da combinare con lo sforzo assiale globale.

---
*Fine del Compendio Definitivo d'Esame — Laboratorio di Tecnica delle Costruzioni.*
