# Sistemi Operativi I - 2023-24 (I Canale)

[News](#News) | [Informazioni Generali](#Informazioni-Generali) | [Syllabus](#Syllabus) | [Materiale Didattico](#Materiale-Didattico) | [Anni Precedenti](#Anni-Precedenti)

## News
- **ANNUNCIO:** La lezione dello **02/11/2023** si svolgerà da remoto via Zoom. Per ulteriori dettagli, si prega di consultare il messaggio sul forum della pagina Moodle del corso.
- **IMPORTANTE:** La lezione del **31/10/2023** è annullata.
- Si invitano tutti gli studenti intenzionati a frequentare il corso ad iscriversi **quanto prima** alla pagina Moodle del corso, [come indicato di seguito](#Pagina-Moodle-del-Corso).
- L'inizio delle lezioni è fissato per il giorno **martedì 3 ottobre 2023**, e l'orario completo degli insegnamenti del I semestre a.a. 2023-24 è disponibile al seguente [link](https://docs.google.com/spreadsheets/d/e/2PACX-1vSAhLT3Qu3Rj93yibn9yJceDgutT6rMzD5LDpF4rSbhJNsSnZLPJsHpDL4wXEF2S4aEFuFQWGKjrm_T/pubhtml).

## Informazioni Generali

Benvenuti sul sito web del corso di Sistemi Operativi - I Modulo!

Il corso si svolge al primo semestre del secondo anno della [Laurea Triennale in Informatica della Sapienza Università di Roma](https://www.studiareinformatica.uniroma1.it/laurea).

Questo repository contiene il materiale didattico del corso sottoforma di slide PDF ed esercizi relativi all'anno accademico 2023-24, limitatamente al I canale.

### Orario delle Lezioni
- **Martedì** dalle **16:00** alle **19:00**
- **Giovedì** dalle **13:00** alle **15:00**

Entrambe le lezioni si svolgeranno nell'Aula III - Edificio "V. Caglioti" c/o Dipartimento di Chimica [[map](https://goo.gl/maps/EtRwnoZbxySaRW6dA)]

### Pagina Moodle del Corso
Gli studenti **devono** registrarsi alla pagina Moodle che si trova al seguente indirizzo web, utilizzando le stesse credenziali istituzionali (username/password) per l'accesso ai servizi Wi-Fi e Infostud: https://elearning.uniroma1.it/course/view.php?id=16966

### Orario di Ricevimento
Per garantire la massima flessibilità, è preferibile concordare con il docente un ricevimento su appuntamento (in presenza o a distanza). Si prega di inviare la propria richiesta via email all'indirizzo: tolomei@di.uniroma1.it, indicando come soggetto "_SO-I 2023-24: Ricevimento_".<br/> 
I ricevimenti in presenza si terranno nell'ufficio del docente, presso la Stanza 106 al I piano dell'Edificio "E" situato in Viale Regina Elena, 295 ([map](https://goo.gl/maps/5dSuQbvaeqXePV9y6)).


### Contatti Docente
- Email: tolomei@di.uniroma1.it
- Sito web: https://www.di.uniroma1.it/~tolomei
- Bacheca Sapienza: https://corsidilaurea.uniroma1.it/it/users/gabrieletolomeiuniroma1it
- Ufficio: Stanza 106 I piano Edificio "E" c/o Viale Regina Elena, 295 ([map](https://goo.gl/maps/5dSuQbvaeqXePV9y6))

### Obiettivi del Corso
I sistemi operativi sono parte essenziale di un sistema di calcolo e costituiscono l'esempio ideale di un concetto fondamentale e trasversale all'intero percorso di studio in Informatica, ossia quello dell'_astrazione_. 

Più specificamente, grazie al processo di virtualizzazione delle risorse fisiche, i sistemi operativi consentono ai programmatori di sviluppare software applicativi evitando di doversi concentrare sui dettagli della macchina hardware, garantendo infine un miglior livello di usabilità da parte dell'utente finale. È pertanto necessario che uno studente di Informatica possieda le basi per comprendere le principali problematiche relative all'efficace progettazione (e utilizzo) di un software altamente complesso come quello di un sistema operativo moderno.

Allo scopo di fornire tali basi, durante il corso verranno discussi alcuni concetti fondamentali relativi ai sistemi operativi cosiddetti _general purpose_ (tipicamente installati su PC/laptop) e alle loro funzionalità primarie (gestione dei processori, della memoria e dei dispositivi di ingresso/uscita). Verranno altresì forniti cenni sulle caratteristiche principali dei sistemi operativi installati sui dispositivi mobili (tablet/smartphone).

I concetti generali previsti per il corso, ampiamente coperti dal materiale bibliografico consigliato, verranno discussi a lezione in maniera relativamente indipendente da specifici sistemi operativi. Essi saranno comunque esemplificati facendo riferimento a sistemi operativi noti e di utilizzo comune, come ad esempio UNIX/Linux, Windows, Mac, Android, iOS, etc.

### Prerequisiti
- Concetti fondamentali di architetture degli elaboratori
- Fondamenti di programmazione

### Modalità di Esame
Per il superamento dell'esame è prevista una **prova scritta**, basata su un quiz Moodle a risposta multipla. Tutti coloro che superano la prova scritta con un punteggio _compreso tra **15** e **17**_ (estremi inclusi) sono ammessi, nonché **obbligati**, a sostenere la successiva **prova orale**. Coloro che, invece, ottengono un punteggio sufficiente (_maggiore o uguale a **18**_) alla prova scritta possono decidere di confermare il voto ottenuto **oppure** sostenere un'ulteriore prova orale integrativa opzionale.

### Testi Consigliati
Sebbene **non** obbligatori ai fini del superamento dell'esame, i seguenti libri di testo (preferibilmente in lingua inglese) costituiscono una fonte utile per assimilare più approfonditamente i concetti esposti durante le lezioni:
- _Operating System Concepts_ [Silberschatz _et al._];
- _Modern Operating Systems_ [Tanenbaum _et al._];
- _Operating Systems: Three Easy Pieces_ [Remzi] (<a href="http://pages.cs.wisc.edu/~remzi/OSTEP/" target="_blank">disponibile gratuitamente online</a>).

I primi due libri sono comunque disponibili anche in versione italiana:
- _Sistemi Operativi. Concetti ed Esempi_ [Silberschatz _et al._];
- _I Moderni Sistemi Operativi_ [Tanenbaum _et al._]
 
<hr>

## Syllabus
**Parte I: Introduzione**
- Concetti di base
- Storia dei sistemi operativi
- Relazione tra macchina fisica (HW) e sistemi operativi
- Struttura dei sistemi operativi

**Parte II: Gestione dei Processi**
- Processi
- CPU Scheduling
- Threads

**Parte III: Sincronizzazione tra Processi/Thread**
- Strumenti per la Sincronizzazione
- Esempi di Sincronizzazione
- Deadlock

**Parte IV: Gestione della Memoria**
- Memoria Principale (RAM)
- Memoria Virtuale

**Parte V: Gestione dei Sistemi di I/O**
- Dispositivi di Memoria di Massa
- Sistemi di I/O

**Parte VI: File System**
- Interfaccia del File System
- Implementazione del File System
- Struttura del File System

**Parte VII: Advanced Topics**
- Protezione
- Sicurezza
- Sistemi distribuiti
- Sistemi per dispositivi mobili

<hr>

## Materiale Didattico

| Lezione \# | Data | Argomento                                     | Materiale      | 
|------------|------|-----------------------------------------------|----------------|
| Lezioni 1-2  | 03/10/2023-05/10/2023 | Introduzione e Richiami di Concetti Base | [slides: <a href="./lectures/slides/Introduction.pdf" target="_blank">PDF</a>] |
| Lezione 3  | 10/10/2023 | Relazione tra Sistema Operativo e Macchina Fisica | [slides: <a href="./lectures/slides/Computer_Architecture_and_OS_Structures.pdf" target="_blank">PDF</a>]|
| Lezione 4  | 12/10/2023 | Spazio di Indirizzamento Logico e PCB | [slides: <a href="./lectures/slides/Process_Virtual_Address_Space_and_PCB.pdf" target="_blank">PDF</a>] |
| Lezione 5  | 17/10/2023 | Concetti Base della Gestione dei Processi | [slides: <a href="./lectures/slides/Basics_of_OS_Process_Management.pdf" target="_blank">PDF</a>] [<a href="./code/processes.tgz" download="processes.tgz">code</a>]|
| Lezione 6  | 19/10/2023 | Scheduling della CPU (Parte I) | [slides: <a href="./lectures/slides/CPU_Scheduling_1.pdf" target="_blank">PDF</a>] |
| Lezioni 7-8  | 24/10/2023-26/10/2023 | Scheduling della CPU (Parte II) | [slides: <a href="./lectures/slides/CPU_Scheduling_2.pdf" target="_blank">PDF</a>] |
| Lezione 9  | 02/11/2023 | Threads | [slides: <a href="./lectures/slides/Threads.pdf" target="_blank">PDF</a>] |
| Lezione 10  | 07/11/2023 | Implementazione dei Thread| [slides: <a href="./lectures/slides/Thread_Implementation.pdf" target="_blank">PDF</a>] [<a href="./code/threads.tgz" download="threads.tgz">code</a>]|
| Lezione 11 | 09/11/2023 | Sincronizzazione tra Processi/Thread | [slides: <a href="./lectures/slides/Synchronization.pdf" target="_blank">PDF</a>]|
| Lezioni 12-13 | 14/11/2023-16/11/2023  | Implementazione Meccanismi di Sincronizzazione | [slides: <a href="./lectures/slides/Synchronization_Implementation.pdf" target="_blank">PDF</a>] [<a href="./code/synchronization.tgz" download="synchronization.tgz">code</a>]|
| Lezioni 14-15 | 21/11/2023-24/11/2023 | Deadlock | [slides: <a href="./lectures/slides/Deadlock.pdf" target="_blank">PDF</a>] |
<!--| Lezione 16 | 29/11/2022 | Gestione della Memoria: Binding e Rilocazione | [slides: <a href="./lectures/slides/13_Memory_Management_Binding_and_Relocation.pdf" target="_blank">PDF</a>] |
| Lezione 17 | 01/12/2022 | Gestione della Memoria: Allocazione Contigua e Paginata | [slides: <a href="./lectures/slides/14-15_Memory_Management_Allocation.pdf" target="_blank">PDF</a>] |
| Lezione 18 | 06/12/2022 | Gestione della Memoria: Paginazione Avanzata (Segmentazione) | [slides: <a href="./lectures/slides/16_Advanced_Paging.pdf" target="_blank">PDF</a>] |
| Lezioni 19 - 20 | 06/12/2022 - 13/12/2022 | Memoria Virtuale | [slides: <a href="./lectures/slides/17-18_Virtual_Memory.pdf" target="_blank">PDF</a>] |
| Lezione 21 | 15/12/2022 | Dispositivi di Memoria di Massa | [slides: <a href="./lectures/slides/19_Mass_Storage.pdf" target="_blank">PDF</a>] |
| Lezione 22 | 20/12/2022 | Scheduling del Disco | [slides: <a href="./lectures/slides/20_Mass_Storage_Disk_Scheduling.pdf" target="_blank">PDF</a>] |
| Lezione 21 | 14/12/2020 | File System: Interfaccia e Implementazione | [slides: <a href="./lectures/slides/13_File_System.pdf" target="_blank">PDF</a>] |
| Lezioni 22 - 23 - 24 | 16/12/2020 - 21/12/2020 - 23/12/2020 | Esercitazioni | |
-->

# Anni Precedenti
In questa sezione è possibile accedere alle informazioni del corso relativamente agli anni accademici precedenti rispetto a quello corrente.

**NOTA:** _La directory che include il materiale didattico è **unica** e il suo contenuto può subire modifiche o aggiornamenti di anno in anno; pertanto, è possibile che vi siano discrepanze tra ciò che è presente su questo sito e ciò che invece è stato mostrato in un determinato anno, diverso da quello corrente._

- [2022-23](./oldest/2022-23.md)
- [2020-21](./oldest/2020-21.md)
- [2019-20](./oldest/2019-20.md)
