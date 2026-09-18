# FantAmici – Risultati & Analisi

Webapp statica client-side per analizzare il foglio `Database` del file Excel.

## Pubblicazione su GitHub Pages
1. Caricare tutti i file della cartella nella root del repository.
2. In **Settings → Pages**, pubblicare dal branch desiderato.
3. Aprire l'URL del sito. Il file Excel incluso viene caricato automaticamente.

## Aggiornamento dati
- Dalla webapp: usare **Importa Excel**. I dati rimangono nel browser per la sessione corrente.
- Per aggiornare anche il file iniziale del sito: sostituire `F2627_Risultati_e_analisi.xlsx` mantenendo lo stesso nome.

## Requisiti del file
Il file deve contenere il foglio `Database` con le colonne: Giornata, Squadra, Modulo, Giocatore, Ruolo, Voto, Fantavoto, BonusMalus, Titolare, VotoUtile, Sostituisce, VdM (mln €).

La webapp ricalcola Dashboard, classifiche VdM, schede squadra, grafici e Top 11 direttamente nel browser. Nessun dato viene inviato a un server.
