# 🎬 PoLive – Human-Computer Interaction Project

Progetto di gruppo del team **Bit-Event** per il corso di **Fondamenti di Human-Computer Interaction**, **Politecnico di Milano**.

**PoLive** è un'app mobile che raccoglie in un unico posto gli eventi universitari organizzati dal Politecnico e dalle associazioni studentesche, per collegare in modo più diretto chi organizza e chi partecipa.

> *We communicate. We catch. We connect.*

📄 **[Presentazione finale (PDF)](./src/C6/Presentazione_finale_BitEvent.pdf)**

## Il problema

Gli eventi universitari vengono comunicati attraverso email e tante pagine social diverse. Non esiste un canale centralizzato, così gli studenti faticano a scoprire cosa succede in università e le associazioni faticano a raggiungere il proprio pubblico.

## Il processo di design

Il progetto ha seguito l'intero ciclo di **design centrato sull'utente**, in sei consegne successive.

**1. Needfinding.** Abbiamo raccolto i bisogni degli utenti con un questionario esteso e generale e con interviste dirette, anche mirate a profili specifici. Ne è emersa la richiesta di un'unica piattaforma in cui gli eventi siano raccolti e categorizzati.

**2. Personas, scenario e journey map.** Abbiamo definito tre personas (un'utente base, un organizzatore di eventi e un utente estremo), uno scenario d'uso disegnato e una journey map che segue lo studente dalla frustrazione iniziale, quando cerca eventi su fonti sparse, fino alla condivisione dell'evento con gli amici.

**3. Ideazione e task analysis.** Tra le soluzioni proposte (schermi interattivi, maxischermo in piazza Leonardo, newsletter, annunci radio e altre) abbiamo scelto l'applicazione. Le funzionalità emerse sono state raggruppate per area e tradotte in tre task principali: ricercare un evento ed esprimere un giudizio per gli utenti, pubblicare un evento per gli organizzatori.

**4. Prototipazione.** Dagli storyboard dei task siamo passati a prototipi a fedeltà crescente: **low-fidelity**, **mid-fidelity** e infine **high-fidelity**.

**5. Valutazione euristica.** Il prototipo è stato valutato da un altro gruppo secondo le **10 euristiche di Nielsen**. Il giudizio complessivo è stato molto positivo sull'idea e sull'immediatezza dell'interfaccia; i problemi segnalati riguardavano soprattutto la coerenza tra le schermate, che abbiamo corretto nella versione successiva.

**6. Usability testing.** Abbiamo testato il prototipo high-fidelity con **7 utenti** su **7 task** reali, dalla consultazione del calendario alla creazione e pubblicazione di un evento come organizzatore. Ogni task è stato seguito da una domanda sulla facilità d'uso ispirata alla SEQ, e il test da un questionario ispirato alla **System Usability Scale**.

## Risultati

Il questionario post-test ha dato un punteggio medio di **82,14 / 100**, un risultato molto buono per un prototipo. Dalle domande conclusive sono emersi i tre punti su cui lavorare in vista di una vera implementazione: schermate più pulite e chiare, una distinzione più netta tra organizzatore e partecipante, e una separazione più evidente tra eventi passati e futuri.

## L'app

L'app si naviga da una barra inferiore con cinque sezioni:

- **Homepage**: eventi in evidenza e suggerimenti basati sulle proprie preferenze;
- **Ricerca**: barra di ricerca, eventi divisi per categoria e visualizzazione filtrata;
- **Preferiti**: gli eventi salvati;
- **Calendario**: gli eventi di un giorno, distinguendo iscrizioni, preferiti e altri eventi;
- **Area personale**: profilo e, per gli utenti verificati, gli strumenti da organizzatore per creare eventi, gestire le bozze e modificare gli eventi pubblicati.

Dalla schermata di un evento si possono consultare data, luogo e descrizione, mettere like o dislike, salvarlo nei preferiti e segnalare la propria partecipazione. Il progetto include anche una proposta di **architettura back-end**, con moduli separati per la gestione di utenti ed eventi.

## Il team

Andrea Grandieri, Giorgio Alotto, Matteo Cavalleri, Andrea Bellocci, Daniel Carrozzo, **Ilaria Brunelli**.

## Materiali

Tutte le consegne del progetto sono nella cartella [`src`](./src):

| Consegna | Contenuto |
|---|---|
| [C1](./src/C1) | Individuazione dei bisogni |
| [C2](./src/C2) | Raffinamento e focus |
| [C3](./src/C3) | Task e prototipi low-fidelity |
| [C4](./src/C4) | Prototipo mid-fidelity e README per i valutatori |
| [C5](./src/C5) | Valutazione euristica di gruppo |
| [C6](./src/C6) | Usability testing, prototipo high-fidelity e presentazione finale |

## Fonte e licenza

Questo repository è un fork del repository del gruppo, [AndreaGrandieri/BitEvent](https://github.com/AndreaGrandieri/BitEvent), distribuito con licenza MIT (vedi [`LICENSE`](./LICENSE)).
