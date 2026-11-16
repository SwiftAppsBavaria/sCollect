# Informativa sulla privacy di sCollect

Aggiornamento: 2026-11-16

## In breve

sCollect non raccoglie, non memorizza e non trasmette **alcun** dato personale. L’app
lavora esclusivamente sul tuo Mac o PC Windows. Non ci sono account, nessun collegamento al cloud,
nessun servizio di analisi e nessuna pubblicità.

## Quali dati elabora l’app

sCollect legge e scrive i file multimediali nelle cartelle che gli hai espressamente
affidato — scegliendole nella finestra di apertura oppure trascinandole sulla finestra.
Vengono letti il nome del file, la dimensione del file, la data e i metadati del file;
vengono scritte le informazioni che inserisci nell’editor.

Senza una tua scelta l’app non accede ad alcun file. macOS lo impone attraverso la
sandbox dell’app.

## Che cosa l’app deposita sul tuo Mac

- **La libreria stessa** nella cartella che hai scelto per essa: i dati del catalogo, le
  copertine e un registro delle sincronizzazioni non ancora eseguite.
- **Impostazioni e posizioni delle finestre** nella cartella protetta dell’app.
- **Il permesso di macOS di riaprire le tue cartelle al prossimo avvio.** Vengono
  memorizzati i percorsi delle cartelle, non i contenuti dei file. Solo così l’app non
  deve chiedere di nuovo a ogni avvio.
- **Un registro diagnostico** con orari e conteggi delle operazioni. Resta sul tuo Mac;
  puoi salvarlo e trasmetterlo se segnali un errore.

Tutto questo viene rimosso quando elimini l’app e la sua libreria.

## Due autorizzazioni che possono far sorgere domande

**Accesso alla rete.** L’app lo richiede perché senza questa autorizzazione macOS mostra
vuota la finestra di aiuto integrata — l’aiuto viene visualizzato da un componente di
sistema che ne ha bisogno, anche se carica soltanto file del programma stesso. Di sua
iniziativa sCollect **non richiama alcun indirizzo su internet**, non scarica nulla e non
segnala nulla.

Le librerie su unità di rete (SMB, NFS) l’app le raggiunge attraverso il file system del
tuo Mac, non tramite una connessione propria.

**Controllo di Apple Music.** Quando esporti una playlist, sCollect apre Apple Music con
il file generato. Per questo macOS richiede il tuo consenso, che viene chiesto la prima
volta. L’app non controlla altri programmi.

## I tuoi file

sCollect modifica i metadati esattamente nei file che appartengono alla tua libreria e li
sposta, quando li archivia, all’interno delle cartelle che hai autorizzato.

**Gli elementi collegati restano intatti** — si trovano fuori dalla libreria, e lì l’app
non scrive nulla.

I file eliminati finiscono dapprima in un cestino proprio all’interno della libreria e da
lì possono essere recuperati. Vengono rimossi definitivamente solo quando lo svuoti.

## Su Windows

Le sezioni precedenti descrivono il Mac. Su Windows, sCollect salva quanto segue esclusivamente in locale:

Nella cartella dati dell’app (`%LOCALAPPDATA%\Packages\<pacchetto>\LocalState` e `Settings`):

- **Impostazioni, posizione della finestra e vista** — le librerie aperte di recente, la selezione nella barra laterale, gli
  ultimi titoli riprodotti, le colonne e l’ordinamento.
- **L’associazione tra le cartelle Mac di una libreria e cartelle del tuo PC** (solo percorsi di cartelle).
- **Suggerimenti di inserimento** — valori che hai già usato in campi come genere o lingua, proposti come suggerimenti.
- **Un identificativo casuale di questo PC.** Distingue i tuoi computer nelle copie di una libreria e non contiene nulla su di
  te.
- **Un registro diagnostico** con orari, operazioni e i percorsi dei file interessati, e un **registro degli errori**
  (`fehler.log`, sette giorni). Entrambi restano sul tuo PC; puoi trasmetterli se segnali un errore.

Nella cartella della libreria che hai scelto: i dati del catalogo, le copertine, il cestino della libreria e — se ha delle copie
— le loro posizioni e le sincronizzazioni non ancora eseguite. Finché sCollect ha una libreria aperta, vi tiene inoltre un
**file di blocco** con il **nome del tuo PC**, perché due computer non scrivano contemporaneamente nella stessa libreria. Se la
libreria si trova su un’unità di rete, gli altri utenti di quell’unità possono vedere il nome.

Ciò che si trova nella cartella dati dell’app viene rimosso quando disinstalli l’app; la libreria resta finché non la elimini
tu.

sCollect legge e scrive file multimediali solo nelle cartelle che gli affidi. L’app non stabilisce connessioni di rete proprie,
non usa servizi di analisi e non mostra pubblicità. I file che Windows non riproduce da sé vengono passati al programma
predefinito per quel tipo di file, che scegli in Windows. Per convertire e accorciare audio e video usa l’FFmpeg incluso, anche
questo solo sul tuo PC.

Se invii una playlist a iTunes, sCollect apre iTunes per Windows con quella playlist; l’app non controlla altri programmi. Se
esporti una playlist per VLC o per un dispositivo, l’app ne copia i file nella cartella che scegli.

## Microsoft Store

Su Windows, acquisto, download e aggiornamenti passano attraverso il Microsoft Store; per questi vale l’informativa sulla
privacy di Microsoft.

## Nessuna trasmissione, nessuna analisi

Non c’è pubblicità, non ci sono servizi di analisi, non ci sono rapporti di arresto
anomalo verso terzi e non ci sono account.

## Contatto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
