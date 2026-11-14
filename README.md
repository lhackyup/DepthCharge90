# Depth Charge '90 🚀⚓

Un arcade retro ispirato ai classici giochi marittimi e spaziali dei primi anni '90, realizzato interamente in un **singolo file HTML5** con grafica Canvas pixel art proceduralmente renderizzata e motore sonoro sintetizzato in tempo reale tramite **Web Audio API** (nessun asset o dipendenza esterna).

---

## 🌟 Caratteristiche Principali

- **3 Scenari / Teatri Operativi Selezionabili**:
  - **Atlantic 1943 (`W43`)**: Seconda Guerra Mondiale con aerosilurante a elica, U-Boot, corazzate e cacciatorpediniere, cariche di profondità idrostatiche, contraerea e mare del Nord Atlantico.
  - **Modern 1990 (`M90`)**: Guerra navale moderna con jet d'interdizione, incrociatori lanciamissili, sottomarini nucleari d'attacco, bombe guidate ad alette e ciclo meteo dinamico (giorno, tramonto, notte, tempesta).
  - **Orbital 2190 (`S90`)**: Battaglia fantascientifica in cui l'alta orbita è il vuoto cosmico, il mare è la densa atmosfera planetaria, le navi di superficie sono stazioni e corazzate da guerra stellari e i sottomarini sono droni caccia atmosferici, armati di dardi al plasma e siluri fotonici.
- **Fisica a Doppio Mezzo**:
  - Moto parabolico gravitazionale con attrito aerodinamico nel mezzo superiore.
  - Impatto, smorzamento della velocità e trascinamento viscoso con affondamento terminale nel mezzo inferiore.
- **Campagna a 10 Settori Progressivi**:
  - Difficoltà crescente con bersagli multipli, bersagli corazzati con punti ferita multipli, manovre evasive (Settori 7+) e contrattacco nemico (contraerea Flak e siluri verticali).
- **Hall of Fame & High Scores Multipli**:
  - Top 5 piloti persistente in `localStorage`.
  - Inserimento a 3 lettere stile cabinato arcade con selezione slot e lettere.
  - Colonna `ERA` con colorazione tematica per scenario.
- **Controlli Flessibili**:
  - Supporto completo tastiera, mouse e touchscreen con tasti tattili su schermo per dispositivi mobili.

---

## 🕹️ Comandi di Gioco

| Azione | Tastiera | Mouse / Touchscreen |
| :--- | :--- | :--- |
| **Sgancia Bomba / Lancia Missione** | <kbd>Spazio</kbd> / <kbd>Invio</kbd> | Click su Canvas / Tasto `DROP` |
| **Rallenta / Accelera** | <kbd>←</kbd> / <kbd>→</kbd> oppure <kbd>A</kbd> / <kbd>D</kbd> | Tasti `SLOW` / `FAST` |
| **Inverti Rotta Velivolo** | <kbd>I</kbd> | Tasto `FLIP` |
| **Selezione Scenario / Teatro** | <kbd>T</kbd> (poi <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd>) | Pulsante `THEATER [T]` / Tocco su card |
| **Tabella Record (Hall of Fame)** | <kbd>H</kbd> | Pulsante `SCORES [H]` |
| **Attiva / Disattiva Audio** | Click su `SOUND` | Pulsante `SOUND` |

---

## 🚀 Come Giocare

Non serve alcun server o installazione:
1. Clona il repository:
   ```bash
   git clone https://github.com/lhackyup/DepthCharge90.git
   ```
2. Apri `depth_charge_90_retro_arcade.html` con qualsiasi browser moderno (Chrome, Firefox, Safari, Edge).
