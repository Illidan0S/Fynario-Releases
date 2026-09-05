<p align="center">
  <img src="assets/fynario-icon.png" alt="Fynario icon" width="128">
</p>

# Fynario

**Fynario** is a personal portfolio management app for Android, designed to help users track investments, cash, recurring investment plans, staking rewards, returns, and portfolio history in one place.

> **Project status:** Fynario is under active development. Releases published here are stable builds intended for early use and testing while the application continues toward a future Google Play release.

## Download

**Current stable version:** [Fynario 0.21.0](https://github.com/Illidan0S/Fynario-Releases/releases/tag/v0.21.0)  
**Build:** 2100

Download the Android installer:

**[Fynario-0.21.0-android.apk](https://github.com/Illidan0S/Fynario-Releases/releases/download/v0.21.0/Fynario-0.21.0-android.apk)**

> `fynario-update.json` is metadata used internally by Fynario's update checker. It is **not** the application installer.

## Install on Android

1. Download `Fynario-0.21.0-android.apk` from the current stable release.
2. Open the downloaded file on your Android device.
3. If Android asks for permission, allow your browser or file manager to install apps from that source.
4. Confirm the installation.

Fynario does not silently install updates. Updates can be checked from **Fynario → Settings → Updates**. Compatible releases can be downloaded, verified, and handed off to the Android installer from inside Fynario, while you remain in control of the final installation.

## What's new in 0.21.0

- Built-in Android updater with foreground/background update checks
- Update notifications and direct access to the Updates page
- APK download with SHA-256 integrity verification and package/version checks
- Guided Android installation flow with unknown-source permission handling
- Faster mobile charts with fewer unnecessary historical provider requests
- Persistent chart ranges and improved automatic refresh behavior
- Improved Home and PositionDetail lifecycle/cancellation handling
- Various stability and performance improvements

## Main features

- Portfolio and position tracking
- Purchases, sales, deposits, withdrawals, and transfers
- Cash management and remuneration tracking
- Recurring investment plans (PAC)
- Staking management and staking rewards
- Portfolio charts and historical ranges
- Backup and restore between supported Fynario environments
- Light, dark, and system themes
- Built-in stable update checks, verified APK download, and guided Android installation

## Official stable release channel

This repository is the official public stable release channel for Fynario. The source code is maintained privately and is not published here.

Fynario Mobile checks the latest stable GitHub release and reads its `fynario-update.json` asset to determine whether a newer compatible version is available. A release contains a digitally signed APK for manual or in-app guided installation, update metadata, and concise release notes.

## Security and integrity

Only install Fynario packages obtained from this repository or, in the future, from the official Google Play listing. Do not install APKs presented as Fynario by unrelated mirrors or third-party download sites.

**Fynario 0.21.0 APK SHA-256:**

`A09A8EF8111B463127B07AB77067DDEBAAB0B86B0FA4E6BDCC299B5705228FF7`

Official Android builds are digitally signed. The checksum above can be used to verify the downloaded APK independently.

This repository must never contain signing keys, passwords, private databases, backups, credentials, or other secrets.

## Versioning

- Version: `0.21.0`
- Android build/version code: `2100`
- Installer: `Fynario-0.21.0-android.apk`

## Google Play

A Google Play release is planned for the future. Fynario is **not currently available on Google Play**. Until then, this repository remains the official public channel for stable Android builds and update metadata.

---

## Italiano

**Fynario** è un'app Android per la gestione e il monitoraggio del proprio portafoglio finanziario.

Il progetto è ancora in sviluppo attivo. Le versioni pubblicate qui sono build stabili destinate all'utilizzo anticipato e ai test, in attesa di una futura distribuzione tramite Google Play.

### Download e installazione

**Versione stabile corrente:** [Fynario 0.21.0](https://github.com/Illidan0S/Fynario-Releases/releases/tag/v0.21.0)  
**Build:** 2100

Scarica l'installer Android:

**[Fynario-0.21.0-android.apk](https://github.com/Illidan0S/Fynario-Releases/releases/download/v0.21.0/Fynario-0.21.0-android.apk)**

1. Apri il file scaricato sul dispositivo Android.
2. Se richiesto, autorizza il browser o il file manager a installare app da quella fonte.
3. Conferma l'installazione.

Il file `fynario-update.json` **non è l'app**: contiene esclusivamente i metadati usati dal controllo aggiornamenti integrato.

Gli aggiornamenti possono essere controllati da **Fynario → Impostazioni → Aggiornamenti**. Per le release compatibili, Fynario può scaricare e verificare l'APK e poi aprire il flusso di installazione Android; la conferma finale resta sempre all'utente.

### Novità della 0.21.0

- Updater Android integrato con controlli in foreground e background
- Notifiche quando è disponibile una nuova versione
- Download APK con verifica SHA-256 e controlli su pacchetto/versione
- Installazione guidata con gestione del permesso per origini sconosciute
- Grafici Mobile più rapidi e con meno richieste storiche inutili
- Persistenza dei range dei grafici e auto-refresh migliorato
- Gestione lifecycle/cancellazione migliorata in Home e PositionDetail
- Miglioramenti generali di stabilità e prestazioni

### Sicurezza e integrità

Installa Fynario esclusivamente dalle release ufficiali di questo repository o, in futuro, dalla pagina ufficiale Google Play. Fynario non è attualmente disponibile sul Play Store.

**SHA-256 dell'APK Fynario 0.21.0:**

`A09A8EF8111B463127B07AB77067DDEBAAB0B86B0FA4E6BDCC299B5705228FF7`
