D&D Character Sheet Web App

Applicazione web single-page per la gestione completa di un personaggio Dungeons & Dragons 5e, con supporto a combattimento, incantesimi, inventario, condizioni, mondo di gioco e strumenti avanzati come combo di azioni.

Funzionalità
Combat
Gestione iniziativa con tiro automatico
Attacchi corpo a corpo e magici
Calcolo automatico di tiri per colpire, danni e critici
Supporto bonus competenza e statistiche
Incantesimi
Slot incantesimo da livello 1 a 9
Trucchetti separati
Selezione statistica per incantatore
Calcolo DC e bonus attacco
Gestione concentrazione integrata
Inventario
Gestione monete (CP, SP, GP, EP, PP)
Oggetti magici con attunement
Armi, armature e consumabili
Inventario generale con quantità e peso
Combo System
Creazione di sequenze di azioni
Supporto per azioni, azioni bonus e reazioni
Integrazione con incantesimi
Validazione dei limiti per turno
Gestione concentrazione
World Building
Gestione PNG con dettagli completi
Gestione luoghi e informazioni narrative
Condizioni
Supporto condizioni D&D 2014 e 2024
Visualizzazione dettagliata per ogni condizione
Attivazione e gestione dinamica
Homebrew
Sezioni personalizzate modificabili
Tracker attività con progress bar
Export / Import
Esportazione personaggio in formato JSON
Importazione completa dello stato
Tecnologie utilizzate
HTML5
CSS3 (custom properties, dark/light theme)
JavaScript vanilla (senza framework)
LocalStorage per persistenza dati
Installazione
git clone https://github.com/tuo-utente/dnd-character-sheet.git
cd dnd-character-sheet

Aprire index.html direttamente nel browser.

Persistenza dati

I dati del personaggio vengono salvati automaticamente in localStorage.

Backup disponibile tramite:

Export JSON
Import JSON
Tema

L’app supporta modalità:

Dark mode
Light mode

La preferenza viene salvata automaticamente.

Architettura del progetto

Il progetto è basato su una struttura state-driven:

C → stato globale del personaggio
render() → rigenera l’interfaccia
mk() → helper per costruzione DOM
save() → persistenza automatica

Licenza

MIT License (consigliata per progetti open source)
