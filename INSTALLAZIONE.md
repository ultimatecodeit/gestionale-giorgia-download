# Come installare Gestionale Giorgia

Guida veloce per installare l'app sul tuo computer. Serve solo un
browser — nessun programma particolare, nessuna chiavetta USB.

## 1. Scarica il file giusto

Vai su:

**https://github.com/ultimatecodeit/gestionale-giorgia-download/releases/latest**

(Non serve nessun account GitHub né login per scaricare: la pagina è
pubblica.)

Nella sezione "Assets" in fondo alla pagina trovi tre file `.zip`.
Scarica quello che corrisponde al tuo computer:

| Il tuo computer | File da scaricare |
|---|---|
| Windows | `Gestionale-Giorgia-Setup-X.X.X.exe.zip` |
| Mac con chip Apple (M1, M2, M3, M4...) | `Gestionale-Giorgia-X.X.X-arm64.dmg.zip` |
| Mac con processore Intel | `Gestionale-Giorgia-X.X.X-x64.dmg.zip` |

**Non sai se il tuo Mac è Apple o Intel?** Clicca sul logo Apple in alto
a sinistra → *Informazioni su questo Mac*. Alla voce "Chip" (o
"Processore"): se c'è scritto "Apple M..." scegli la versione *arm64*,
se c'è scritto "Intel" scegli la versione *x64*.

## 2. Estrai il file (richiede una password)

I file sono protetti da password per evitare che chiunque li scarichi
senza autorizzazione — **chiedi la password a chi ti ha mandato questo
link**, non è scritta qui.

Sono file `.zip` normali (cifrati AES-256): **non serve installare nulla**,
li apre lo strumento già incluso nel sistema operativo.

- **Windows**: doppio clic sul file scaricato per aprirlo, poi trascina
  fuori (o clic destro → *Estrai tutto...*) il file `.exe` contenuto.
  Windows chiederà la password al momento dell'estrazione.
- **Mac**: doppio clic sul file scaricato. Finder chiede subito la
  password, poi estrae automaticamente il `.dmg` nella stessa cartella.

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

**Perché i file sono dentro uno `.zip` con password?** Per evitare che
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
