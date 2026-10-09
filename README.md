# Arcana Narrativa

[![Versione](https://img.shields.io/badge/versione-1.0.0-blue.svg?style=flat-square)](https://github.com/tagtthespellcaster/Arcana-Narrativa/releases/tag/v1.0.0)
[![Licenza: AGPL v3](https://img.shields.io/badge/licenza-AGPL_v3-black.svg?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Piattaforma](https://img.shields.io/badge/piattaforma-Web-green.svg?style=flat-square)](https://tagtthespellcaster.github.io/Arcana-Narrativa/)

Arcana Narrativa è un'applicazione web ideata per la generazione di spunti narrativi, la strutturazione di storie e lo sblocco creativo attraverso l'estrazione combinata di mazzi teorici e strutturali.

## Applicazione Live

L'applicazione è pronta all'uso al seguente indirizzo:
https://tagtthespellcaster.github.io/Arcana-Narrativa/

## Funzionalità

- **Database Integrato di 43 Carte Teoriche:**
  - **31 Funzioni di Vladimir Propp:** Elementi morfologici per la struttura della fiaba e dell'intreccio narrativo.
  - **12 Fasi del Viaggio dell'Eroe:** Tappe mitologiche ed evolutive per lo sviluppo dei personaggi (secondo i modelli di Campbell e Vogler).
- **Integrazione Dati Nativa:** Ciascuna carta fornisce titolo, categoria di appartenenza, descrizione strutturale, indicazioni sul contesto operativo e spunto/prompt pratico per la scrittura.
- **Modalità di Estrazione Flessibile:** Supporto per l'estrazione di 1 carta (spunto rapido), 3 carte (inizio / svolta / fine), 4 carte (struttura in quattro atti) o 5 carte (percorso complesso).
- **Filtraggio per Mazzo:** Possibilità di estrarre carte da un singolo mazzo (solo Propp o solo Viaggio dell'Eroe) oppure dal totale combinato dei mazzi disponibili.
- **Algoritmo di Mescolamento:** Implementazione dell'algoritmo Fisher-Yates per garantire un'estrazione casuale senza ripetizioni.
- **Animazione e Visualizzazione 3D:** Carte coperte sul tavolo da gioco con animazione di ribaltamento (Flip 3D) al click o tap.
- **Comando Gira Tutte:** Pulsante per scoprire contemporaneamente tutte le carte estratte.
- **Taccuino dello Scrittore Integrato:** Spazio di lavoro laterale con funzioni di scrittura, copia rapida del testo negli appunti e pulizia del contenuto.
- **Interfaccia Responsive e Scura:** Layout progettato con palette Dark Mode ad alta visibilità, ottimizzato per schermi desktop, tablet e mobile.
- **Nessuna Dipendenza Esterna:** Implementazione autonoma eseguibile direttamente tramite un singolo file HTML comprensivo di CSS e JavaScript nativi.

## Guida all'Uso

1. Apri l'applicazione nel browser.
2. Seleziona il mazzo desiderato dal menu a tendina (Tutti i Mazzi, Funzioni di Propp oppure Viaggio dell'Eroe).
3. Scegli il numero di carte da estrarre (1, 3, 4 o 5).
4. Clicca sul pulsante **Estrai Carte** per disporre le carte sul tavolo.
5. Clicca su ciascuna carta per scoprirne il contenuto oppure utilizza il pulsante **Gira Tutte**.
6. Utilizza il **Taccuino dello Scrittore** sul lato destro per annotare idee, sviluppi o trame generate dagli spunti estratti.

## Installazione e Deployment

L'applicazione è distribuita come risorsa statica e non richiede alcun processo di compilazione o installazione di pacchetti.

Per eseguirla in locale o su un server proprio:

1. Clona il repository:
   ```bash
   git clone [https://github.com/tagtthespellcaster/Arcana-Narrativa.git](https://github.com/tagtthespellcaster/Arcana-Narrativa.git)
