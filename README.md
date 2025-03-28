# Telegram Unused Chat Leaver (TUCL)

**Telegram Unused Chat Leaver (TUCL)** è uno script Python che ti permette di abbandonare automaticamente le chat di Telegram che non hanno avuto attività per un certo numero di giorni. È possibile filtrare il tipo di chat da abbandonare (chat personali, gruppi, canali) e configurare una whitelist per evitare di abbandonare chat importanti.

## Funzionalità
- Abbandona le chat in base alla data dell'ultimo messaggio.
- Seleziona il tipo di chat da abbandonare (chat personali, gruppi, canali).
- Aggiungi chat alla whitelist per evitare di abbandonarle.
- Supporto per l'autenticazione 2FA di Telegram.
- Filtra le chat per tipo e numero di giorni di inattività.
- Mostra un'arte ASCII di benvenuto al lancio dello script.

## Requisiti

1. **Python 3.7 o superiore**.
2. **Biblioteca `telethon`** (per interagire con l'API di Telegram).
3. **API ID e API Hash** (per autenticarsi con Telegram).

## Installazione

### Passo 1: Installare Python e pip

Assicurati di avere **Python 3.7+** e **pip** installati. Puoi verificarlo eseguendo i seguenti comandi:

```bash
python --version
pip --version

'''bash
pip 
install 
telethon

'''bash
python
leave.py

Made by ChatGPT by OpenAI
