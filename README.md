# transfer-calculator

Il **transfer-calculator** è una semplice applicazione web che consente di calcolare il tempo necessario per caricare o scaricare un file in base alla sua dimensione e alla velocità della connessione di rete. L'applicazione supporta diverse unità di misura sia per la dimensione del file che per la velocità di rete, rendendo il calcolo più flessibile e adattabile a diverse esigenze.

## Funzionalità principali

- Calcola il tempo necessario per l'upload o il download di un file.
- Supporta una varietà di unità di misura:
  - **Dimensione del file**: Byte (B), Kilobytes (KB), Megabytes (MB), Gigabytes (GB), Terabytes (TB), Petabytes (PB).
  - **Velocità di rete**: Kilobits per secondo (Kbps), Megabits per secondo (Mbps), Gigabits per secondo (Gbps), Kilobytes per secondo (KBps), Megabytes per secondo (MBps), Gigabytes per secondo (GBps), Terabytes per secondo (TBps), Petabytes per secondo (PBps).
  
- La conversione automatica tra le diverse unità di misura permette all'utente di inserire i valori con le unità più appropriate per il caso specifico.

## Come funziona

1. **Inserisci la dimensione del file**: Immetti la dimensione del file che desideri caricare o scaricare. Puoi scegliere l'unità di misura (B, KB, MB, GB, TB, PB).
2. **Imposta la velocità di rete**: Inserisci la velocità della tua connessione internet. Puoi scegliere tra diverse unità di misura (Kbps, Mbps, Gbps, KBps, MBps, GBps, TBps, PBps).
3. **Calcola**: Dopo aver inserito i valori, fai clic sul pulsante **Calcola** per ottenere il tempo stimato di upload o download.
4. **Visualizza il risultato**: Il risultato verrà visualizzato in un formato leggibile (giorni, ore, minuti, secondi).

## Tecnologie utilizzate

- **HTML**: La struttura della pagina web.
- **CSS** (via Bootstrap): Lo stile della pagina per un'interfaccia utente responsive e moderna.
- **JavaScript**: La logica di calcolo per la conversione delle unità di misura e la determinazione del tempo di upload/download.

## Istruzioni per l'uso

1. Clona il repository nel tuo ambiente locale:
   ```bash
   git clone https://github.com/masonedotcloud/transfer-calculator.git
   ```
   
2. Apri il file `index.html` in un browser web:
   ```bash
   open index.html
   ```
   
3. Inserisci la dimensione del file e la velocità di rete, quindi premi **Calcola** per ottenere il tempo di upload/download.

## Esempio di calcolo

Se hai un file di 500 MB e una velocità di rete di 10 Mbps, cliccando su **Calcola** il risultato ti darà il tempo stimato per completare il trasferimento del file.

## Licenza

Questo progetto è distribuito sotto la Licenza MIT - vedi il file [LICENSE](LICENSE) per ulteriori dettagli.


## Autore

Questo progetto è stato creato da [alessandromasone](https://github.com/alessandromasone).