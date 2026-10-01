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
4. **Doppio clic** sull'app. Al primo avvio macOS la blocca, perché l'app
   non ha un certificato Apple a pagamento: compare un avviso con i
   pulsanti **"Fine"** e **"Sposta nel Cestino"**. Clicca **"Fine"**
   (NON "Sposta nel Cestino").
5. Apri il menu Apple (la mela in alto a sinistra) → **Impostazioni di Sistema** → **Privacy e
   sicurezza**. Scorri in fondo alla pagina: trovi la scritta *"L'apertura
   di "Gestionale Giorgia" è stata bloccata..."*. Clicca **"Apri
   comunque"**, inserisci la password del Mac (o usa Touch ID) e conferma
   ancora con **"Apri comunque"**.
6. Compare la finestra **"Avvio in corso..."**: al primissimo avvio può
   restare lì fino a un paio di minuti (macOS controlla i file appena
   scaricati). Non chiuderla e non riaprire l'app: si apre da sola.
7. Dalle volte successive si apre normalmente con un doppio clic, in pochi
   secondi.

> Su macOS più vecchi (14 Sonoma o precedenti) al passo 4 può comparire
> invece un pulsante **"Apri"**: in quel caso basta cliccarlo.

**Se al passo 5 non compare il pulsante "Apri comunque"** (alternativa
sempre valida): apri l'app **Terminale** (Launchpad → cerca "Terminale"),
incolla questa riga e premi Invio:

```
xattr -cr "/Applications/Gestionale Giorgia.app"
```

Poi chiudi il Terminale e apri l'app con un normale doppio clic.

## Domande frequenti

**L'antivirus/Windows Defender segnala qualcosa?** Può capitare con
installer non firmati digitalmente — il file è comunque sicuro. Se il tuo
antivirus lo blocca, aggiungilo come eccezione.

**Su Mac clicco l'app e non succede nulla.** Al primo avvio la finestra
"Avvio in corso..." può tardare qualche secondo: attendi senza fare altri
clic. Se dopo un minuto non è comparso nulla, usa il comando del Terminale
qui sopra (`xattr -cr ...`) e riprova.

**Ho una versione precedente già installata.** Installa sopra quella nuova
nello stesso modo: su Windows esegui il nuovo `.exe`, su Mac trascina la
nuova app in Applicazioni e scegli "Sostituisci". I dati dei pazienti non
vengono toccati.

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
