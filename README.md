# Ferie · Permessi e Straordinari — v2.1

App per GitHub Pages. Avvio contabilità: **1 settembre 2026**.

## Funzionalità
- Tre saldi separati: ferie, permessi e straordinari.
- Maturazione mensile automatica ferie **14,44 h** e permessi **5,67 h**, entrambi personalizzabili in Impostazioni.
- Saldi iniziali impostabili al 1° settembre 2026.
- Straordinari inseriti manualmente mese per mese.
- Utilizzi in ore o giorni (1 giorno = 8 h), scegliendo la categoria da scalare.
- Permessi futuri già detratti dai saldi e visibili come programmati nello storico.
- Statistiche, modifica/cancellazione movimenti e backup JSON.
- Icona personalizzata con palma e scritta Ferie.

## Installazione
1. Carica tutti i file di questa cartella nella root di un repository GitHub.
2. Settings → Pages → Deploy from a branch → main → /(root).
3. Apri il link sul telefono e usa Aggiungi a schermata Home.

## Note
I dati sono salvati nel browser del dispositivo (localStorage). Fai periodicamente backup da Impostazioni. L'app non sincronizza automaticamente dispositivi differenti. Se stai aggiornando una precedente versione, mantieni lo stesso indirizzo e repository per conservare i dati già salvati sullo stesso dispositivo.

## Correzione v1.2
- Risolto il blocco di Safari sul valore intero (es. 2 giorni) per il modulo Usa ore e Aggiungi ore.

## v1.7
Tre saldi compatti sempre visibili in alto durante la compilazione, moduli e pulsanti più ravvicinati.

## v1.9
- Il numero di versione nelle Impostazioni deriva da APP_VERSION nel codice in esecuzione.
- Cache PWA aggiornata a ferie-v8.

## Riepilogo annuale 2026
In Impostazioni inserisci le ore già utilizzate gennaio–agosto (facoltative, default 0). Non vengono scalate dai saldi iniziali. La pagina Statistiche ricostruisce il totale: residuo al 31 agosto + consumo precedente + maturazioni settembre–dicembre, con progress bar usato/disponibile.

## Versione 2.0 – Pianificazione ferie
Previsione ferie, permessi e straordinari al 31 dicembre 2026, con maturazioni future e utilizzi programmati. Il modulo Usa ore mostra il saldo previsto per il mese selezionato e permette di prenotare usando anche le ore che matureranno entro quel mese. Nessuna modifica ai dati memorizzati.

## Versione 2.1 – Avvio settembre
Saldi iniziali riferiti al 1° settembre 2026, prima della maturazione di settembre. Da settembre a dicembre sono conteggiati 4 mesi. Se avevi già inserito un residuo riferito al 30 settembre, aggiorna il valore iniziale nelle Impostazioni per evitare di contare settembre due volte.
