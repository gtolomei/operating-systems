# Sistemi Operativi - I Modulo (2020-2021)

[News](#News) | [Informazioni Generali](#Informazioni-Generali) | [Syllabus](#Syllabus) | [Materiale Didattico](#Materiale-Didattico) | [Anni Precedenti](#Anni-Precedenti)

## News
- <u><b>IMPORTANTE:</b></u> Gli studenti che seguiranno le lezioni in **modalità a distanza** sono pregati di pazientare ancora un po': non appena tutte le istruzioni per l'accesso alle videoconferenze online verranno stabilite in modo definitivo dagli organi competenti, saranno rese disponibili immediatamente su questa pagina.
- L'inizio delle lezioni del I semestre dell'a.a. 2020-21 è stato fissato per il giorno **~~23~~ 28 settembre 2020** (anziché 21 settembre come originariamente previsto), e l'orario è disponibile al seguente [link](https://www.studiareinformatica.uniroma1.it/laurea/orario-lezioni). Si invitano, inoltre, tutti gli studenti a prendere visione delle informazioni relative alla doppia modalità di svolgimento delle lezioni (in presenza e a distanza), pubblicate sulla [pagina web di Sapienza dedicata](https://www.uniroma1.it/it/notizia/covid-19-fase-3-lezioni-esami-e-lauree-presenza-e-distanza).
- Si invitano tutti gli studenti intenzionati a frequentare il corso - sia in presenza che a distanza - ad iscriversi **quanto prima** alla pagina Moodle del corso, [come indicato di seguito](#Pagina-Moodle-del-Corso).

## Informazioni Generali

Benvenuti sul sito web del corso di Sistemi Operativi - I Modulo!

Il corso si svolge al primo semestre del secondo anno della [Laurea Triennale in Informatica della Sapienza Università di Roma](https://www.studiareinformatica.uniroma1.it/laurea).

Questo repository contiene il materiale didattico del corso sottoforma di slide PDF ed esercizi relativi all'anno accademico 2020/21, limitatamente al II canale (M-Z).

### Orario delle Lezioni
- **Lunedì** dalle **15:00** alle **18:00** (Aula Cabibbo - Dipartimento di Fisica "E. Fermi" [edificio CU033])
- **Mercoledì** dalle **14:00** alle **16:00** (Aula Cabibbo - Dipartimento di Fisica "E. Fermi" [edificio CU033])

### Orario di Ricevimento
- **Martedì** dalle **14:00** alle **16:00** presso la stanza G39 situata al II piano della Palazzina G di viale Regina Elena 295<br>
(**NOTA:** _A causa dell'emergenza sanitaria tuttora in atto, i ricevimenti in presenza sono sospesi fino a nuova comunicazione. Tuttavia, è possibile richiedere l'appuntamento per un ricevimento a distanza via Google Meet o Zoom facendone esplicita richiesta via email all'indirizzo:_ tolomei@di.uniroma1.it)

### Pagina Moodle del Corso
Gli studenti **devono** registrarsi alla pagina Moodle che si trova al seguente indirizzo web, utilizzando le stesse credenziali istituzionali (username/password) per l'accesso ai servizi Wi-Fi e Infostud: https://elearning.uniroma1.it/course/view.php?id=11838

### Contatti Docente
- Email: tolomei@di.uniroma1.it
- Sito web: https://www.di.uniroma1.it/~tolomei
- Bacheca Sapienza: https://corsidilaurea.uniroma1.it/it/users/gabrieletolomeiuniroma1it

### Obiettivi del Corso
I sistemi operativi sono parte essenziale di un sistema di calcolo e costituiscono l'esempio ideale di un concetto fondamentale e trasversale all'intero percorso di studio in Informatica, ossia quello dell'_astrazione_. 

Più specificamente, grazie al processo di virtualizzazione delle risorse fisiche, i sistemi operativi consentono ai programmatori di sviluppare software applicativi evitando di doversi concentrare sui dettagli della macchina hardware, garantendo infine un miglior livello di usabilità da parte dell'utente finale. È pertanto necessario che uno studente di Informatica possieda le basi per comprendere le principali problematiche relative all'efficace progettazione (e utilizzo) di un software altamente complesso come quello di un sistema operativo moderno.

Allo scopo di fornire tali basi, durante il corso verranno discussi alcuni concetti fondamentali relativi ai sistemi operativi cosiddetti _general purpose_ (tipicamente installati su PC/laptop) e alle loro funzionalità primarie (gestione dei processori, della memoria e dei dispositivi di ingresso/uscita). Verranno altresì forniti cenni sulle caratteristiche principali dei sistemi operativi installati sui dispositivi mobili (tablet/smartphone).

I concetti generali previsti per il corso, ampiamente coperti dal materiale bibliografico consigliato, verranno discussi a lezione in maniera relativamente indipendente da specifici sistemi operativi. Essi saranno comunque esemplificati facendo riferimento a sistemi operativi noti e di utilizzo comune, come ad esempio UNIX/Linux, Windows, Mac, Android, iOS, etc.

### Modalità di Esame
Per il superamento dell'esame è prevista una **prova scritta**, basata su un quiz Moodle a risposta multipla. Tutti coloro che superano la prova scritta con un punteggio _compreso tra **15** e **17**_ (estremi inclusi) sono ammessi a sostenere la successiva **prova orale**. Coloro che, invece, ottengono un punteggio sufficiente (_maggiore o uguale a **18**_) alla prova scritta possono decidere di confermare il voto ottenuto **oppure** sostenere un'ulteriore prova orale integrativa.

### Libri di Testo Consigliati
Sebbene non obbligatori ai fini del superamento dell'esame, i seguenti libri di testo (preferibilmente in lingua inglese) costituiscono una fonte utile per assimilare più approfonditamente i concetti esposti durante le lezioni:
- _Operating System Concepts_ [Silberschatz _et al._];
- _Modern Operating Systems_ [Tanenbaum _et al._];
- _Operating Systems: Three Easy Pieces_ [Remzi] (<a href="http://pages.cs.wisc.edu/~remzi/OSTEP/" target="_blank">disponibile gratuitamente online</a>).

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
<!--| Lezione 1  | 24/09/2019 | Introduzione | [slides: <a href="./lectures/slides/01_Intro.pdf" target="_blank">PDF</a>] |
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
| Lezioni 20 - 21 | 10/12/2019 - 12/12/2019 | Memoria Virtuale | [slides: <a href="./lectures/slides/11_Virtual_Memory.pdf" target="_blank">PDF</a>] |
| Lezione 22 | 17/12/2019 | Dispositivi di Memoria di Massa | [slides: <a href="./lectures/slides/12_Mass_Storage.pdf" target="_blank">PDF</a>] |
| Lezione 23 | 18/12/2019 | File System: Interfaccia e Implementazione | [slides: <a href="./lectures/slides/13_File_System.pdf" target="_blank">PDF</a>] |-->

# Anni Precedenti
In questa sezione è possibile accedere alle informazioni del corso relativamente agli anni accademici precedenti rispetto a quello corrente.

**NOTA:** _La directory che include il materiale didattico è **unica** e il suo contenuto può subire modifiche o aggiornamenti di anno in anno; pertanto, è possibile che vi siano discrepanze tra ciò che è presente su questo sito e ciò che invece è stato mostrato in un determinato anno, diverso da quello corrente._

-   [2019-20](./oldest/2019-20.md)
