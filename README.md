# Gobbo — Teleprompter

**Poche funzioni, tutte affidabili.** Un teleprompter che si apre in 3 secondi, senza account, senza server: il testo non lascia mai il tuo dispositivo. Funziona su Android, iPhone, Windows e Mac dal browser, installabile come app e utilizzabile offline.

*Few features, all reliable. A teleprompter that opens in 3 seconds — no account, no server: your text never leaves your device.*

## Cosa fa
- **Scorrimento fluido** con linea di lettura all'altezza della webcam
- **Un tocco** = avvia/ferma · **+ e −** sul bordo destro regolano la velocità mentre leggi
- **Libreria script**: salva più testi con nome, con Annulla dopo l'eliminazione
- **Esporta/importa** file di testo per spostare gli script tra dispositivi
- **Modalità specchio** per il vetro da teleprompter fisico
- **IT⇄EN traduce tutto**: interfaccia e testo da leggere. L'originale viene conservato: tornando alla lingua di partenza riappare il tuo testo esatto. Usa il traduttore integrato del browser (il testo resta sul dispositivo); dove manca, chiede il consenso per un servizio online. Rileggi sempre la traduzione prima della call
- Schermo sempre acceso durante la lettura
- Al primo avvio trovi uno **script demo**: tocca "Avvia prompter" e guardalo scorrere

## Uso in videochiamata — leggi prima della call
- **💻 Computer** (lo scenario più comune): Gobbo in una finestra stretta subito sotto la webcam. ⚠️ Se condividi lo schermo, **condividi la singola finestra, mai lo schermo intero**, o i partecipanti vedranno il gobbo.
- **🤖 Android**: split-screen — app di chiamata sopra, Gobbo sotto. La camera continua a trasmettere.
- **🍎 iPhone**: usa **due dispositivi** — chiamata sul computer, Gobbo sul telefono accanto alla webcam. iOS può spegnere la tua camera quando esci dall'app di chiamata: il limite è del sistema operativo e riguarda tutti i teleprompter, quindi il telefono da solo non è affidabile.
- **🎯 Prova generale**: prima di una call importante, avvia una riunione da solo per 2 minuti e verifica che la tua camera resti accesa con Gobbo aperto.
- Tastiera (desktop): **Spazio** = play/pausa · **↑ ↓** = velocità · **Esc** = esci

## Installazione come app
- **Android/Chrome**: menu ⋮ → "Aggiungi a schermata Home"
- **iPhone/Safari**: Condividi → "Aggiungi a Home"
- **Windows/Mac (Chrome/Edge)**: icona di installazione nella barra degli indirizzi

## Laboratorio 🧪
Le funzioni sperimentali (scorrimento a voce, finestra flottante, link di condivisione, traduzione) vivono in [`lab.html`](./lab.html). Sono utili ma hanno limiti noti — ad esempio la modalità voce può non funzionare su iPhone durante una chiamata attiva, perché iOS riserva il microfono all'app di chiamata. Verranno promosse nella versione principale quando saranno affidabili in condizioni reali.

## Privacy
Nessun account, nessun tracciamento, nessun invio di dati. Testi e preferenze restano in localStorage sul dispositivo.

## Licenza
[MIT](./LICENSE) — usa, modifica e condividi liberamente.
