# Scheda Personaggio D&D 5e Interattiva

Applicazione web interattiva per la gestione completa di personaggi di Dungeons & Dragons 5e.

Il progetto è una single-page web app pensata per essere utilizzata direttamente dal browser, senza installazione e senza backend.

---

## Link applicazione

https://gdr-sys.github.io/Scheda-personaggio-dnd-interattiva/

---

## Descrizione

Questa applicazione permette di gestire in modo completo una scheda personaggio D&D 5e, includendo:

- statistiche e bonus
- combattimento
- incantesimi
- inventario
- condizioni
- worldbuilding
- combo di azioni
- strumenti avanzati per gestione sessione

Tutto viene salvato automaticamente nel browser.

---

## Funzionalità principali

### Personaggio
- Creazione e gestione completa del personaggio
- Statistiche base e modificatori
- Calcolo automatico bonus e valori derivati

### Combattimento
- Tiro iniziativa cliccabile
- Attacchi con calcolo hit/danni
- Gestione critici
- Attacchi magici e fisici separati

### Incantesimi
- Slot da livello 0 a 9
- Trucchetti separati
- Calcolo DC incantesimi
- Bonus attacco magico
- Gestione concentrazione

### Inventario
- Monete (CP, SP, GP, EP, PP)
- Armi, armature e oggetti
- Oggetti magici con attunement
- Gestione quantità e peso

### Condizioni
- Supporto condizioni D&D 2014 e 2024
- Visualizzazione dettagliata
- Attivazione e rimozione dinamica

### Combo system
- Sequenze di azioni personalizzate
- Integrazione incantesimi + azioni
- Gestione turni (azione, bonus, reazione)
- Controllo concentrazione

### Worldbuilding
- Gestione PNG incontrati
- Gestione luoghi e informazioni
- Note narrative

### Homebrew
- Sezioni personalizzate
- Tracker attività con progress bar

### Export / Import
- Esportazione completa in JSON
- Importazione personaggi
- Backup manuale

---

## Come si usa

1. Aprire il link dell’applicazione
2. Creare un nuovo personaggio
3. Compilare le sezioni (statistiche, abilità, incantesimi, inventario)
4. Utilizzare le funzioni di combattimento durante il gioco
5. I dati vengono salvati automaticamente nel browser

---

## Salvataggio dati

- Tutti i dati vengono salvati automaticamente in localStorage
- Nessun server o account richiesto
- Possibilità di esportare il personaggio in JSON
- Possibilità di importare backup salvati

---

## Requisiti

- Browser moderno (Chrome, Firefox, Edge, Safari)
- JavaScript attivo
- Nessuna installazione richiesta

---

## Installazione locale (opzionale)

Se si vuole eseguire il progetto in locale:

1. Scaricare il repository
2. Aprire `index.html` nel browser

Non è necessario alcun server.

---

## Tecnologie utilizzate

- HTML5
- CSS3 (custom properties, tema chiaro/scuro)
- JavaScript vanilla (senza framework)
- LocalStorage per persistenza dati

---

## Architettura del progetto

Il progetto è basato su una struttura state-driven:

- `C` → stato globale del personaggio
- `render()` → aggiorna l’interfaccia utente
- `mk()` → helper per creazione elementi DOM
- `save()` → salvataggio automatico dati

---

## Note

Il progetto è pensato come strumento leggero, veloce e completamente offline-friendly per sessioni di gioco D&D.
