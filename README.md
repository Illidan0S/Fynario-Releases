<p align="center">
  <img src="assets/fynario-icon.png" alt="Fynario icon" width="128">
</p>

# Fynario

**Fynario** is a personal portfolio management app for Android. It brings investments, cash, recurring plans and income, staking rewards, returns, and portfolio history together in one private workspace.

> **Project status:** Fynario is under active development. Releases published here are stable builds intended for early use and testing while the application continues toward a future Google Play release.

## Download

**Current stable version:** [Fynario 0.31.2](https://github.com/Illidan0S/Fynario-Releases/releases/tag/v0.31.2)<br>
**Build:** 3102

Download the Android installer:

**[Fynario-0.31.2-android.apk](https://github.com/Illidan0S/Fynario-Releases/releases/download/v0.31.2/Fynario-0.31.2-android.apk)**

> `fynario-update.json` is metadata used internally by Fynario's update checker. It is **not** the application installer.

## Install on Android

1. Download `Fynario-0.31.2-android.apk` from the current stable release.
2. Open the downloaded file on your Android device.
3. If Android asks for permission, allow your browser or file manager to install apps from that source.
4. Confirm the installation.

Fynario never installs updates silently. Updates can be checked from **Fynario → Settings → Updates**. Compatible releases can be downloaded, verified, and handed off to the Android installer from inside Fynario; the final installation always remains under your control.

## What's new in 0.31.2

- Fixed staking reward management.
- Expected rewards are now automatically proposed when due.
- You can adjust estimated amounts and confirm the rewards actually received.
- Improved handling of previously recorded rewards to prevent duplicate credits.
- Improved reward scheduling and history.

Fynario proposes rewards based on its own estimates and always asks you to confirm them: it does not import rewards automatically from brokers.

## Main features

- Portfolio overview with current holdings, liquidity, invested capital, profit and performance.
- Position details with allocation by custodian, related accounts, movements, recurring investment plans and crypto staking.
- Purchases, sales, deposits, withdrawals, transfers, income transactions and initial positions.
- One-time and recurring income for salary, winnings, gifts, refunds and other incoming funds.
- Active recurring-payment management with scheduling, editing, suspension and reactivation.
- Recurring investment plans (PAC) with confirmed executions.
- Crypto staking agreements, schedules, expected rewards and recorded staking rewards.
- Interactive portfolio and position charts across multiple historical ranges.
- Local backup and restore with integrity validation.
- Light, dark and system themes.
- Built-in stable update checks, verified APK download and guided Android installation.

## Official stable release channel

This repository is the official public stable release channel for Fynario. The source code is maintained privately and is not published here.

Fynario Mobile checks the latest stable GitHub release and reads its `fynario-update.json` asset to determine whether a newer compatible version is available. Each release contains a digitally signed APK for manual or in-app guided installation, update metadata and concise release notes.

## Security and integrity

Only install Fynario packages obtained from this repository or, in the future, from the official Google Play listing. Do not install APKs presented as Fynario by unrelated mirrors or third-party download sites.

**Fynario 0.31.2 APK SHA-256:**

`9F79CE878FB22CEA0FBD0457F6858739928E6D8377A461A1F5AABD7F7CEF309D`

Official Android builds are digitally signed. The checksum above can be used to verify the downloaded APK independently. Fynario also validates compatible package and version metadata before handing an update to Android.

This repository must never contain signing keys, passwords, private databases, backups, credentials, source code or other secrets.

## Versioning

- Version: `0.31.2`
- Android build/version code: `3102`
- Installer: `Fynario-0.31.2-android.apk`
- Release channel: `stable`

## Google Play

A Google Play release is planned for the future. Fynario is **not currently available on Google Play**. Until then, this repository remains the official public channel for stable Android builds and update metadata.

---

## Italiano

**Fynario** è un'app Android per gestire e monitorare in un unico spazio privato investimenti, liquidità, piani ed entrate ricorrenti, staking, rendimenti e storico del portafoglio.

> **Stato del progetto:** Fynario è ancora in sviluppo attivo. Le versioni pubblicate qui sono build stabili destinate all'utilizzo anticipato e ai test, in attesa di una futura distribuzione tramite Google Play.

### Download e installazione

**Versione stabile corrente:** [Fynario 0.31.2](https://github.com/Illidan0S/Fynario-Releases/releases/tag/v0.31.2)<br>
**Build:** 3102

Scarica l'installer Android:

**[Fynario-0.31.2-android.apk](https://github.com/Illidan0S/Fynario-Releases/releases/download/v0.31.2/Fynario-0.31.2-android.apk)**

1. Apri il file scaricato sul dispositivo Android.
2. Se richiesto, autorizza il browser o il file manager a installare app da quella fonte.
3. Conferma l'installazione.

Il file `fynario-update.json` **non è l'app**: contiene esclusivamente i metadati usati dal controllo aggiornamenti integrato.

Fynario non installa mai aggiornamenti senza conferma. Gli aggiornamenti possono essere controllati da **Fynario → Impostazioni → Aggiornamenti**. Per le release compatibili, Fynario può scaricare e verificare l'APK e poi aprire il flusso di installazione Android; la conferma finale resta sempre all'utente.

### Novità della 0.31.2

- Risolta la gestione dei reward staking.
- I reward previsti vengono ora proposti automaticamente alla scadenza.
- È possibile modificare l'importo stimato e confermare quello effettivamente ricevuto.
- Corretta la gestione dei reward già registrati, evitando accrediti duplicati.
- Migliorata la gestione delle scadenze e dello storico dei reward.

Fynario propone i reward in base alle proprie stime e chiede sempre la tua conferma: non importa automaticamente i reward dai broker.

### Funzioni principali

- Riepilogo del portafoglio con posizioni, liquidità, capitale investito, profitto e rendimento.
- Dettaglio posizione con distribuzione per custodia, conti collegati, movimenti, PAC e staking crypto.
- Acquisti, vendite, depositi, prelievi, trasferimenti, entrate e posizioni iniziali.
- Entrate una tantum o ricorrenti per stipendi, vincite, regali, rimborsi e altri accrediti.
- Gestione delle ricorrenze attive con pianificazione, modifica, sospensione e riattivazione.
- Piani di accumulo (PAC) con conferma delle esecuzioni.
- Accordi staking crypto, scadenze, reward previsti e accrediti realmente registrati.
- Grafici interattivi del portafoglio e delle posizioni su più intervalli storici.
- Backup e ripristino locali con validazione dell'integrità.
- Temi chiaro, scuro e di sistema.
- Controllo aggiornamenti stabile integrato, download APK verificato e installazione Android guidata.

### Canale stabile ufficiale

Questo repository è il canale pubblico ufficiale delle release stabili di Fynario. Il codice sorgente è mantenuto privatamente e non viene pubblicato qui.

Fynario Mobile controlla l'ultima release stabile e legge il relativo asset `fynario-update.json`. Ogni release contiene un APK firmato digitalmente, i metadati per l'updater e note di rilascio concise.

### Sicurezza e integrità

Installa Fynario esclusivamente dalle release ufficiali di questo repository o, in futuro, dalla pagina ufficiale Google Play. Non installare APK distribuiti da mirror o fonti di terze parti non autorizzate.

**SHA-256 dell'APK Fynario 0.31.2:**

`9F79CE878FB22CEA0FBD0457F6858739928E6D8377A461A1F5AABD7F7CEF309D`

Le build Android ufficiali sono firmate digitalmente. Il checksum permette di verificare autonomamente l'integrità dell'APK; Fynario controlla inoltre pacchetto e versione prima di passare un aggiornamento all'installer Android.

### Versionamento

- Versione: `0.31.2`
- Build/version code Android: `3102`
- Installer: `Fynario-0.31.2-android.apk`
- Canale: `stable`

### Google Play

È prevista una futura distribuzione tramite Google Play. Fynario **non è attualmente disponibile sul Play Store**; fino ad allora questo repository resta il canale pubblico ufficiale per build Android stabili e metadati di aggiornamento.
