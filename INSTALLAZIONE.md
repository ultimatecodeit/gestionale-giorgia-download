# Come installare Gestionale Giorgia

Guida veloce per installare l'app sul tuo computer. Serve solo un
browser — nessun programma particolare, nessuna chiavetta USB.

## 1. Scarica il file giusto

Vai su:

**https://github.com/ultimatecodeit/gestionale-giorgia-download/releases/latest**

(Non serve nessun account GitHub né login per scaricare: la pagina è
pubblica.)

Nella sezione "Assets" in fondo alla pagina trovi tre file `.rar`.
Scarica quello che corrisponde al tuo computer:

| Il tuo computer | File da scaricare |
|---|---|
| Windows | `Gestionale-Giorgia-Setup-X.X.X.exe.rar` |
| Mac con chip Apple (M1, M2, M3, M4...) | `Gestionale-Giorgia-X.X.X-arm64.dmg.rar` |
| Mac con processore Intel | `Gestionale-Giorgia-X.X.X-x64.dmg.rar` |

**Non sai se il tuo Mac è Apple o Intel?** Clicca sul logo Apple in alto
a sinistra → *Informazioni su questo Mac*. Alla voce "Chip" (o
"Processore"): se c'è scritto "Apple M..." scegli la versione *arm64*,
se c'è scritto "Intel" scegli la versione *x64*.

## 2. Estrai il file (richiede una password)

I file sono protetti da password per evitare che chiunque li scarichi
senza autorizzazione — **chiedi la password a chi ti ha mandato questo
link**, non è scritta qui.

- **Windows**: serve un programma per aprire i file `.rar` — se non ne hai
  già uno, scarica gratis [7-Zip](https://www.7-zip.org/) o
  [WinRAR](https://www.win-rar.com/). Poi clic destro sul file scaricato
  → *Estrai qui* (o simile) → inserisci la password quando richiesta.
- **Mac**: scarica gratis [The Unarchiver](https://apps.apple.com/app/the-unarchiver/id425424353)
  dal Mac App Store (una sola volta). Poi doppio clic sul file `.rar` →
  inserisci la password quando richiesta.

Al termine avrai il file `.exe` o `.dmg` vero e proprio, pronto per il
passo successivo.

## 3. Installa — Windows

1. Apri il file `.exe` appena estratto (doppio clic).
2. Windows mostrerà un avviso blu: **"Windows ha protetto il PC"**. È
   normale — l'app non ha ancora un certificato di firma a pagamento, ma
   il programma è sicuro. Clicca su **"Ulteriori informazioni"**, poi su
   **"Esegui comunque"**.
3. Segui la procedura guidata (puoi lasciare tutto come proposto di
   default) fino alla fine.
4. L'app si apre da sola al termine, e trovi anche un'icona sul Desktop e
   nel menu Start per le volte successive.

## 4. Installa — Mac

1. Apri il file `.dmg` estratto al passo 2 (doppio clic).
2. Si apre una finestra: trascina l'icona dell'app nella cartella
   **Applicazioni**.
3. Chiudi quella finestra e apri **Applicazioni** (dal Finder o da
   Launchpad).
4. **Al primo avvio soltanto**: NON fare doppio clic sull'app. Fai invece
   **clic con il tasto destro** (o Control+clic) sull'icona dell'app →
   scegli **"Apri"** dal menu. macOS mostrerà un avviso perché l'app non
   viene da un "developer identificato" — è normale, clicca di nuovo
   **"Apri"** nella finestra di conferma.
5. Dalle volte successive potrai aprirla normalmente con un doppio clic.

## Domande frequenti

**L'antivirus/Windows Defender segnala qualcosa?** Può capitare con
installer non firmati digitalmente — il file è comunque sicuro. Se il tuo
antivirus lo blocca, aggiungilo come eccezione.

**Perché i file sono dentro un `.rar` con password?** Per evitare che
l'app possa essere scaricata ed eseguita da chiunque trovi il link per
caso — solo chi riceve la password da te può effettivamente installarla.

**Dove vengono salvati i dati dei pazienti?** In una cartella dedicata sul
tuo computer, separata dal programma stesso — non vengono mai inviati a
internet. Trovi il percorso esatto e il pulsante per aprirla direttamente
dalla scheda di ogni paziente nell'app ("Apri Cartella").

**Posso avere l'app su più computer?** Sì, ripeti semplicemente questa
procedura su ogni computer — ma ricorda che l'archivio pazienti non si
sincronizza da solo tra computer diversi: per spostare i dati, usa
*Impostazioni → Backup Dati* nell'app (crea un backup su un computer,
ripristinalo sull'altro).
