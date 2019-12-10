# Sistemi Operativi - I Modulo

## News
- **Lezioni di Recupero**<br/>
Il giorno **giovedì 12/12/2019** dalle ore **11:00** alle ore **13:00** presso l'Aula T2 di Giurisprudenza [CU046] si svolgerà la prima delle due lezioni di recupero previste.<br/>
La seconda lezione di recupero avrà luogo **mercoledì 18/12/2019**, sempre in Aula T2, dalle ore **10:00** alle ore **12:00** .<br/>
-  **22/11/2019**<br/>
Durante la lezione di **venerdì 22/11** sarà dedicato uno spazio di **almeno 15 minuti** nel quale gli studenti saranno invitati a compilare il Questionario delle Opinioni degli Studenti (OPIS), tramite i propri dispositivi mobili.<br/>
Ulteriori dettagli e istruzioni sulle modalità di compilazione del questionario verranno forniti durante la lezione.<br/>
Si invitano gli studenti alla massima partecipazione.<br/>
-  **25/10/2019**<br/>
A causa dello sciopero nazionale dei trasporti, la lezione di Sistemi Operativi di **venerdì 25/10** terminerà in anticipo rispetto al solito, presumibilmente intorno alle **17:30**.

## Informazioni Generali

Benvenuti sul sito web del corso di Sistemi Operativi - I Modulo!

Il corso si svolge al primo semestre del secondo anno della [Laurea Triennale in Informatica della Sapienza Università di Roma](https://www.studiareinformatica.uniroma1.it/laurea).

Questo repository contiene il materiale didattico del corso sottoforma di slide PDF ed esercizi relativi all'anno accademico 2019/20, limitatamente al II canale (M-Z).

### Orario delle Lezioni
- **Martedì** dalle **17:00** alle **19:00** (Aula III - edificio MATEMATICA G. CASTELNUOVO [CU006])
- **Venerdì** dalle **16:00** alle **19:00** (Aula III - edificio MATEMATICA G. CASTELNUOVO [CU006])

### Orario di Ricevimento
- **Giovedì** dalle **10:00** alle **12:00** in viale Regina Elena 295 c/o Palazzina G, III piano, stanza G49

### Pagina Moodle del Corso
Gli studenti devono registrarsi alla pagina Moodle che si trova al seguente indirizzo web, utilizzando le stesse credenziali (username/password) per l'accesso ai servizi Wi-Fi e Infostud: https://elearning.uniroma1.it/course/view.php?id=8017

### Obiettivi del Corso
I sistemi operativi sono parte essenziale di un sistema di calcolo e costituiscono l'esempio ideale di un concetto fondamentale e trasversale all'intero percorso di studio in Informatica, ossia quello dell'_astrazione_. 

Più specificamente, grazie al processo di virtualizzazione delle risorse fisiche, i sistemi operativi consentono ai programmatori di sviluppare software applicativi evitando di doversi concentrare sui dettagli della macchina hardware, garantendo infine un miglior livello di usabilità da parte dell'utente finale. È pertanto necessario che uno studente di Informatica possieda le basi per comprendere le principali problematiche relative all'efficace progettazione (e utilizzo) di un software altamente complesso come quello di un sistema operativo moderno.

Allo scopo di fornire tali basi, durante il corso verranno discussi alcuni concetti fondamentali relativi ai sistemi operativi cosiddetti _general purpose_ (tipicamente installati su PC/laptop) e alle loro funzionalità primarie (gestione dei processori, della memoria e dei dispositivi di ingresso/uscita). Verranno altresì forniti cenni sulle caratteristiche principali dei sistemi operativi installati sui dispositivi mobili (tablet/smartphone).

I concetti generali previsti per il corso, ampiamente coperti dal materiale bibliografico consigliato, verranno discussi a lezione in maniera relativamente indipendente da specifici sistemi operativi. Essi saranno comunque esemplificati facendo riferimento a sistemi operativi noti e di utilizzo comune, come ad esempio UNIX/Linux, Windows, Mac, Android, iOS, etc.

### Modalità di Esame
Per il superamento dell'esame è prevista una **prova scritta** a cui può far seguito una prova orale _opzionale_ (a discrezione del docente).

### Libri di Testo Consigliati
Sebbene non obbligatori ai fini del superamento dell'esame, i seguenti libri di testo (preferibilmente in lingua inglese) costituiscono una fonte utile per assimilare più approfonditamente i concetti esposti durante le lezioni:
- _Operating System Concepts_ [Silberschatz _et al._];
- _Modern Operating Systems_ [Tanenbaum _et al._];
- _Operating Systems: Three Easy Pieces_ [Remzi] [available online](http://pages.cs.wisc.edu/~remzi/OSTEP/).

I primi due libri sono comunque disponibili anche in versione italiana:
- _Sistemi Operativi. Concetti ed Esempi_ [Silberschatz _et al._];
- _I Moderni Sistemi Operativi_ [Tanenbaum _et al._]
 
<hr>

## Syllabus
**Introduzione**
- Concetti di base
- Storia dei sistemi operativi
- Relazione tra macchina fisica (HW) e sistemi operativi
- Struttura dei sistemi operativi

**Gestione dei Processi**
- Processi
- CPU Scheduling
- Threads
- Sincronizzazione
- Deadlock

**Gestione della memoria**
- Memoria principale (RAM)
- Memoria virtuale

**Gestione dei sistemi di I/O**
- Dispositivi di memoria di massa
- Interfaccia del file system
- Implementazione del file system
- Sistemi di I/O

**Concetti avanzati**
- Protezione
- Sicurezza
- Sistemi distribuiti
- Sistemi per dispositivi mobili

<hr>

## Materiale Didattico

| Lezione \# | Data | Argomento                                     | Materiale      | 
|------------|------|-----------------------------------------------|----------------|
| Lezione 1  | 24/09/2019 | Introduzione | [slides: <a href="./lectures/slides/01_Intro.pdf" target="_blank">PDF</a>] |
| Lezione 2  | 27/09/2019 | Relazione tra Sistema Operativo e Hardware | [slides: <a href="./lectures/slides/02_OS_and_Computer_Architecture.pdf" target="_blank">PDF</a>]|
| Lezioni 3 - 4  | 01/10/2019 - 04/10/2019 | Struttura di un Sistema Operativo | [slides: <a href="./lectures/slides/03_OS_Structure.pdf" target="_blank">PDF</a>]|
| Lezioni 5 - 6  | 08/10/2019 - 11/10/2019 | Processi | [slides: <a href="./lectures/slides/04_Processes.pdf" target="_blank">PDF</a>] [<a href="./code/processes.tgz" download="processes.tgz">code</a>]|
| Lezione 7  | 15/10/2019 | Scheduling della CPU (1) | [slides: <a href="./lectures/slides/05_CPU_Scheduling_1.pdf" target="_blank">PDF</a>] |
| Lezioni 8 - 9 | 18/10/2019 - 22/10/2019 | Scheduling della CPU (2) | [slides: <a href="./lectures/slides/05_CPU_Scheduling_2.pdf" target="_blank">PDF</a>]|
| Lezioni 10 - 11 | 25/10/2019 - 29/10/2019 | Threads | [slides: <a href="./lectures/slides/06_Threads.pdf" target="_blank">PDF</a>] [<a href="./code/threads.tgz" download="threads.tgz">code</a>]|
| Lezione 12 | 12/11/2019 | Sincronizzazione tra Processi/Thread (1) | [slides: <a href="./lectures/slides/07_Synchronization_1.pdf" target="_blank">PDF</a>]|
| Lezione 13 | 15/11/2019 | Sincronizzazione tra Processi/Thread (2) | [slides: <a href="./lectures/slides/07_Synchronization_2.pdf" target="_blank">PDF</a>] [<a href="./code/synchronization.tgz" download="synchronization.tgz">code</a>]|
| Lezioni 14 - 15 | 19/11/2019 - 22/11/2019 | Deadlock | [slides: <a href="./lectures/slides/08_Deadlock.pdf" target="_blank">PDF</a>] |
| Lezione 16 | 26/11/2019 | Esercitazione I | [slides: <a href="./exercises/Questions_I.pdf" target="_blank">PDF</a>] |
| Lezione 17 | 29/11/2019 | Gestione della Memoria (1) | [slides: <a href="./lectures/slides/09_Memory_Management.pdf" target="_blank">PDF</a>] |
| Lezioni 18 - 19 | 03/12/2019 - 06/12/2019 | Gestione della Memoria (2) | [slides: <a href="./lectures/slides/10_Memory_Management_Paging.pdf" target="_blank">PDF</a>] |

