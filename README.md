# Telegram Unused Chat Leaver (TUCL)

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Telethon](https://img.shields.io/badge/Library-Telethon-orange)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac%20%7C%20Termux-green)
[![SonarQube Cloud](https://sonarcloud.io/images/project_badges/sonarcloud-highlight.svg)](https://sonarcloud.io/summary/new_code?id=LightYagami28_TUCL--Telegram-Unused-Chat-Leaver)

## 📌 Introduzione
**Telegram Unused Chat Leaver (TUCL)** è uno script Python progettato per abbandonare automaticamente le chat di Telegram inattive per un determinato numero di giorni.

Permette di:
- Selezionare il tipo di chat da lasciare (chat private, gruppi, canali).
- Configurare una whitelist per escludere chat importanti.
- Ottimizzare la gestione dell'account, evitando il limite di **500 chat su Telegram Free**.
- Ridurre il consumo di banda e risorse.
- Supportare **Termux**, consentendo l'esecuzione su dispositivi Android.

---

## 🌟 Funzionalità

- 🔗 **Abbandono automatico** delle chat in base all'inattività.
- 🌍 **Selezione personalizzata**: chat private, gruppi o canali.
- ✅ **Whitelist**: evita di abbandonare chat importanti.
- ⚡ **Supporto 2FA** (autenticazione a due fattori).
- ⏳ **Filtraggio per giorni di inattività**.
- 🎨 **ASCII Art** "TUCL" all'avvio dello script.
- 🌐 **Selezione lingua**: Italiano / Inglese.
- 📱 **Compatibile con Termux**: funziona senza problemi su Android.

---

## ⚙ Requisiti

- **Python 3.7+**
- **Libreria Telethon** (per interagire con l'API di Telegram)
- **API ID e API Hash** di Telegram

---

## 💻 Installazione

### 1️⃣ Installare Python e le dipendenze

Assicurati di avere **Python 3.7+** installato:
```bash
python --version
pip --version
```
Installa la libreria necessaria:
```bash
pip install telethon
```

### 2️⃣ Ottenere le API di Telegram

1. Vai su **[my.telegram.org](https://my.telegram.org)** e accedi con il tuo numero di telefono.
2. Clicca su **API Development Tools**.
3. Crea una nuova applicazione inserendo nome e descrizione.
4. Dopo la creazione, otterrai **API ID** e **API Hash**, necessari per l'autenticazione.

---

## 🔄 Esecuzione dello script

Dopo aver configurato le API, esegui:
```bash
python leave.py
```
All'avvio, potrai scegliere la lingua dello script (**Italiano o Inglese**).

---

## 🇬🇧 English Version

**Telegram Unused Chat Leaver (TUCL)** is a Python script that allows you to automatically leave Telegram chats that have been inactive for a set number of days.

### 🌟 Features

- 🔗 **Automatically leaves inactive chats**.
- 🌍 **Custom selection**: private chats, groups, or channels.
- ✅ **Whitelist**: prevent leaving important chats.
- ⚡ **2FA support**.
- ⏳ **Filter by days of inactivity**.
- 🎨 **ASCII art "TUCL"** at script startup.
- 🌐 **Language selection**: Italian / English.
- 📱 **Compatible with Termux**: works seamlessly on Android.

### 💻 Installation

Ensure you have **Python 3.7+** installed:
```bash
python --version
pip --version
```
Install the required library:
```bash
pip install telethon
```

### 2️⃣ Get Telegram API Credentials

1. Go to **[my.telegram.org](https://my.telegram.org)** and log in with your phone number.
2. Click on **API Development Tools**.
3. Create a new application by entering name and description.
4. Once created, you will receive **API ID** and **API Hash** for authentication.

### 🔄 Run the script

After configuring the API credentials, run:
```bash
python leave.py
```
At startup, you will be able to choose the script language (**Italian or English**).

---

## 👨‍💻 Autore

Realizzato da **ChatGPT by OpenAI**.

---

