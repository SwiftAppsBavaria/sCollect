# Aiuto per sCollect

## Che cosa fa l’app

sCollect gestisce collezioni di media — musica, film, video personali, audiolibri,
podcast, e-book — e pezzi da collezione che non sono file multimediali, per esempio monete
o francobolli. Come si chiamano le categorie lo stabilisci tu in **Impostazioni →
Etichette categorie**.

Quello che inserisci nell’editor, l’app lo **riscrive nel file**, non soltanto nel proprio
catalogo.

## Primi passi

1. Al primo avvio scegli una cartella per la libreria. Lì si troveranno poi i dati del
   catalogo e, se lo desideri, anche i file multimediali.
2. Porta dentro file o cartelle con **File → Importa file** (⌘O) oppure **File → Importa
   cartella** (⇧⌘O), o trascinali sulla finestra.
3. Durante l’importazione decidi per ogni passaggio se i file vengono **copiati nella
   libreria** o soltanto **collegati**.

## Gestito o collegato?

| | |
|---|---|
| **Gestito** | Il file si trova nella libreria. sCollect lo archivia, lo rinomina secondo il tuo schema e scrive i tag. |
| **Collegato** | Il file resta dov’è. sCollect ne memorizza la posizione e **non tocca il file**. |

La colonna «Collegato» nell’elenco mostra qual è il caso.

## Domande frequenti

**Una voce ha un triangolo di avviso arancione.**
Il suo file non è stato trovato durante l’ultimo passaggio di **File → Libreria →
Contrassegna elementi mancanti**. La voce non si lascia allora modificare — non c’è nulla su cui si
possa scrivere. Dal menu contestuale l’app offre **Cerca il file…**; il file trovato viene
riportato nella libreria.

**Nel menu contestuale c’è «Unità non collegata», in grigio.**
Allora non manca il file, ma il disco. sCollect distingue espressamente i due casi: quello
che non è collegato non lo può nemmeno controllare — e perciò non lo contrassegna neppure
come mancante. Collega il disco e ripeti il passaggio.

**Un tipo di media è grigio e non si lascia modificare.**
La sua cartella al momento non è raggiungibile. sCollect blocca questi tipi invece di
depositare i file altrove senza dirlo. Appena il disco torna disponibile, il blocco
finisce.

**L’editor mostra «Un campo differisce dal file».**
Il file contiene in un campo qualcosa di diverso rispetto alla libreria — di solito perché
nel frattempo lo ha modificato un altro programma. La striscia sopra i campi mostra quali
campi sono interessati, e decidi tu campo per campo se il valore del file viene adottato.

**Non trovo un campo che mi serve.**
Per i pezzi da collezione ci sono tre campi liberamente denominabili. Come debbano
chiamarsi lo imposti per ogni categoria in **Impostazioni → Etichette campi**.

**Posso riprendere la mia raccolta di iTunes o Musica?**
Sì. sCollect legge l’XML di iTunes con valutazioni e playlist. I brani vengono associati
attraverso i loro percorsi di file; le valutazioni già presenti non vengono sovrascritte.

**Come faccio a riportare fuori la mia collezione?**
Attraverso l’**sCollect-XML** — è senza perdite e serve allo stesso tempo come copia di
sicurezza. Accanto a questo c’è l’esportazione come iTunes-XML e come playlist per Apple
Music.

**Che cosa fa la sincronizzazione con le copie?**
Una libreria può registrare altre librerie come copie. Le modifiche all’archivio principale
vengono riportate lì, file e tag compresi. Se una copia è momentaneamente offline, la
modifica resta in attesa e viene recuperata più tardi.

⚠️ **Questo non è un backup.** Un file eliminato viene eliminato anche nelle copie — è
proprio lo scopo di una sincronizzazione. Per il caso in cui qualcosa vada storto ti serve
in aggiunta una vera copia di sicurezza.

**Il mio file perde qualità quando vengono scritti i tag?**
No. I dati audio e delle immagini vengono ripresi invariati; non viene ricodificato nulla.
Dove è possibile, sCollect cambia soltanto i pochi byte del tag invece di riscrivere il
file.

**Posso annullare una modifica?**
Le voci eliminate le riporta indietro ⌘Z. Le modifiche ai metadati no — prima di una grande
operazione a lotti crea quindi una copia di sicurezza.

## Qualcosa va storto?

sCollect scrive un registro nella cartella della tua libreria — annota che cosa ha fatto
l’app e quando. Allegalo volentieri alla descrizione dell’errore.

## Contatto

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
