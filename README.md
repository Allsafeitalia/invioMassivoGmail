# Invio Email di Presentazione Personalizzato con Google Apps Script

## Descrizione
Questo progetto fornisce uno script **Google Apps Script** che automatizza l'invio di email personalizzate a più destinatari, partendo da un elenco salvato in un foglio Google Sheet. Ogni destinatario riceve un'email individuale, contenente il proprio nome e altri dettagli personalizzati, per creare una comunicazione professionale e personale.

Lo script è particolarmente utile per inviare email di presentazione aziendale, promozioni, aggiornamenti o altre comunicazioni mirate, mantenendo l'approccio "uno a uno", senza che i destinatari vedano le altre persone a cui è stata inviata la stessa email.

## Funzionalità principali
- **Automazione dell'Invio di Email**: Lo script recupera un elenco di destinatari da Google Sheets e invia un'email personalizzata a ciascuno di essi.
- **Personalizzazione del Contenuto**: Utilizza segnaposti nel corpo dell'email (`{{nome}}`) per personalizzare automaticamente ogni messaggio.
- **Facile da Configurare**: Basta inserire i nomi e le email in un Google Sheet e modificare il contenuto del messaggio direttamente nello script.
- **Integrazione con Gmail**: Sfrutta l'API di Gmail per inviare le email in maniera diretta, senza bisogno di plugin esterni.

## Tecnologie Utilizzate
- **Google Apps Script**: Linguaggio di scripting basato su JavaScript per automatizzare e collegare prodotti Google.
- **Google Sheets**: Utilizzato come archivio per i destinatari e le loro informazioni.
- **Gmail API**: Utilizzata per l'invio delle email.

## Come Utilizzare
1. **Crea un foglio Google Sheet** con i nomi e le email dei destinatari.
2. **Copia e incolla lo script** in Google Apps Script.
3. **Personalizza il messaggio** con il tuo contenuto e invia l'email.

## Prerequisiti
- Un account Google con accesso a **Google Sheets** e **Gmail**.
- Conoscenze di base su come utilizzare **Google Apps Script**.

## Esempio di Utilizzo
Il foglio di lavoro "Destinatari" include:

| Nome     | Email              |
|----------|--------------------|
| Marco    | marco@esempio.com  |
| Laura    | laura@esempio.com  |
| Giovanni | giovanni@esempio.com |

Lo script invierà un'email personalizzata a ciascun destinatario, utilizzando il modello definito direttamente nello script.

## Obiettivo del Progetto
L'obiettivo di questo progetto è semplificare l'invio di email personalizzate a più destinatari, mantenendo la comunicazione personale e migliorando l'efficienza delle attività di email marketing o comunicazioni aziendali.

## Licenza
Questo progetto è rilasciato sotto la **MIT License**. Vedi il file `LICENSE` per maggiori dettagli.

---

Made with ❤️ from giuseppemastronardi.dev
