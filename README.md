# Fynario

**Fynario** is a personal portfolio management app for Android, designed to help users track investments, cash, recurring investment plans, staking rewards, returns, and portfolio history in one place.

> **Project status:** Fynario is under active development. Releases published here are stable builds intended for early use and testing while the application continues toward a future Google Play release.

## Download

Official Android builds of Fynario are distributed through the **Releases** section of this repository.

**Latest stable release:** [Fynario 0.12.0](https://github.com/Illidan0S/Fynario-Releases/releases/tag/v0.12.0)

For a normal Android installation, download the `.apk` file attached to the latest stable release.

> `fynario-update.json` is update metadata used internally by Fynario. It is **not** the application installer.

## Install on Android

1. Open the latest stable release.
2. Download the Fynario `.apk` file.
3. Open the downloaded file on your Android device.
4. If Android asks for permission, allow your browser or file manager to install apps from that source.
5. Confirm the installation.

Future updates can be checked directly from:

**Fynario → Settings → Updates**

Fynario does not silently install updates. You remain in control of when an update is installed.

## Main features

Current Fynario Mobile functionality includes:

- portfolio and position tracking;
- purchases, sales, deposits, withdrawals, and transfers;
- cash management;
- recurring investment plans (PAC);
- staking management and staking rewards;
- cash remuneration and interest tracking;
- unified returns history;
- portfolio charts and historical ranges;
- backup and restore between supported Fynario environments;
- light, dark, and system themes;
- built-in stable update checks.

Fynario is still evolving, so features and user experience may change between releases.

## Official stable release channel

This repository is the **official public stable release channel** for Fynario.

Fynario Mobile checks the latest stable GitHub release and reads the `fynario-update.json` asset to determine whether a newer compatible version is available.

A stable Android release can include:

- a digitally signed Android APK for manual installation;
- `fynario-update.json` for Fynario's built-in update checker;
- release notes describing relevant changes.

The Fynario source code is maintained privately and is not published in this repository.

## Security

Only install Fynario packages obtained from this repository or, in the future, from the official Google Play listing.

Official Android builds are digitally signed. Do not install APKs presented as Fynario from unrelated mirrors or third-party download sites.

The SHA-256 checksum of each public APK is included in its release notes so that the downloaded file can be independently verified.

This repository must never contain signing keys, passwords, private databases, backups, credentials, or other secrets.

## Versioning

Fynario Android releases use:

- a human-readable version such as `0.12.0`;
- an Android build/version code such as `1200`.

The Android version code increases for newer installable releases.

## Google Play

A Google Play release is planned for the future. Until then, this repository is the official public channel for stable Android builds and update metadata.

---

## Italiano

**Fynario** è un'app Android per la gestione e il monitoraggio del proprio portafoglio finanziario.

Il progetto è ancora in sviluppo attivo. Le versioni pubblicate qui sono build stabili destinate all'utilizzo anticipato e ai test, in attesa di una futura distribuzione tramite Google Play.

### Download e installazione

1. Apri la sezione **Releases** di questo repository.
2. Seleziona l'ultima versione stabile.
3. Scarica il file `.apk` di Fynario.
4. Apri il file sul dispositivo Android.
5. Se richiesto, autorizza il browser o il file manager a installare app da quella fonte.
6. Conferma l'installazione.

Il file `fynario-update.json` **non è l'app**: serve esclusivamente al sistema integrato di controllo aggiornamenti.

Dopo l'installazione, gli aggiornamenti possono essere controllati da:

**Fynario → Impostazioni → Aggiornamenti**

Per sicurezza, installa Fynario esclusivamente dalle release ufficiali di questo repository o, in futuro, dalla pagina ufficiale Google Play.
