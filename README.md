<div align="center">

# 🧠 Brain Duel
**HTML5 • CSS3 • JavaScript • Mobile First • Zero Dependencies**

</div>

Brain Duel è un gioco a quiz (Trivia) moderno, veloce e interattivo, progettato con un approccio mobile-first per schermi verticali. Unisce un'interfaccia pulita in stile iOS Glassmorphism a meccaniche competitive in locale, racchiudendo l'intera applicazione (struttura, stile, grafica vettoriale, logica e sintetizzatore audio) in un singolo file HTML.

🎮 **[Gioca alla Live Demo qui](https://davide23567.github.io/brain-duel/)**

---

## ✨ Caratteristiche Principali

* **👤 Modalità Singolo & 👥 Versus (1v1 Locale):** Gioca da solo per battere il tuo record oppure sfida un amico sullo stesso smartphone in modalità Pass & Play.
* **🕵️‍♂️ Suspense 1v1 (Risultati Nascosti):** Nella sfida a due giocatori, l'esito delle risposte resta segreto durante i turni per non avvantaggiare l'avversario. Errori, risposte esatte e vincitore vengono svelati solo nel riepilogo finale.
* **⚡ Power-Up Integrati:** Ogni giocatore dispone di due aiuti strategici per partita:
  * **50:50:** Rimuove istantaneamente due opzioni errate.
  * **Congela Tempo:** Blocca il timer per riflettere senza pressione, attivando un feedback visivo glaciale sulla UI.
* **🎨 UI/UX iOS Glassmorphism:** Pannelli semitrasparenti con `backdrop-filter`, icone vettoriali custom, animazioni fluide, coriandoli su canvas e sfondo SVG animato integrato nel codice.
* **🔊 Audio Sintetizzato & Feedback Aptico:** Effetti sonori generati in tempo reale tramite Web Audio API (nessun file `.mp3` esterno) e vibrazione aptica sincronizzata sugli smartphone supportati.
* **💾 Salvataggio Automatico:** Record personale, partite giocate e storico delle vittorie 1v1 salvati in locale tramite `localStorage`.
* **📚 5 Categorie di Gioco:** Storia, Geografia, Cinema, Scienza e la modalità Mix Totale.

---

## 🛠️ Architettura "Single-File"

Il progetto è strutturato in un unico file `index.html` senza librerie o asset esterni. Questa scelta architetturale garantisce:
* **Portabilità Totale:** Si apre istantaneamente in qualsiasi browser mobile o desktop, anche offline.
* **Sviluppo Immediato:** Perfetto per essere modificato e testato al volo da qualsiasi editor di testo o IDE, anche in mobilità, senza bisogno di server locali.
* **Pronto per il Deploy:** Facilissimo da pubblicare su GitHub Pages o da impacchettare in una WebView per la distribuzione su store mobile.

---

## 🚀 Come Iniziare

Non serve alcuna installazione o build process:

1. Clona il repository o scarica il file `index.html`:
   ```bash
   git clone [https://github.com/davide23567/brain-duel.git](https://github.com/davide23567/brain-duel.git)
   
